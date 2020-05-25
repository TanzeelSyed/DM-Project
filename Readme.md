#DM 103348: Implementation of RSA Cryptography#

###PROJECT MEMBERS###
StdID | Name
------------ | -------------
**60790** | **Syed Muhammad Tanzeel** <!--group leader-->
61505 | Hafiz Hibar Khan


## Project Description ##
In this project we encrypt and dycrypt plain english text using RSA cipher. This project is implemented on C# using windows form. Our aim is to make privacy between two persons during chating,Texting that if they share secret information than it must be in decrypted form and the person who receives the message can only decrypt that information.



##Discrete Math Concepts Used ##
RSA Crytography is mainly the concept based upon Discrete Maths and computer science. RSA Crytography is used in sending messages in social media sites or application  like Whatsapp where end to end encryption is used. 
We can also use this project in various frameworks. It can be implemented in OpenSSL, wolfCrypt, cryptlib and various other cryptographic libraries.


##Problems Faced##

The problem i faced when i implementing is the encrypted text appear in something like Chinese form and it doesn't appear in Alphanumeric because after encryption i have a list of bytes. They are not alphanumeric characters but only a list of numbers that my system convert to strange characters. than i found a solution by which i can convert a list of bytes to base64 to make some readable encrypted text but it doesn't supports on large text that's why i again change it to list of bytes.




##References##

- [Github](https://guides.github.com/features/mastering-markdown/)
- [GeeksforGeeks](https://www.geeksforgeeks.org/rsa-algorithm-cryptography/)
- [Rosettacode](https://rosettacode.org/wiki/RSA_code)