| Test Case 1: Successful Sign Up (Valid Data)                                              |
| ----------------------------------------------------------------------------------------- |
|                                                                                           |  |  |  |
| Steps                                                                                     | Actions | Expected Result | Actual Result |
| Navigate to the AppKube sign-up page.                                                     |  |  |  |
| Enter a valid Full Name.                                                                  |  |  |  |
| Enter a valid Username.                                                                   | Fill in all fields with correct information. | User should be successfully registered. | User is successfully registered. |
| Enter a valid Email address.                                                              | Verify that the password meets the minimum requirements. | User is redirected to the AppKube dashboard or a confirmation page. | User is redirected to the expected page. |
| Enter a valid Password.                                                                   | Click on the "Create Account" button. | User account details are stored in the database. | User account details are confirmed to be stored in the database. |
| Click on the "Create Account" button.                                                     |  |  |  |
|                                                                                           |  |  |  |
| Test Case 2: Sign Up with Existing Email (Invalid Data)                                   |
|                                                                                           |  |  |  |
| Steps                                                                                     | Actions | Expected Result | Actual Result: |
| Navigate to the AppKube sign-up page.                                                     |  |  |  |
| Enter a valid Full Name.                                                                  | Fill in all fields with correct information. | User should receive an error message indicating that the email address is already in use. | User receives the expected error message. |
| Enter a valid Username.                                                                   | Use an email address that is already associated with an existing account. | User should not be allowed to proceed with the sign-up process. | User is prevented from proceeding with the sign-up using an existing email. |
| Enter an Email address that is already registered.                                        | Click on the "Create Account" button. |  |  |
| Enter a valid Password.                                                                   |  |  |  |
| Click on the "Create Account" button.                                                     |  |  |  |
|                                                                                           |  |  |  |
| Test Case 3: Sign Up with Weak Password (Invalid Data)                                    |
|                                                                                           |  |  |  |
| Steps                                                                                     | Actions | Expected Result | Actual Result: |
| Navigate to the AppKube sign-up page.                                                     |  |  |  |
| Enter a valid Full Name.                                                                  | Fill in all fields with correct information. | User should receive an error message indicating that the password is too weak. | User receives the expected error message. |
| Enter a valid Username.                                                                   | Use a password that does not meet the minimum strength requirements. | User should not be allowed to proceed with the sign-up process. | User is prevented from proceeding with the sign-up using a weak password. |
|  Enter a valid Email address.                                                             | Click on the "Create Account" button. |  |  |
|  Enter a weak Password (e.g., less than 8 characters).                                    |  |  |  |
| Click on the "Create Account" button.                                                     |  |  |  |
|                                                                                           |  |  |  |
| Test Case 4: Sign Up with Missing Required Fields (Invalid Data)                          |
|                                                                                           |  |  |  |
| Steps                                                                                     | Actions | Expected Result | Actual Result: |
| Navigate to the AppKube sign-up page.                                                     |  |  |  |
| Leave one or more of the required fields (Full Name, Username, Email, or Password) blank. | Leave one or more required fields empty. | User should receive appropriate error messages for each missing field. | User receives the expected error messages. |
| Click on the "Create Account" button.                                                     | Click on the "Create Account" button. | User should not be allowed to proceed with the sign-up process until all required fields are filled. | User is prevented from proceeding with the sign-up until all required fields are filled. |