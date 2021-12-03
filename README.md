We used Windows 10 OS and completed this assignment in VSCode.

We compiled the code in MSYS2 MINGW-64 using the Makefile. Simply type make to remove past exe, compile program, and run.

![Screenshot1](https://user-images.githubusercontent.com/23744162/144625992-af793fb4-8402-4cc5-b400-a6b05b742f26.JPG)
![Screenshot2](https://user-images.githubusercontent.com/23744162/144625995-08df52a9-40c0-42fe-a0df-3f29b1884f6e.JPG)
![Screenshot3](https://user-images.githubusercontent.com/23744162/144625986-898ec369-d537-4290-a0fe-eafb80d7fb46.JPG)
![Screenshot4](https://user-images.githubusercontent.com/23744162/144625987-cb4f266f-2b1c-4604-9d3f-5b9ca3429374.JPG)
![Screenshot5](https://user-images.githubusercontent.com/23744162/144625990-c614ed76-183f-4f2d-835f-7544f2a1c27b.JPG)

Controlable features:
- Press the arrow keys to move the selected light.
- Press 1 and 2 to change which light is selected.
- Press l to turn the lights on or off.
- Use w a s d to change the direction of the cannon.
- Press f to disable/enable friction mode.
- Press x, y, and z to increase the rotation of the scene around each respective axis.
- Press X, Y, and Z to decrease these rotations.
- Press p to enter particle camera mode, which follows the next particle until it dies.
- Press t to enable/disable particle trails.
- Press space to turn the fountain on or off.
- Press = and - to zoom in and out respectively.
- Press r to reset the particles.
- Press q to exit the program.

Design decision notes:
- particle trails follow the entire path of each particle when setting is toggled on with 't' and only disapear if particle 
dies or setting is toggled off.
- when particles are resert with 'r' the fountain stays on.
- canon rotation has a maximum rotation of 45 degrees in each direction.
- instead of arrow keys, we used x, y and z for scene rotations in order to enable user to rotate about the x, y and z axes.
- arrow keys are used to move the light sources which are represented by teapots. 1 and 2 toggle which source is currently 
seleccted.
- the floor is a grid just for easier evaluation.
