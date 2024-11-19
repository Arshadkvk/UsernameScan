# Email Enumeration Script

This Python script enumerates valid email addresses by interacting with a web application's login functionality. It simulates login attempts and checks the server's response to determine if an email address is valid or not.

## Features

- Sends HTTP POST requests to test email validity.
- Reads email addresses from a file and processes them.
- Logs valid and invalid email addresses.
- Outputs a list of valid emails for further use.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/Arshadkvk/email-enumerator.git
   cd email-enumeration
   
## Steps to Update and Run the Script

1. **Update the script**:
   - Replace the `url` variable in the script with the actual endpoint of the login functionality.
   - Adjust the `invalid_error` variable to match the server's error message for invalid emails.

2. **Prepare an email list**:
   - Create a file (e.g., `emails.txt`) with one email address per line.

3. **Run the script**:
   ```bash
   python3 script.py emails.txt

4. **Example Output**:
   - [INVALID] test@example.com
   - [INVALID] test@example.com
     
   - Valid emails found:
   - valid@example.com



