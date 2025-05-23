# Asset Management System

## Project Summary  
I built the Asset Management System to enable secure tracking of company hardware and software assets. Designed for IT administrators, the app ensures complete lifecycle visibility of each asset, from procurement to decommission.

Authentication is secured via Azure Active Directory with role-based access for Admins and Technicians. The backend is a robust ASP.NET Core Web API with EF Core for data persistence to Azure SQL Server. The React frontend integrates MSAL.js for SSO with Azure AD and provides intuitive asset tracking dashboards.

## Key Features  
- Azure AD login with Admin and Technician roles  
- Track hardware/software by category, status, and location  
- Asset assignment, maintenance, and decommission history  
- React UI with sortable/filterable tables  
- EF Core + SQL Server schema with full migration support  
- Hosted on Azure App Service

## Tech Stack  
- React, MSAL.js  
- ASP.NET Core Web API  
- Entity Framework Core, Azure SQL Server  
- Azure AD authentication  
- Azure App Service hosting

## What I Delivered  
- Created secure Azure AD apps with role claims  
- Designed normalized DB schema with relationships and indexes  
- Built full RESTful APIs with logging and validation  
- Integrated MSAL.js in React with protected routes  
- Deployed both apps to Azure with CI/CD pipeline  
- Delivered user documentation and administrator guides

