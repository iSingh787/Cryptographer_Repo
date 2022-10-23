PROBLEM DEFINITION:

These days, data security is getting more significant in information stockpiling and transmission. Pictures are generally utilized in various cycles. Subsequently, the 
security of picture information from unapproved utilizes is significant. Picture encryption assumes a significant part in the field of data covering up. Picture 
encryption technique arranged data incomprehensible. Consequently, no programmer or snoop, including worker executives and others, approach unique message or 
some other kind of sent data through open organizations, for example, internet.



EXISTING SYSTEM:

1. There is no alternative to attempt every one of the calculations together in one framework. 
2. There is no advantage for the client to send the scrambled message to other individual as a mail. 
3. There is no data set stockpiling for the current framework. Further recovery of the code is absurd. 
4. The framework don't check for any confirmation. Any client can scramble also, unscramble. 
5. It is simple for an intruder (third party) to get to the content and he can make his own progressions in it.


PROPOSED SYSTEM:
•	Characters in information to be scrambled are assembled into blocks; each square contains a predefined number of characters. This square is changed over to a number. 
A XOR key, which has the very number of pieces with the size of pieces of the whole number that addresses the square of characters is created. XOR activity is then 
performed between the produced key and the whole number that addresses the square. The subsequent whole number is then changed over to encoded character which could be 
sent over vehicle of correspondence organization.
 
•	To decode the information, scrambled character is changed over to a number utilizing similar number of characters utilized during encryption measure. The subsequent
number is XORed with the XOR key, the number got because of this activity is then changed over back to characters equivalent to the quantity of characters as contained 
in the block before encryption. Figure 1 is the flowchart of the program that is utilized to test the improved calculation. Figure2 is the flowchart that shows the 
improved XOR calculation for encryption measure. 
