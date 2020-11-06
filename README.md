# Screen Time App
This app records the usage time for each specified app. It shows these times in a bar chart. It also saves the times so that it can show the total usage time on previous days. This app was built using python and is intended for use on Windows 10.

[All Releases](https://github.com/Vynokris/ScreenTime/releases)

[Direct Download (Latest Release: v1.4)](https://github.com/Vynokris/ScreenTime/releases/download/v1.4/Screen.Time.v1.4.zip)

### 1. General information
- If the app is closed, times are saved.
- If the app is open and the date changes, the times are saved to the day they were recorded.
- You can change tab using the dropdown menu at the top. The default tab is "Today".
- The default update interval of the timer is 5 minutes. This means time will be added to the timer only every 5 minutes. To change this, see number 4.

### 2. Tab: "Today"
![Tab: "Today"](https://i.imgur.com/dnUQV9H.png)
- Today's times are shown in a bar chart in the middle of the window.
- At the bottom, today's total time is shown.
- The "Details" tick box enables/disables the individual app times (under the app names on the chart).
- The button at the top left pauses/resumes the timer.
- The button at the top right saves the times to the day they were recorded.

### 3. Tab: "History"
![Tab: "History"](https://i.imgur.com/vAZSMNc.png)
- This tab shows a list of the total time of previous days. 
- First is the date, then the total time, and then the mainly used app.
- You can use the scrool wheel of your mouse to go down the list and show older days.

### 4. Tab: "Options"
![Tab: "Options"](https://i.imgur.com/3gz59O6.png)
- You can enter the timer update interval in the first line.
- You can change the list of apps that you use in the second line. This is caps sensitive. To know the name of an app in windows 10, you can hover over the app icon in the taskbar, the name should show up in white at the top. Entering only a part of the app name is possible (ex: "YouTube - Google Chrome" can be shortened to "YouTube"). All app names must be separated by a comma and a space: ", " (ex: "YouTube, reddit, Twitch, Google Chrome, Other").
- You can change the name exceptions in the third line. This is used to detect an app by its name, but show another on the chart. Enter the app name followed by a colon and then the shown name. Multiple name exceptions must be separated by a coma and a space: ", " (ex: "YouTube:Youtube, reddit:Reddit" 1st app name is "YouTube" and 1st shown name is "Youtube", 2nd app name is "reddit" and 2nd shown name is "Reddit")
- On the fourth line, you can make the app start on windows startup (boot) by ticking the box.
- On the fifth line, you can make the app minimize instead of closing when the red cross is clicked by ticking the box.
- You can open the app files directory in the windows explorer by pressing the "Open file directory" button.
- You can open this help document by pressing the "Help" button.
