1. Define CRUD.

*Create, Read, Update, Destroy. The four functions that an application needs to be able to do get, and react to repsonses over the internet.*

3. Define MVC.

*Model, Viewer, Controller. The three parts of what needs to happen when interacting with a database with HTTP requests. The model interacts directly with the database, the viewer makes the requests via HTTP requests and the Controller acts as the middle man between the other two.*

4. What two files would you need to create/modify for a Rails application to respond to a GET request to /api/v1/tasks, assuming you have a Task model.

*The routes file and the task_controller file. The routes file allows you to define the route that is needed to call a specific task, while the task_controller will define what those specific tasks do when they are called upon.*

5. What are params? Where do they come from?

*The params is a built in thing within Rails that asks for specific parameters to be sent when looking to do one of the tasks. It allows the parameters to be strongly defined so that they only accept the keys its looking for.*

6. What is the purpose of a serializer?

*To help configure the data that is requested by users. If the user is wanting only some of the stored data, then the serializer allows the model to return only what is requested while maintaining the full amount of data.*
