Disclaimer
--
Development environments are as personal as taste in music, food, or art. With these notes,
I merely aim to present *one* possible solution for getting started with Django. There are
many others. I encourage you to find the tools that work best for you, and make sense for
your work flow.

Steps
-- 

1. Python.org 
  * Git for windows (Presentation: Do Windows tip)
2. Download Python Highest numbered python (3.6.4 as of time of writing)
3. Run the installer, check the "Include Python in path" check box
4. After install, click the "Disable path length limit" button
5. Win+r -> type "cmd" to open a command line
6. pip install virtualenv
7. pip install virtualenvwrapper-win
8. mkvirtualenv <projectName>
9. pip install django (Presentation: Do windows Tip)
10. pip install pylint
11. Install Editor (VSCode used during Demo)
12. `code .`
13. Install the `Python` extension from within VSCode
14. To configure you're manually installed version of pylint, use Ctrl+, to open VSCode
Settings, and enter: `"python.pythonPath": "C:/Users/<username>/Envs/<envname>/Scripts/python.exe"`
15. django-admin startproject indypy
16. python manage.py migrate
17. Continue Tutorial at: https://docs.djangoproject.com/en/2.0/intro/tutorial01/


Windows Tips:
--

* To see the path of an executable, use `where python` - this will show you whether you're
running the system's python, or a virtualenv's version of python

* Use Win+<Left> or Win+<Right> to snap a window to the left or right. After first window
is snapped, windows allows you to select an other window to pick for the other side

* Type `explorer .` (note trailing period) to open an explorer window at the current
command line location.

* Type `cmd` or `powershell` in Windows Explorer address bar to open that console at that
path 

* From a `cmd` session, use the Up arrow key to re-type a previous command in the
window. Press enter to re-execute it

* While typing a path in a `cmd` window, press the TAB key to auto-complete the folder
or file name within the current folder (also called directories on Mac & Linux)

* Consider using an alternate Command Shell, Like Console2, or ConsoleZ

* Clear REPL console in windows:
```
>>> import os
>>> clear = lambda: os.system('cls')
>>> clear()
```
