# Linq Desktop Application Test Cases

## TC001: Verify the UI of the welcome page or SignUp/Login Page of the Linq Desktop application.
**Steps:**  
1. Launch the browser  
2. Navigate to Linqapp.com/welcomepage  
3. Observe the LinqLogin/welcomepage  
**Expected Result:**  
User should able to see phone number text box, Continue Button and other Login options like Email, Apple, Google, Linkedin login Buttons respectively.

## TC002: Verify the navigation when user clicks on login buttons like email/Apple/Google/LinkedIn respectively.
**Steps:**  
1. Launch the browser  
2. Navigate to Linqapp.com/welcomepage  
3. Observe the LinqLogin/welcomepage  
4. Click on email, Apple, Google, LinkedIn buttons respectively and observe  
**Expected Result:**  
User should be navigated to respective pages when clicked on buttons

## TC003: Verify by clicking on continue button without giving the phone number in text box and observe
**Steps:**  
1. Launch the browser  
2. Navigate to Linqapp.com/welcomepage  
3. Observe the LinqLogin/welcomepage  
4. Observe the login/sign up page with phone number text box on the top  
5. Click on Continue Button without entering Phone Number and Observe  
**Expected Result:**  
User should see the phone number is required or error message highlighted and user should not navigate to next screen

## TC004: Verify giving more than 10 numbers in the phone number text field box and observe the behavior
**Steps:**  
1. Launch the browser  
2. Navigate to Linqapp.com/welcomepage  
3. Observe the LinqLogin/welcomepage  
4. Observe the login/sign up page with phone number text box  
5. Type any random mobile number which has more than 10 numbers and observe  
**Expected Result:**  
User should be restricted to 10 numbers only and should not able to enter more than 10 number nor it should be displayed on the screen. If user entered more than 10 or less than 10 numbers user should see the text message in highlighted text "Please enter a valid Phone Number".

## TC005: Verify giving a valid phone number and functional click on continue button.
**Steps:**  
1. Launch the browser  
2. Navigate to Linqapp.com/welcomepage  
3. Enter the valid phone number in the text field box  
4. Click on Continue button  
5. Observe the behavior  
**Expected Result:**  
User should be navigated to next screen successfully

## TC006: Verify the UI of Sign Up page
**Steps:**  
1. Launch the browser  
2. Navigate to Linqapp.com/welcomepage  
3. Enter the valid phone number and click on continue  
4. Observe the UI  
**Expected Result:**  
User should able to see First Name and Last Name text Box, Entered Phone Number Text Box and Email Address Text Box

## TC007: Verify the Back button Functionality in Sign Up page post any action is done
**Steps:**  
1. Launch the browser  
2. Navigate to Linqapp.com/welcomepage  
3. Enter the valid phone number and click on continue  
4. Observe back button in Sign up page and click it  
5. Check the functionality post any action like after entering email/phone/first and last name  
6. Observe the behaviour  
**Expected Result:**  
User should be navigated to previous screen whenever clicked on the back button

## TC008: Verify the sign up page takes all the details correctly and are restricted like phone number to 10 digits and first name /last name without infinite letters and email without @ and .com
**Steps:**  
1. Launch the browser  
2. Navigate to Linqapp.com/welcomepage  
3. Enter the valid phone number and click on continue  
4. Navigate to Sign Up page  
5. Enter the details like invalid name/phone number/email and click on continue button  
6. Observe the behavior  
**Expected Result:**  
User should get respective highlighted text message when invalid details are given and no highlighted text message should be seen when entered valid details

## TC009: Verify the functionality of Privacy policy
**Steps:**  
1. Launch the browser  
2. Navigate to Linqapp.com/welcomepage  
3. Enter the valid phone number and click on continue  
4. Navigate to Sign Up page  
5. Click on Privacy policy link text and observe  
**Expected Result:**  
User should able to see privacy policy popup with dismiss button to dismiss

## TC010: Verify the functionality of Continue button without giving the user details in signup page
**Steps:**  
1. Launch the browser  
2. Navigate to Linqapp.com/welcomepage  
3. Enter the valid phone number and click on continue  
4. Navigate to Sign Up page  
5. Click on continue button without entering the user details and observe  
**Expected Result:**  
User should see highlighted error text message on the top of the text field box and user should stay in the same screen should not navigate to next screen

## TC011: Verify the UI of about me page post signing up
**Steps:**  
1. Launch the browser  
2. Navigate to Linqapp.com/welcomepage  
3. Enter the valid phone number and click on continue  
4. Enter the valid details and click continue button  
5. Observe the UI in the about me page  
**Expected Result:**  
User should able to see the expected UI like text fields: Job Title, Employee, Location, Company Website, Who will be using Linq and Continue Button

