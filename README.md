# Wolf3d
Wolfeinstein-like ray casting program

## About Wolf3d

Wolf3d is a game build on ray casting algorithm. Prokect made on C, using MinilibX.

**Project can be launched only on MacOS with installed _MinilibX Library_.**

## Compiling

1. Run `make` after downloading.
2. Run `./wolf3d maps/[map_name]`

## How to use?

Arrows  - moving;

Shift   - sprint;

Space   - change wall textures;

Enter   - reload map from the start point;

ESC     - quit the game.

## Map format

Every map is a text file, where

0 - empty space

1 - player's start point

2 - wall.

Every map should have the same amount of elemets in every line. In other words, map should be rectangle, otherwise validating function shows error message.

Map example:

<img width="344" alt="Screen Shot 2019-06-03 at 6 21 26 PM" src="https://user-images.githubusercontent.com/25118092/58813510-994aa600-862c-11e9-9958-207467c8d142.png">


## Screenshots

<img width="998" alt="1" src="https://user-images.githubusercontent.com/25118092/58813775-242ba080-862d-11e9-8858-14499c35d895.png">


<img width="1002" alt="2" src="https://user-images.githubusercontent.com/25118092/58813796-33125300-862d-11e9-9836-7b9de43f2468.png">


<img width="1003" alt="3" src="https://user-images.githubusercontent.com/25118092/58813825-3e657e80-862d-11e9-8688-566e34d0b451.png">

