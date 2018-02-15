# RubicCube
A basic Rubic Cube in OPENGL, i have not included the engine running the whole cube as it was not made by me.
the cube can turn each of it faces by key strokes, change directions and have a diffrent angle (not only 90 degrees swaps, but also 180,45,22.5...) - it wont let you swap another face while the other havnt done a clear swap (meaning modulo 90).
whole of the cubes are each with its own mat4 for rotations and positions. the shader renders it in real time and we only "play with the numbers".
it saves the last rotation to allow convolution as animation and not a "sharp" switch.
![alt text](https://raw.githubusercontent.com/AmitTurner/RubicCube/master/testt.gif)
![alt text](https://raw.githubusercontent.com/AmitTurner/RubicCube/master/testt2.gif)
Mixer is WIP and so does solver. as it needs multi-threading.
