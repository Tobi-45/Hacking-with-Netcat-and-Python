# Hacking-with-Netcat-and-Python
In this method, with the help of [Netcat tool](https://nmap.org/ncat/) you can create a [reverse shell](https://www.acunetix.com/blog/web-security-zone/what-is-reverse-shell/) on the victims device, and if you are on the same network you can easily access it. But the problem here is that you cannot always have access to the victims device to execute the ***netcat command*** soo, I got an idea, what if you write a python script which will automate the command for you, and if you add some fancy code that the victim will see on his device before creating a shell, that makes it more appealing. So in this post, I will share this method with you.

## Is it my idea ??
 I think, I got this idea while solving the machines/box. Where, in any input box if you type a command that lets you have a reverse shell on the targets website and you get a shell access on the webserver. All I did was just overthink and take the idea to a next level.

## A Personal note from writer.
 This is my first time creating a proper Github post, soo plz let me know if there is anything missing or something, I did wrong. 

# Method
Its a simple but very effective way that a hacker might use to hack their Target. In this type of attack, the attacker will be on your same network as you and send a python script that if you execute, will open a shell on a certain port that the attacker might connect to and try to do anything on your device. Lets see how its Done...

First Lets understand how to create a Reverse shell with Netcat command


The post is not complete, I am still working on it. Plz share your thoughts on it.
