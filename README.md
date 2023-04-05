# Example-code-
This repository is linked to my stackoverflow, this is mainly where i share code examples to help other developers on the platform. All code is saved in readme.md files

import subprocess
import tkinter as tk

def execute_command():
    command = "Example code" #This is where you put your code
    subprocess.run(command, shell=True)

root = tk.Tk()

button = tk.Button(root, text="Execute Command", command=execute_command)
button.pack()

root.mainloop() 
