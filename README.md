# Zoom-bot

Python program to automatically join the online zoom classes based on the given input in the "meetingschedule.csv".

##Modules##

use pip install {name of modules given below}

Modules used:
1. keyboard
2. time 
3. subprocess
4. pyautogui
5. pandas 
6. datetime
7. pillow

##Requirements##

1. Zoom app must be installed in your system.
2. You must be logged in to your Zoom account.
3. Meeting time for the day along with Meeting ID and passcode must be entered manually into the "meetingschedule.csv"
4. check your settings of your zoom app(like join audio on joing classes)
5. Python - Download and install from https://www.python.org/downloads/

##steps##

1. Change your location of zoom app at line 29
2. Change x and y coordinates at line 32 [coordinates on your screen where join button located at the zoom application]
3. Extract MousePosition32bit.zip file and run the apllication to see your x and y coordinates of your join button and then enter on line 20
4. open "meetingschedule.csv" enter the schedule time in the editor in correct columns in the correct format


Time :hh:mm [24 hrs format] Meeting ID : 123456123 (string) Meeting Password : 1234 (string)

5. make sure to close all windows and free up the desktop (my program runs on Image Recognition and automatic movement of your mouse )

run main.py

6. keep an eye out in case of errors and failures I am not responsible for any troubles caused to you if the program does not function as intended, or if it is misused, please make sure to test it before executing

7. do not let the computer sleep when there is long intervals between lectures
8. edit run.bat file and add path of your python.exe and your .py file
9. if you don't want to do this type of coding stuff then you can use zoom bot.rar file,
   it is direct exe file of coding but you need to edit schedule.isc file according to your class schedule.

