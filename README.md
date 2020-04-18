# facebook-phising
Warning: Only meant for educational purpose. The author is not responsible for what a reader does with this info.
The author doesn't promote unethical hacking, or any illegal activity.
Its intended towards ethical hackers, so they can learn to protect themselves.
Also, i believe this code won't work anymore in 2020 with modern browsers and websites.

**Do not break the law!**

------

My source code was inspired by other authors.

 I made this back in 2012. To hack into a Facebook account through the Phising Technique.    

This project was inspired by my "Orkut" phising project which i made back in 2010.(Also uploaded on the github)

First, a link(of login_again.htm) is sent to the victim and he opens it. Thinking its the real fb login page, he enters all the login info. When he clicks on the signin button, instead of being logged into fb, his login details are written on a file named lol.txt. I can access that file from the host website and I have his login credentials now.  

This has 3 files. Which I hosted on a free server.

1. login_again.htm
2. index.php
3. hello.php


login_again.htm was made by first copying the source code of the fb login page. Then modifying it.

index.php has reference to hello.php

hello.php creates a lol.text file. And then writes the username and password to it.

