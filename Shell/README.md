```
Example: 

Directory: /Users/Angelo/Github/Projects/Shell

To compile the C file: gcc -lreadline myShell.c -o shellObj
To run the program: ./shellObj
[Note]: You can name the object whatever you want, I gave it shellObj for demonstration purposes

[angelo_Shell]~> ls
myShell.c  README.md  shellObj

[angelo_Shell]~> list
myShell.c  README.md  shellObj

[angelo_Shell]~> pwd
/Users/Angelo/Github/Projects/Shell

[angelo_Shell]~> printwd
/Users/Angelo/Github/Projects/Shell

[angelo_Shell]~> cd ..

[angelo_Shell]~> printwd
//Users/Angelo/Github/Projects/

[angelo_Shell]~> chdir Shell/

[angelo_Shell]~> printwd
/Users/Angelo/Github/Projects/Shell

[angelo_Shell]~> history

 1) ls
 2) list
 3) pwd
 4) printwd
 5) cd ..
 6) printwd
 7) chdir Shell/
 8) printwd
 9) history
[angelo_Shell]~> help

		 Help Menu:
-------------------------------------------------------

	 The commands that this Shell supports:
~> ls or list : for listing the the files and directory of your current Directory
~> pwd or printwd: Prints out the current working directory
~> cd .. -OR-  cd [stateDirectory]: to either go back to one directory; 
		 or change into a given directory
~> chdir .. -OR- chdir [state_directory]: to change directory
~> history: view the previously entered commands
~> Arrow key: Goes back to previously entered commands
~> exit: Terminates the shell

[angelo_Shell]~> exit

Thank you. Goodbye


```
