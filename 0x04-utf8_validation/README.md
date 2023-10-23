# 0x04-utf8_validation

## Author
Joseph Williams

## Project Sponsor
ALX SE

## Contact Information
- LinkedIn: [Joseph Williams](https://www.linkedin.com/in/josephwilliams)
- Medium: [Joseph Williams](https://medium.com/@josephwilliams)
- GitHub: [Thinktanksy](https://github.com/Thinktanksy)

## Description
This project, 0x04-utf8_validation, is a coding challenge solution for validating UTF-8 encoding. It contains code that checks whether a given list of integers represents valid UTF-8 encoding or not.

The UTF-8 encoding is a variable-length character encoding for Unicode. It is capable of encoding all possible characters in Unicode, making it a fundamental encoding for international text processing. This project ensures the integrity of UTF-8 encoded data.

## Getting Started
To get started with this project, follow these instructions:

1. Clone the GitHub repository to your local machine:

   ```
   git clone https://github.com/Thinktanksy/0x04-utf8_validation.git
   ```

2. Navigate to the project directory:

   ```
   cd 0x04-utf8_validation
   ```

3. The main code for UTF-8 validation can be found in the `0-validate_utf8.py` file.

## Usage
You can use this project to validate UTF-8 encoded data by calling the provided functions in the `0-validate_utf8.py` file. Ensure that you have the necessary data in the correct format to pass to the validation functions.

Example usage:

```python
from utf8_validation import validUTF8

data = [197, 130, 1]
if validUTF8(data):
    print("Valid UTF-8 encoding")
else:
    print("Invalid UTF-8 encoding")
```

## Contributing
Contributions to this project are welcome. If you find any issues or have ideas for improvements, please submit them as GitHub issues or pull requests on the [GitHub repository](https://github.com/Thinktanksy/0x04-utf8_validation).

## License
This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgments
Special thanks to ALX SE for sponsoring this project.

Thank you for using 0x04-utf8_validation!
