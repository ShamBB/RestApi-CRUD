# RestApi-CRUD

## Overview
A simple REST API for performing CRUD operations.

## Database
This application uses SQL Server as its database management system.

## Installation
To set up the project, clone the repository and restore the dependencies using the following commands:
```bash
- cd projectname
- dotnet restore

### Configuration
- Change the connection string in `appsettings.json`:
json
"ConnectionStrings": {
"DefaultConnection": "Data Source=(LocalDb)\\MSSQLLocalDB;Initial Catalog=RestAPI;Integrated Security=True;Connect Timeout=30;Encrypt=False;TrustServerCertificate=False;ApplicationIntent=ReadWrite;MultiSubnetFailover=False"
}


### Database Migration
- Run the migration in the Package Manager Console:
update-database
- dotnet-run
```

