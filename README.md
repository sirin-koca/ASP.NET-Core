# ASP.NET Core with C# MVC

Welcome to this GitHub repository focused on the basics of ASP.NET Core using C# and the MVC design pattern.

## Introduction

### What is ASP.NET Core?
- ASP.NET Core is a free and open-source framework developed by Microsoft.
- It's a modern, cloud-based, internet-connected application framework.
- Allows developers to build web apps, RESTful APIs, and mobile backends.

### What is C#?
- C# (pronounced "C Sharp") is a modern object-oriented programming language.
- It's part of the .NET family and is designed for building Windows applications.

### MVC Design Pattern
- MVC stands for Model-View-Controller.
- It's a design pattern that separates an application into three interconnected components:
  - **Model**: Handles data and business logic.
  - **View**: Displays the user interface and visuals.
  - **Controller**: Manages user inputs and interacts between Model and View.

## Code Examples

1. ## Simple Controller
```csharp
public class HomeController : Controller
{
    public IActionResult Index()
    {
        return View();
    }
}
```
2. ## Model Example
```csharp
public class Student
{
    public int Id { get; set; }
    public string Name { get; set; }
    public int Age { get; set; }
}
```
3. ## View Example (Razor syntax)
```csharp
@model Student
<h2>@Model.Name's Profile</h2>
<p>Age: @Model.Age</p>
```
### Get Started
Install the latest .NET SDK
### Create a new ASP.NET Core MVC project:
``` dotnet new mvc -n YourProjectName```
### Navigate to your project directory:
``` cd YourProjectName ```
### Run the application:
``` dotnet run ```

### Further Reading
- [Official ASP.NET Core Documentation](https://docs.microsoft.com/aspnet/core/)
- [C# Guide](https://docs.microsoft.com/dotnet/csharp/)
- [MVC Design Pattern](https://docs.microsoft.com/aspnet/core/mvc/overview)


#### Feel free to contribute to this repository and make it a great resource for beginners!
