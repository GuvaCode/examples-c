# examples-c
<img align="left" src="https://github.com/raysan5/raylib/raw/master/logo/raylib_logo_animation.gif" width="64">
Examples and samples made for raylib using C

## Building
The examples use premake. Each example is a project on it's own. Premake will setup the build systems for each project for you, and download any needed libraries (raylib and box2d)

### For Visual Studio
Run premake-VisualStudio.bat. When it is done each example folder will have a .sln file in it that you can open and run.

### For MinGW
Run premake-mingw.bat. When it is done each example folder will have a makefile that you can build, just cd into the example folder and type make.

### For GCC On Linux
Run "premake5 gmake2". When it is done each example folder will have a makefile that you can build, just cd into the example folder and type make.

### For GCC On MacOs
Run "premake5.osx gmake2". When it is done each example folder will have a makefile that you can build, just cd into the example folder and type make.

# Circle In View 2D
Code showing how to check if a circle is inside a view cone. Shows examples of using dot products to find what side of a vector a point is on, and how to compute the nearest point on a vector to another point.
![circle_in_view](https://user-images.githubusercontent.com/322174/149637442-c701f9cb-883a-4d44-96fe-f91e8a86dea6.gif)

# Texture Repeat
An example of how to do a repeating background inside a camera 2d
![repeat](https://user-images.githubusercontent.com/322174/149637440-b7f7b1d2-1e1d-4ad8-a465-e11ce2388793.gif)

# Full 3d Billboards
An example of how to make a billboard that follows the camera in any orientation
![3D_Billboards](https://user-images.githubusercontent.com/322174/159843788-74bb43ef-c582-40c5-9c50-cf8935d801f1.gif)

# Unsorted Billboards
An example of using shaders to discard pixels with 0 alpha to allow billboards to be drawn in any order.
![unsorted_billobards](https://user-images.githubusercontent.com/322174/148694937-f7c4b166-b81a-4d48-af8f-eefbc1a3f487.gif)

# Ray2d And Rect Intersection
Code to show how to quickly detect if a 2d ray intersects a rectangle
![intersect](https://user-images.githubusercontent.com/322174/150265976-3b27ab1f-2087-4273-9e8e-a2e393339d96.gif)

# Rect Circle Collisions
Example of how to get the intersection point between a rectangle and a cirlce and use that to do collision detection.
This is one way to do collisions on a player in 2/2.5d against world objects.
![collision_rects](https://user-images.githubusercontent.com/322174/151831283-c88c5823-46cb-4c46-b3ad-d096ec3ad111.gif)

# Camera Clamp
A simple example of how to keep a camera view on a map but still follow the player when possible.
![camera_clamp](https://user-images.githubusercontent.com/322174/152666088-6812df46-fe05-45f0-adb1-60282a68140e.gif)

# Camera World Rect
A simple example of how to get the screen rectangle in world space, with pan and zoom taken into account
![screen_in_world_rect](https://user-images.githubusercontent.com/322174/152667574-f3761c91-6e81-4592-ad35-6ce1a0dd94c6.gif)

# Mouse Zoom
An example of how to zoom a Camera2d around the mouse cursor.
![mouse_zoom](https://user-images.githubusercontent.com/322174/179423394-6012957e-d892-42d8-b927-b6db10921ad7.gif)

# Platform Motion
Example of simple platfomer motion and collision
![platform](https://user-images.githubusercontent.com/322174/208321841-9f4bdb9b-1bab-4e90-9559-40bb3fd5b67f.gif)

# rlgl_example
Example of using raw rlgl to draw geometry

# lua_embed
Example of embeding lua into a game and exposting functions and data to lua scripts, using raylib

# camera worldspace
Example of how to use a camera to create a nominal worldspace with any window size

# Shoot
Example of how to do basic motion and shooting

