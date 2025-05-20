# WebAPIMPC

This is an ASP.NET Core Web API project.

## Project Structure

- `WebAPIMPC/` - Main project folder
  - `Controllers/` - API controllers
  - `appsettings.json` - Main configuration file
  - `appsettings.Development.json` - Development configuration
  - `Program.cs` and `Startup.cs` - Application entry point and startup configuration

## Prerequisites

- [.NET 8.0 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)

## Getting Started

1. **Restore dependencies:**
   ```powershell
   dotnet restore
   ```
2. **Build the project:**
   ```powershell
   dotnet build
   ```
3. **Run the API:**
   ```powershell
   dotnet run --project WebAPIMPC/WebAPIMPC.csproj
   ```
4. **API Documentation:**
   - If Swagger is enabled, navigate to `https://localhost:5001/swagger` or the URL shown in the console output after running.

## Configuration

- Edit `WebAPIMPC/appsettings.json` and `appsettings.Development.json` for environment-specific settings.

## License

Specify your license here.
