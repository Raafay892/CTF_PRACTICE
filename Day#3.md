#day3#
#picoCTF#

where are the robots
 | 100 points 
AUTHOR: ZARATEC/DANNY

Description
Can you find the robots? https://jupiter.challenges.picoctf.org/problem/56830/ (link) or http://jupiter.challenges.picoctf.org:56830

Hints 
What part of the website could tell you where the creator doesn't want you to look?
Solution:
Just open the robots.txt file and got the clue as 
User-agent: *
Disallow: /1bb4c.html
open the file 1bb4c.html

Flag : picoCTF{ca1cu1at1ng_Mach1n3s_1bb4c}

