# Excel_Password_Manager
Lightweight Excel password manager. This is not aimed at replacing existing solutions such as LastPass or Keeper. This solution is for environments that do not allow for the use of password managers or may have intermittent internet access. 

This Password manager utilizes a SHA1HMAC to hash the master password. While there are other cryptographic and hashing methods available such as AES, those often require the instalation of version 3.5 of the .NET Framework. You may have version 4 installed which 3.5 is a subset of, it is not enabled by default. I initally wanted to create a password manager that will work in a default environment. In my use case I did not have access in order to enable version 3.5. 

V1.1 Fixed bug found with Error handling

V1.2 Added password for developer access

V1.3 Fixed bug with lock value 

Default admin password to access the developer window is Admin. I recommend changing this right away. This can be done through the vbproject properties. Right click on the project when you have opened the developer view. Select properties and you can change the password in there. 

Features I am looking to add:
- Method of updating the master password
- Adding a choice for encryption and hashing methods for individuals that have version 3.5 of the .NET Framework installed and enabled. 
