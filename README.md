# vsCodeCLI
Angular Application Built Using the CLI

Documentation of process to do initial commit of this angular application

CLI Project -ANGULAR 
	GETTING STARTED

FOLLOWED THE STEPS SHOWN HERE
http://candordeveloper.com/2017/04/12/how-to-use-angular-cli-with-visual-studio-2017/
	
Blank ASP.Net Web Solution in Visual Studio
Install Node JS 
	NOTE YOU WILL NEED TO Make sure the destination folder below has permissions granted to EVERYONE for this install to work 
	x = your user name 
			C:\Users\x\AppData\Local\Temp

Then from git bash on repo location (c:\users\x\source\repos\AngularProject)
	Disable firewall to get this to run successfully
		ng new angularTestCLI --routing --skip-git --directory angularTestCLI
		
		Depricated Package so Installed this 
		npm install --save core-js@^3

To create a component 
	ng generate component [name] 

	VS Code would not let me run the commands below this line so ran this first
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned
