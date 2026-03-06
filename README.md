# .NET 10 Web API Demo Project

A minimal ASP.NET Core Web API demonstration project built with .NET 10.

## Features

- **RESTful API Endpoints** - Sample weather forecast API
- **Swagger/OpenAPI** - Interactive API documentation
- **Dependency Injection** - Built-in service container
- **HTTPS Support** - Secure by default
- **Minimal Hosting** - Streamlined startup configuration

## Prerequisites

- .NET 10 SDK
- Visual Studio 2022 / VS Code (optional)

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/SanjayJaiswal07/MyFirstRepo.git
cd MyFirstRepo
```

2. Restore dependencies:
```bash
dotnet restore
```

3. Run the API:
```bash
dotnet run
```

4. Access the API:
- **API Base URL**: https://localhost:5001
- **Swagger UI**: https://localhost:5001/swagger/index.html

## API Endpoints

### Weather Forecast
- **GET** `/api/weatherforecast` - Returns a list of weather forecasts

## Project Structure

```
MyFirstRepo/
├── Program.cs                      # Application startup and configuration
├── MyFirstProject.csproj           # Project file
├── appsettings.json                # Application settings
├── Controllers/
│   └── WeatherForecastController.cs # Sample API controller
└── README.md                       # Documentation
```

## License

This project is open source and available under the MIT License.