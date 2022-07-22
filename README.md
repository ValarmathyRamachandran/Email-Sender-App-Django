# Email-Sender-App-Django
Sending email from gmail using Django

Email-Sender-Python-Django
Send email from your Gmail Id in Django python using HTML Template

Mandatory changes to be done in the Host Gmail account

 Go to https://myaccount.google.com/security  Scroll till you find "Signing in to Google"  In that section, you will see the "App Passwords"  When you click on "App Passwords", you will be asked to enter your Gmail account password. Enter it and the page would open:  Under select the app and device options, click on the drop-down, select other option and enter your app name (for example email_sender_app)  Click generate button to generate your app password. This password has to be used in our project for EMAIL_HOST_PASSWORD in settings.py

Guidelines to run email_sender_app using Django

Step 1: Install Django using the command on the terminal as python -m pip install Django or else to check whether Django is already installed using this command python -m django --version Step 2: Creating a project using command django-admin startproject project_name In settings.py add the project name to the installed app, and add the email host password i.e which we got from the app password google account. Step 3: create another app name email-sender-app using python manage.py startapp another_project_name Step 4: add views in send_email_app and templates Step 5: python manage.py runserver -go to the given live server urls and the sent email will be executed.
