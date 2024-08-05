READ ME

COMMUNICATION CONTRACT:

This is a microservice application that takes input Dollar amounts, uses an API to check exchange rates, and then generates a conversion to Euros based on the input information. 

API USED:
This application uses the free version of the following API: https://www.exchangerate-api.com/  - in order to generate a key, you must go through the sign up process on the website

HOW TO REQUEST DATA FROM CONVERTER.PY

To request data from this converter, you must start the converter.py application first. Then, the requesting application should create/modify an 'input.txt' file that is hosted in the same directory as the converter.py file. The converter searches for
and reads the input.txt file every 15 seconds, clearing the data from input.txt after it reads it, so as to not repeat the conversion.

HOW TO RECEIVE DATA FROM CONVERTER.PY

The converter.py program writes to a file called 'output.txt' hosted in the same directory as the converter application. In order to receive the data, the program must be able to read text files and extract the conversions from that txt file. 

Example call:
C:\Users\mibra\Desktop>python requester.py
Enter dollar amounts to write to the input file (type 'done' to finish):
Enter amount in dollars: 251.32
Enter amount in dollars: 1222215.32
Enter amount in dollars: 500
Enter amount in dollars: 457.35
Enter amount in dollars: done
Written 4 amounts to input.txt

Amount in Euros:
230.49
1120893.67
458.55
419.44



![UML](https://github.com/user-attachments/assets/289915ad-ad0e-4bee-ad09-8bff6531da6d)









