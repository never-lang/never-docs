Another example which demos Never and raylib FFI.

Code mentioned below is adopted to from [raylib examples](https://www.raylib.com/examples.html).

![raylib cubes][raylib_cubes]

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
/*******************************************************************************************
*
*   raylib [models] example - Waving cubes
*
*   This example has been created using raylib 2.5 (www.raylib.com)
*   raylib is licensed under an unmodified zlib/libpng license (View raylib.h for details)
*
*   Example contributed by Codecat (@codecat) and reviewed by Ramon Santamaria (@raysan5)
*
*   Copyright (c) 2019 Codecat (@codecat) and Ramon Santamaria (@raysan5)
*   Copyright (c) 2020 Slawomir Maludzinski (Never port)
*
********************************************************************************************/
use raylib
use raylib_camera
use raylib_models
use raylib_text
use raylib_touch

func main() -> int
{
    /* Initialization */
    let screenWidth = 800;
    let screenHeight = 450;
    let numBlocks = 15;
    var blockScale = 0.0;
    var time = 0.0d;
    var cameraTime = 0.0d;
    var scale = 0.0;
    var scatter = 0.0;
    var cubePos = raylib.Vector3;
    var cubeColor = raylib.Color;
    var camera = raylib.Camera3D;
    var cubeSize = 0.0;
    var i = 0;
    var x = 0;
    var y = 0;
    var z = 0;

    raylib.InitWindow(screenWidth, screenHeight, "raylib [models] example - waving cubes");

    /* Initialize the camera */
    camera = raylib.Camera3D(nil, nil, nil, 0.0f, 0);
    camera.position = raylib.Vector3(30.0f, 20.0f, 30.0f);
    camera.target = raylib.Vector3(0.0f, 0.0f, 0.0f);
    camera.up = raylib.Vector3(0.0f, 1.0f, 0.0f);
    camera.fovy = 70.0f;
    camera.type = raylib_camera.CameraType::CAMERA_PERSPECTIVE;

    raylib.SetTargetFPS(60);

    /* Main game loop */
    while (!raylib.WindowShouldClose())    /* Detect window close button or ESC key */
    {
        /* Update */        
        time = raylib.GetTime();

        /* Calculate time scale for cube position and size */
        scale = (2.0f + sin(time)) * 0.7f;

        /* Move camera around the scene */
        cameraTime = time * 0.3;
        camera.position.x = cos(cameraTime)*40.0f;
        camera.position.z = sin(cameraTime)*40.0f;
        
        /* Draw */
        raylib.BeginDrawing();

            raylib.ClearBackground(raylib.RAYWHITE);

            raylib.BeginMode3D(camera);

                raylib_models.DrawGrid(10, 5.0f);

                for (x = 0; x < numBlocks; x = x + 1) 
                {
                    for (y = 0; y < numBlocks; y = y + 1) 
                    {
                        for (z = 0; z < numBlocks; z = z + 1) 
                        {
                            /* Scale of the blocks depends on x/y/z positions */
                            blockScale = (x + y + z)/30.0f;

                            /* Scatter makes the waving effect by adding blockScale over time */
                            scatter = sin(blockScale*20.0f + (time*4.0f));

                            /* Calculate the cube position */
                            cubePos = raylib.Vector3(
                                (x - numBlocks/2)*(scale*3.0f) + scatter,
                                (y - numBlocks/2)*(scale*2.0f) + scatter,
                                (z - numBlocks/2)*(scale*3.0f) + scatter
                            );

                            /* Pick a color with a hue depending on cube position for the rainbow color effect */
                            cubeColor = raylib.ColorFromHSV(raylib.Vector3(((x + y + z) * 18) % 360, 0.75f, 0.9f));

                            /* Calculate cube size */
                            cubeSize = (2.4f - scale)*blockScale;

                            /* And finally, draw the cube! */
                            raylib_models.DrawCube(cubePos, cubeSize, cubeSize, cubeSize, cubeColor)
                        }
                    }
                };
                
            raylib.EndMode3D();
            
            raylib_text.DrawFPS(10, 10);

        raylib.EndDrawing()
    };

    /* De-Initialization */
    raylib.CloseWindow();  /* Close window and OpenGL context */

    0
}
```

[raylib_cubes]: raylib_cubes.gif "raylib cubes"


