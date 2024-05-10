# Keylogger Project

This project consists of two files: game.sh and off.py. Together, they create a covert keylogging mechanism that captures keyboard inputs without the user's knowledge.

# Introduction:

A keylogger is a tool used to record keystrokes made by a user on a computer. While keyloggers can have legitimate purposes, such as monitoring computer activity or debugging software, they can also be exploited for malicious activities like stealing sensitive information such as passwords or credit card numbers.

# Files:

1. game.sh
The game.sh script serves as the initiator of the keylogging process. When executed, it instructs the off.py script to run in the background, quietly capturing keystrokes.

# Usage:
To initiate the keylogging process, simply execute the game.sh script from the command line.

2. off.py
The off.py script is the keylogger itself, written in Python. It listens to keyboard inputs and logs them into a hidden file named .keylog.txt.


# Instructions:

Setup Environment:
Ensure that you have Python 3.x installed on your system.
Initiate Keylogger:
Run the game.sh script to start the keylogging process. This will instruct off.py to run in the background and create a hidden file to store the captured keystrokes.
View Logs:
The captured keystrokes are logged into a hidden file named .keylog.txt, located in the same directory as the off.py script.

# Disclaimer:
Warning: This software is provided for educational purposes only. The misuse of this software for malicious purposes is illegal and unethical. The author(s) of this software are not responsible for any damages or legal consequences resulting from the misuse of this software. Always respect the privacy and rights of others.
