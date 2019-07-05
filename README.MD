Modernizing Classic ASP.NET (MVC) + SQL Server App
==================================================

This project intends to explore and define a modernization path
for an existing traditional Windows/IIS ASP.NET 4.5 MVC
application underpinned by a SQL Server database, by achieving
following goals:

## Milestone 0

- Create test/regression suite, per [Issue #1](/../../issues/1).

## Milestone 1

- Target not only Windows, but also Linux, including Docker
containers and container orchestrators like Kubernetes.
- Make it compatible with PostgreSQL open-source database, to
enable usage of scalable could-based PostgreSQL as a service.
- Eliminate dependencies on components requiring proprietary
licenses.

## Milestone 2

- Use AWS or Kubernetes-based CI/CD pipeline to automate software
build, validation (security, license, quality), and "canary"
deployment to production.

## Milestone 3

- Replace relational database with an eventually
-consistent, highly scalable cloud data store.

# System Requirements

- Visual Studio 2019 (Community or better), with ASP.NET and
**LocalDb** support add-ons installed.

# Building and Running

- Build solution in Visual Studio. Ensure all dependency NuGet
packages were restored.
- Run `database-update` command in Visual Studio "Package Manager
Console" to create and seed the database.
- Run ContosoUniversity project to see the web UI page.
- For troubleshooting and other details, see [Microsoft Sample 
page](https://code.msdn.microsoft.com/ASPNET-MVC-Application-b01a9fe8).
