# Infinite Love Script

This is a simple Python script that continuously prints "Love you" followed by the number of times it has been printed. It uses a `while` loop to run indefinitely until the script is manually stopped.

## Script Overview

The script initializes a counter `count` with a value of 1. It then enters an infinite loop, printing the message "Love you" with the current value of `count` appended. After each print, it increments the counter by 1.

### Code

```python
count = 1
while True:
    print(f"Love you {count} times")
    count += 1
```

### How to Run

1. **Install Python**: Make sure Python is installed on your computer. You can download it from [python.org](https://www.python.org/).
   
2. **Save the Script**: Save the above code in a file named `love_script.py`.

3. **Run the Script**:
   - Open a terminal or command prompt.
   - Navigate to the directory where you saved `love_script.py`.
   - Run the script by typing:
     ```
     python love_script.py
     ```

### Stopping the Script

Since this script runs indefinitely, you will need to manually stop it:
- On Windows, press `Ctrl + C` in the terminal.
- On MacOS/Linux, press `Ctrl + C` in the terminal.

### Disclaimer

This script will run indefinitely until manually stopped. Make sure to monitor the script while it's running to avoid any unwanted resource consumption.

## License

This project is open-source and available under the MIT License.