# Task Manager

## The Idea

This project was made in order to test out Razor, a framework that runs C# in your browser through Web Assembly. Nothing really fancy, but enough to try out the basics of the platform.

## Running on Linux (Arch-based)

### Requirements
- Download the [.NET SDK (AUR)](https://aur.archlinux.org/packages/dotnet-sdk-bin/) in order to be able to run dotnet commands on terminal and compile stuff.
- If "dotnet" command can't find a compatible framework, download [ASP.NET Runtime (AUR)](https://aur.archlinux.org/packages/aspnet-runtime-bin/) . The runtime is needed as it hasn't been implemented in the .NET SDK repository and it's a must to run Blazor projects.

### Running it locally

Run the command `dotnet run` to simply compile stuff on localhost;

If you want to enable hot-reload, the command `dotnet watch run` will do.
