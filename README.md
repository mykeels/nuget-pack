# Nuget-Pack

Powershell scripts for automating working with Nuget in your .NET projects

## Scripts

- Nuget-Pack.bat

This batch script will pack your project, including your assembly information, as a Nuget package

- Nuget-Push.bat

This batch script will push your nuget package to nuget.org ... 

    - Make sure to edit the endpoint if you use a different nuget server
    - Make sure to have the `Nuget_Api_Key` environment variable saved on your computer. See [guide for windows](http://helpdeskgeek.com/how-to/create-custom-environment-variables-in-windows-7/).

## How to use

- Clone the Repository
- Copy the `Nuget` folder into your `.csproj` project folder
- Start using the scripts