# Robot simulator

### Description

- This toy robot simulator project is purely based on Javascript.
- The application is a simulation of a toy robot moving on a square tabletop, of dimensions 5 units x 5 units
- No other obstruction on the table surface
- The robot is free to roam around the surface of the table but must prevent from falling

### System Dependencies & Configuration

To run this app, you will only need code editor and your browser. That's it!

### Application Installation Instructions

No installation needed. No changes will be made to your system.

To get the application, just clone a repo, then `cd` its directory and you are ready to run the app:

```
$ git clone git@github.com:jayyasay/robot-simulator-exam.git
$ cd robot-simulator-exam
```

### Operations and commands

You will just type commands in the ```input``` area.

These are the commands:

```
PLACE X,Y,F
MOVE
LEFT
RIGHT
REPORT
```

### Here are the full instructions (based on the assignment task)

PLACE will put the robot on the table in position X,Y and facing NORTH, SOUTH, EAST or WEST. The origin (0,0) can be considered to be the SOUTH WEST most corner.

The first valid command to the robot is a PLACE command, after that, any sequence of commands may be issued, in any order, including another PLACE command.

This application should discard all commands in the sequence until a valid PLACE command has been executed.

MOVE will move the robot one unit forward in the direction it is currently facing.

LEFT and RIGHT will rotate the robot 90 degrees in the specified direction without changing the position of the robot.

REPORT will announce the X,Y and orientation of the robot

**Note:** Please make sure that you setup your SSH key before you can ```pull``` and ```push```

### Reference

[jsfiddle](http://jsfiddle.net/tinglu/hsqu6vz0)