# basic-keylogger
This basic keylogger script is built using the pynput library in Python. It captures keyboard inputs in real-time and logs them into a text file named "keyfile.txt". Each key press is recorded, including alphanumeric characters, special keys, and modifiers.

The script utilizes the on_press event handler from the pynput.keyboard module to detect key presses. When a key is pressed, the keyPressed function is triggered, which retrieves the pressed key's character representation. If the pressed key is an alphanumeric character, it is logged into the "keyfile.txt" file.

Please note that this keylogger is a simple implementation and may lack advanced features present in more sophisticated keylogging software. It serves as a basic demonstration of keyboard input capture using Python and pynput.

For improved functionality and security, consider using more advanced keylogging solutions or adding additional features, such as encryption, stealth mode, or remote monitoring capabilities.

Important: It's essential to use this keylogger responsibly and ethically. Unauthorized use of keylogging software to capture sensitive information without proper consent is illegal and unethical. Always ensure that you have permission to monitor keyboard activity on any device.
