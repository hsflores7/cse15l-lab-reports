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

### Public Key on Github
Located in Github -> Setting -> SSH and GPG keys

![image](https://user-images.githubusercontent.com/103228508/167325631-e7cb75e8-7f75-43ee-a715-569a8ac21817.png)

### Private Key on Sever
Located on server account -> .ssh -> authorized_keys 

![image](https://user-images.githubusercontent.com/103228508/167325876-bc3b4c94-e13d-43dd-9c20-9ebe293c726c.png)

### Running git Commmands

![image](https://user-images.githubusercontent.com/103228508/167326991-0dc3d08e-c25d-4f55-8049-0547b7a60180.png)

![image](https://user-images.githubusercontent.com/103228508/167329354-5b426a65-5d23-4bcb-935a-9d15e85da7c4.png)


## Copy whole directories with scp -r
### Copying markdown-parse

For my understanding this image includes all of the commit file (correct me if I'm wrong)
![image](https://user-images.githubusercontent.com/103228508/167335192-a3a3a470-c094-48ff-9383-306c7a467d2f.png)

### Running tests
![image](https://user-images.githubusercontent.com/103228508/167335883-2f312382-4db9-4ece-a8ee-44b355c0a4b3.png)

### Combining scp
![image](https://user-images.githubusercontent.com/103228508/167336906-0d9e5df6-9690-47dd-bbd6-064c3e408cff.png)
