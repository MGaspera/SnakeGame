# Capybara Platformer
A simple platformer attempt using pygame

# Required Libraries: <br>
***Pygame*** <br>
(installation instructions from https://www.pygame.org/wiki/GettingStarted)  <br>   Pygame requires Python; if you don't already have it, you can download it from python.org. It's recommended to run the latest python version, because it's usually faster and has better features than the older ones. Bear in mind that pygame has dropped support for python 2.

The best way to install pygame is with the pip tool (which is what python uses to install packages). Note, this comes with python in recent versions. We use the --user flag to tell it to install into the home directory, rather than globally.

``` python3 -m pip install -U pygame --user``` 

To see if it works, run one of the included examples:

``` python3 -m pygame.examples.aliens``` 

***os***
os allows us to search through various directories. Currently, it's being used to locate the "images" folder, which stores all the sprites and the background.


#Assets
***Background***
"STRINGSTAR FIELDS" by trixelized on Itch.io: https://trixelized.itch.io/starstring-fields

***Player Sprite***
"Charlie the Capybara by niffirgGames on itch.io: https://niffirggames.itch.io/charliethecapybara
