# TaskManagementApi

A simple ASP.NET Core Web API for managing tasks using Entity Framework Core and SQLite, built in GitHub Codespaces.

## Setup Instructions
1. Clone the repository: git clone https://github.com/Akansha157/TaskManagerApi.git
2. Open the project in Github Codespaces
3. Navigate to the project folder in Termilnal: cd TaskManagerApi
4. Install dependencies: dotnet restore
5. Apply migrations: dotnet ef database update
6. Run the project: dotnet run
7. Access the API at https://laughing-engine-677jwg976rgfpp4-5256.app.github.dev/.

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
