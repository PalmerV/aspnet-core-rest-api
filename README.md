# GameStore API

A RESTful backend for a digital game storefront, built with .NET Core. A work in progress.

## Tech Used
* Framework: .NET 10
* Language: C#
* Database: Microsoft SQL Server
* ORM: Entity Framework Core
* Architecture: REST API

## Features
* Game Management: CRUD operations for the game catalog.
* Database Integration: SQL Server data persistence with EF Core migrations.

## How to Get Started
1. Clone repository: `git clone https://github.com/PalmerV/aspnet-core-rest-api.git`
2. Setup database: Make sure SQL Server is running, and update `appsettings.json` connection string.
3. Apply migrations: `dotnet ef database update`
4. Run project: `dotnet run`

## Future Plans (Coming soon!)
- [ ] Frontend Integration: Implementing a front-end using either Blazor, or React.
- [ ] Search Function: Implementing search capabilities for games.
- [ ] Implementing JWT is next on list, right now.

Example:
<img width="1920" height="1200" alt="GameStore_Screenshot" src="https://github.com/user-attachments/assets/adf43220-7957-4983-82b5-3e55c0af6f73" />
