# 3D-Bowling-Game-on-Unbounded-Surface

Introduction
The main objective of this project is to hit as many bowling pins as possible, given that
the ball has not fallen down to the surface, as the score corresponds to the number of hit bowling
pins. In addition, this project will utilize mainly a three.js framework, build on top of WebGL,
other relevant javascript frameworks (tentative), and package the model under GitHub to run the
3D game application model in the browser.

Project Details
* User Input Controller
In the initial stage, the user has to input the corresponding name. Afterward, with the help of the Three.js (cross-browser library for the JavaScript programming language), the user can start to move the ball in a certain direction according to the input, as follow:
** If the user presses the ‘w’ button on the keyboard, the ball will go to the north side.
** If the user presses the ‘a’ button on the keyboard, the ball will go to the west side.
** If the user presses the ‘s’ button on the keyboard, the ball will go to the south side.
** If the user presses the ‘d’ button on the keyboard, the ball will go to the east side.
** If the user presses the ‘space’ button on the keyboard, the ball will jump.
** If the user presses the ‘esc’ button on the keyboard, the game will restart.
** If the user moves the trackpad or mouse during the game, the view direction will be changed dynamically.

* Object Placing
a. In each iteration, the bowling pin, ball, and obstacles will be located randomly on
the surface.
b. The obstacles can be moved in a small tangent from the collision of the ball.
3. Surface
a. The surface will be a fixed-sized rectangular shape without any boundaries.
b. After the ball fell down from the previous surface, the new surface will be
generated accordingly to enable the user to play the game again.

* Scoring Mechanism
a. The score will be accumulated according to the number of hit bowling pins, given
that the ball has not fallen down the surface yet.
b. The score will be reset once either the ball falls down from the surface or the user
refreshes the website.


## Getting Started

* Clone the project
* install the dependencies 

### Prerequisites

You need to have installed following softwares and libraries in your machine before running this project.

```
1. Visual Studio Code
2. Git
3. Node.js
```

## Built With

* Tree.js
* Cannon-es
* Typescript

## Authors

* Andrew Thenedi

## Acknowledgement
* COMP4422 (Computer Graphics) Course
