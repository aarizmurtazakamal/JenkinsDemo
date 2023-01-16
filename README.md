# JenkinsDemo

Jenkins Demo Readme!

This project is for integrating Github with Jenkins

step 1: install Git into your server

Step 2: install Jenkins and run on your server

Step 3: Use Git clone to clone this project.

		git clone HTTPS URL

Step 4: Login into Jenkins GUI (Graphic user interface) Console.

Step 5: Go to New Item

Step 6: Put name JenkinsDemo ---> choose freestyle Project

Step 7: Give a good discription accordingly.

Step 8: Go to SCM (Source Code Managment) ---> choose Git

Step 9: Give your remote repository URL which is created using GITHUB.

	    EX:-https://github.com/aarizmurtazakamal/JenkinsDemo

Step 10: Click on ADD under credentials

Step 11: Give Username and Password for your GITHUB in Required feild and Add it.

Step 12: Select the Credentils created from Drop-Down.

Step 11: Go in Build Trigger Section.

Step 12: Check Box Poll SCM

Step 13: Define a Schedule for checks for automatic Build for change in Source code.

	     EX:- H/5 * * * *

Step 14: Go to Build Enviroment and select Add timestamps to the Console Output

Step 15: Go to Build Steps Select Execute Shell from drop down

         put the Execute Command
		 EX:-
		 javac hello.java
         java HelloWorld
         javac age.java
         java age
         javac Pattern.java
         Java Pattern

Step 16: Click on Apply and Save

Step 17: Click on Build now form Jenkin Console

Step 18: Right Click on Build NO #1 ----> Console Output

Step 19: Check for Successfuly Output (Hurrrrray !)

Step 20: Any cahnges on SCM (Source code will automatically Trigger Build)

Thanks you!




