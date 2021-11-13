# A BLAZING JOURNEY
To run on mac download the .net software development kit

use the command below to create a new blazor application

    dotnet new blazorserver -o BlazorApp --no-https

To run the application run the command 

    dotnet watch
    
### Observations    
1. .razor file contains both @page directive, Html, and @code directive 
2. The .razor file name is the name of the component, a component has the @code annotation
3. Properties are referenced using the @ annotation    
    
## INTRODUCTION
Lets C# Software Engineers build web applications with their skills in C# and Microsoft.NET Developers can build front-end and back-end logic for web apps with common languages, frameworks and tools.

- Accelerate app development.
- Reduce the complexity of the build pipeline.
- Simplify maintenance.
- Let developers understand and work on both client-side and server-side code.

### What is Blazor? - 
Blazor apps are composed of reusable web UI components using C#, HTML and CSS developers can build client and server code with C#.
- They can also share code and libraries between the frontend client code and backend logic

You can use Blazor to generate:
- Server-side code that handles UI interactions over a WebSocket connection.
- A client-side web app that runs directly in the browser via WebAssembly.

### What is WebAssembly(WASM)?
- Its an open binary standard 
- It defines a portable code format for programs designed to run in web browsers
- WebAssembly is a textual assembly language with a compact binary format for fast downloads and near-native performance.
- WebAssembly provides a compilation target for languages such as C, C++, and Rust.
- It's designed to run alongside JavaScript so that both work together
- WebAssembly also can generate progressive web applications to be downloaded and run offline.

### What is Blazor WebAssembly?
- With Blazor WebAssembly, developers can run .NET code in a browser.
- It's a single-page app framework and uses the WebAssembly open standards without requiring plug-ins or code generation.
- .NET code executed via WebAssembly in a browser runs in the browser's JavaScript sandbox. 

![image](https://user-images.githubusercontent.com/17984713/141642623-a6ce1bb8-927e-4b58-95b8-209fe2add22a.png)
- Blazor uses a .NET runtime compiled to a WebAssembly module that is downloaded with an app.
- The module can execute .NET Standard code included in a Blazor app.
- A Blazor WebAssembly app is restricted to the capabilities of the browser that executes the app. But the app can access full browser functionality via JavaScript interop

### What is Blazor Server?
- Blazor Server provides support for hosting Razor components on the server in an ASP.NET Core app.
- UI updates are handled over a SignalR connection.
- The runtime stays on the server and handles:
- Executing the app's C# code.
- - Sending UI events from the browser to the server.
- - Applying UI updates to the rendered component that are sent back by the server.
- The connection used by Blazor Server to communicate with the browser is also used to handle JavaScript interop calls.
![image](https://user-images.githubusercontent.com/17984713/141642784-6572fdfe-24f6-44be-9bab-12abff480c5e.png)

- A client-side web app that runs directly in the browser via WebAssembly.

Use the command below to create a new Blazor Project in a directory of your choice
    
    dotnet new blazorserver -f net6.0
- Boom    
    
