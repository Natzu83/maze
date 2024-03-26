The Maze

The Maze is 3D game built using SDL and Raycasting. On the map, the player can move in all four directions using keys W, A, S, and D.

The player can move through the maze and turn left or right as desired.

If the player hits a wall, they cannot move unless they change their direction. Because the walls are solid objects.

The player can move on several directions and rotate in the same time.
Installation

Compiling

This project makes use of gcc and make for the compilation process.
Linux

First make sure SDL is installed. If you haven't install SDL by running make linux_install. Then run the following command:

make linux 

to compile.

Ensure sdl is installed. Then run the following command:

How to star the program

After successfully compiling run the program using following command:

./maze MAP

where MAP is the name of the file found in the maps folder. You can create other maps and pass them while running program as above. Map files accept only the allowed characters.
Controls

W - Moving forward

S - Moving backward

A - Look left

D - Look right

Mouse move left/right - look left or right

M - Turn off map visibility. The 2D map won't be visible on clicking

N - Turn on map visibility. The 2D map will be visible again if it wasn't

Have fun!
Directories

src

Contains all the source code files written in C.

inc

Contains all the header files.

maps

Contains map data files. This will be used by the program to output the map layout.

images

Contains image files.
Images

image
Texture sources

Weapon

https://www.seekpng.com/idown/u2w7u2t4i1y3a9y3_call-of-duty-guns-firearms-gun-weapons-coat/
Contributing

    Read the source files in src folder and the header files in inc folder.
    Clone the repo and make a new branch: $ git checkout https://github.com/candiepih/The-Maze -b [name_of_new_branch].
    Add a feature, fix a bug, or refactor some code :)
    Write/update tests for the changes you made, if necessary.
    Update README.md if necessary.
    Open a Pull Request with a comprehensive description of changes.

Related

The Maze - Holberton Project Page
License

Authors

Omar Velez natzuac@yahoo.com