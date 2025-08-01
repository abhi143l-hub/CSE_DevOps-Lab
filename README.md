# Ask user for email
email = input("Enter your email: ")

# Ask user for password (input hidden)
import getpass
password = getpass.getpass("Enter your password: ")

print("Email entered:", email)
print("Password entered: [hidden]")  # Do not print password in real use
