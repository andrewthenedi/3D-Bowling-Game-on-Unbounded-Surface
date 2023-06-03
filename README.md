# 3D Bowling Game on Unbounded Surface

Introduction
* The main objective of this project is to hit as many bowling pins as possible, given that
the ball has not fallen down to the surface, as the score corresponds to the number of hit bowling
pins. 
* In addition, this project utilizes mainly a three.js framework, build on top of WebGL,
other relevant javascript frameworks, and package the model under GitHub to run the
3D game application model in the browser.

Project Report: https://drive.google.com/file/d/14FI6AwaF_sT4LrCu1ZxO7NFbnhnyXQuM/view?usp=sharing

Project Details 
* User Input Controller
In the initial stage, the user has to input the corresponding name. Afterward, with the help of the Three.js (cross-browser library for the JavaScript programming language), the user can start to move the ball in a certain direction according to the input, as follow:
  * If the user presses the ‘w’ button on the keyboard, the ball will go to the north side.
  * If the user presses the ‘a’ button on the keyboard, the ball will go to the west side.
  * If the user presses the ‘s’ button on the keyboard, the ball will go to the south side.
  * If the user presses the ‘d’ button on the keyboard, the ball will go to the east side.
  * If the user presses the ‘space’ button on the keyboard, the ball will jump.
  * If the user presses the ‘esc’ button on the keyboard, the game will restart.
  * If the user moves the trackpad or mouse during the game, the view direction will be changed dynamically.

* Object Placing
  * In each iteration, the emerald (target), bowling ball, and large cube-shaped glasses (obstacles) will be located randomly on the surface. 
  * The obstacles or the bowling ball can be moved in a certain tangent from the collision event, as the collision effect is performed dynamically during the gameplay runtime. 
  * All of such components are modeled with the help of Cannon.js (physics engine library for the JavaScript programming language). 
  * In addition, shadows and depth of field using texture mipmaps of the objects are applied with the help of the Three.js.

* Surface
  * The surface will be a fixed-sized rectangular shape without any boundaries.
  * After the ball falls from the previous surface, with the help of the Three.js, the new surface will be generated accordingly to enable the user to play the game again.
  * In addition, shadows and depth of field using texture mipmaps of the surface are applied with the help of the Three.js.

* Scoring Mechanism
  * The score will be accumulated based on how fast the user can hit the emerald with the bowling ball before the countdown ended, which in this case is 10 seconds.
  * The score will be reset when either the ball falls from the surface or the user refreshes the website.
  * However, the score and the corresponding user name will be inserted into the leaderboard on the top right-hand corner of the screen, as long as the NPM (package manager for the JavaScript programming language) server is still running.

## Getting Started

* Clone the project
* Install the dependencies 

### Prerequisites

You need to have installed following softwares and libraries in your machine before running this project.

```
1. Visual Studio Code
2. Git
3. Node.js
```

## Built With

* Three.js
* Cannon-es
* Typescript

## Authors

* Andrew Thenedi

## Acknowledgement
* COMP4422 (Computer Graphics) Course
