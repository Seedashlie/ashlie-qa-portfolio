\# Exploratory Testing – Login Feature

\*\*Application:\*\* Login Page  
\*\*Testing Type:\*\* Exploratory Testing

\---

\#\# Objective  
To explore the login functionality and identify usability issues, validation gaps, and unexpected behaviors beyond predefined test cases.

\---

\#\# Test Approach  
Performed unscripted testing by interacting with the login page using various inputs and user behaviors, including invalid credentials, boundary values, and UI interactions.

\---

\#\# Observations

\- Login functionality works correctly for valid and invalid credentials  
\- Error messages display properly for incorrect login attempts  
\- Password validation correctly enforces minimum and maximum length  
\- Login fails appropriately for locked user accounts  
\- Blank field validation works as expected

\---

\#\# Issues Identified

\#\#\# 1\. Password Reset Link Not Functioning  
\- Clicking "Forgot your password?" does not redirect to reset page  
\- Expected behavior: User should be redirected to password reset page

\---

\#\#\# 2\. Password Field Does Not Mask Input  
\- Entered password characters are visible instead of hidden  
\- Expected behavior: Password should be masked for security

\---

\#\#\# 3\. Missing Password Visibility Toggle  
\- No "eye icon" present to show/hide password  
\- Expected behavior: User should have option to toggle password visibility

\---

\#\# Test Ideas Explored

\- Entering valid and invalid login credentials  
\- Testing locked user login behavior  
\- Submitting blank fields  
\- Testing password length boundaries (below min, min, max, above max)  
\- Interacting with password field (masking, visibility)  
\- Testing password reset functionality

\---

\#\# Potential Improvements

\- Fix password reset link functionality  
\- Ensure password input is masked for security  
\- Add password visibility toggle (eye icon)  
\- Improve UI consistency for login-related actions

\---

\#\# Conclusion

Exploratory testing identified several functional and usability issues within the login feature, particularly related to password handling and reset functionality. Addressing these issues would improve both security and user experience.