

Challenge : 

*The password for the next level is stored in a file called readme located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.*


For this one, we're gonna use the command `ls` to list the files in the directory, and then using `cat readme` to open the file `readme` if he is actually there :

![](https://github.com/Kaalig/OverTheWire-WriteUps/blob/23f816f1662e7337b47accefe04bfce0b680c30c/images/Pasted%20image%2020250707192512.png)

And he was ! By opening it we got the password of this level that we're gonna use to connect to the level 1 to 2 using SSH.

Note : Don't forget to save your level passwords in a text file or you will have to start all over again.

