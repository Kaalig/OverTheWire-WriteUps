**Bandit - Level 1-2**

Challenge : *The password for the next level is stored in a file called - located in the home directory*


As we did with level 0-1, we are going to use `ls` to see to locate the file, then we will do `cat -` to open it :

![](https://github.com/Kaalig/OverTheWire-WriteUps/blob/026539f214fcc286d3c1c47181c64b84658a71d3/images/Pasted%20image%2020250707193303.png)

And we will see that it does nothing. In fact, the UNIX OS doesn't interpret "-" as a printed character but more as a beginning of an argument. In order to open it then, we can "hide" the filename dash by using this command : `cat ./-` 

![](https://github.com/Kaalig/OverTheWire-WriteUps/blob/026539f214fcc286d3c1c47181c64b84658a71d3/images/Pasted%20image%2020250707193519.png)


We got the flag just like that. It always never happens but it is still interesting to have this knowledge in your toolbox.
