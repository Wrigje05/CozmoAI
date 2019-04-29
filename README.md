# CozmoAI
Using AI with Anki Cozmo

# Goals
- solve robot kidnap problem
1) take images
- rotate and take images
- save images to particular folder
2) Stitch images
- stitch the images for a panorama view
- maybe grayscale it
- consider low res to make it easier to work with
3) get lost
- program random movements to "kidnap" itself
4) read the scene
- have it understand where it is

# Setup:
- use a python editor

# Installation: https://developer.anki.com/blog/learn/tutorial/getting-started-with-the-cozmo-sdk/

- For windows: 
1) Developer website: https://developer.anki.com/
- Click "Get Started" page
- Go to "Installation-Windows"
2) Download latest version of Python from Python.org
- during installation, tick the "Add Python to Path" checkbox on setup screen on the first screen of the installer
- install
3) Get the Cozmo SDK files onto computer
- On the python installation on the windows install page (where you just were)
- open up command prompt
- (optional) pin the command prompt to task bar for quick/easy access to SDK
- use command: ""pip3 install --user cozmo[camera]""

- Mobile device setup for Android
1) from Cozmo SDK website click "Android Debug Bridge" page
2) click "link" to download "platform-tools-latest-windows.zip"
3) click "open folder"
4) Open new files explorer window
5) go to your user folder, such that you see "Desktop", "Contacts", "Favorites", "Pictures", etc.
6) Create new folder "Android" (note: this is case-sensitive)
7) Go inside "Android" folder
8) move over the downloaded "platform-tools-latest-windows.zip" into the "Android" folder, then extract all
9) go into the folder "platform-tools-latest-windows" and go into the "platform-tools" folder
10) right click start menu, select "system", "Advanced system settings", "Advanced", "evironment variables"
11) "User variables for user" > "Path" > "edit"
12) in "edit environment variable" > "new" > add path to adb
- this should be in the format of "C:\Users\name\Android\platform-tools-latest-windows\platform-tools"
13) click "ok" on everything

- to double check you have it setup properly
1) open "Command Prompt" > enter "adb" and enter

- Final Installation step
1) enable USB debugging on android device
- find "build number" from "settings" > "about phone" and tap it 7 times
- "settings" > "developer options" > "enable USB debugging" enable it
2) connect phone to computer
3) command prompt > "adb devices"
4) with cozmo app running, connect phone to robot
5) In app on phone, go to main menu > "settings" > "Cozmo SDK" > "Enable SDK"

- Get some programs
1) on computer developer site > go to "Downloads" page > "Windows SDK Examples"
2) in command line > navigate to the folder you have the examples in (look for "Cosmo SDK examples" folder)
3) Extract the files (remember where you extracted to)
4) in command line, navigate to where you have "Cozmo SDK examples" and go to their tutorials

- Run a code
1) go to the program you want to run: ""cd 01_basics""
- run "Hello World" program
2)in command prompt


#) To install OpenCV use the following: pip install openCV-python


# Sources:
Set up:
- https://www.youtube.com/watch?v=9TJeK_AEFYo
- https://web.archive.org/web/20171218032016/http://www.mobileway.net/2015/02/14/install-opencv-for-python-on-mac-os-x/
- https://blogs.sap.com/2018/07/30/cozmo-read-to-me/
