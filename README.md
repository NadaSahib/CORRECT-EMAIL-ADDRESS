# CORRECT-EMAIL-ADDRESS
CHANGE EMAIL ADDRESS

def extract_username(email):
    # Split the email address at the '@' symbol to separate the username and domain
    parts = email.split('@')

    # The username is the first part before the '@' symbol
    username = parts[0]
    
    return username

# Example email address
email_address = "nitish24singh@gmail.com"

# Extract the username from the email address
username = extract_username(email_address)
print(f"The username is: {username}")
