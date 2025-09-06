# CapybarasGameWithHandTracking

## ABOUT THE GAME

You are a Capybara with a water hose, and you have to extinguish the max number of fire possible in 120 seconds, and then, you put your name on a leaderboard, with the number of points you got, so you can keep the competitiveness with your friends!

And you control the capybara just with the power of your hands! without a keyboard, mouse or controller.

It was made with the intention to represent what Pantanal in Mato Grosso do Sul (Brazil) faces today, and aware people of it.

<img width="1917" height="1077" alt="Captura de tela 2025-09-05 211625" src="https://github.com/user-attachments/assets/7acef941-819f-432e-965e-6bb49297faa4" />

_Gameplay screenshot_

I made and used this system and game for a big exposition at my school. fell free to add or ask anything.

### SYSTEM USED:
#### GTX 1660 SUPER 
#### RYZEN 7700 
#### 32GB OF DDR5 6000MHZ 
#### W11
250-300 FPS 1080p, CPU not even at 25% usage. Anything modern should run fine.

ALL THE ASSETS HAVE THE ORIGINAL CREATOR MENTIONED


## SETUP


For that project, I used [Unity 3D 6000.1.15f1](https://unity.com/pt/download) and [Python 3.11.9](https://www.python.org/downloads/release/python-3119/).

I highly recommend you to use some version of [Python 3.11](https://www.python.org/downloads/release/python-3119/) or [3.12](https://www.python.org/downloads/release/python-31211/), because MediaPipe does not have support for 3.13 yet. (for now)

libraries:
ctypes, keyboard, opencv, MediaPipe, and pyautogui. Just do the simple "pip install -------".

### NOTICE:

These libs can be a little bit tricky to install, so make sure you [set the PATH to the correct Python](https://youtu.be/OdIHeg4jj2c?si=eP2Jr4AQZgKEoaGb) and you're not using the Microsoft Store version.
And to help you, I made a [simple script to check if all the libraries are OK](libtest.py), I recommend running it just to make sure.


## RUNNING

### Hand Tracking

Just import [the folder](handtrackingforcapybara/) to your IDE and run it, a window with your webcam should open.

### Game

Just open [CapybaraGame.exe](CapybaraGame.exe) and the game will pop up in a few seconds. and import the [source code](CapybaraSourceCode.zip) to Unity after your unzip it if you want to have acess to the project.

## Troubleshooting

### Common Issues:

Camera not detected: Check if other apps are using your webcam

Libraries not found: Run the libtest.py script

Performance issues: Lower Unity resolution if needed

Python PATH errors: Follow the PATH setup guide

_Please open an issue if it persists_


