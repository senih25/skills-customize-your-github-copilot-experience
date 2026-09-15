# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a small REST API with FastAPI and practice defining routes, validating request data, and returning structured JSON responses.

## 📝 Tasks

### 🛠️ Create the FastAPI application

#### Description
Create a FastAPI application with a root endpoint and run it locally with Uvicorn.

#### Requirements
Completed program should:

- Create a `FastAPI` application instance
- Implement `GET /` returning a JSON welcome message
- Be runnable with Uvicorn

### 🛠️ Add an items resource

#### Description
Add endpoints for reading and creating items using a Pydantic model for request validation.

#### Requirements
Completed program should:

- Define an `Item` model with a name and price
- Implement `GET /items/{item_id}`
- Implement `POST /items`
- Return JSON responses using validated data

### 🛠️ Handle invalid input

#### Description
Verify that FastAPI rejects malformed requests and returns useful validation errors.

#### Requirements
Completed program should:

- Reject requests missing required fields
- Reject invalid field types
- Document one example validation error and explain why it occurs
