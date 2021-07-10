# NET-Identity-MVC

```sh
dotnet new -l
dotnet new sln -n NET-Identity-MVC

dotnet new mvc -o app
dotnet sln add app

dotnet add app package Microsoft.EntityFrameworkCore.SqlServer -v 5.0.0
dotnet add app package Microsoft.EntityFrameworkCore.Design -v 5.0.0
dotnet add app package Microsoft.AspNetCore.Identity.EntityFrameworkCore -v 5.0.0

dotnet restore app
```