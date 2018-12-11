# Dindo Bot

[![Python](https://img.shields.io/badge/python%20%3E%3D-2.7-blue.svg)](#)
[![GTK](https://img.shields.io/badge/gtk-3.0-brightgreen.svg)](#)
[![OS](https://img.shields.io/badge/os-Linux-orange.svg)](#)

Farming bot for Dofus game.

![screenshot](screenshot.gif)

## Installation

First, you need to install some dependencies using one of the following commands:

**Debian & derivatives:**
```bash
sudo apt install python-gi gir1.2-gtk-3.0 gir1.2-wnck-3.0 python-xlib python-pil
```

**Arch Linux & derivatives:**
```bash
sudo pacman -S python-gobject python-xlib python-pillow
```

To run the bot:
```bash
cd /path/to/bot
python bot.py
```

To run the bot in developer mode (brings some additional features):
```bash
python bot.py --dev
```

**Note:** you can also run the bot from the [desktop file](dindo-bot.desktop).

## To Know

- Dindo bot use screen pixels to interact with the game client, so it's not a socket bot or even not a MITM bot.
- Is it detectable by the Anti-bot?
> It shouldn't be, because it imitates exactly the human behaviour, but as a conclusion, nothing is 100% safe.
- The main goal of this bot is to simplify repetitive tasks and reduce boredom during your game play.
- Also, the bot does not encourage multi-boting and does not support it anyway.
