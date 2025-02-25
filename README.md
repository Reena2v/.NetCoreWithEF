# .NetCoreWithEF
.Net Core with Entity Framework

Step 1: Install nuget packeages for Entity framework
    Microsoft.EntityFrameworkCore.SqlServer
    Microsoft.EntityFrameworkCore.Tools : to write commands for entity framework core, To create Database, migrate changes
    Microsoft.EntityFrameworkCore.Design

Step2: Add DB context class
        Add new App DB Context class
        Inherit it from DBContext class and use base class constructor
        Create connectionString configurations in appSettings file
        Configure your AppDBContext class in Program.cs with builder services

Add .gitignore file
Add .gitignore file and add file we want to ignore  remove cache use command : git rm -r --cached

