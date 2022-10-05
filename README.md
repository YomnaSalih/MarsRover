
# Mars Rover

## Overview

You are part of the team that explores Mars by sending remotely controlled vehicles to the surface of 
the planet. Develop an API that translates the commands sent from earth to instructions that are 
understood by the rover.
When the rover touches down on Mars, it is initialised with it’s current coordinates and the direction 
it is facing. These could be any coordinates, supplied as arguments (x, y, direction) e.g. (4,
2, EAST).

## Approach

You should tackle this problem as you would any real world requirement that would be shipped as 
part of a real product. You should showcase how you work and the way you decompose a problem 
into smaller pieces.

## Performance

The rover is given a command string which contains multiple commands. This string must then be 
broken into each individual command and that command then executed. 

## Methods

This project is based on four functions using JavaScript.
- `moveForward()`
Move forward on current heading
- `moveBackwards()`
Move backwards on current heading
- `turnLeft()`
Rotate left by 90 degrees
- `turnRight()`
Rotate right by 90 degrees

## Working examples

The modules are implemented and tested in Visual Studio Code using JavaScript
and the output is found in the console.

After running out project, a window will appear to enter the command `(f, b, l, r, or s)`.
First we will enter "s" to exit the infinte loop, then right-click on the screen and press on "inspect" and then on "console" to see the output on it.

After that we should reftesh the page to enter the command that we want again in the window and see the result on the console.
For example, if we entered:
- f -> (0, 1) North
- b -> (0, -1) North
- l -> (0, 0) West
- r -> (0, 0) East
- flfffbr -> (-2, 1) North
- s -> break

## Libraries
- Babel se6/7
- jest - to perform unit testing 



