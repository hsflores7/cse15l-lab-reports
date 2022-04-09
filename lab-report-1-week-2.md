# Lab Report 1
[Main Page](https://hsflores7.github.io/cse15l-lab-reports/index.html)

## Instlling VS Code
1. Go to the VS Code website, looking up "vs code download" should do the trick! 
   And the select the option that is best for you! (Windows, Apple, or Linux)
  ![vs code](https://user-images.githubusercontent.com/103228508/162542180-e62e1f81-2e46-471b-8c9d-df9f231e7622.png)
2.  Accept terms and services
 	
	![vs code term conditions](https://user-images.githubusercontent.com/103228508/162582058-964f0038-1dd3-4a40-82cd-06cccf5c19ac.png)
3.  Select from options (to your liking)
4.  And your done with your setup! Enjoy!

## Remote Access Steps!
1. type in "ssh cs15lsp22XXX@ieng6.ucsd.edu" replace "xxx" with your 3 letter code.
2. You might get a question about fingerpringting and if so just type “yes”
3. Type your password (hopefully already reset, if not go do that now!!) *Additional Note: You won't see your password as you type it in so don't fear when you can't see it!* *Also! You might have to keep trying to put your password in several times even if you think you typed it right it might just say you are wrong and you need to try again.*
![Screenshot 2022-03-31 184158](https://user-images.githubusercontent.com/103228508/162582133-5ca59bc3-b837-420d-af96-e471b205e630.png)

## Commands!
* Go ahead and try commands, with the outcome I came across!
	1. cd ~
		- file system starts at home
	2. cd <file>
		- file system starts at <file>
	3. ls -lat
		- brings up a list of hidden files
		- does -a, -l, and -t things at the same time
	![ls -lat command](https://user-images.githubusercontent.com/103228508/162582225-0fd5d68f-3551-4dd0-a6cd-f5885459b1e2.png)
	4. ls -l
		- number of public files and public files
	5. ls  -a 
		- brings up files
	![ls -a command](https://user-images.githubusercontent.com/103228508/162582281-66c936e6-059b-4c87-95aa-2f9430913c5b.png)
	6. ls  <directory> 
		- *having a windows operating system causes the need for different commands (e.i. dir instead of ls)*
		- what happened on my laptop: access denied
		- what it acutally does: brings up accounts public folders
	7. ls -t 
		- brings up public folders
	8. cp <directory>
		- permission denied - likely due to the directory that was chosen couldn't have been accessed by my account(?)
	9. exit or crlt-d
		- to close/disconnect from the server

## Moving files with scp
* After creating a java file on YOUR device (so if you are logged into the server log off)
* Then you can run the **scp** command and add the file and then the server login plus ":~/" (represents you want in the home directory
![where am i edit](https://user-images.githubusercontent.com/103228508/162583014-b0193db5-b4cf-45f4-8daf-6ea8d4f876fa.png)
* To double check it worked you can log back onto the server and check the file list (with ls as pictured above)
* Then you can use javac and java to run the program from the server!

## Setting an SSH Key

	
	
	
	
	
