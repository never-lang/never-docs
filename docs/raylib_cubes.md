Another example which demos Never and raylib FFI.

Code mentioned below is adopted to from [raylib examples](https://www.raylib.com/examples.html).

![raylib cubes][raylib_cubes]

```never
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

    raylib.InitWindow(screenWidth, screenHeight, "raylib [models] example - waving cubes");

    /* Initialize the camera */
    let camera = raylib.Camera3D(nil, nil, nil, 0.0f, 0);
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
        let time = raylib.GetTime();

        /* Calculate time scale for cube position and size */
        let scale = (2.0f + sin(time)) * 0.7f;

        /* Move camera around the scene */
        let cameraTime = time * 0.3;
        camera.position.x = cos(cameraTime)*40.0f;
        camera.position.z = sin(cameraTime)*40.0f;
        
        /* Draw */
        raylib.BeginDrawing();

            raylib.ClearBackground(raylib.RAYWHITE);

            raylib.BeginMode3D(camera);

                raylib_models.DrawGrid(10, 5.0f);

                let x = 0;
                for (x = 0; x < numBlocks; x = x + 1) 
                {
                    let y = 0;
                    for (y = 0; y < numBlocks; y = y + 1) 
                    {
                        let z = 0;
                        for (z = 0; z < numBlocks; z = z + 1) 
                        {
                            /* Scale of the blocks depends on x/y/z positions */
                            let blockScale = (x + y + z)/30.0f;

                            /* Scatter makes the waving effect by adding blockScale over time */
                            let scatter = sin(blockScale*20.0f + (time*4.0f));

                            /* Calculate the cube position */
                            let cubePos = raylib.Vector3(
                                (x - numBlocks/2)*(scale*3.0f) + scatter,
                                (y - numBlocks/2)*(scale*2.0f) + scatter,
                                (z - numBlocks/2)*(scale*3.0f) + scatter
                            );

                            /* Pick a color with a hue depending on cube position for the rainbow color effect */
                            let cubeColor = raylib.ColorFromHSV(raylib.Vector3(((x + y + z) * 18) % 360, 0.75f, 0.9f));

                            /* Calculate cube size */
                            let cubeSize = (2.4f - scale)*blockScale;

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


