WebsiteSellLaptop API
Backend API for website of sell laptop, built with ASP.NET Core and SQL Server.

Features
CRUD Product, Brand, Category
Order & OrderItems
Dashboard statistics
Tech Stack
ASP.NET Core 8
SQL Server
Dapper
Swagger
Installation
Clone repo: git clone https://github.com/yourname/WebsiteSellLaptop.git

Open appsettings.json and change:

DefaultConnection: Server=your_server\SQLEXPRESS;Database=your_database;Trusted_Connection=True;TrustServerCertificate=True;

Add frontend IP to AllowedOrigins

Run MainProgram.cs or run command: dotnet run

Open swagger in browser: http://{server-ip}:{port}/swagger ``
