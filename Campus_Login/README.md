<h1>Campus Internet Login</h1>

<ul>
	<li><h3><a href="#description">Read the description</a></h3></li>
	<li><h3><a href="#how-should-i-use-the-script">How to use it?</a></h3></li>
	<li><h3><a href="#automate-the-script">Automatically run the script on startup</a></h3></li>
</ul>


<h2>Description</h2>
This script is designed for SMVDU students to automate their internet login process. We are logged out automatically if our internet connection is idle for a certain period of time, and this happens quite a lot with us. This Script is currently designed for linux users only, but soon (in a day or two) it will be available for windows as well as mac users. There may be any problem with someone using it, please tell me on facebook, so that I could improve it. 

<h2>How should I use the script?</h2>

Follow these steps to use the script:

1. <a href="#download-this-way">Download</a> these two files namely, login.py and dependencies.sh. 
2. Open file login.py in your favorite text editor and put your entry no. and password in line no. 22 and 26 respectively. Now save the file.
3. Open file dependencies.sh in text editor and put your computer user_name instead of lavee_singh in line 13 and 15. Now save the file.
4. Open terminal and run dependencies file using 
	```
	sudo sh dependencies.sh
	```
5. Now you can set the script to run <a href="#automate-the-script">automatically</a>. If you do so, you will automatically be logged into your internet account on startup of computer. But if you don't want so, you can login to your internet account anytime just by typing ```login.py``` in the terminal. And you can delete dependencies file now.

<!-- 5. Convert the login.py into executable by using:
	```
	chmod a+x login.py
	```
6. Run the file by:
		a. double clicking and and choosing run option.
		b. running ```./login.py``` command in terminal -->


<h2>Automate The Script</h2>
To run this script automatically on computer startup, follow these steps:

1. Press ```alt+f2``` and typing dash should appear.
2. Type ```gnome-session-properties``` and open that application.
3. Now click `add` button to add a new startup command, a pop-up will appear.
4. Type anything in <b>name</b> and <b>comment</b> section, but in command section type ```login.py```, and click `add`.
5. Close the dialog box and you can check the script, by logging out of account and then restarting computer, or by typing ```login.py``` in the terminal.

<h3 >Download this way</h3>
To download a file, follow these steps:

1. Click on the file, this will open a new layout.
2. Click on the ```raw``` button on right-upper corner of the editor division. This will open the file content in raw mode.
3. Press ```ctrl+s``` to save/download the file.