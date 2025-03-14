# week 1 - Day 1 - Number system.
## Decimal and binary interchangable operations.
### To go from binary to decimal use 2^n-1 , for ex number 1000 in decimal would be  1(2^3) + 0(2^2)+... = 8
### But the process of going from decimal to binary isnt as simple as that , lets say you have to get 128 in binary , you have to conduct a set of divisions of 2 , untill the reminder is unsolvable with 2 ...... 128 / 2 = 64 (reminder = 0, which would be the ones place digit of the binary ) now divide 64 with 2 and again a zero would come on tens place , again divide 32 with 2 , another 0 on hundreth place... it goes on till 10000000 comes out as an answer.
## Encoders and Decoders.
### Encoders are used to translate the decimal input from the hardware to the proccessing unit in binary form , cuz our CPU doesnt understand decimal operations so we use  encoder as a medium of translation from decimal to binary , then we place a decoder , a device which translates binary output by the cpu to decimal for convinence. Lets say , you input 7 + 2 in a calc , the encoder will then convert the input into binar y form letting the cpu process it and then the binary output for 9 that is 1001 , a decoder is placed at the end of CPU unit to convert this result in decimal that is 9. Hence the digital output 9 is observed at other end. Together these make upto , translation logic circuits.

 
