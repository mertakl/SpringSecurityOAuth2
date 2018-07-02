# SpringSecurityOAuth2
An example of OAuth2 implemantation on Spring Framework
It is a maven based project. You need to import this project into your favorite IDE. Than you need to clean and build the project.<br>
After that if you have postman installed. Than follow these steps:<br>
Type in this url than make a POST request.<br>
http://localhost:8080/SpringSecurityOAuth2Example/oauth/token?grant_type=password&username=mert&password=1234<br>
It is going to generate an access token copy that and paste on this url.Than make a get request.<br>
http://localhost:8080/SpringSecurityOAuth2Example/user/?access_token=YOUR_ACCESS_TOKEN<br>
If no errors occured you should see some data.


