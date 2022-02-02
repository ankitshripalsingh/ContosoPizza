# ContosoPizza
Create a web API with ASP.NET Core Controllers

This is my first web API application using ASP.NET Core Controllers with .NET 6.0 and C#.

Tech Stack: Visual Studio Professional, .NET 6.0, C#, HTTPREPL, Command Prompt

The data store used is in-memory cache.
I have implemented CRUD operations using GET | POST | PUT | DELETE http verbs to view, create, update and delete pizza records.
I have tested the web API action methods from the command prompt using HTTPREPL.

# Benefits of creating APIs in ASP.NET Core

With ASP.NET you can use the same framework and patterns to build both web pages and services.
This means you can reuse model classes, validation logic, and even serve both web pages and services side-by-side in the same project.
There are a number of benefits to this approach.

1. Simple serialization
ASP.NET was designed for modern web experiences.
Endpoints automatically serialize your classes to properly formatted JSON out of the box.
No special configuration is required. Of course, serialization can be customized for endpoints that have unique requirements.

2. Authentication and authorization
Secure API endpoints with built-in support for industry standard JSON Web Tokens (JWT).
Policy-based authorization gives you the flexibility to define powerful access control rules—all in code.

3. Routing alongside your code
ASP.NET lets you define routes and verbs inline with your code, using attributes.
Data from the request path, query string, and request body are automatically bound to method parameters.

4. HTTPS by default
HTTPS is an important part of modern, professional web APIs.
It relies on end-to-end encryption to provide privacy and ensure your API calls aren't intercepted and altered between client and server.
ASP.NET provides first class support for HTTPS out of the box.
It automatically generates a test certificate and easily imports it to enable local HTTPS so you run and debug your applications securely, before you publish them.

5. Share code & knowledge with .NET apps
Leverage your .NET skills and ecosystem to share logic from your web API to other apps built with .NET including mobile, web, desktop, services, and more.

# Testing web APIs using the .NET HTTP REPL
When you are developing a traditional website, you will usually view and test your work in a web browser.
Web APIs accept and return data rather than HTML, so a web browser isn't the best web API testing tool.
One of the easiest options to use for exploring and interacting with web APIs is the .NET HTTP REPL.
REPL stands for Read-Eval-Print Loop.
It's a simple and popular way to a build interactive command-line environments.
