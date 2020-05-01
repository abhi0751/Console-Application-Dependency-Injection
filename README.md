# Console-Application-Dependency-Injection
Adding Dependency Injection and Configuration to a .net core console application.


1.    Add App.cs file to the project
2.    Add a Run method to the App.cs file, as shown below

The App.cs class that will be used to run the application.
Program.cs will be used to do the setup and register the IOC container, and the App.cs will contain all of the running console application code.
Add a json configuration file to the project and name it `appsettings.json`

1. Install Nuget Package `Microsoft.Extensions.DependencyInjection`
2. Install Nuget Package `Microsoft.Extensions.Configuration`
3. Install Nuget Package `Microsoft.Extensions.Configuration.Binder`
4. Install Nuget Package `Microsoft.Extensions.Configuration.Json`
IMPORTANT: Open appsettings.json properties, and change Copy To Output Directory, to Copy if newer or Copy always

https://dev.to/ballcapz/adding-dependency-injection-to-net-core-console-applications-on-windows-3pm0
