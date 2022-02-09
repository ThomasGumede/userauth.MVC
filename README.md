# userauth.MVC user management system

user management system built using C# asp.net core 6 MVC, EF Core 6, Postgresql 13 and asp.net core identity framework.

## development Environment
- Windows 10, VS Code

## Features
- Able to upload profile image & it is store on wwwroot/profile/{file.FileNAme}
- Other Identity Scattfold generated features

## Run System
- Replace Postgresql connection string with your own connection string
- dotnet ef migrations add "message" --context ApplicationDBContext --output Data/Migrations
- dotnet ef database update --context ApplicationDBContext
- dotnet run

## Access Admin panel
- Find admin creditials on Data/ContextSeed.cs

## Final Note
- I'm still learning asp.net core with EF Core and Postgresql. My goal is to extend this project with additional features that i'll discover as i continue discovering & learning asp.net core features,
So FYI, i'll continue extending this project
