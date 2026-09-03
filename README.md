# 🏀 HoopsOS

HoopsOS is a basketball-themed web operating system I made with HTML, CSS, and JavaScript. I wanted to make something that feels like a real desktop OS, but built completely around basketball.

It has apps for keeping track of games, stats, schedules, notes, basketball videos, a calculator, drawing, weather, browsing the web, and even a small basketball game.

Everything runs directly in your browser, so there is nothing to install and no server needed.

## 🚀 Getting Started

Using HoopsOS is pretty simple.

1. Open https://hoops-os.netlify.app/ in a web browser.
2. Let the HoopsOS boot screen finish.
3. Enter the desktop.
4. Double-click an app icon to open it.
5. Use the taskbar at the bottom to quickly open or minimize apps.
6. Use the search bar at the top of the desktop to find an app.
7. Right-click the desktop for extra shortcuts and options.

The windows work like a normal desktop. You can drag them around, resize them, minimize them, maximize them, or close them.

HoopsOS also works with touch controls, including long-pressing for the desktop context menu.

## 🏀 Apps

### 📋 Playbook

The Playbook is basically a basketball notepad.

You can write down plays, ideas, strategies, reminders, or anything else you want. Your notes are saved in your browser using local storage, so they can still be there when you reopen the app.

### 🏀 Scoreboard

The Scoreboard is for keeping track of a game.

You can:

* Change the Home and Away team names
* Add 1 point
* Add 2 points
* Add 3 points
* Remove a point
* Reset the score

The live score is also shown on the desktop widget.

### ⏱️ Clock

The Clock app has three different modes:

**Shot Clock**

A basketball shot clock that can be started and paused. When it reaches zero, HoopsOS can play a buzzer and show a shot clock violation notification.

**Timer**

Set your own minutes and seconds and start a countdown.

**Stopwatch**

Use it as a normal stopwatch with start, pause, and reset controls.

### 🧢 Locker Room

The Locker Room is more of a personal profile app.

It shows the player profile, jersey number, position, and a little information about the person who made HoopsOS.

### 🧮 Calculator

A normal calculator built directly into HoopsOS.

It has a simple calculator interface so you do not have to leave the OS just to do some quick math.

### 📊 Stat Tracker

The Stat Tracker is made for keeping track of basketball stats during a game.

You can increase or decrease the available stat counters and reset everything when you are finished.

### 🗓️ Schedule

The Schedule app lets you keep track of upcoming games.

You can:

* View scheduled games
* Edit opponents
* Edit game times
* Add new games
* Remove games

There is also a quick "New Game" option in the desktop context menu.

### 🎯 Hoops Shootout

Hoops Shootout is a small reaction game built into HoopsOS.

You get **20 seconds** to click as many basketball targets as possible.

Every time you hit a target:

* Your score increases
* A new target appears somewhere else
* A swish sound can play
* Confetti appears

When the timer is over, the game stops.

### 🎨 Paint

Paint is a simple drawing app.

It includes:

* Pen
* Eraser
* Color picker
* Brush size control
* Clear button
* Save as PNG

You can draw with a mouse or touchscreen and save your drawing as `hoopsos-drawing.png`.

### ⛅ Weather

The Weather app shows the current temperature and weather conditions.

HoopsOS tries to use your location for the weather. If location access is unavailable, it falls back to Dubai.

The weather data is loaded from an online weather service, so this app needs an internet connection to get current information.

### 🌐 Browser

HoopsOS has its own built-in browser.

It includes:

* Address and search bar
* Back
* Forward
* Reload
* Browser tabs
* Google
* Wikipedia
* NBA quick link
* External page fallback

The browser uses an iframe to display websites when possible. Some websites block being loaded inside other websites, so HoopsOS provides an option to open those pages in a normal browser tab instead.

### 🖥️ Terminal

The Terminal is a small command-line interface built into HoopsOS.

Type `help` to see the available commands.

```text
help
whoami
score
stats
clock
roster
ls
open <app>
clear
date
echo <text>
```

Some examples:

```text
score
```

Shows the current scoreboard.

```text
stats
```

Shows the current tracked stats.

```text
clock
```

Shows the current game clock and quarter.

```text
ls
```

Lists the installed HoopsOS apps.

```text
open calculator
```

Opens an app directly from the Terminal.

```text
echo hello
```

Prints text in the Terminal.

The Terminal also has command history, so you can use the up and down arrow keys to go through previous commands.

### 📺 Watch

The Watch app is for basketball highlights.

You can pick a highlight from the list and watch it inside HoopsOS when embedding is allowed. There is also a YouTube fallback for videos that cannot be embedded.

### 🏆 Hall of Fame

The Hall of Fame app contains basketball legends and quick facts about them.

You can select a player to see their information and open their NBA player page.

### ⚙️ Settings

