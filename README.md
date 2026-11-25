# Product Management API

A REST API for product management with a layered backend and integration tests.

## Features

- Product controllers and DTOs
- business rules and service layer
- repository-based persistence
- integration-test project and Docker test configuration

## Technology stack

C#, .NET 9, ASP.NET Core, MongoDB, OpenAPI, Docker Compose.

## Getting started

Install the .NET 9 SDK and configure a local or dedicated MongoDB test instance using the application settings. Restore dependencies with `dotnet restore ZTP1.sln`. Review `docker-compose.test.yml` and the integration-test project before running tests. Do not commit credentials.
