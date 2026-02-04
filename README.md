# Simple Notes App 
This is a simple notes app built with React and Django.

## Requirements
1. Python 3.9
2. Node.js
3. React

## Installation
1. Clone the repository
```
git clone https://github.com/LondheShubham153/django-notes-app.git
```

2. Build the app
```
docker build -t notes-app .
```

3. Run the app
```
docker run -d -p 8000:8000 notes-app:latest
```


Method 2 — Run Using Docker Compose (One-Command Setup)

You can clone the repository and start the application using Docker Compose with these command:
1. Clone the repository
```
git clone https://github.com/LondheShubham153/django-notes-app.git 
```
2. go in the directory 
```
cd django-notes-app 
```
3. Run the Docker compose file to start build the Application
```
docker compose up -d
```

4. After all containers start, open:
```
http://localhost:8000
```

to access the Notes App.
## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`
`sudo apt install nginx`
