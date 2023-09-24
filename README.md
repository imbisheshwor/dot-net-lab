Setup Environment
    • Open the integrated terminal.
    • Change directories (cd) to the folder that will contain the project folder.
    • Run the following commands:

    .NET Core CLI
    coreate a folder name TodoApi
    dotnet new webapi 
    dotnet add package Microsoft.EntityFrameworkCore.SqlServer
    dotnet add package Microsoft.EntityFrameworkCore.InMemory
    dotnet run
    

The preceding commands:
    o Creates a new web API project and opens it in Visual Studio Code.
    o Adds the NuGet packages which are required in the next section.
Running the project
- dotnet build
- dotnet run

Project run in :
http://localhost:5196/Weatherforecast
or 
using swagger 
http://localhost:5196/swagger/index.html