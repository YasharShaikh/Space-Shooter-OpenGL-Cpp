# Space Shooter

A two-player local arcade duel built with C++, legacy OpenGL, and GLUT. Two players share a keyboard, fire lasers, and win by reducing the other ship’s health to zero.

| Player | Move | Fire |
| --- | --- | --- |
| 1 | W, A, S, D | C |
| 2 | I, J, K, L | M |

## Build

The game is implemented in [main.cpp](main.cpp). Install the OpenGL and GLUT development libraries, then compile and link against them. On Linux with GCC and freeGLUT installed:

```sh
g++ main.cpp -o space-shooter -lglut -lGL
./space-shooter
```

Choose **Start** from the game menu. The code includes separate views for the intro, instructions, match, and game over.
