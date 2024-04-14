You have to install a new virtual ENV everytime you close and open this

Check the digital Ocean FLASK AUTHENTICATION TUTORIAL
https://www.digitalocean.com/community/tutorials/how-to-add-authentication-to-your-app-with-flask-login

1. cd desktop
2. cd flask_auth_app
3. python -m venv auth
4. source auth/bin/ativate
5. pip install flask flask-sqlalchemy flask-login
6. export FLASK_APP=project
7. export FLASK_DEBUG=1
8. flask run
9. 127.0.0.1:5000

IF YOU GET A HASH (SHA256) ERROR (INVALID TYPE): 
1. DELETE SQLITE.DB from instance folder
2. Delete pyvenv.cfg
3. Do everything all over again, and launch.

FINALLY: RESTORE pyvenv.cfg to the 'project'(whatever you named it) folder, outside of templates.

You should see auth, instance, project, and README.txt

Corey