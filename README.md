# Keylogger using Python with pynput

This Python script enables keylogging functionality using the `pynput` library, allowing you to monitor and log keystrokes on your system. It captures both standard keys and special keys like Shift and Ctrl.

## How it Works

The script utilizes the `keyboard` module from `pynput` to listen for keypress events. When a key is pressed, it checks if it's a special key (e.g., Shift, Ctrl) and logs it accordingly. The logged keystrokes are stored in a file named `keylog.txt`.

## Usage
1. Clone the repository or download the script.
2. Ensure you have Python installed.
3. Install the `pynput` library using pip: `pip install pynput`.
4. Run the script (`python keylogger.py`).
5. Press keys, and the keystrokes will be logged in `keylog.txt`.
