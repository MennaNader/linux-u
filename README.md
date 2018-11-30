# linux-u


Project webiste  http://udacity.menna.com/
ip : 18.196.138.155


Please use the id_rsa to open as grader
and use udacity to open as ubuntu default


the following packages are used: 

    apt-get -qqy install python python-pip
    pip2 install --upgrade pip
    pip2 install flask packaging oauth2client redis passlib flask-httpauth
    pip2 install sqlalchemy flask-sqlalchemy psycopg2-binary bleach requests

first i created the grader user and changed it's access
then i changed the port for ssh
installed apache and cloned my project from git
created a catalog database
followed a tutorial to publish it on apache
```https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps```

- apache2 was used to create the server
- wsgi apache_mod


