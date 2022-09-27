#day2 #
we exploitation 

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
