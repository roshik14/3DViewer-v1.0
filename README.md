# 3DViewer-v1.0

### This is a group project

## Information
Implementation of project 3DViewer_v1.0 using C language and GTK+ library.
This is a program to view 3D wireframe models.
The models themselves load from .obj files and viewable on the screen with the ability to rotate, move and scale.
The program allows you to set custom settings regarding the display of the 3D model.
In addition, the recording of the received image into files of bmp and jpeg formats is implemented.
The program also allows you to record small screencasts in a .gif file

## Usage

### Rotate and move object
 To rotate or move object just type x,y,z values and click the button <b>Rotate</b> or <b>Move</b>

### Scale object
To scale object just type scale value and click the button <b>Scale</b>.
The program does not accept negative values. To constriction object , for example by 5, just type 0.5

### Record object
To record small screencast in a .gif file click the button <b>Record</b>, then click the button <b>Save gif</b>
Then move, rotate, scale, or do what you want to record screencast.
To finish recording click the button <b>Record</b> again and then click the button <b>Stop</b>

## Installation
### Install:
To install the program type pre>p>code>make install</code></pre>
Then go to folder where application was installed. 
(Usually this is /Users/Username/Desktop/3DViewer/)
Then type `./viewer`

## Uninstallation
To uninstall program type `make uninstall`




