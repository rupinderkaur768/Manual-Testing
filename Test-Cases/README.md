# Test Cases for Box Authentication Flows
This repository contains comprehensive test cases designed to validate the authentication and security features of the Box application. The test cases cover the following flows:

# Login Flow
|  Objective | Tests Include |
|----------|----------|
| Verify that users can successfully log in to their Box accounts. | - Successful login with valid credentials. <br>  - Error handling with invalid credentials. <br> - Login with hCpatcha. | 

# Logout Flow
|  Objective | Tests Include |
|----------|----------|
| Ensure that users can log out of their Box accounts and that the session is properly terminated. | - Successful logout from the application.  | 

# Reset Password
|  Objective | Tests Include |
|----------|----------|
| Validate the process for users to reset their passwords. | - Initiating password reset via email link.  <br> - Completing password reset with a new password.  | 

# Box 2FA Flows
|  Objective | Tests Include |
|----------|----------|
|Test the SMS-based two-factor authentication (2FA) setup and removal. | - Enabling SMS verification. <br>  - Removing SMS verification. <br>  - Validating correct SMS code entry and handling incorrect codes. | 
|Test the email-based two-factor authentication (2FA) setup and removal.|- Enabling email verification. <br>  - Removing email verification. <br>  - Validating email verification link and handling invalid or expired links.|
|Verify the setup and removal of Time-based One-Time Password (TOTP) two-factor authentication.|- Enabling TOTP verification. <br>  - Removing TOTP verification. <br>  - Validating TOTP code entry and handling incorrect codes.|







