# double-submit-cookie-pattern-csrf
Double submitting cookies is defined as sending a random value in both a cookie and as a request parameter, with the server verifying if the cookie value and request value are equal.

IT17127356

Double Submit Cookie Pattern

REQUIREMENTS >>
WAP Server

HOW TO RUN >>
1. Copy/Extract all files to C:\wamp64\www
2. Open web browser and navigate to http://localhost/double-submit-cookies-pattern/
3. UserName - admin Password - pass

When user suceessfully loginin server generates a session ID abd CSRF token for the session and those are set as browser
cookies and when user submits the update user form the server validates the session ID and CSRF token whether they are matched or not.

READ MORE >>
Blog Post :
https://invasionxx.blogspot.com/2019/05/double-submit-cookies-pattern.html
