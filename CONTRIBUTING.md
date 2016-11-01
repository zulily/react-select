# Contributing
This is a fork from parent repository https://github.com/JedWatson/react-select. 

## These are the contribution details specific to Zulily employees

### Build the changes you made to the repository. 

* Install gulp globally.
	* npm install -g gulp

* Build the repository
	* gulp build

* Checkin your changes.
	* git push

* Go to react-datum repository

* If you have created a new branch and are trying to test it make sure react-datum/package.json has the right branch
	* Under dependencies change to add beanch "react-select": "git+https://github.com/zulily/react-select.git#<branchName>"

* Now npm install react-select so you get the latest updated code
	* npm install react-select

* Note that grunt watch does not pickup the changes. You need to manually npm install.  




