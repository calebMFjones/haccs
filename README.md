# haccs
Python program used to check if your password has ever been hacked.
This program takes the passed in password, runs it through a SHA1 hash and checks if the first 5 of that hash key are found
in the hacked passwords database at pwnedpasswords.com. It then returns how many times your password has been hacked. 
If no hacks are reported, it will let you know it is still secure.

Run the program from the command line followed by the password you would like to check, see below:

>>>python checkmypass.py mysupersecretpassword<br>
mysupersecretpassword was found 3 times. You should probably change your password!
