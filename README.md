# Mouser: Activity Simulator
This simple Python program, Mouser App, is designed to simulate mouse activity to prevent your computer from going into sleep mode. It's particularly useful when you want to keep your work computer active without having to restart it repeatedly.

## Table of Contents
- [Mouser: Activity Simulator](#mouser-activity-simulator)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Prerequisites](#prerequisites)
  - [Usage](#usage)
  - [License](#license)

## Introduction
When you're working on your computer and don't want it to go into sleep mode, you can use this program to simulate mouse activity. It moves the mouse cursor in a square pattern, right-clicks, and then waits for a specified duration before repeating the process. This activity keeps your computer awake and prevents it from going to sleep.

## Prerequisites   
Before using this program, make sure you have the following installed on your computer:

- [Python](https://www.python.org/downloads/) (This program was developed with Python 3. You can check your Python version by running `python --version`.)

You'll also need to install a few Python packages using pip:

- `tkinter`: This is typically included with Python but may need to be installed separately in some cases.

```bash
pip install tk
pyautogui: A Python library to control the mouse and keyboard.
pip install pyautogui
```

## Usage
- Run the program by executing the following command in your terminal or command prompt:
```
python main.py
```
- The application window will appear.

- Click the "Start" button to begin simulating mouse activity. The program will move the mouse cursor in a square pattern and right-click, preventing your computer from going to sleep.

- To stop the activity, click the "Stop" button.

- You can adjust the mouse movements and sleep duration in the code to suit your preferences.

 <div align="center"> <img src="https://github.com/QC20/Mouser-Activity-Simulator/assets/36644388/b709d702-bbaa-4671-88ae-4a759e9c88d0" width="75%" height="75%"> </div>


 ## Setup.py file
 The *setup.py* script is used for packaging and distributing Python code. In this setup configuration, it utilizes *cx_Freeze* to create an executable version of the *mouser.py* script. This allows for easy distribution and execution of the Python script as a standalone application across various platforms.

## License
Feel free to use, modify, and share this program as needed to keep your computer active and prevent it from going into sleep mode during your work sessions. If you encounter any issues or have suggestions for improvements, please open an issue on this GitHub repository.
