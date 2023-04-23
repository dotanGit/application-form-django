# django Form Application
This is a simple Flask application that allows users to submit a form with their personal details, such as first name, last name, email, date of birth, and occupation. 
The form data is stored in a SQLite database and an email notification is sent to the user upon successful submission of the form

### Usage
To run the application, run the following command in the terminal:
python manage.py runserver in your terminal of the Django project and hit enter.

1) Fill out the form with your first name, last name, email address, date, and occupation.

2) Click the "Submit" button to submit the form.

3) You will receive a confirmation email at the email address you provided in the form.

### Configuration
The following configuration options can be modified in the settings.py file:

SECRET_KEY: A secret key used by Django to sign cookies and other data.

DATABASES: The database settings.

EMAIL_BACKEND: The email backend to use.

EMAIL_HOST: The hostname of the email server.

EMAIL_PORT: The port number of the email server.

EMAIL_USE_SSL: Whether to use SSL encryption when connecting to the email server.

EMAIL_HOST_USER: The email address to use as the sender.

EMAIL_HOST_PASSWORD: The password for the email address.

### Admin user
in oreder to create an admin user :

Creating an admin user
$ python manage.py createsuperuser. Enter your desired username and press enter.
Username: admin. You will then be prompted for your desired email address:
Email address: admin@example.com. ...
Password: ********** Password (again): ********* Superuser created successfully

then when the app is running enter the url and add /admin
for example : http://127.0.0.1:8000/admin
and enter you password and user name.
