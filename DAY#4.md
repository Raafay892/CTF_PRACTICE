# CTF_PRACTICE #
Include some practice of CTF

3login#
 | 100 points 
AUTHOR: BROWNIEINMOTION
Description
My dog-sitter's brother made this website but I can't get in; can you help?
login.mars.picoctf.net

HINT:
NONE 

SOLUTION:

just open the source code and got two files .js and .css
 opened both of the files and got the clue in the .js file where i got the clue in the code 
 password was encoded in the base64 
 using the simple base 64 decode  https://www.base64decode.org/
 converted the following code: cGljb0NURns1M3J2M3JfNTNydjNyXzUzcnYzcl81M3J2M3JfNTNydjNyfQ
and finally got the flag 
FLAG: picoCTF{53rv3r_53rv3r_53rv3r_53rv3r_53rv3r}


