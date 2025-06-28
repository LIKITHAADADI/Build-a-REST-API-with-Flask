## Objective: To build a simple REST API using Flask that allows you to manage user data using CRUD operations
---
## CRUD operations:
1. Create
2. Rea
3. Update
4. Delete
---
## Tools Used:
1. Python – programming language
2. Flask – lightweight web framework to build APIs
3. VS Code – code editor
4. Thunder Client – API testing tool (built into VS Code)
---
## Step-by-Step Process:
### Step-1 :
Environment Setup Installed Python and Flask
### Step-2 :
Set up a folder in VS Code
(Optional) Created a virtual environment using python -m venv venv
### Step-3 :
Flask App Creation Created a file named app.py
### Step-4 :
Wrote a basic Flask app with routes:
* /users – for listing or adding users
* /users/ – for updating or deleting users
### Step-5 :
Data Handling Used a Python list (users = []) to store users in memory
Each user is a dictionary with:
* id
* name
* email
### Step-6 :
* Implemented API Endpoints GET /users – returns list of users
* POST /users – adds a new user
* PUT /users/ – updates an existing user
* DELETE /users/ – deletes a user
### Step-7 :
* Testing with Thunder Client Used Thunder Client in VS Code to send API requests
Verified responses like user creation, update, and delete
---
