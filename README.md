# Structural-Health-Monitoring
** Upcoming **
Welcome to the SHM prototype, developed to aid the user in Signal processing and other ML tools. Currently it is still in development stage.

P.S: Please use Python3 for all purposes. Make sure Python3 is installed. Check the following link.
https://www.python.org/downloads/

Usage Instructions
1) Install Python3
	-> sudo apt-get install python3
	-> For a specific version of python3, eg: python3.6
		sudo apt-get install python3.6

2) Install Pip and virtualenv 
	i) Make sure Pip is up-to-date with the latest version
		-> (For Linux users only)
		-> [sudo] python3 -m pip install --user --upgrade pip
		-> Run python3 -m pip --version to verify the location

	ii) Install virtualenv on your OS
		-> (For Linux users only)
		-> [sudo] python3 -m pip install --user virtualenv

3) Run virtualenv and activate
	i) Create a project directory and enter it.
	ii) Run the command from within the project directory
		-> python3 -m virtualenv venv
		-> The second argument is the location to create the virtualenv. Generally, you can just create this in your project and call it venv.
	iii) Before you can start installing or using packages in your virtualenv you’ll need to activate it.
		-> source venv/bin/activate
		-> You can confirm you’re in the virtualenv by checking the location of your Python interpreter, it should point to the env directory. Run the following command.
			-> which python
			   .../env/bin/python

	iv) Run the command	to deactivate and exit the virtualenv
		-> deactivate

	v) Now that you are in the virtualenv, you can install packages. 
		-> pip install requests
4) Install the requirements.txt
	i) After installing virtualenv, and activating it, go to the project directory (The repository you have cloned)
	ii) Run the following command
		-> pip install -r requirements.txt
6) Check if sip is installed
	i) Once virtualenv is activated, check if sip is installed. Run the following
		-> sip -V

5) Install PyQt4 dev tools in your virtualenv.
	i) Run the following code to install
		-> sudo apt-get install python3-pyqt4
	ii) Also run the following to install pyuic4 and other tools
		-> sudo apt-get install pyqt4-dev-tools

## If everything fails,
	i) If everything fails, please install sip and PyQt4 from riverbankcomputing.com and compile both from source. Do it while the virtualenv is activated.	


Once everything has been setup, please run  
	-> [sudo] python3 SHM.py

The GUI window opens up.

Enjoy!!

