Upgrade to Python3

Python2 is approaching its end-of-life.
As such, the existing code will become increasingly difficult to maintain and enhance.

Although there are some differences, most of our project consists of calls to libraries
which already have a python3 version available.
As a result, it should be possible to write a new main loop in python3
and then, without making any significant changes to the logic, adjust the syntax for the
remainder of the code so that it will link with the new versions of those libraries 

The resulting implementation would be a drop-in replacement for the existing program
It would provide the same interfaces and responses, but run within the Python3 infrastructure.
