Documentation of Linq Web Application Testing Using 

# Postman 

# API Inspection Overview 

I utilized Postman to simulate and inspect various API interactions with the Linq app, 

focusing on: 

• Phone Number OTP Verification 

• Contact Information Submission 

• Welcome Page Retrieval 

# Phone Number OTP Verification 

Endpoint : POST  https://api.linqapp.com/api/v1/auth/create_confirmation 

Headers :

• Accept : application/json 

• Content -Type : application/json 

• Origin : https://linqapp.com 

• Referer : https://linqapp.com/ 

• User -Agent : Standard browser user -agent string 

Request Body in json format: 

{

"input": "3305540565", 

"force_auth_code": false 

}

Response :

• Status Code : 201 Created 

• Body : Contains confirmation details for OTP verification. Observations :

• A 201 Created status indicates the OTP was successfully generated. 

• Ensure the phone number is in the correct format and not previously registered to 

avoid errors. 

# Contact Information Submission 

Endpoint : POST  https://api.linqapp.com/api/v1/users/create 

Headers :

• Accept : application/json 

• Content -Type : application/json 

• Origin : https://linqapp.com 

• Referer : https://linqapp.com/ 

• User -Agent : Standard browser user -agent string 

Request Body (json format) 

{

"name": "Anika Basin", 

"phone_number": "+12342962731", 

"email": " csush30@gmail.com ", 

"country_code": "us" 

}

Response :

• Status Code : 200 OK (Note: Typically, a 201 Created status is expected for 

successful resource creation.) 

• Body : Contains user profile details. 

Observations :

• Initially received a 500 Internal Server Error due to duplicate data. 

• Changing the email and phone number to unique values resolved the issue. • It's crucial to ensure the uniqueness of user data to prevent server errors. 

# Welcome Page Retrieval 

Endpoint : GET  https://api.linqapp.com/api/v1/welcome 

Headers :

• Accept : application/json 

• User -Agent : Standard browser user -agent string 

Response :

• Status Code : 200 OK 

• Body : Contains welcome page content. 

Observations :

• Successful retrieval of the welcome page confirms the endpoint is accessible and 

functioning as expected. 

# Additional Insights and Findings 

• Postman Console : Utilized the Postman Console to inspect request and response 

details, including headers and payloads. This tool was instrumental in debugging 

and understanding API interactions. 

• Browser Dev Tools : Leveraged browser developer tools to monitor network activity, 

which helped in replicating requests within Postman accurately. 

• Error Handling : Encountered a 500 Internal Server Error when attempting to 

create a user with existing credentials. This underscores the importance of handling 

duplicate entries gracefully and providing informative error messages.