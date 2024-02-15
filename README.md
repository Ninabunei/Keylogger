# WHAT IS A KEYLOGGER
A keylogger is a software that monitors and keeps track of keystrokes as you type.
I will be using a  macbook hence we first have to bypass the standard security measures put in place.
## INSTALLING PYNPUT
we will be using the pynput module to listen to mouse events. start by installing this module 
execute pip install pynput on your terminal.
To check if it has been installed properly , run "import pynput" on your IDLE no error should occur 

## BUILDING THE KEYLOGGER
1.Create a new Python file and import Key and Listener from pynput.keyboard and the logging module
2. Next set a variable which points to where you want to save the logs; leave this as an empty string to save the log beside the python script. Then set up the logging module.
3.Then create a definition for keypresses called on_press which takes key as a parameter. In this definition, we want to log the key using the logging info method. The key will need to be cast to a string before logging it.
4.Next setup an instance of Listener and define the on_press method in a with statement and then .join() the thread to the main thread.

 
