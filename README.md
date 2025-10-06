# Django Notes app
This is a simple notes app built with React and Django for practice. Users can create, save, update, and delete notes.
This project was also used to practice **containerization with Docker and Docker Compose**.  

## Requirements
1. Python 3.9
2. Node.js
3. React


## Installation
1. Clone the repository
```
git clone https://github.com/KiranPatil98/django-notes-app.git
```

2. Build the app
```
docker build -t notes-app .
```

3. Run the app
```
docker run -d -p 8000:8000 notes-app:latest
```

## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`
`sudo apt install nginx`
