# HoopsOS

HoopsOS is a lightweight, high-performance web operating system built using HTML, CSS, and JavaScript. The entire operating system, including its window manager, application suite, and custom desktop UI, is packed into a single HTML file with zero external dependencies.

Live Site: https://hoops-os.netlify.app/

---

## What is Inside

* Playbook: A simple note-taking application for writing down plays or quick thoughts. Notes automatically save directly to your browser's local storage.
* Scoreboard: A score tracking tool for Home and Away teams with quick point addition and a global reset button.
* Shot Clock: Standard 24-second and 14-second shot clock timers with start, stop, and reset controls.
* Terminal: A command-line interface supporting commands like `help`, `clear`, or launching system applications directly by name (`playbook`, `scoreboard`, `shotclock`, `settings`).
* Settings: An application that allows you to change the system's accent color dynamically.

---

## System Features

* Window Manager: Features draggable windows, click-to-focus depth layering (`zIndex`), minimizing, and closing.
* Desktop and Dock UI: Dynamic desktop icons and a bottom system dock with active app indicator lights.
* Court Design Theme: Dark theme styling with a top menu bar showing an active real-time clock.

---

## How to Try It

Open https://hoops-os.netlify.app/ in any web browser. Everything runs directly in the browser with no build steps, dependencies, or installations required.

---

Built for the Stardance Web OS project.
