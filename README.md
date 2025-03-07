# Password-Strength-Checker


## Overview
This project is a **password strength checker** built with Python and Streamlit. It allows users to enter a password, evaluate its strength, and generate a strong password automatically.

## Features
- **Password Strength Analysis**: Checks for length, uppercase/lowercase letters, numbers, and special characters.
- **Blacklist Protection**: Rejects commonly used weak passwords.
- **Automatic Password Suggestion**: Generates a strong password if needed.
- **User-Friendly UI**: Built with Streamlit for an interactive experience.

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/password-checker.git
   cd password-checker
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the application:
   ```sh
   streamlit run password_checker.py
   ```

## Usage
1. Enter a password to check its strength.
2. If the password is weak, suggestions will be provided.
3. Click **Generate Strong Password** to get a recommended secure password.
4. Use the generated password or improve yours based on feedback.
5. Click **Sign Up** to simulate account creation (only succeeds if the password is strong).

## Technologies Used
- Python
- Streamlit
- Regular Expressions (`re` module)
- Random & String modules for password generation

## Future Improvements
- Add user authentication
- Store passwords securely using hashing
- Implement a database to store users' credentials

## License
This project is open-source and free to use.
Developed by Ayesha-Ashraf-Chandio

