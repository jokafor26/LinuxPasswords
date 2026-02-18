# LinuxPasswords

Linux Passwords

In this lab I came into a problem where I did not remember my password for my user account, so a “Login incorrect” prompt would appear. A reason why a “Login incorrect” error might occur when trying to log into a system is because the I might have entered the either the username or password incorrectly by adding a capital letter instead of lowercase, because passwords are case sensitive. Another reason is because the account could be disabled due to me putting in too many incorrect passwords. could have been locked by the admin, or I’m trying to login into the wrong machine.



An example of poor passwords which are security risks are:
•	Centos – This password is related to the software being used so its easy to guess if someone is hacking into it & it does not have a mix of letters and numbers.
•	Qwerty1234 – This password is a very well-known password; it has a mix of numbers and letters, but it is too simple
•	12345 – This password is too short. An error would occur if trying to use this password. The error that would be displayed is “BAD PASSWORD: it is too short”
•	cYber - is not acceptable, it is too short. it is also too simple, so it is possible for it to be easily guessed or cracked using software. There is also no mix of letters and numbers, No mix of capital and lowercase letters.

If you cannot log into your account, you could change the password by using the root account if all other solutions fail. Before doing that, you must verify that all usernames and passwords are correct. See the /etc/password file to confirm you have the right spelling for the username account you are trying to connect too. Must make sure you are logging into the right account.


I’m going to use the root account to change my user account by first using the # passwd jokafor command which prompted me to input a new password. I’m going to input a bad password like cat. An error occurs when I change it too dog because it is too short, does not contain different letters and numbers, and is too simple as well as well known.

 ![Image](https://github.com/user-attachments/assets/4da633f4-35e6-4b80-a99e-37c6c4bd16a7)

After changing it to an acceptable password it works and changed. It has a mix of capital and lower-case letters and has numbers; it is also not a well-known place.

 ![Image](https://github.com/user-attachments/assets/b4f87ace-1268-4c78-bac3-3bca81be00e7)

I could display the man page for shadow in section 5 of the system you would have to type in man shadow 5 then press enter. It will show the options h for help q for quit
 
![Image](https://github.com/user-attachments/assets/804aac4e-f4ff-4f53-9525-c5699bda6200)

