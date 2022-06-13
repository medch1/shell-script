## Development



**First** 
Write script in python 


**Second**
Mark your Python file as executable
```sh
$ chmod +x mycmd.py
```

**Third**
remove extension
```sh
$ mv mycmd.py mycmd
```
**Finally**
Make sure your program is on the PATH
```sh
$ mkdir -p ~/bin
```
```sh
$ cp mygit ~/bin
```
```sh
export PATH=$PATH":$HOME/bin"
```

Add the this line to .profile or .bash_profile in your home directory: 
```sh
export PATH=$PATH":$HOME/bin".
```
You can either use an editor to do it or run the following command to do that: 
```sh
echo 'export PATH=$PATH":$HOME/bin"' >> .profile
```






#### TEST

For production release:

```sh
$ mycmd Hello, World!
/Users/youruser/bin/mygit
Hello,
World!
```
