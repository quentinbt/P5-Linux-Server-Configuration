# P5: Linux Server Configuration

This part show how to set our previous python app on a linux production server

## SSH access

52.11.68.114 via port 2200

the command line is:
ssh -i ~/.ssh/udacity_key.rsa root@52.11.68.114 -p2200

## Access tp the app

Just copy past in browser http://52.11.68.114/
You also need a facebook account


## Software installed


- git
- psycopg2
- postgresql-server-dev
- python-psycopg2
- libpq-dev
- libapache2-mod-wsgi python-dev
- virtualenv
- httplib2
- requests
- sqlalchemy
- Flask-SQLAlchemy
- oauth2client
- flask-seasurf
- python-dev
- python-pip
- virtualenv
- Flask
- postgresql
- postgresql-contrib
- psycopg2
- Glances
- unattended-upgrades

## third-party resources/documentation used

http://askubuntu.com/questions/7477/how-can-i-add-a-new-user-as-sudoer-using-the-command-line
http://askubuntu.com/questions/168280/how-do-i-grant-sudo-privileges-to-an-existing-user
https://help.ubuntu.com/community/UbuntuTime#Using_the_Command_Line_.28terminal.29
https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps
http://www.postgresql.org/docs/9.1/static/app-createuser.html
http://www.postgresql.org/docs/9.1/static/auth-pg-hba-conf.html
http://killtheyak.com/use-postgresql-with-django-flask/
http://flask.pocoo.org/docs/0.10/config/
http://drumcoder.co.uk/blog/2010/nov/12/apache-environment-variables-and-mod_wsgi/
https://discussions.udacity.com/t/graceful-way-to-change-ssh-port-and-ufw/4830
https://help.ubuntu.com/community/UFW
https://help.ubuntu.com/lts/serverguide/automatic-updates.html
https://help.ubuntu.com/community/PostgreSQL
https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-ubuntu-14-04
https://pypi.python.org/pypi/Glances
https://www.digitalocean.com/community/tutorials/how-to-protect-ssh-with-fail2ban-on-ubuntu-14-04
