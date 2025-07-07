**Bandit - Level 3-4**

Challenge : 

*The password for the next level is stored in a hidden file in the inhere directory.*



They talk about a hidden file in the inhere directory, that means we're going to use `ls -a` whereas the argument means listing all files, including hidden file in a directory. First we're going into the directory by using the command `cd` :

![](https://github.com/Kaalig/OverTheWire-WriteUps/blob/238ccdb5df428ef2813e17af8bf6364d9a7fccc5/images/Pasted%20image%2020250707194909.png)

Notice that I used ls without any argument and that didn't returned anything. Using `ls -a` we come across a file named "...Hiding-From-You", let's open it : 

![](https://github.com/Kaalig/OverTheWire-WriteUps/blob/238ccdb5df428ef2813e17af8bf6364d9a7fccc5/images/Pasted%20image%2020250707195055.png)
