
Q1. pwd prints your current location on the computer. Basically, it shows the absolute path of the exact folder youre in right now.

Q2. ls shows normal, visible files in the folder you’re currently looking at. Whereas, ls -a shows all the hidden files too as well as the visible files.

Q3. The first column in ls -l shows the file’s type and the access permissions of that file.

Q4. Coding-cafe/week02 is a relative path. It works from where we are standing because it is interpreted relative to where you are actually present in the computer right now. It works because the coding-cafe folder exists inside my current directory. It is a relative path because it doesn’t start from the root directory.

Q5. mv first moved the file README-Backup.md to week01 folder and then it was used to renamed the folder.

Q6. There are 14 folders in my path.

Q7. /Library/Frameworks/Python.framework/Versions/3.14/bin/python3

Q8. No, the two paths are not the same. This might be because i use macOS and he uses linux.

Q9. The shell said:
zsh: command not found: pyton3
The shell looked through all the folders in my PATH for a program called pyton3, but it couldn't find one. This is because pyton3 is an error. It should be python3.

Q10. This is because .venv is a hidden file/folder. ls -a shows hidden files.

Q11. .venv appeared at the beginning of the prompt which meant that a box was activated.

Q12. It showed a path pointing to the Python executable inside the .venv folder, instead of the system Python path. Activate changed my PATH so that the virtual environment's Python is found first.

Q13. The first pip list (right after creating the venv) shows almost nothing — just pip and maybe setuptools. After running pip install requests, the second list adds requests 

Q14. It removes .venv from the front and the shell goes back to finding the system python first.

Q15. ls -h is the same as ls as it shows only the non hidden files/folders.

Q16. Ctrl+C sends an interrupt signal that forcibly kills whatever's currently running
     Ctrl+D is an end of input signal similar to the exit signal. It basically exits the program. 

