# PRODIGY_CS_04
# 🔐 Basic Keylogger

This project implements a basic keylogger program using Python, Tkinter for the GUI, and the `pynput` library for capturing keyboard events. Please note the ethical considerations and permissions required for such projects.

## 📖 Overview

This keylogger tool records and logs keystrokes while providing basic functionality to start and stop logging. It saves the logged keys to a text file (`keylog.txt`).

## 🛠️ Features

- Start and stop logging of keystrokes.
- Logs are saved to `keylog.txt`.
- Simple GUI built with Tkinter.

## 🚀 How to Execute the Program

1. **Clone the Repository:**
   sh
   git clone <repository-url>
   cd <repository-directory>
   

2. **Install Dependencies:**
   Ensure you have Python installed. Install necessary dependencies using pip:
   sh
   pip install pynput
   

3. **Run the Program:**
   sh
   python keylogger.py
   

## 📂 Code Overview

### File: `keylogger.py`

This file contains the main implementation of the keylogger tool with a Tkinter GUI for control and `pynput` library for capturing keyboard events.

#### Imports
python
import tkinter as tk
from tkinter import ttk, messagebox
from pynput import keyboard
import os


#### Class: `KeyloggerApp`

##### Methods:

- **`__init__(self, root):** Initializes the Tkinter application.
- **`create_widgets(self):`** Sets up GUI elements including buttons and text area.
- **`start_keylogger(self):`** Starts capturing keyboard events and writes them to `keylog.txt`.
- **`stop_keylogger(self):`** Stops the keylogging process.
- **`write_to_file(self, key):`** Writes captured keys to `keylog.txt`.
- **`on_press(self, key):`** Callback function for key press events.
- **`on_release(self, key):`** Callback function for key release events.

### Usage Instructions:

- Click "Start Keylogger" to begin logging keystrokes.
- Click "Stop Keylogger" to stop logging.
- Logs are saved to `keylog.txt` in the same directory as `keylogger.py`.

## 🙏 Contribution and Issues

Contributions are welcome! If you encounter any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

### Ethical Considerations

- Ensure you have appropriate permissions and legal rights before using or distributing a keylogger tool.
- Respect privacy and adhere to ethical standards when developing or using such software.

---
