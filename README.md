# Jarvis
Jarvis is an open-source Python project designed to bring the power of automation and artificial intelligence to your computer. Named after the intelligent AI assistant from the Iron Man movies, Jarvis aims to simplify and enhance your daily computing tasks.
A Personal Assistant for Linux, MacOS and Windows

Jarvis

Jarvis is a simple personal assistant for Linux, MacOS and Windows which works on the command line. He can talk to you if you enable his voice. He can tell you the weather, he can find restaurants and other places near you. He can do some great stuff for you.

Getting Started With Installation
In order to install Jarvis, follow these steps:

Clone this repository with git clone https://github.com/sukeesh/Jarvis.git
Run the command python installer (or python3 installer if that doesn't work) from the terminal.
Run Jarvis from anywhere by command jarvis, or ./jarvis from within the project directory to start up Jarvis!

You can start by typing help within the Jarvis command line to check what Jarvis can do for you.

Frequently encountered issues
Question: When I run Jarvis, it shows an error relating to module not found
Platform: Windows
Solution 1: Uninstall and/or install the module package
Example:
Error: ImportError: DLL load failed while importing win32api: The specified module could not be found.
Solution:
pip uninstall pywin32
pip install pywin32 or conda instapll pywin32
Solution 2: add the package to your environment variables system PATH.

If you find other issues and/or have found solutions to them on any platform, please consider adding to this list!
