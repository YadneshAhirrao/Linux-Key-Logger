# Linux-Key-Logger

**Linux-Key-Loggerr** is a simple keylogger for Linux.
## Installation

The following instructions will install Keylogger using pip3 .

```
  pip3 install pyxhook
```

## How to run it

```
$: nohup python3 keylogger.py &
[1] 12529 //this is the keylogger's PID (process ID)
$: fg
```
1. `nohup`: This is a command used in Unix-like systems to run a command or script in the background even after the user logs out or closes the terminal. It prevents the process from being terminated when the terminal session ends.

2. `python3`: This is the command to run the Python 3 interpreter, which executes Python scripts.

3. `keylogger.py`: This is the name of the Python script you want to run. In this case, it seems to be a keylogger script, which might be used for logging keyboard inputs.

4. `&`: The ampersand symbol at the end of the command is used to put the process in the background. It allows you to continue using the terminal while the script runs in the background.

So, when you run the command `nohup python3 keylogger.py &`, it starts the `keylogger.py` script in the background, allowing it to keep running even after you close the terminal or log out of the system.

The Keylogger is now running! It will log your strokes to a file .
Stop it by typing the command `fg` then hitting `CTRL+C`

or

`kill {PID}` for example `kill 12529`


---
