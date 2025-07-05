# task-manager-api
A simple task manager backend REST API for managing tasks, built using Python and Flask. Ideal for beginners learning backend development and RESTful APIs. 

---

## Features
-Create a Task
-View all tasks
-Mark task as completed
-Delete task

---

##Tech Stack
-Python
-Flask
-REST API
-JSON

---

##API Endpoints

| Method | Endpoint            | Description                   |
|--------|---------------------|-------------------------------|
| GET    | '/tasks'            | Get all tasks                 |
| POST   | '/task'             | Add a new task                |
| PUT    | '/task/<id>'        | Mark task as completed        |
| DELETE | '/task/<id>'        | Delete a task                 |
---------------------------------------------------------------

##Example POST Payload
'''json
{
"title": "Complete Resume"
}
