## Project 1.1 - CovidZAR.EIEIO
#### Due: 07-16-2020 (Thursday @ 12:30 p.m.)

This is part 1 of [P01](../P01/README.md). Much more coming.

## Overview of Part 1

Simply create a game window that shows a player in the middle of the screen. Your player can be a sprite or a colored shape. You should have the ability to move the player around the screen without going off the edge (you get stopped).


### Requirements
- Your game will be configured by command line parameters.
  - Window size (width and height)
  - Player size.
  - Game Title
  - Background color (or image / texture if you're feeling ambitious)
  - If you use a sprite, then path to your sprite.
  - ~~If you use a shape, then the color of your shape~~. Use a sprite.
  - Example command: `python basic.py title="Move My Player" img_path=./images/player.png width=640 height=480`

- You should be able to move your player using either the keyboard OR the mouse (don't have to do both).
- Your player should not leave the window at all (not one pixel)!
- This is exactly the stuff you put in your README (which keys or how to move).


### Helper Code

- I placed some code in [basic.py](basic.py) to help with processing command line params.
- If its confusing let me know, I can go over it on discord.


## Deliverables

- Create a folder called `P01.1` in your `Assignments` folder.
- Add a file to your folder called `game.py` with the above code.
- Screen Shots
  - Run your game with a screen size of 640x480
  - Please don't screen shot your whole desktop with our output as a tiny little window on it.
  - Include 3 screen shots with your player in various positions on the screen
  - Link to the three screen shots in your readme. Here is how to link to a file.
    - Upload the image to your repo folder. Lets say its called `screen_shot1.png`.
    - Link to it the markdwown way: `![alt text](screen_shot1.png)`. This works, but will not let you size the image.
    - Link to it the html way: `<img src="screen_shot1.png" width="300">`. This also works AND will let you pick the size.
- Add a `README.md` file to your `P01.1` folder with instructions on how to run your program guided by [R03](../../Resources/R03/README.md)


## Pseudo Rubric

- Does the program run?
- Can you move your "player" with the keyboard or mouse?
- Is movement predictable and consistent?
- Does your player stop at the edge of the window? Not one portion goes offscreen?
- Is your code commented? (Letter Grade)


