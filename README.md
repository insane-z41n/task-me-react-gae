# task-me
## Project Overview:
Task Me is a task management web application. The project consists of a frontend and a backend service and both are deployed to Google App Engine. Created tasks are stored in a Firestore NoSQL database and end users can perform basic CRUD operations (Create, Read, Update, Delete) through frontend-backend requests/responses.

### Application Screenshots:
![app](https://screenshots-bucket-38293.s3.amazonaws.com/app.png)
![create](https://screenshots-bucket-38293.s3.amazonaws.com/create.png)
![update_delete](https://screenshots-bucket-38293.s3.amazonaws.com/update_delete.png)
![update](https://screenshots-bucket-38293.s3.amazonaws.com/update.png)

### Database Screenshots:
![database](https://screenshots-bucket-38293.s3.amazonaws.com/database.png)

## Project Goals: 
Deploy the below to Google App Engine (GAE):
1. Python web service
2. ReactJS frontend

Two separete deployments to Google App Engine will be carried out in this project, one for the backend web service and another for the frontend.

The frontend will be sending HTTP requests to the backend. The backend will be processing the frontend HTTP requests and connect to the Firestore database and perform basic CRUD operations accordingly. Backend web service will return repsonse to the frontend and frontend in its turn will be displaying the response data.

## Why App Engine:
App Engine provides access to other google services.

## Project Diagram:
![project_diagram](https://screenshots-bucket-38293.s3.amazonaws.com/diagram.png)

## Project Details:
### Frontend:
1. ReactJS: JavaScript Framework.
2. Axios: Establish connection with the backend web service (sends requests and receives responses).
3. React-Bootstrap: CSS framework to build React-like HTML components.

### Backend:
1. Python
2. Flask: A web framework, it is a Python module that lets you develop web applications
3. google-cloud-firestore: SDK for Google Cloud Firestore.
4. firebase-admin: The Admin SDK is a set of server libraries that lets you interact with Firebase from privileged environments and perform CRUD operations.

### Database:
Firestore: Google Cloud Firestore is a NoSQL document database built for automatic scaling, high performance, and ease of application development.

