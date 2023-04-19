# Twitch Chat Key Scanner #

This is a simple Python script that scans a Twitch channel's chat for activation keys and automatically enters them into the text box. It uses the IRC protocol to connect to the Twitch chat and the pynput library to simulate key presses.

## Requirements ##

This script requires Python 3 and the pynput library. You can install pynput by running 

** pip install pynput **


## Usage ##

+ Clone this repository to your local machine.
+ Navigate to the directory containing the script.
+ Open the script in your preferred code editor and replace the input statements with your own Twitch username, OAuth token, and the channel you want to scan.
+ Run the script using the command python main.py.
+ Place your cursor on the text box where you enter the activation key.
+ The script will start scanning the chat for activation keys. When it finds one, it will automatically enter it into the text box.

## Notes ##

This script is intended for educational purposes only. Use it at your own risk.
The script currently only supports activation keys in the format XXXXX-XXXXX-XXXXX.
The pynput library may not work on all operating systems. You can get your [key here](https://twitchapps.com/tmi/).
