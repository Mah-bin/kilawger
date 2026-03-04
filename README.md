# Simple Python "kilawger"

A lightweight Python script that monitors and records keystrokes, logging them to a local text file. This project uses the `pynput` library to listen to keyboard events in the background and includes logic to handle both standard alphanumeric characters and special keys (such as Space, Enter, and Shift).

> **Disclaimer:** This script is provided for **educational and ethical testing purposes only**. You must only run this software on systems you own or have explicit, written permission to monitor. Unauthorized deployment of keylogging software is a violation of privacy and is strictly illegal. 

---

## Features

* **Background Monitoring:** Captures keystrokes globally across the operating system.
* **Special Key Handling:** Formats special keys cleanly (e.g., records actual spaces and line breaks for the Space and Enter keys, and tags other keys like `[Key.shift]`).
* **Real-time Logging:** Appends keystrokes to a local text file continuously.

## Prerequisites

Before running the script, ensure you have Python 3.x installed on your machine. You will also need to install the `pynput` library.

Install the required dependency using pip:

```bash
pip install pynput
