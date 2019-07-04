Project Overview
================

This project intends to explore and define a modernization path
for a traditional ASP.NET 4.5 MVC application underpinned by a
SQL Server database, by turning it into an ASP.NET Core web app,
eliminating dependencies on Windows and IIS, and also by 
replacing SQL Server with LINQ-friendly PostgreSQL - a mature 
opensource relational database. Later we will try to abstrac away
data tier, while adding support to highly-scalabale, eventually-
consistent datastores like AWS DynamoDB.

The end goal of the project is to have Linux- and Kubernetes-
compatible ASP.NET web application, independend of Microsoft 
prorietary licenses. Initial phase of this modernization effort
will focus on using only opensource target platforms and
components. Later it may get updated to use AWS managed services
as dependencies.
