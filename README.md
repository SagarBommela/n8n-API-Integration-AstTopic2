# Topic 2 – Making Your First API Calls

## Overview

In this topic, I learned how to make different API requests using Postman and n8n. I used the ReqRes mock API to practice GET, POST, PUT, PATCH, and DELETE requests.

## Tools Used

- **Postman** – To test API requests.
- **n8n** – To create and execute API workflows.
- **ReqRes** – To test REST API operations.

## API Details

- **Base URL:** `https://reqres.in`
- **Resource:** `/api/users`
- **Response Format:** JSON

## HTTP Methods Used

| Method | Purpose |
|---|---|
| GET | Retrieve user details |
| POST | Create a new user |
| PUT | Update user details |
| PATCH | Partially update user details |
| DELETE | Delete a user |

## Implementation Steps

### 1. GET Request – Retrieve Users

- Used the GET method.
- Added the query parameter `page=2`.
- Retrieved the list of users.
- Verified the 200 OK response.

### 2. POST Request – Create User

- Used the POST method.
- Configured the request body in JSON format.
- Sent user details (name and job).
- Verified the 201 Created response.

### 3. PUT Request – Update User

- Used the PUT method.
- Updated the existing user's name and job.
- Verified the 200 OK response.

### 4. PATCH Request – Partial Update

- Used the PATCH method.
- Updated only the job field.
- Verified the successful response.

### 5. DELETE Request – Delete User

- Used the DELETE method.
- Sent a request to delete user ID 2.
- Verified the 204 No Content response.

## Combined n8n Workflow

Created a combined workflow using the following nodes:

`Manual Trigger → POST → PUT → DELETE`

### Workflow Execution

- Configured all HTTP Request nodes.
- Connected the nodes in sequence.
- Saved the workflow as **N8N CRUD Verification Workflow**.
- Executed the workflow successfully.
- Verified the execution results.


GIT url:


Loom Video:

https://www.loom.com/share/881c3911e04f471a9ec3b6a0cb45f3d6

