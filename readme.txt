Todo
====

* Download and install wamp: http://www.wampserver.com/en/
* Download and install git: https://git-scm.com/downloads
* Create an account on github: https://github.com
	Repository: https://github.com/Maarten3107/RasMar

	- Go to www folder of wamp server, create subfolder called "RasMar" and navigate into this folder
	- Right click and choose "Git Bash Here"
	- In the commandline that just opened, type "checkout https://github.com/Maarten3107/RasMar.git"
	- Start wampserver and copy following url in your browser: "localhost/Rasmar" or "127.0.0.1/Rasmar" --> This should open up the website
	

After doing some work you can check in your code:
* Navigate to the created subfolder in the www folder, right click and choose "Git Bash Here"
* Type in "git add ." (this will add all the changes you made)
* Type "git commit -m '<Type message here>'" --> Type the main changes between the brackets <>
* Type "git push"

To check the status between your local files and the github, type: "git status"

To pull changes from github, type: "git pull"