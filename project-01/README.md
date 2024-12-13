# Project-01

## Overview
Project-01 is a minimal ASP.NET API project that provides weather forecast information. It demonstrates the use of minimal APIs and includes a controller to handle HTTP requests related to weather forecasts.

## Project Structure
```
project-01
├── Controllers
│   └── WeatherForecastController.cs
├── Program.cs
├── Startup.cs
├── appsettings.json
├── appsettings.Development.json
└── project-01.csproj
```

## Setup Instructions

1. **Clone the repository:**
   ```
   git clone <repository-url>
   cd project-01
   ```

2. **Restore dependencies:**
   ```
   dotnet restore
   ```

3. **Run the application:**
   ```
   dotnet run
   ```

## Usage
Once the application is running, you can access the weather forecast endpoint at:
```
http://localhost:5000/weatherforecast
```

## Configuration
- The application settings can be found in `appsettings.json` and `appsettings.Development.json`.
- Modify these files to change connection strings and other application settings as needed.

## Contributing
Feel free to submit issues or pull requests for improvements or bug fixes.