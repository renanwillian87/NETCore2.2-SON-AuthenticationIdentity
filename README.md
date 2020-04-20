# NETCore2.2-SON-AuthenticationIdentity

 - Create Project with Ident
 - Installing CodeGenerator

## Points:
 - Create Project
 - Add Claim and Policy
 - Custom Pages

## Code Generator
$ Install Tool </br>
> dotnet tool install -g dotnet-aspnet-codegenerator --version 2.2.3.0 </br> </br>
$ Install Packge Nuget </br>
> dotnet add package Microsoft.VisualStudio.Web.CodeGeneration.Design --version 2.2.3 </br> </br>
$ Show All Files </br>
> dotnet aspnet-codegenerator identity --listFiles </br> </br>
$ Generate code Account.Register scaffolding </br>
>dotnet aspnet-codegenerator identity -dc AuthenticationMVC.Data.ApplicationDbContext --file Account.Register </br> </br>
$ Generate code Account.Login scaffolding </br>
>dotnet aspnet-codegenerator identity -dc AuthenticationMVC.Data.ApplicationDbContext --file Account.Login </br> </br>
