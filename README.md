# Community Notes App with Monitoring & Logging Stack

Welcome to the **Notes App**, a generic, open-source note-taking application created by **Shivang** for the community! 

This app is built with React and Django. It is designed to be simple, scalable, and easy to deploy. Additionally, it has been supercharged with a robust **Monitoring and logging stack** to help you keep up with the metrics, performance, and logs of the project in real-time.

## Features
- **Manage Notes**: Create, Read, Update, and Delete your daily notes.
- **Monitoring & Logging**: Included stack to track application health, metrics, and aggregated logs.
- **Community-Driven**: Created by Shivang for anyone to use, learn from, and contribute to.

## Requirements
1. Python 3.9
2. Node.js
3. React
4. Docker (for the app and monitoring stack)

## Installation & Setup

1. **Clone the repository**
```bash
git clone https://github.com/LondheShubham153/django-notes-app.git
```

2. **Build the app**
```bash
docker build -t notes-app .
```

3. **Run the app**
```bash
docker run -d -p 8000:8000 notes-app:latest
```

## Nginx

Install an Nginx reverse proxy to make this application available:

```bash
sudo apt-get update
sudo apt install nginx
```

## Monitoring & Logging
This project includes a fully configured monitoring and logging stack to help you keep up with project metrics and logs. 
- **Metrics**: Track application performance, request rates, and resource usage.
- **Logs**: Centralized logging for easier debugging and auditing.

