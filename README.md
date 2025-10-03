Understand the Django authentication system
Create views and templates for user login and logout
Create views and templates for user registration
Authentication: The process of verifying the identity of a user or system.
User: Represents an individual who interacts with the Django application. It typically includes information such as username, password, and email.
Registration: The process of creating a new user account in the application.
Login: The process by which a user provides credentials (such as username and password) to access a protected area of the application.
Logout: The process of ending a user’s session and removing their authentication status.

wget "https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0251EN-SkillsNetwork/labs/m5_django_advanced/lab2_template.zip"
unzip lab2_template.zip
rm lab2_template.zip
cd lab2_template

pip install --upgrade distro-info
pip3 install --upgrade pip==23.2.1
pip install virtualenv
virtualenv djangoenv
source djangoenv/bin/activate
pip install -U -r requirements.txt

python3 manage.py makemigrations
python3 manage.py runserver

python3 manage.py createsuperuser

We updated/created codes in this order: Template HTML, view.py, then url.py
