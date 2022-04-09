# Lab Report 1
[Main Page](https://hsflores7.github.io/cse15l-lab-reports/index.html)

## Instlling VS Code
1. Go to the VS Code website, looking up "vs code download" should do the trick! 
   And the select the option that is best for you! (Windows, Apple, or Linux)
  ![vs code](https://user-images.githubusercontent.com/103228508/162542180-e62e1f81-2e46-471b-8c9d-df9f231e7622.png)
2.  Accept terms and services
  ![vs code term conditions](https://user-images.githubusercontent.com/103228508/162542423-735c9124-6d0b-43c5-9805-c1652476acd9.png)
3.  Select from options (to your liking)
4.  And your done with your setup! Enjoy!

## Remote Access Steps!
1. type in "ssh cs15lsp22awu@ieng6.ucsd.edu" 
2. You might get a question about fingerpringting and if so just type “yes”
3. Type your password (hopefully already reset, if not go do that now!!) *Additional Note: You won't see your password as you type it in so don't fear when you can't see it!*
![Screenshot 2022-03-31 184158](https://user-images.githubusercontent.com/103228508/162542966-4176c5e0-732a-4f0a-882f-5076e2a7aa49.png)

## Commands!
* Go ahead and try commands, with the outcome I came across!
	1. cd ~
		- file system starts at home
	2. cd <file>
		- file system starts at <file>
	3. ls -lat
		- brings up a list of hidden files
		- does -a, -l, and -t things at the same time
	![ls -lat command](https://user-images.githubusercontent.com/103228508/162543941-3d44722e-efd8-4f07-9354-396e4c2c1d4d.png)
	4. ls -l
		- number of public files and public files
	5. ls  -a 
		- brings up files
	![ls -a command](https://user-images.githubusercontent.com/103228508/162543927-056c7446-7490-496c-94cf-282e47190199.png)
	6. ls  <directory> 
		- *having windows causes the need for different commands (e.i. dir instead of ls)*
		- access denied (could be because their password isn’t work atm)
		- brings up accounts public folders
	7. ls -t 
		- brings up public folders
	8. cp <directory>
		- permission denied - likely due to the directory that was chosen couldn't have been accessed by my account(?)
	9. exit or crlt-d
		- to close/disconnect from the server

## Moving files with scp
