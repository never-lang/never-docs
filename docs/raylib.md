Never can be used to invoke more functions from dynamically loaded libraries. The
following code uses [raylib](https://www.raylib.com/) library to draw a ball which changes its color
when mouse button is pressed. Never connects with raylib using FFI which
passes records and externalizes library functions. To run the program it is
required to compile raylib and pass proper path in extern function declarations.

Code mentioned below is adopted to from [raylib examples](https://www.raylib.com/examples.html).

![raylib FFI][ffiraylib]

```never
record Vector2
{
    x : float;
    y : float;
}

record Color
{
    r : char;
    g : char;
    b : char;
    a : char;
}

let MOUSE_LEFT_BUTTON = 0;
let MOUSE_RIGHT_BUTTON = 1;
let MOUSE_MIDDLE_BUTTON = 2;

let DARKBLUE = Color(chr(0), chr(82), chr(172), chr(255));
let DARKGRAY = Color(chr(80), chr(80), chr(80), chr(255));
let LIME = Color(chr(0), chr(158), chr(47), chr(255));
let MAROON = Color(chr(190), chr(33), chr(55), chr(255));
let RAYWHITE = Color(chr(245), chr(245), chr(245), chr(245));

let screenWidth = 800;
let screenHeight = 450;

extern "libraylib.so" func InitWindow(width : int, height : int, title : string) -> void
extern "libraylib.so" func SetTargetFPS(fps : int) -> void
extern "libraylib.so" func WindowShouldClose() -> char
extern "libraylib.so" func CloseWindow() -> void
extern "libraylib.so" func GetMousePosition() -> Vector2
extern "libraylib.so" func IsMouseButtonPressed(button : int) -> char
extern "libraylib.so" func BeginDrawing() -> void
extern "libraylib.so" func EndDrawing() -> void
extern "libraylib.so" func ClearBackground(color : Color) -> void
extern "libraylib.so" func DrawCircleV(center : Vector2, radius : float, color : Color) -> void
extern "libraylib.so" func DrawText(text : string, posX : int, posY : int, fontSize : int, color : Color) -> void

func c2b(c : char) -> bool
{
    c != chr(0) ? true : false
}

func main() -> int
{
    let ballPosition = Vector2( -100.0, -100.0 );
    let ballColor = Color;

    ballColor = DARKBLUE;

    InitWindow(screenWidth, screenHeight, "Never meets raylib");
    SetTargetFPS(60);

    while (!c2b(WindowShouldClose()))
    {
        ballPosition = GetMousePosition();

        if (c2b(IsMouseButtonPressed(MOUSE_LEFT_BUTTON)))
        {
            ballColor = MAROON
        }
        else if (c2b(IsMouseButtonPressed(MOUSE_MIDDLE_BUTTON)))
        {
            ballColor = LIME
        }
        else if (c2b(IsMouseButtonPressed(MOUSE_RIGHT_BUTTON)))
        {
            ballColor = DARKBLUE
        }
        else
        {
            ballColor
        };

        BeginDrawing();

            ClearBackground(RAYWHITE);
            DrawCircleV(ballPosition, 40.0, ballColor);
            DrawText("move ball with mouse and click mouse button to change color", 10, 10, 20, DARKGRAY);

        EndDrawing()
    };

    CloseWindow();

    0
}
```

[ffiraylib]: ffiraylib.png "raylib FFI"


