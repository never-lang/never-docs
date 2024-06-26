Another example which demos Never and raylib FFI.

Code mentioned below is adopted to from [raylib examples](https://www.raylib.com/examples.html).

![raylib 3d camera][raylib_3d_camera]

```never
/**********************************************************************************************
*   LICENSE: zlib/libpng
*
*   raylib is licensed under an unmodified zlib/libpng license, which is an OSI-certified,
*   BSD-like license that allows static linking with closed source software:
*
*   Copyright (c) 2013-2020 Ramon Santamaria (@raysan5)
*   Copyright (c) 2020 Slawomir Maludzinski (binding to Never language)
*
*   This software is provided "as-is", without any express or implied warranty. In no event
*   will the authors be held liable for any damages arising from the use of this software.
*
*   Permission is granted to anyone to use this software for any purpose, including commercial
*   applications, and to alter it and redistribute it freely, subject to the following restrictions:
*
*     1. The origin of this software must not be misrepresented; you must not claim that you
*     wrote the original software. If you use this software in a product, an acknowledgment
*     in the product documentation would be appreciated but is not required.
*
*     2. Altered source versions must be plainly marked as such, and must not be misrepresented
*     as being the original software.
*
*     3. This notice may not be removed or altered from any source distribution.
*
**********************************************************************************************/
/***
 * A small hack in raylib library is needed
 *
 * Add the following function:
 *
 *  Camera UpdateCameraCopy(Camera camera)
 *  {
 *    UpdateCamera(&camera);
 *    return camera;
 *  }
 *
 */
use raylib
use raylib_camera
use raylib_models
use raylib_shapes
use raylib_text

let MAX_COLUMNS = 20;

func main() -> int
{
    /* Initalization */
    let screenWidth = 800;
    let screenHeight = 450;
    var camera = raylib.Camera3D;
    var heights = {[ MAX_COLUMNS ]} : float;
    var positions = {[ MAX_COLUMNS ]} : raylib.Vector3;
    var colors = {[ MAX_COLUMNS ]} : raylib.Color;
    var i = 0;

    raylib.InitWindow(screenWidth, screenHeight, "raylib [core] example - 3d camera first person");

    /* Define the camera to look into our 3d world (position, target, up vector) */
    camera = raylib.Camera3D(nil, nil, nil, 0.0, 0);
    camera.position = raylib.Vector3(4.0, 2.0, 4.0);
    camera.target = raylib.Vector3(0.0, 1.8, 0.0);
    camera.up = raylib.Vector3(0.0, 1.0, 0.0);
    camera.fovy = 60.0;
    camera.type = raylib_camera.CameraType::CAMERA_PERSPECTIVE;

    /* Generates some random columns */
    for (i = 0; i < MAX_COLUMNS; i = i + 1)
    {
        heights[i] = raylib.GetRandomValue(1, 12);
        positions[i] = raylib.Vector3( raylib.GetRandomValue(-15, 15), heights[i]/2, raylib.GetRandomValue(-15, 15) );
        colors[i] = raylib.Color( chr(raylib.GetRandomValue(20, 255)), chr(raylib.GetRandomValue(10, 55)), chr(30), chr(255) )
    };

    /* Set a first person camera mode */
    raylib_camera.SetCameraMode(camera, raylib_camera.CameraMode::CAMERA_FIRST_PERSON); 

    /* Set our game to run at 60 frames-per-second */
    raylib.SetTargetFPS(200);                           

    /* Main game loop */
    while (!raylib.WindowShouldClose()) /* Detect window close button or ESC key */
    {
        /* Update camera */
        camera = raylib_camera.UpdateCameraCopy(camera);

        /* Draw */
        raylib.BeginDrawing();

            raylib.ClearBackground(raylib.RAYWHITE);

            raylib.BeginMode3D(camera);

                raylib_models.DrawPlane(raylib.Vector3(0.0, 0.0, 0.0), raylib.Vector2(32.0, 32.0), raylib.LIGHTGRAY); /* Draw ground */
                raylib_models.DrawCube(raylib.Vector3(-16.0, 2.5, 0.0), 1.0, 5.0, 32.0, raylib.BLUE);     /* Draw a blue wall */
                raylib_models.DrawCube(raylib.Vector3(16.0, 2.5, 0.0), 1.0, 5.0, 32.0, raylib.LIME);      /* Draw a green wall */
                raylib_models.DrawCube(raylib.Vector3(0.0, 2.5, 16.0), 32.0, 5.0, 1.0, raylib.GOLD);      /* Draw a yellow wall */

                /* Draw some cubes around */
                for (i = 0; i < MAX_COLUMNS; i = i + 1)
                {
                    raylib_models.DrawCube(positions[i], 2.0, heights[i], 2.0, colors[i]);
                    raylib_models.DrawCubeWires(positions[i], 2.0, heights[i], 2.0, raylib.MAROON)
                };

            raylib.EndMode3D();

            raylib_shapes.DrawRectangle( 10, 10, 220, 70, raylib.Fade(raylib.SKYBLUE, 0.5));
            raylib_shapes.DrawRectangleLines( 10, 10, 220, 70, raylib.BLUE);

            raylib_text.DrawText("First person camera default controls:", 20, 20, 10, raylib.BLACK);
            raylib_text.DrawText("- Move with keys: W, A, S, D", 40, 40, 10, raylib.DARKGRAY);
            raylib_text.DrawText("- Mouse move to look around", 40, 60, 10, raylib.DARKGRAY);

        raylib.EndDrawing()
    };

    /* De-Initialization */
    raylib.CloseWindow();  /* Close window and OpenGL context */

    0
}
```

[raylib_3d_camera]: raylib_3d_camera.gif "raylib 3d camera"
