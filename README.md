# Opengl-SolarSystem :ringed_planet:
Project of creating a simple solar system with 2 planets using C++ and the Opengl library -UOI Project

## Prerequisite
- C++ 
- OpenGL Download [here](https://opengl.org/)
- GLFW GLEW GLM Download and Setup [here](https://www.wikihow.com/Set-Up-OpenGL-GLFW-GLEW-GLM-on-a-Project-with-Visual-Studio)

## Controls :joystick:

We created a solar system in a window 800x800 which shuts down with **Q** keyboard button.
  
We move in the X-axis with **W** and **X** buttons, in the Y-axis with **A** and **D** and we can do zoom in with <+>(**plus**) and zoom out with <->(**minus**) keyboard buttons.

When the user press **Space button** a meteor is launched towards the sun. If it finds the planet first , a destruction will be happen and both spheres will be destroyed.
Otherwise there will be a collision between Sun and Meteor and Meteor will be absorbed by the Sun.
