# Spinning Cube

A small C++ learning project that renders a rotating ASCII cube in the terminal.

This was a fun project to build while following a tutorial. I spent time researching the math behind 3D rotation and experimenting with the cube’s size, display dimensions, camera distance, and rotation speed.

## What I learned

* Applying rotation formulas to points in 3D space.
* Projecting 3D coordinates onto a 2D terminal display.
* Using a character buffer to prepare each frame.
* Using z-buffering to determine which surfaces appear in front.
* Using `usleep()` to add a delay between frames.

## Build and run on macOS

```bash
clang++ main.cpp -o spinning_cube
./spinning_cube
```

Press **Ctrl+C** to stop the animation.

Expand the terminal to accommodate the configured 180-column × 66-row display.
