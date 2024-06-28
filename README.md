# Keylogger

This Python script (`keylogger.ipynb`) logs keystrokes interactively into a text file (`keylog.txt`) until Enter is pressed without input.

## Features

- **Interactive Logging**: Captures keystrokes interactively as they are input.
- **File Logging**: Stores logged keystrokes in a specified text file (`keylog.txt`).
- **User Control**: Stops logging upon pressing Enter without input.

## Usage

1. **Run the Script**: Execute `keylogger.ipynb` in your Python environment.
2. **Input Keystrokes**: Press keys as prompted; each key is logged into `keylog.txt`.
3. **Stop Logging**: Press Enter without input to terminate logging and the script.

## Example

```plaintext
Press a key (Enter to stop logging): A
Press a key (Enter to stop logging): B
Press a key (Enter to stop logging): C
Press a key (Enter to stop logging): 
```

Contents of `keylog.txt`:

```
A B C 
```

## Notes

- Ensure appropriate permissions to create and write to files (`keylog.txt`).
- Customize logging behavior or file handling as needed for specific use cases.
- Respect legal and ethical considerations regarding the use of keylogging software.

---
