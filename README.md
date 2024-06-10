This code validates email addresses entered by the user.

Features:

Checks minimum length (at least 6 characters)
Ensures presence of a single "@" symbol
Verifies valid domain extension (., .com, etc.)
Detects invalid characters (spaces, uppercase letters, non-alphanumeric symbols except _, @, and .)
How to Use:

Save the code as a Python file (e.g., email_validator.py).
Run the script from your terminal: python email_validator.py
Enter your email address when prompted.
Output:

"Valid email!" for correctly formatted addresses (Note: Original code might print "Invalid email" here, this needs correction)
"Invalid email" for addresses with errors
Limitations:

This basic validation doesn't guarantee a deliverable email address.
More robust validation might involve checking MX records for valid domains.
