# travelapp

Travel App - 

Multirole Application

App Features:
1.  Add User
2.  Delete User
3.  View Users
4.  Add Destination
5.  Delete Destination
6.  View Destinations
7.  Select Destionation
8.  Deselect Destination
9.  User Login
10. Register User
11. Forgot Password - (Password Reset Mail Not Sent, Only Printed to Console)
12. Change Password
13. User Profile
14. Home/Index Page

Security Features:
1.  Argon2 Password Hashing
2.  Password Complexity - { size: 12, type: Alpha Numeric With Symbol }
3.  Security Headers - (X-XSS-Protection, X-Content-Type-Option, X-Frame-Options, Strict-Transport-Security)
4.  No credentials in source code
5.  Cookie Flags Set - (HTTPOnly, Secure)
6.  Proper Authentication (Session Management)
7.  Proper Authorization (Role Based Access Control)
8.  Custom User Input Validation
9.  Django ORM and Models used for DB interactions (No SQLi)
10. Django Templates used for HTML (No XSS)
11. Google reCAPTCHA used with User Registeration

Config Vars:
DEBUG: 0
GOOGLE_RECAPTCHA_SECRET_KEY: 6LfLO-IUAAAAAI4UYxLoP6yWKJ_XQMMM2nR18JKu
SECRET_KEY: jm6=@vys6_aw8ec-yef8blj6!ib_5#-4e8mfj818ee&(s!(w97
