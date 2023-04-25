Note: Please read this document carefully before starting the application.
****************************************************************************************************************************************
Differences between high-fidelity prototype and the final UI implementation:

1) After conducting the user testing we got feedback from the user that it's better to build the app first for web and then if the app gets success then it’s better to build for mobile devices.
Therefore, we have migrated to the web UI implementation.

2) Also, we had a question mark help button in the prototype. However, we removed it in the final web implementation. This change was done based on the user feedback. This is because the majority of the users didn’t use it and a couple of users thought it’s an overkill.

*********************************************************************************************************************************************
How to start interacting with the front end:

  I) Users can directly launch the application by clicking on the index.html, since it’s the starting point of the application.
  II) Then everything is self explanatory where the user can login and search for a destination and can select a car and then make a payment.
 III) However, since we don’t have any backend to store the user data. Users can directly type their name on the username section and any random characters on the password section and can click on the login button.
  IV) Also, all the input fields don't have any authentication or verification to check if the value entered in the input fields is right or wrong. This is because it’s a multi page application with no backend support.
   V) Therefore, users can click on buttons like “login” “search” “favorite destinations” “sign up” “Send code” and all the other buttons without actually typing anything in the input fields.
  VI) For example, users can directly click on the search button after login without typing anything in the search box. It still works because it doesn’t have any database to store or retrieve the information.
The button kind of thing that is being displayed on the card info screen are not clickable. It is only for display purposes for the user to check what cards they linked with the app. We clearly mentioned with a text in the app that those button kind of things are not clickable.

**************************************************************************************************************************************************

contributions of every group member:

Anurag - Built the select a car page, payment page, change payment method page and the confirmation page. And connected all these three pages in such a way that it works flawlessly. For example if a user clicks on the first car in the select a car page. Then the same car image will be displayed in the following screens until the ride is confirmed. Achieved this functionality without a database.

Madhava - Built the welcome page which includes the forget password page and also the sign up page. This allows the user to login or sign up to the application. Also, built the ride history page where it shows the past rides.

Varshith- Worked on the home page which allows the user to search for a destination or to select a destination from the favorite destinations page. Also, built the card info page which displays the information of the existing cards that the user has previously linked with the application.  Also, built an account info page.

Whereas, for the demo script everyone equally contributed to finish it to the fullest.
