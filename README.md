# SiakJover

**Sick of losing the battle? Still fighting manually with `Ctrl+F` and endless scrolling?** 😫 <br> Fear not! <br> SiakJover is here to streamline your war with minimal effort. Just make sure you have a decent internet connection! 😄

## Setup Instructions

### 1. Download Required Files

   - **Get Python**: This code runs on Python, so you'll need to have it installed. If you don’t have it, download it from https://www.python.org/downloads/. An IDE is a bonus but not required.
   - **Download SiakJover**: You can clone the repository (use terminal) or download the ZIP file.
```
git clone https://github.com/Sl1ckThread/SiakJover.git
```
![how to clone in terminal](./ignore/clonning.png)

   - **Open Terminal** : Open command prompt or terminal depending on your operating system
   - **Navigate to the Folder**: Open your command prompt (Windows) or terminal (macOS/Linux) and change the directory to your SiakJover folder using:

```
cd siakjover/siakwar
```


### 2. Install Required Python Libraries

   You’ll need a couple of Python libraries. Run the following commands in your command prompt or terminal:
```
pip install selenium
```
   Add `--user` behind it if you encounter error installing the library

### 3. Configure the `config.txt` File

   Open the `config.txt` file and update it with your username, password, and subject codes. You can find it by going to the directory  stated on the terminal
   
![how to navigate to config](./ignore/configedit.png)

   To find the matkul code you are looking forward can be found by hovering the subject you want
   
![how to find matkul code](./ignore/matkulcode.png)

### 4. Run the Program

   - Execute the program using the command:
```
     python siakjover.py
```
`If you are NOT on windows`, please download the correct chromedriver based on your operating system (linux/mac) on https://googlechromelabs.github.io/chrome-for-testing/
Replace the current chromedriver in the folder with the one you installed
### 5. Follow the Prompts

   - The program will automatically open a browser window and try to log in using the credentials from `config.txt`.
   - It will then navigate to the course selection page and start selecting subjects based on the codes you provided.
   - If there are issues with logging in or finding subjects, the program will show error messages.

## Whatsupp with testground?

I have created a specific folder for you to test the code. Please make sure to edit the config.txt file as needed. Then, navigate to the testground directory in your terminal by running cd testground, and execute the script with python siakjover.py.

To test the changes for the matkul code, run the Python file first and hover over the desired matkul code you want to test.

## Warnings!!

Do not `Go back one page` or you will break the program

## Troubleshooting

- **Login Issues**: Verify that your username and password in `config.txt` are correct. Ensure your internet connection is stable.
- **Browser Issues**: Make sure Chrome and ChromeDriver are properly installed and up-to-date.
- **Non-Windows Users**: If you're not on Windows, download the correct version of ChromeDriver for your operating system (Linux/macOS). Place the ChromeDriver executable in the SiakJover folder and, if needed, the testground folder for testing purposes.
- **Program Errors**: If an error occurs, it will be printed in the console. Check these messages for guidance.
- **Terminal Errors** : If for somewhat reason your terminal went stuck and unable to load and want to restart the program, press `Ctrl+C` on the terminal to keyboardinterrupt

## Credits

I took inspiration from the legendary Co-author SiakTzu, Hocky, Dennis and Galang. I have modified their codes to my liking.  

## Contact

For further assistance, text me via discord sl1ckthread
