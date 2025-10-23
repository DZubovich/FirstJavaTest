### Test. User Signup and Deletion ###

My first Java autotests.
Tests verify the complete scenario of registration a new user on the website and deletion the account.

### Technologies Used
- **Java** 
- **Maven** 
- **TestNG** 
- **Selenium**

### User signup Scenario:
1. Launch browser
2. Navigate to url 'http://automationexercise.com'
3. Click on 'Signup / Login' button
4. Enter name and email address
5. Click 'Signup' button
6. Fill details: Title, Name, Email, Password, Date of birth
7. Select checkbox 'Sign up for our newsletter!'
8. Select checkbox 'Receive special offers from our partners!'
9. Fill details: First name, Last name, Company, Address, Address2, Country, State, City, Zipcode, Mobile Number
10. Click 'Create Account button' 
11. Verify that 'ACCOUNT CREATED!' is visible

### Account deletion Scenario:
1. Launch browser
2. Navigate to url 'http://automationexercise.com'
3. Click 'Signup/Login' button
4. Fill details: Email, Password
5. Click Login button 
6. Click 'Delete Account' button 
7. Verify that 'ACCOUNT DELETED!' is visible