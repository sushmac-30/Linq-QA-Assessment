
# Linq Desktop Application Test Cases

| Test Case ID | Description | Steps | Expected Result |
|--------------|-------------|-------|------------------|
| TC001 | Verify the UI of the welcome page or SignUp/Login Page of the Linq Desktop application. | 1. Launch the browser<br>2. Navigate to Linqapp.com/welcomepage<br>3. Observe the LinqLogin/welcomepage | User should be able to see phone number text box, Continue Button and other Login options like Email, Apple, Google, LinkedIn login Buttons respectively. |
| TC002 | Verify the navigation when user clicks on login buttons like email/Apple/Google/LinkedIn respectively. | 1. Launch the browser<br>2. Navigate to Linqapp.com/welcomepage<br>3. Observe the LinqLogin/welcomepage<br>4. Click on email, Apple, Google, LinkedIn buttons respectively and observe | User should be navigated to respective pages when clicked on buttons. |
| TC003 | Verify clicking on continue button without giving the phone number in text box and observe | 1. Launch the browser<br>2. Navigate to Linqapp.com/welcomepage<br>3. Click Continue without entering Phone Number | User should see an error message and should not navigate to the next screen. |
| TC004 | Verify entering more than 10 digits in the phone number text field | 1. Launch the browser<br>2. Navigate to Linqapp.com/welcomepage<br>3. Enter a number with more than 10 digits | User should be restricted to 10 digits and see an error message for invalid input. |
| TC005 | Verify entering a valid phone number and clicking on continue | 1. Launch the browser<br>2. Navigate to Linqapp.com/welcomepage<br>3. Enter valid phone number and click Continue | User should be navigated to the next screen. |
| TC006 | Verify the UI of Sign Up page | 1. Launch the browser<br>2. Navigate to Linqapp.com/welcomepage<br>3. Enter valid phone number and click Continue | User should see First Name, Last Name, Phone Number, and Email text boxes. |
| TC007 | Verify the Back button functionality on Sign Up page | Steps similar to TC006, then click the back button | User should navigate to previous screen without data loss. |
| TC008 | Verify valid/invalid inputs in Sign Up fields | Steps similar to TC006, then input invalid and valid data | Errors should appear for invalid input; valid input should pass without errors. |
| TC009 | Verify the functionality of Privacy Policy link | Navigate to Sign Up page and click on Privacy Policy link | User should see a popup with a dismiss button. |
| TC010 | Verify clicking Continue without entering user details in Sign Up page | Click Continue with all fields empty | Error messages should appear and no navigation should happen. |
| TC011 | Verify UI of About Me page | Complete sign up, then observe the next page | User should see fields for Job Title, Employee, Location, Company Website, and other details. |
| TC012 | Verify input restrictions for numeric and text fields | Enter numbers in text fields and letters in number fields | Inputs should be restricted accordingly. |
| TC013 | Verify Back button on professional details page | Navigate to this page and click Back | User should go back and previous inputs should remain intact. |
| TC014 | Verify clicking Continue on professional details without input | Click Continue without entering anything | User should be allowed to proceed. |
| TC015 | Verify the UI of Profile Image Page | Navigate to Profile Image page | User should see Add Profile Image link and Create Page button. |
| TC016 | Verify Create Page button functionality | Click on Create Page | A subscription popup should appear. |
| TC017 | Verify Add Profile Image functionality | Click Add Profile Image link | Windows explorer should open to choose a file. |
| TC018 | Verify No Thanks on subscription popup | Click No Thanks | User should be navigated to profile page. |
| TC019 | Verify UI of Profile Page | Observe UI after navigation to Profile Page | User should see edit profile details and relevant UI. |
| TC020 | Verify successful sign out | Use hamburger menu → Sign Out → Confirm | User should be signed out and returned to welcome page. |