Settings lets you customize the way HoopsOS looks and works.

It has five sections.

#### Appearance

Change the accent color and desktop background.

Accent colors include:

* Sunset Orange
* Bucket Red
* Court Teal
* Championship Purple
* Away Blue
* Home Gold

Desktop backgrounds include:

* Hardwood Court
* Plain
* Nebula
* Grid
* Dots
* Leather
* Arena Lights

#### Icons

Change how desktop icons look and behave.

You can adjust:

* Icon size
* Automatic icon arrangement
* Whether desktop icons are shown
* The desktop clock widget

You can also drag icons around the desktop yourself.

#### Mascot

HoopsOS has a basketball mascot that can move around the desktop.

You can:

* Turn the mascot on or off
* Make it follow the cursor
* Change its movement speed
* Change its icon

#### Sound

Turn HoopsOS sounds and effects on or off.

This includes things like the shot clock buzzer and other interface sounds.

#### About

The About section explains HoopsOS and gives some quick instructions for using it.

## 🖥️ Desktop Features

HoopsOS is more than just a collection of apps. The desktop itself has a bunch of features.

### 🔎 App Search

The Spotlight search bar at the top lets you quickly search for installed apps.

Type an app name and press Enter to launch it.

### 📌 Taskbar

The taskbar at the bottom contains pinned apps.

Click an app to open it or minimize it if it is already running.

You can also right-click an app to get more options, including pinning or removing it from the taskbar.

### 🖱️ Windows

Apps open inside their own windows.

Windows can be:

* Moved
* Resized
* Minimized
* Maximized
* Closed

HoopsOS also keeps the app windows above the desktop search area so the search bar stays where it belongs.

### 🖱️ Desktop Context Menu

Right-clicking the desktop opens a menu with shortcuts such as:

* View
* Refresh
* New Folder
* New Note
* New Game
* Open Terminal
* Display settings
* Personalize
* Settings

You can also create folders and drag app icons into them.

### 🏀 Game Clock Widget

The desktop has a basketball game clock widget.

It starts at 12:00 and includes:

* Start
* Pause
* Reset
* Next Quarter

It supports quarters and overtime periods.

### 🏀 Live Score Widget

The desktop also shows the current Home and Away score from the Scoreboard app.

### 🔔 Notifications

HoopsOS can show notifications when apps are opened or certain events happen.

There is also a notification panel accessible from the top bar.

### 🔋 Battery

When the browser supports the Battery Status API, HoopsOS can show the device's current battery percentage and charging status.

## 🎨 Design

I wanted HoopsOS to feel like a mix between a modern operating system and a basketball arena.

The interface uses dark panels, basketball-inspired colors, desktop icons, floating windows, animations, sound effects, a taskbar, widgets, and a basketball mascot.

The boot screen is also basketball themed, with fake system services loading before the desktop starts.

## 🛠️ Built With

HoopsOS is made with:

* HTML
* CSS
* JavaScript
* Canvas
* Local browser storage
* Browser APIs
* Iframe-based web content

There is no backend and no installation process.

## 💾 Data and Storage

Some parts of HoopsOS use your browser's local storage.

For example, Playbook notes are saved locally in the browser.

Other things, such as weather and embedded web pages, may need an internet connection.

## 📱 Desktop and Touch Support

HoopsOS is designed to work with both mouse and touch input.

On desktop, you can use normal clicking, double-clicking, dragging, and right-clicking.

On touch devices, you can tap apps and use long-press interactions where supported.

## 💡 Quick Start

If you are opening HoopsOS for the first time, I recommend trying these:

**Scoreboard** if you want to keep track of a game.

**Clock** if you want a shot clock, timer, or stopwatch.

**Stat Tracker** if you are tracking player stats.

**Playbook** if you want somewhere to write plays.

**Hoops Shootout** if you just want to play something.

**Settings** if you want to customize the desktop.

**Terminal** if you want to mess around with the command line.

## 📂 Project Structure

HoopsOS is currently designed as a single HTML project.

The main file contains the HTML structure, CSS styling, and JavaScript functionality needed to run the OS.

You can simply open the HTML file in a browser and start using it.

## 🏁 About the Project

I made HoopsOS because I wanted to see how far I could push a single web page and make it feel like an actual operating system.

Instead of making another normal website, I wanted it to feel like you were opening a basketball computer with its own apps, tools, games, settings, widgets, and little details.

There are a lot of small things throughout the OS that are there just to make it feel more alive, from the boot sequence and notifications to the mascot, sounds, animations, desktop widgets, and basketball themed design.

This is still a project I can keep improving, adding more apps, fixing bugs, and making the OS feel even more like a real basketball computer.

---

**HoopsOS v3**

Built with HTML, CSS & JavaScript.

🏀 Built for basketball. Built as an OS. Built by me.
