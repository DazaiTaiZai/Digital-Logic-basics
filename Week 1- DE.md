# week 1 - Day 1 - Number system.
## Decimal and binary interchangable operations.
### To go from binary to decimal use 2^n-1 , for ex number 1000 in decimal would be  1(2^3) + 0(2^2)+... = 8
### But the process of going from decimal to binary isnt as simple as that , lets say you have to get 128 in binary , you have to conduct a set of divisions of 2 , untill the reminder is unsolvable with 2 ...... 128 / 2 = 64 (reminder = 0, which would be the ones place digit of the binary ) now divide 64 with 2 and again a zero would come on tens place , again divide 32 with 2 , another 0 on hundreth place... it goes on till 10000000 comes out as an answer.
## Encoders and Decoders.
### Encoders are used to translate the decimal input from the hardware to the proccessing unit in binary form , cuz our CPU doesnt understand decimal operations so we use  encoder as a medium of translation from decimal to binary , then we place a decoder , a device which translates binary output by the cpu to decimal for convinence. Lets say , you input 7 + 2 in a calc , the encoder will then convert the input into binar y form letting the cpu process it and then the binary output for 9 that is 1001 , a decoder is placed at the end of CPU unit to convert this result in decimal that is 9. Hence the digital output 9 is observed at other end. Together these make upto , translation logic circuits.
## Introduction to hexadecimal number system and base.
### Base of a number basically informs you about the number of bits it will hold. lets say a number 10 with base 10 (base 10 is used for decimal numbers , 2 for binary and 16 for hexadecimal ) says "There are 10 objects" where as number 10 with base 2 says there are 2 objects. So when a number is presented , a base should be specified. 
## Bin to Hex conversion and vice versa.
### When you are dealing with microcontrollers of different sorts , there is a 8/10 possibility you might encounter a conversion b/w hexadecimal and binary. To do this we simply use a 4 bit operation. To convert a Binary number to hexadecimal we divide binary numbers starting from ones place in 4 bit operators and write specific hexadecimal number for them using the 2 to the power method ... for example the number 10001001 is divided as 1000 and 1001, the first is easily 8 and 1001 is 9, therefore the result is 89. In hexadecimal system , alphabets are used from 10 to 16 , simply use them if the result exceeds 10:).

### To convert hexadecimal to binary we will use, just reverse the process. For ex - C9 with base 16, we just write binary codes for both of them and put em all together. For C or 12 , we have 1100 and for 9 we have 1001. Therefore the answer is , 11001001.

## Decimal to Hexadecimal conversion and vice versa.
### To go from hexa decimal to decimal system , things are similar to binary to decimal conversion , the only change is we use 16 instead of 2 , so to convert 2B to decimal , we will multiply 2 by 16 to the power 1 and B aka 11 to 16 to the power 0 and add them , therefore the answer is 32 + 11 = 43. 43 to the base 10 to be precise :0. Now to go back from decimal to hexa , we will use similar process as binary just divide it by 16 and keep a record of remainders. For ex - 43 with base 10, we will divide it by 16 , the first remainder will be 11, and then 32 divided by 16 is 2 .. therefore the answer is 2 and 11 aka B , 2B.

## For octal operations refer textbook .


 
