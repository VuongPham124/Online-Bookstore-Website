# Nhà Sách — Online Bookstore Website

A full-stack bookstore web application built with ASP.NET (C#) and SQL Server.

## Tech Stack

- **Backend:** ASP.NET, C#
- **Frontend:** HTML5, CSS3, JavaScript
- **Database:** SQL Server
- **Deployment:** Docker, Render.com

## Features

- Browse and search books by category, title, author
- Shopping cart and order management
- User authentication and role-based access (customer / admin)
- Admin panel: manage products, orders, users
- Responsive UI compatible with mobile browsers

## Database

SQL schema included in `NhaSachCNPMNC.sql`. Import into SQL Server before running.

## Getting Started

**Option 1 — Run locally:**
1. Clone the repo
2. Import `NhaSachCNPMNC.sql` into SQL Server
3. Update connection string in `appsettings.json`
4. Run with Visual Studio or `dotnet run`

**Option 2 — Docker:**
```bash
docker build -t nhasachmetnoi .
docker run -p 8080:80 nhasachmetnoi
```

## Project Structure

```
NhaSachMetMoi/        # Main ASP.NET project
NhaSachCNPMNC.sql     # Database schema
Dockerfile            # Docker config
render.yaml           # Render.com deploy config
```
