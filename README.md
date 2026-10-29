# Secure Equipment Rental API

A security-focused Flask application demonstrating authentication, authorization, secure credential handling, validation, logging, and automated security testing.

## Tech Stack

- Python
- Flask
- pytest
- Werkzeug
- REST APIs
- Bandit
- Flake8

## Security Features

- Password hashing with Werkzeug
- Environment-based secret management
- Authentication
- Role-based access control (RBAC)
- Protected API endpoints
- Input validation
- Exception handling
- Application logging
- Automated security testing
- Static security analysis

## Access Roles

The application supports multiple access levels:

- Guest
- User
- Administrator

Each role is restricted to the functionality it is authorized to access.

## Secure Credential Handling

Passwords are stored using secure hashing rather than plaintext credentials. Sensitive configuration values are loaded from environment variables instead of being hardcoded directly into the application.

## Validation and Error Handling

The application validates incoming data before processing it and handles invalid or unauthorized requests safely.

Examples include:

- Negative rental durations
- Missing required values
- Invalid users
- Unauthorized access attempts
- Unexpected application errors

## Logging

Application events are recorded using multiple severity levels, including:

- INFO
- WARNING
- ERROR

This provides visibility into normal application activity as well as validation and security-related failures.

## Automated Testing

The project includes automated pytest coverage focused on application security and API behavior.

Security testing verifies areas such as:

- Authentication behavior
- Authorization restrictions
- Protected API access
- Input validation

## Static Analysis

The implementation was also evaluated using:

- **Bandit** for Python security analysis
- **Flake8** for code-quality and style checks

## What I Built

I strengthened an equipment-rental Flask application by remediating insecure credential handling, adding password hashing, validating user input, implementing role-based authorization, improving logging and exception handling, and building automated security tests to verify the protections.

## Source Code

The complete academic implementation is maintained in a private repository. Source access can be provided for professional review upon request.

## Author

**Nicholas Cornes**  
B.S. Software Engineering
