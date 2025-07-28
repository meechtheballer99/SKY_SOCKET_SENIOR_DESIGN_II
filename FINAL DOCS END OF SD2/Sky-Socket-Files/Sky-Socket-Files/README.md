There are two ways to access our project:
- Installer: A windows EXE installer. It will install the required files,
	download and configure a custom embedded python, and create a start
	menu icon, installer, and launcher. Due to 2 curl requests, a CMD
	window will appear asking for your user's password. This is the only
	way to automate this process through CMD without installing other
	dependencies. The password is purely local.
- Soucre Code: All of the files installed with the installer but lacking a
	python environment to be run in. If you are against using the
	installer, the setup.bat file shows all the commands/links needed
	to create your own custom python installation.
