# Bcrypt Hash Generator

[https://github.com/charlpcronje/Bcrypt-Hash-Generator](https://github.com/charlpcronje/Bcrypt-Hash-Generator)

## Overview
This Python script is designed to generate secure bcrypt hashes from plain text strings. It's particularly useful for hashing passwords in a secure manner, using the bcrypt hashing algorithm, which is widely recognized for its cryptographic strength.

## Requirements
- Python 3.x: Ensure Python 3 is installed on your system.
- bcrypt library: A Python library that provides bcrypt hashing utilities.

## Installation
Before running the script, you need to install the bcrypt library. This can be done using pip, the Python package manager. Run the following command in your terminal:

```bash
pip install bcrypt
```

## Usage
To use the script, run it from the command line with a single argument: the string you wish to hash.

Syntax:

```bash
python bcryptHashGenerator.py [string_to_hash]
```

Replace `[string_to_hash]` with the string you want to convert into a bcrypt hash.

### Example
To hash the string "mySecurePassword", you would run:

```bash
python bcryptHashGenerator.py mySecurePassword
```

The script will output the bcrypt hash of "mySecurePassword".

## How It Works
The script performs the following steps:
1. Takes a string as input and encodes it into bytes.
2. Generates a salt using bcrypt's `gensalt()` function.
3. Creates a hash using the input string and the generated salt.
4. Decodes the hashed bytes back into a UTF-8 string and prints it.

## Security Notes
- While bcrypt is a robust and secure hashing algorithm, remember that no security measure is infallible. Regularly review your security practices.
- Do not store plain text passwords. Always store the bcrypt hash.
- Keep your hashed passwords secure and follow best practices for password management and security.

## Contributing
Contributions to this script are welcome. Please follow standard Python coding conventions and provide documentation for any changes.

## License
This script is released under the MIT License. For more details, see the LICENSE file in the repository.

## Contact
- Author: Charl Cronje
- Email: charl.cronje@mail.com
- LinkedIn: [https://www.linkedin.com/in/charlpcronje](https://www.linkedin.com/in/charlpcronje/)
- [https://github.com/charlpcronje/Bcrypt-Hash-Generator](https://github.com/charlpcronje/Bcrypt-Hash-Generator)
---

## Additional Resources
- [bcrypt documentation](https://pypi.org/project/bcrypt/)
- [Python 3 documentation](https://docs.python.org/3/)

