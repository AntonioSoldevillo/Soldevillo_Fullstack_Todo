Django Api Endpoints

Get All Tasks (GET) = https://backend-uv0r.onrender.com/api/todolist/

Create a Task (POST) =https://backend-uv0r.onrender.com/api/todolist/

Get a Specific Task (GET) = https://backend-uv0r.onrender.com/api/todolist/{id}/

Update a Task (PUT) = https://backend-uv0r.onrender.com/api/todolist/{id}/

Delete a Task (DELETE) = DELETE https://backend-uv0r.onrender.com/api/todolist/{id}/


Report on the To-Do App:

Overview:
The To-Do app allows users to manage tasks efficiently with functionalities like adding new tasks, editing existing tasks, and deleting tasks. Additionally, the app offers a filtering feature to view completed or pending tasks and provides a dark mode option for better user experience.

Key Features:
Dark Mode: Users can switch between dark and light modes.

Task Management:

Add Task: Users can create new tasks.

Edit Task: Users can edit the title of an existing task.

Delete Task: Users can remove tasks from the list.

Task Filters: Tasks can be filtered by their completion status, showing either all, completed, or pending tasks.

Challenges Faced:
Deployment Issues (Render):

Initially, I encountered problems with the deployment of the app on Render due to incorrect configuration in the ALLOWED_HOSTS setting in Django. The issue was resolved by setting the ALLOWED_HOSTS to the domain of the deployed app on Render.

Installation of Dependencies:

I faced some difficulties in installing the required dependencies from requirements.txt. The issue was solved by ensuring the correct setup of the Python environment and reinstalling the necessary packages.

Solutions:
Deployment Issue:

I corrected the ALLOWED_HOSTS in the Django settings to match the deployed URL on Render, allowing the app to serve requests correctly.

Dependency Installation:

I verified the environment and manually installed the dependencies, ensuring that all packages were up-to-date and compatible with my project requirements.

Conclusion:
The To-Do app is now fully functional and deployed. It supports basic task management features with an enhanced user interface, offering dark mode and task filtering. The challenges faced during deployment and setup were addressed, and the app is now accessible online.
