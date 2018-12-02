# Django Login Registration
A simple and robust django login registration, this app contain how to configure login/logout functionality with the built user authentication and then there's a signup page so user can register for new accounts and login again with his new accounts.

# How to Use
1. Clone or download this repository
2. Make sure already activate virtualenvironment
3. Change directory to this directory
4. Migrate the database first using `py manage.py migrate`
5. To test the django login is working, create superuser first `py manage.py createsuperuser`
6. And then login with that superuser in `http://127.0.0.1:8000/`
7. If you want to login with new user, register your new accounts first `http://127.0.0.1:8000/accounts/signup/`
8. Go back to `http://127.0.0.1:8000/` and try with your new accounts.
9. To check forget your password try `http://127.0.0.1:8000/accounts/password_reset/`
10. To check reset your password try `http://127.0.0.1:8000/password_reset/done/`
11. To setting up a new password try `http://127.0.0.1:8000/accounts/reset/Mg/set-password/`
12. To check password reset is done try `http://127.0.0.1:8000/accounts/reset/done/`

# Note
1. If error occurs, go to django settings in `project/settings.py` and change `accounts` in installed applications with `accounts.apps.AccountsConfig`
2. If you want to try reset password, go check in your directory there's a new folder such as `sent_email` and then click the links that already provided.
