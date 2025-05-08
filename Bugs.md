LINQ_BUGS 

Bugs: 

Bug 1: 

Bug Description: Phone number text field should only take 10 numerical and it is taking 

more than 10 like infinite number 

Steps to reproduce 

1. Launch the welcome page 

2. Post navigating the screen enter the mobile number like infinite and observe 

Expected result: User should be restricted to 10 numbers only I.e Phone number 

Actual Result: Used able to enter infinite numbers in the phone number text field 

Screenshot: 

Bug 2: 

Bug Description: Post navigating to the phone number login page where phone number is 

displayed should be constant from name, phone number and email details 

Steps to Reproduce: 

1. Launch the welcome page 

2. enter the phone number in the welcome page 3. post navigating to the details screen 

4. observe the phone number column and 

5. Try to edit the number 

Expected result : the entered phone number should be constant and should not allow the 

user to edit 

Actual result: the entered phone number can be changed and can add more numbers to 

the phone number 

Bug 3: 

Bug Description: Confirm Phone Number should be displayed when tried logged in 

using phone number, but it is displayed as Confirm Email 

Steps to Reproduce: 

1. Launch the welcome page 

2. enter the phone number in the welcome page 

3. Click on Continue button 

4. Navigate to OTP page 

5. Observe the UI text Confirm Email 

Expected Result: It should be displayed as Confirm Mobile Number 

Actual Result: It is displayed as Confirm Email Bug 4: 

Bug Description: There is no Functional use of Continue button in OTP Confirmation page 

Steps to reproduce: 

1.  Launch the welcome page 

2.  Enter the phone number which is existing 

3.  Click on continue button 

4.  Navigate to OTP verification page 

5.  Try Entering Invalid OTP and Valid OTP 

6.  Observe the behavior 

Expected Result: “Could not validate authentication code” popup is displayed without 

hitting on continue button when invalid OTP is given 

Actual Result: User is navigated to next page without hitting continue button when valid 

OTP is given 

Bug 5: Bug Description: Team size cannot be zero, but it is taking 0 when typed in professional 

details and user can be navigated to next screen when clicked on Continue .

Steps to Reproduce: 

1.  Launch the welcome page 

2.  Login using Phone number 

3.  Navigate to Professional details 

4.  Click on the dropdown called who will be using Linq 

5.  Select my team 

6.  Enter 0 and click on Continue and observe the behavior 

Expected Result: It should not take when the team size is 0 

Actual Result : It is taking 0 and post clicking on the continue button user is navigated to 

next screen which should not be happen 

Bug 6: 

Bug Description: Post clicking on cancel icon from the subscription popup the popup is 

closed but the user is navigating to profile page. 

Steps to Reproduce: 

1.  Launch the web application 

2.  Login using phone number 

3.  Continue with professional details 

4.  Navigate to Add Photo Page 5.  Click on Create Page and observe a subscription popup 

6.  Click on cancel ‘x’ icon from the popup and observe the scenario 

7.  User can be able to dismiss the popup but navigated to profile page 

Expected Result: User should be able to dismiss the popup and should stay in same page 

Actual Result: User is navigated to profile page but able to dismiss the popup.