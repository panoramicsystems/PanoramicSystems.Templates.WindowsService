# PanoramicSystems.DotNetTemplates
dotnet core templates

To install
```
dotnet new -i PanoramicSystems.Templates.WindowsService
dotnet new -i PanoramicSystems.Templates.ConsoleApp
```
To update use the same command and specify a version or you may clear your nuget cache.
```
dotnet new -i PanoramicSystems.Templates.WindowsService::1.0.3
# or 
dotnet nuget locals all --clear
```

Example of usage:
```
mkdir NewApp.NameSpace
cd NewApp.NameSpace
dotnet new windowsservice
```
