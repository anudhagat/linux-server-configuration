# linux-server-configuration
Configuration details for a linux server on Amazon AWS.

## IP Address
52.34.126.72

## SSH port to server
2200

## URL to host application
http://ec2-52-34-126-72.us-west-2.compute.amazonaws.com

## Configuration notes

1. All software was installed as root.
2. A user named grader was created and given sudo privilege.
3. Login as grader is done with key authentication.
4. Login as root is disabled.
5. My catalog application is installed in /var/www/FlaskApp/FlaskApp and its url is given above.
6. A firewall is set up according to the project spec ports (HTTP: 80, SSH: 2200, NTP: 123)
7. Local timezone is configured to UTC.
8. An apache web server is configured to server a python mod_wgsi application. 
9. Postgres is installed and a database user catalog with password catalog has been created. The user catalog has been granted access to database 'artists' which is used by my catalog application.

## Software installed
1. Apache2
2. postgresql
3. python2
4. psycopg2
5. git
6. mod_wsgi
7. pip
8. virtualenv
9. sqlalchemy
10. flask
11. oauth2client
12. werkzeug
13. Flask-Login

## Resources used to complete the project
1. Udacity course on Configuring Linux Web Servers
2. Udacity Discussion Forum
3. Ubuntu documentation
4. Ubuntu forum : http://askubuntu.com/questions/423355/how-do-i-check-if-a-package-is-installed-on-my-server
5. Man pages
 
