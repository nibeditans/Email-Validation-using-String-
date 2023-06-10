# Email-Validation-using-String-

The "Email Validation Using String" project is a Python program designed to validate email addresses based on certain criteria. It prompts the user to enter an email address and performs a series of checks to determine its validity.

The program follows the following validation steps:

Length Check: Ensures that the length of the email address is at least 6 characters.
First Character Check: Verifies that the first character of the email address is an alphabet.
"@" Symbol Check: Checks if the "@" symbol is present in the email address and ensures that it appears only once.
Domain Extension Check: Uses the XOR operation to verify if the domain extension is correctly placed with either a 3-character or 4-character format.
Character Validation: Iterates through each character of the email address and performs specific checks:
Whitespace Check: Identifies if there are any whitespace characters.
Uppercase Check: Determines if any alphabetic characters are in uppercase.
Digit Check: Skips over any digits encountered.
Special Character Check: Allows certain special characters such as underscore (_), period (.), and "@" symbol and skips the rest.
Other Character Check: Considers any other character encountered as invalid.
Based on these checks, the program provides feedback on the validity of the entered email address, displaying either "Correct Email" or a specific error message indicating the reason for invalidity.

Repository Structure:

email_validation.py: The Python script containing the email validation code.
README.md: This file, providing an overview of the project.

Feel free to explore the GitHub repository for more information and the complete source code of the project.
