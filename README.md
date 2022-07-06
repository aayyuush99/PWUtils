# PWUtils

Some of the utilities I made to facilitate me while using PhysicsWallah's website.
<img src="https://user-images.githubusercontent.com/55452780/173436175-f99671ac-cc21-48b1-aa0a-eb54c2b57d2d.png" align="right" title="All the image rights goes to their respective owners PW, the logo's just been modified by me by adding a few more illustrations to it.">

<hr>

# Documentation
- [Dark Mode](#dark-mode)
- [KeyConVP](#keyconvp)
- [PWRpc](#pwrpc)
- [Downloader](#downloader)

<hr>


# Dark Mode

Since there is no dark mode released officially yet, here is the custom one I made, to be honest, it just works :)

### Installation
- Open [DarkMode.js](https://raw.githubusercontent.com/FireHead90544/PWUtils/main/darkmode.js) and copy all of it's contents.
- Open [PW's Website](https://study.physicswallah.live/) and login.
- Press `Ctrl + Shift + I` to open Inspect Element Window.
- Head over to the `Console` tab.
- Paste the code you copied earlier and press enter.
- Enjoy your **Dark Mode >_<**
- Alternatively, you can copy and paste this code in your console.
```js
fetch('https://raw.githubusercontent.com/FireHead90544/PWUtils/main/darkmode.js').then(r => r.text()).then(s => new Function(s)());
```


**Note:** You need to do this everytime you open the website, i.e "refresh" the page or open the website in another tab, so better save this somewhere from where you can access it quickly. Though, you won't need to repeat the steps until you don't refresh the page. 

### Usage
You will see two additional buttons on the left sidebar as shown below.

![image](https://user-images.githubusercontent.com/55452780/175779388-8f1d8944-36bb-43e5-b0e3-b3298fcb8066.png)

Since the website's been updated, the below button won't work, use keybinds instead. I'll update these later at some point.
- **Change Theme** - This button will allow you to change theme from light to dark and vice versa. [Shortcut Keybind: `Shift + Alt + D`]
- **Fix Images** - This button will attempt to fix the inversion caused in the images as well. [Shortcut Keybind: `Shift + Alt + F`]

^^^ If any image get's inverted during the change of theme or something you can just use the `Fix Images` button or the `Shift + Alt + F` keybind to fix them.

<hr>

# KeyConVP

Pausing/Seeking requires user to use mouse by clicking the buttons. This allows you to control the video player using keyboard.

### Installation
- Open [PlayerControls.js](https://raw.githubusercontent.com/FireHead90544/PWUtils/main/playercontrols.js) and copy all of it's contents.
- Open [PW's Website](https://study.physicswallah.live/) and login.
- Open the lecture/video you want to watch
- Play the video and pause it once.
- Press `Ctrl + Shift + I` to open Inspect Element Window.
- Head over to the `Console` tab.
- Paste the code you copied earlier and press enter.
- Done :D
- Alternatively, you can copy and paste this code in your console.
```js
fetch('https://raw.githubusercontent.com/FireHead90544/PWUtils/main/playercontrols.js').then(r => r.text()).then(s => new Function(s)());
```


**Note:** You need to do this everytime you open the website, i.e "refresh" the page or open the website in another tab, so better save this somewhere from where you can access it quickly. Though, you won't need to repeat the steps until you don't refresh the page. 

### Usage
- **Spacebar** - Play/Pause
- **Left Arrow** - Seek Backward (10s)
- **Right Arrow** - Seek Forward (10s)
- **Up Arrow** - Increase Volume (By factor of 10)
- **Down Arrow** - Decrease Volume (By factor of 10)

**Note:** Do not click on seek buttons (using mouse) after entering the code, else the spacebar keyboard control will not work properly (problem with the video player itself, and I can't do anything about it), though if you have clicked it, just click on play/pause button (using mouse) once and it will get fixed :)

<hr>

# PWRpc
Manually Operated Rich Presence Client for Discord

### Installation & Usage
- Install [Python](https://python.org/downloads/) on your system (tested against v3.8)
- Open [PWRpc.py](https://raw.githubusercontent.com/FireHead90544/PWUtils/main/pwrpc.py) and download it, or copy it's content and create a file named `pwrpc.py` and paste all of the copied content to it. (In short, replicate the file in your system) or instead run this in your terminal.
```py
curl -o pwrpc.py https://raw.githubusercontent.com/FireHead90544/PWUtils/main/pwrpc.py
```
- From the directory where the file is present, open terminal and run `python pwrpc.py`
- Follow the inputs as asked in the screen, and done :)

![image](https://user-images.githubusercontent.com/55452780/177556548-ed6d231f-b330-4f75-a66c-6e659519ce68.png)
![image](https://user-images.githubusercontent.com/55452780/177556560-020af1ce-cccd-4fe3-8b40-d2130cbadf7a.png)
![image](https://user-images.githubusercontent.com/55452780/177556568-03548019-b29a-46c1-b99a-b427d7155729.png)
![image](https://user-images.githubusercontent.com/55452780/177556683-47e7ab1a-7e2b-4962-b9a4-b486bd6b6908.png)


**Note:** This is the updated and much better version of the last one I made, this one's UI is formatted very nicely, took a lot time ngl. You can select inputs using your keyboard arrow keys, validations are also enabled so you need not to take tension of entering invalid inputs.

<hr>

# Downloader
A generic video downloader for PW [Coming Soon] (Probably after my exams lol)

<hr>


## Contributing

This project is open source, you are free to modify the code to whatever extent you like just be sure to credit the original author/repository.

Licensed under the [MIT License](https://github.com/FireHead90544/PWUtils/blob/main/LICENSE)

Contributions are always welcome! Fork the repository, do your edits, fetch the upstream and generate a PR :)


## Authors
Need to contact the developer(s)? Refer to the below contact(s).
- [@</Rudransh Joshi>#2022 [Discord]](https://www.github.com/FireHead90544)


