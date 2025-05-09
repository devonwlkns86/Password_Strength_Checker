# Password_Strength_Checker Program 

import re

password = input("Enter Your Password: ")
if len(passwordr) < 8:
    print("Password must be at least 8 characters long.")
elif not re.search("[A-Z]", password):
    print("Password must conntain at least one uppercase letter.")
elif not re.search("[a-z]", password):
    print("Password must contain at least one lowercase letter.")
elif not re.search("[0-9]"):
    print("Password must contain at least one number.")
else:
    print("Password is strong.")
