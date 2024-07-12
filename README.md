# Title
This project is intended to perform CRUD operations.

# Execution Flow
* Clone the project:
```
git clone https://github.com/devopsmission24/webapp.git && cd webapp
```
* Install required packages:
```
sudo pip3 install -r requirements.txt
sudo python3 manage.py migrate
```
* Run server from local machine
```
sudo python3 manage.py runserver 0.0.0.0:8000
```
* Run server from remote machine
```
gunicorn main.wsgi --bind 0.0.0.0:8000
```
* Testing from Browser
```
http://127.0.0.1:8000
```
