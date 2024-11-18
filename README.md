# Razor Pages Project

This repository contains a C# Razor Pages project built using Visual Studio 2022. The project includes all necessary files and dependencies to run and test the application.

## Prerequisites

To run this project, you will need:

- **Visual Studio 2022** with the following workloads:
  - **ASP.NET and web development**
  - **.NET Desktop Development** (optional, if additional desktop-based tools are needed)
- **.NET SDK**: This project is built on .NET 6 or higher.
- **SQL Server or SQLite** (based on the database configuration in `appsettings.json`)

## Getting Started

### Running the Project (without GitHub)

1. **Clone the repository locally**:
   If you haven't downloaded the project from GitHub, download the zip file of this repository and extract it to a folder on your computer.

2. **Open the project in Visual Studio 2022**:
   - Open Visual Studio.
   - Select **File > Open > Project/Solution**.
   - Browse to the extracted folder and open the `.csproj` or `.sln` file.

3. **Configure the database connection**:
   - Check `appsettings.json` for database configuration.
   - For SQLite, ensure the database file path is correctly set.
   - For SQL Server, update the connection string with your server and database information.

4. **Run the project**:
   - In Visual Studio, select **Debug > Start Debugging** or press `F5`.
   - The project will build and start on the configured localhost port.

### Running the Project (with GitHub)

If you are working with GitHub, follow these steps to set up the project with Git integration.

1. **Clone the repository from GitHub**:
   - Open Visual Studio 2022.
   - Go to **Git > Clone Repository**.
   - Enter the repository URL and select a location to save the project.
   - Click **Clone** to download the repository.

2. **Open the project**:
   - Once the repository is cloned, Visual Studio will automatically open the project.

3. **Set up GitHub for version control** (if not already configured):
   - Go to **Git > Manage Branches** to see all branches.
   - To create a new branch for your work, go to **Git > New Branch**.

4. **Configure the database connection**:
   - Edit the `appsettings.json` file as needed for your local database configuration.

5. **Run the project**:
   - Select **Debug > Start Debugging** or press `F5`.

6. **Push changes to GitHub** (optional):
   - After making changes, you can commit and push them to GitHub.
   - Go to **Git > Commit** to stage and commit your changes.
   - Then, select **Push** to send your changes to the remote repository.

## Additional Configuration

### Database Setup

Depending on your database choice, additional setup might be required:

- **SQLite**: Ensure the SQLite database file path is set correctly in `appsettings.json`.
- **SQL Server**: Update the connection string in `appsettings.json` to connect to your SQL Server instance. Ensure the database is created before running the application.

### Environment Variables

You can configure environment-specific settings (e.g., database credentials) using environment variables or secret managers for security.

## Troubleshooting

- **Port Issues**: If the application doesn't start, check if another application is using the port defined in `launchSettings.json`.
- **Database Errors**: Verify the database connection string and ensure the database exists and is accessible.

## Contributing

If you wish to contribute, please fork the repository and create a pull request.

1. Fork this repository.
2. Create a feature branch (`git checkout -b feature/YourFeatureName`).
3. Commit your changes (`git commit -am 'Add a feature'`).
4. Push to the branch (`git push origin feature/YourFeatureName`).
5. Open a pull request.

---

Happy coding!
