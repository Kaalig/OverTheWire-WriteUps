**Bandit Level 2-3**

Challenge : 

*The password for the next level is stored in a file called spaces in this filename located in the home directory*



As we did earlier, we are going to use `ls` to list the files in the current directory  then `cat spaces in this filename` to open it and see what happens :

![](https://github.com/Kaalig/OverTheWire-WriteUps/blob/74bdb4587749b0c83f5bfef31536bb5481c48bdb/images/Pasted%20image%2020250707194003.png)


So basically what happened is that the OS doesn't recognize 'spaces in this filename' as a file, but rather as a list of different files/directories. In order to solve this problem, we have 2 methods. 
First we can do it this way : `cat 'spaces in this filename'` put every text into those '``''``  :


![](https://github.com/Kaalig/OverTheWire-WriteUps/blob/74bdb4587749b0c83f5bfef31536bb5481c48bdb/images/Pasted%20image%2020250707194258.png)

Notice that it doesn't matter if it is one or double quotes.

Second method is by putting backslash such as : 

![](https://github.com/Kaalig/OverTheWire-WriteUps/blob/74bdb4587749b0c83f5bfef31536bb5481c48bdb/images/Pasted%20image%2020250707194347.png)



Note : In order to be easier to write, you can press tab after starting to write the beginning of the name's file.
