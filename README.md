# ttk-Breeze
a Tk / ttk theme similar to the KDE standard theme Breeze

![Screenshot](https://github.com/MaxPerl/ttk-Breeze/blob/master/Screenshot.png) 


## To Use

Instructions for how to use the theme in Python <br>
These instructions assume you already have tkinter and python installed

1. Copy the source into your project directory
2. Type the lines 
```from tkinter import ttk, Tk
root = Tk()
s = ttk.Style()
root.tk.call('source', '/absolute/path/to/project/ttk-Breeze/breeze.tcl')
s.theme_use("Breeze")
```
3. Make sure all your tkinter widgets are actually ttk widgets, like `ttk.Label()`
4. Run your code and enjoy the theme!
