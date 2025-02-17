
# Checks for Understanding

### Define CRUD.
Create, Read, Update, Delete – basic operations for managing data

### Define MVC.
Model-View-Controller – an architectural pattern that separates data (Model), UI (View), and logic (Controller)

### What two files would you need to create/modify for a Rails application to respond to a GET request to /api/v1/tasks, assuming you have a Task model.
1. Controller
        app/controllers/api/v1/tasks_controller.rb
2. Routes
        config/routes.rb 

### What are params? Where do they come from?

Params are the data sent with a request, such as form inputs, query strings, or JSON payloads. Rails extracts these parameters and makes them accessible via the params hash in the controller. They are commonly used to pass data from the client to the server in API calls or form submissions.

### What is the purpose of a serializer?
A serializer formats model data into a structured JSON response, making it easier to control what data is exposed through an API. It helps keep API responses consistent and avoids exposing unnecessary attributes. This is especially useful when working with frontend applications that consume the API.
