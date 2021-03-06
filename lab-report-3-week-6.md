# Lab Report 3
[Main Page](https://hsflores7.github.io/cse15l-lab-reports/index.html)

## Streamlining ssh Configuration

### Config File
Add these lines:
`Host ieng6`
`HostName ieng6.ucsd.edu`
`User cs15lsp22<your-three-letter-code>`

![image](https://user-images.githubusercontent.com/103228508/167325344-6cf83cee-9661-4774-97b6-8db7a3cf7f31.png)

### ssh Login
Now you can log in with the shortcut you made, which is the first line of your config file `ieng6`
![image](https://user-images.githubusercontent.com/103228508/167325399-35c143da-8308-44a9-8e8b-2c3e38bf25b0.png)

### scp Command with Login
You can also run command from your local device with the `scp` command using your new shortcut!
![image](https://user-images.githubusercontent.com/103228508/167325204-bda08e5a-fd70-4829-9dce-812078f69c66.png)



## Setup Github Access from ieng6
Setup a key on GitHub then you can run push from your ieng6!
### Public Key on Github
Located in Github -> Setting -> SSH and GPG keys

![image](https://user-images.githubusercontent.com/103228508/167325631-e7cb75e8-7f75-43ee-a715-569a8ac21817.png)

### Private Key on Sever
Located on server account -> .ssh -> authorized_keys 

![image](https://user-images.githubusercontent.com/103228508/167325876-bc3b4c94-e13d-43dd-9c20-9ebe293c726c.png)

### Running git Commmands
*Adding a line to commit*

**pull command**

![image](https://user-images.githubusercontent.com/103228508/167326991-0dc3d08e-c25d-4f55-8049-0547b7a60180.png)

**commit command**

![image](https://user-images.githubusercontent.com/103228508/167329354-5b426a65-5d23-4bcb-935a-9d15e85da7c4.png)

**push command**

Could not get it to work so far but you would use the `git push origin main` command after adding and commiting within the 
directory you want to push to GitHub.

Here is the problems I ran into (several other TAs have been unable to find a solution):
![image](https://user-images.githubusercontent.com/103228508/168731778-8ab5bbd8-e908-4e37-a38d-94bd6343475b.png)

* It seems that the Disk on my server account is full and I don't know how to empty or force it to give more space and this occured when I tried the url-set command with the SSH link from GitHub
* Another possible problem is the keys but I've tried a lot of different key things and had several TAs set up keys with me and none of them seems to remove the problems of having to put in the password for GitHub on the server.
Here is [my Piazza Post](https://piazza.com/class/l0lgl3r7ph370k?cid=609) about it as well if you have any ideas of how to solve the problem(s)
## Copy whole directories with scp -r
### Copying markdown-parse

For my understanding this image includes all of the commit file (correct me if I'm wrong)
![image](https://user-images.githubusercontent.com/103228508/167335192-a3a3a470-c094-48ff-9383-306c7a467d2f.png)

### Running tests
![image](https://user-images.githubusercontent.com/103228508/167335883-2f312382-4db9-4ece-a8ee-44b355c0a4b3.png)

### Combining scp
![image](https://user-images.githubusercontent.com/103228508/167336906-0d9e5df6-9690-47dd-bbd6-064c3e408cff.png)
