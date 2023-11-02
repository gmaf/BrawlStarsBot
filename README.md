# BrawlStarsBot
Brawl stars bot for farming mastery through solo showdown. 
## Info
Inspired by [OpenCV Object Detection in Games Python Tutorial playlist by "Learn Code By Gaming"](https://www.youtube.com/watch?v=KecMlLUuiE4&list=PL1m2M8LQlzfKtkKq2lK5xko4X-8EZzFPI) 

Used yolov5 for object detection, followed ["How To Train YOLOv5 For Recognizing Game Objects In Real-Time" by "Jes Fink-Jensen"](https://betterprogramming.pub/how-to-train-yolov5-for-recognizing-custom-game-objects-in-real-time-9d78369928a8) (might need to sign in to medium), tutorial for how to get started with yolov5.

****Demo of the bot: https://youtu.be/kp5izpAKA-Y****

Bluestacks app player is used to emulate brawl stars onto computer. Bluestacks default game control is modified.

## Requirement
* [Bluestacks 5](https://www.bluestacks.com/download.html) to run brawl star
* Python>= 3.8.0 installed

## How to run the bot?
1. Clone repo and install the required library
```
git clone https://github.com/Jooi025/BrawlStarsBot.git
cd BrawlStarsBot
pip install -r requirements.txt
```
2. Change deafault brawl star game control

Modified game control I used:
![Alt text](control/controlSetup.jpg?raw=true "Example of gamecontrol in Bluestacks")

Game control scheme (com.supercell.brawlstars.cfg) as shown can be found at the [control folder](https://github.com/Jooi025/BrawlStarsBot/tree/main/project/control), you would need to import com.supercell.brawlstars.cfg to the control editor of Bluestacks [(tutorial on how to import game control)](https://support.bluestacks.com/hc/en-us/articles/360056129291-How-to-import-your-game-controls-from-BlueStacks-4-and-use-them-in-BlueStacks-5). Macro is intergrated into the code to automate when "player" is defeated, it will queue up for another match.




