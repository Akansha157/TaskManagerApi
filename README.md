# TaskManagementApi

A simple ASP.NET Core Web API for managing tasks using Entity Framework Core and SQLite, built in GitHub Codespaces.

## Setup Instructions
1. Clone the repository: git clone https://github.com/Akansha157/TaskManagerApi.git
2. Navigate to the project folder: cd TaskManagerApi
3. Install dependencies: dotnet restore
4. Apply migrations: dotnet ef database update
5. Run the project: dotnet run
6. Access the API at https://laughing-engine-677jwg976rgfpp4-5256.app.github.dev/.

## API Endpoints
- GET /api/Tasks: List all tasks
- GET /api/Tasks/{id}: Get a task by ID
- POST /api/Tasks: Create a new task
- PUT /api/Tasks/{id}: Update a task
- DELETE /api/Tasks/{id}: Delete a task

## Technologies Used
- ASP.NET Core 8
- Entity Framework Core
- SQLite
- GitHub Codespaces
