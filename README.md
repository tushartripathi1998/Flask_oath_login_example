# Flask_oath_login_example

Create a basic google login : oauth2 using flask.
Sign in into your google account and when a user signs in, user's name, profile picture and email ID gets displayed.

Help :
https://developers.google.com/identity/sign-in/web/sign-in#before_you_begin

Add on tip : Not to forget, that google does not prefers address in such form - http://127.0.0.1:port_number, rather it prefers this : 
http://localhost:port_number (by default '5000' for flask), that unfortunately isn't mentioned in the docs !
