# Checking If Python is Installed

If you are using some Linux flavour, there is a 99.99% chance that you already have Python already installed.

First, know what version do you have with (run it inside a terminal)

	$ python --version

if you got something like

	Python 2.7.2+


Congratulations, you have Python in your System, YAAAAAY!!!.

# Wait!, There is some not found mumbo jumbo D:

In that case you must install Python or If you have a lesser Python Version (< 2.7) you should install a newer one, but **do not remove the installed version**.

So,  What Python version is better,  2.7.x or 3.x?, Well there are some little differences between them. But 2.7.x have more compatible libraries.


### Installing From The PPA
We will use an Ubuntu based distro for the following commands. 

This is the most easy way, if you have a non Ubuntu based distro you should use the source Luke! (or the package manager from your distro).

	$ sudo add-apt-repository ppa:fkrull/deadsnakes

	$ sudo apt-get update

	$ sudo apt-get install python2.7 python2.7-dev





 