# 0x00-personal_data
# PII Handling, Logging, and Security Project

## Introduction

This project focuses on understanding and implementing best practices for handling Personally Identifiable Information (PII) in Python applications. I have learned about the importance of PII, how to securely log information, how to encrypt and validate passwords, and how to authenticate to a database using environment variables.

## Learning Objectives

### 1. Examples of Personally Identifiable Information (PII)
I have learned that Personally Identifiable Information (PII) includes any data that can be used to identify an individual. Examples include:
- Full name
- Social Security Number (SSN)
- Email addresses
- Phone numbers
- Physical addresses

Understanding what constitutes PII is crucial for ensuring data privacy and compliance with regulations such as GDPR and CCPA.

### 2. Implementing a Log Filter to Obfuscate PII Fields
I have gained knowledge on how to implement a log filter that obfuscates PII fields in log files. This is important because logs often contain sensitive information that should not be exposed. By using Python's `logging` module, I can create custom filters to mask PII, ensuring that logs remain useful for debugging while protecting user privacy.

### 3. Encrypting Passwords and Validating Input Passwords
In this project, I learned how to securely encrypt passwords using the `bcrypt` package. Encrypting passwords ensures that even if they are stored or transmitted insecurely, they cannot be easily compromised. Additionally, I have practiced validating input passwords against the encrypted versions, which is a fundamental aspect of user authentication systems.

### 4. Authenticating to a Database Using Environment Variables
Lastly, I have learned how to securely authenticate to a database using environment variables. Storing sensitive credentials like database passwords in environment variables, rather than hard-coding them in the application, enhances security by reducing the risk of accidental exposure.

## Resources

The following resources were instrumental in my learning:

- **[What Is PII, non-PII, and Personal Data?](https://piwik.pro/blog/what-is-pii-personal-data/)**: This article helped clarify the distinctions between different types of personal data and why they matter.
- **[Python logging documentation](https://docs.python.org/3/library/logging.html)**: This documentation provided detailed guidance on how to set up logging in Python, including filtering and formatting logs.
- **[bcrypt package](https://pypi.org/project/bcrypt/)**: The `bcrypt` documentation was essential for understanding how to securely hash and check passwords.
- **[Logging to Files, Setting Levels, and Formatting](https://www.youtube.com/watch?v=-ARI4Cz-awo)**: This guide covered best practices for logging in Python, including how to write logs to files and control the level and format of logged messages.

## Conclusion

This project has equipped me with the skills to handle PII responsibly, secure sensitive information through encryption, and ensure that authentication credentials are managed securely. These practices are vital for building secure and trustworthy applications.