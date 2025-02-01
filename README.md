# API Activities

### LAB ACT1 INTRODUCTION TO FASTAPI
>This activity uses FastAPI with Python to create an API endpoint at /factorial/{starting_number} that computes the factorial of a given number using a while loop, and returns {"result": false} when the input is 0. It provides a hands-on approach to learning API development, logical coding, and testing with Uvicorn.

### LAB ACT2 WORKING WITH HHTP ACTIONS AND API PARAMETERS
>This activity involves building a To-Do List API with FastAPI to simulate CRUD operations while focusing on proper API parameterization and HTTP method usage. Starting from sample code, you modify it to initialize a task database and create endpoints for GET, POST, PATCH, and DELETE requests. Each endpoint is designed to return a success message ({"status": "ok"}) when operations succeed or an appropriate error message if validations—such as null checks and ensuring non-negative values—fail. This hands-on exercise teaches best practices in API design, data validation, and efficient use of HTTP methods in a concise and practical way.

### LAB ACT3 WORKING WITH JSON 
>This exercise teaches you how to work with JSON in API development using Python. You'll start by cloning a GitHub repository and setting up your environment in the provided lab folder. Then, you'll update the existing main.py file to add a new GET endpoint, /detailed_post/{userID}, which retrieves every post made by a specific user along with all related comments. The task emphasizes practical skills in parsing JSON strings, traversing JSON data, and converting Python data structures into valid JSON format using the key naming conventions detailed in the expected_output.json file. Finally, you'll submit your updated code—and optionally a requirements.txt file—via GitHub.

### LAB ACT4 ADVANCED API EMPLEMENTATION
>This activity focuses on enhancing your API by implementing versioning, authentication, and robust HTTP exception handling. You'll create two API versions—apiv1 and apiv2—and ensure that endpoints correctly handle cases like accessing, deleting, or updating non-existent tasks with 404 errors, while also returning proper status codes (201 for adding, 204 for updates/deletions, and 200 for all other cases). Additionally, you'll integrate API key authentication through environment variables managed in a .env file (which should be excluded from the repository using a .gitignore file), following best practices for secure and maintainable code.

### LAB ACT5 DEPLOYING API IN CLOUD
>This activity involves taking your API from laboratory activity #4 and deploying it to a cloud platform using Render. You'll follow a provided guide to configure, deploy, and expose your API online, transforming your local development project into a live, accessible service. This task hones your skills in cloud deployment and ensures that you can efficiently manage and scale your API in a production environment.
