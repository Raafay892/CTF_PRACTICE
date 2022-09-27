#day2 #
web exploitation 

GET aHEAD
| 20 points
 

Author: madStacks
Description
Find the flag being held on this server to get ahead of the competition 
http://mercury.picoctf.net:47967/

hint:
1.Maybe you have more than 2 choices
2.Check out tools like Burpsuite to modify your requests and look at the responses
 just run the below  head command with curl 
 curl -I HEAD -i http://mercury.picoctf.net:47967/index.php
we got the flag :
flag: picoCTF{r3j3ct_th3_du4l1ty_cca66bd3}

Cookies
| 40 points
Tags: 

Author: madStacks
Description

Who doesn't love cookies? Try to figure out the best one. http://mercury.picoctf.net:27177/

hint :
no hint was given 

Solution :
solution uses the addon "Cookie manager and cookie editor" which is used to edit the value of cookie which is set to -1 
increasing the value to 18 and then  refreshing the webpage we got the flag.

flag : picoCTF{3v3ry1_l0v3s_c00k135_064663be}

Insp3ct0rHow do you inspect web code on a browser?

 | 50 points
 
AUTHOR: ZARATEC/DANNY

Description
Kishor Balan tipped us off that the following code may need inspection: https://jupiter.challenges.picoctf.org/problem/9670/ (link) or http://jupiter.challenges.picoctf.org:9670

Hints:
How do you inspect web code on a browser?
There's 3 parts.

Solution:
Just open the source code and got the clue of flag here in comment:   picoCTF{tru3_d3
Then got the js and css files where i got the other two parts of the flag.
1.t3ct1ve_0r_ju5t
2._lucky?2e7b23e3}
flag: picoCTF{tru3_d3t3ct1ve_0r_ju5t_lucky?2e7b23e3}

Scavenger Hunt
 | 50 points 
AUTHOR: MADSTACKS

Description
There is some interesting information hidden around this site http://mercury.picoctf.net:39491/. Can you find it?

Hint:
You should have enough hints to find the files, don't run a brute forcer.

Solution :
just open the main page source got the first part as
picoCTF{t
now open the js and css file we got 
h4ts_4_l0
now get the directories using sublist3r or any other tool
now go to the robots.txt
we get the third part
t_0f_pl4c
now go to the .htaccess file we get the 4 part 
3s_2_lO0k
now go to the .DS_Store file we get the 5 part 
 _f7ce8828}
 and finally we complete the flag 
 
 flag: picoCTF{th4ts_4_l0t_0f_pl4c3s_2_lO0k_f7ce8828}