## TC012: Verify whether the user is able to type numerics in numeric text field and Alphabets in word text field
**Steps:**  
1. Launch the browser  
2. Navigate to Linqapp.com/welcomepage  
3. Enter the valid phone number and click on continue  
4. Enter the valid details and click continue button  
5. Enter Randomly numbers and alphabets in the text fields and observe the behavior  
**Expected Result:**  
User should restricted internally to enter alphabets and numbers in text and numeric text fields respectively

## TC013: Verify Clicking on Back icon from professional details page and observe the behavior
**Steps:**  
1. Launch the browser  
2. Navigate to Linqapp.com/welcomepage  
3. Enter the valid phone number and click on continue  
4. Enter the valid details and click continue button  
5. Navigate to professional details page and  
6. Click on Back button and observe the behavior  
**Expected Result:**  
User should be navigated to previous screen but all the details in the previous screen should not be erased.

## TC014: Verify Clicking on Continue button in professional details page without giving any details and observe
**Steps:**  
1. Launch the browser  
2. Navigate to Linqapp.com/welcomepage  
3. Enter the valid phone number and click on continue  
4. Enter the valid details and click continue button  
5. Navigate to professional details page and  
6. Click on continue button without giving any details and observe the behavior  
**Expected Result:**  
User should be navigated to next page successfully because that details can be also filled later so user should be navigate to next screen.

## TC015: Verify the UI of Profile Image Page
**Steps:**  
1. Launch the browser  
2. Navigate to Linqapp.com/welcomepage  
3. Enter the valid phone number and click on continue  
4. Enter the valid details and click continue button  
5. Navigate to professional details page and  
6. Click on continue button without giving any details  
7. Navigate to Profile Image Page and Observe the UI  
**Expected Result:**  
User should expected to see a Add Profile Image link and Create page button with a back button

## TC016: Verify the functionality of Create Page button and observe the behavior
**Steps:**  
1. Launch the browser  
2. Navigate to Linqapp.com/welcomepage  
3. Enter the valid phone number and click on continue  
4. Enter the valid details and click continue button  
5. Navigate to professional details page and  
6. Click on continue button without giving any details  
7. Navigate to Profile Image Page and click on create page button and observe the behavior  
**Expected Result:**  
User should able to see a subscription popup as soon as we click on the create page button

## TC017: Verify clicking on Add Profile image link and observe the behavior
**Steps:**  
1. Launch the browser  
2. Navigate to Linqapp.com/welcomepage  
3. Enter the valid phone number and click on continue  
4. Enter the valid details and click continue button  
5. Navigate to professional details page and  
6. Click on continue button without giving any details  
7. Navigate to Profile Image Page and click on add profile image link and observe  
**Expected Result:**  
User should able to see windows explorer from where we select picture and upload

## TC018: Verify clicking on No thanks from the subscription popup and observe the behavior
**Steps:**  
1. Launch the browser  
2. Navigate to Linqapp.com/welcomepage  
3. Enter the valid phone number and click on continue  
4. Enter the valid details and click continue button  
5. Navigate to professional details page and  
6. Click on continue button without giving any details  
7. Click on create page from next page  
8. From the subscription popup click on No Thanks button and observe  
**Expected Result:**  
User should be navigated to my profile page

## TC019: Verify the UI of profile page and observe
**Steps:**  
1. Launch the browser  
2. Navigate to Linqapp.com/welcomepage  
3. Enter the valid phone number and click on continue  
4. Enter the valid details and click continue button  
5. Navigate to professional details page and  
6. Click on continue button without giving any details  
7. Click on create page from next page  
8. From the subscription popup click on No Thanks button  
9. Navigate to profile page and observe the edit profile details and other UI  
**Expected Result:**  
User should see expected UI in profile page and clear user details

## TC020: Verify the successful signout by clicking on hamburger menu options and observe the behavior
**Steps:**  
1. Launch the browser  
2. Navigate to Linqapp.com/welcomepage  
3. Enter the valid phone number and click on continue  
4. Enter the valid details and click continue button  
5. Navigate to professional details page and  
6. Click on continue button without giving any details  
7. Click on create page from next page  
8. From the subscription popup click on No Thanks button  
9. From the profile page click on Hamburger menu option and click on signout button and observe the popup  
10. Click on Yes from signing out from the profile page and observe  
**Expected Result:**  
User should be successfully signed out from the page and navigated back to welcome screen