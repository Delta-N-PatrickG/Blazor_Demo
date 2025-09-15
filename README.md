# BlazorDemo

BlazorDemo is a sample Blazor WebAssembly application targeting .NET 9. It demonstrates various Blazor features, including component interaction, routing, dependency injection, form validation, event callbacks, data binding, lifecycle methods, and JavaScript interop.

## Features

- **Component Demo:** Shows how to build and use reusable components.
- **Routing Demo:** Demonstrates route parameters and navigation.
- **Dependency Injection Demo:** Illustrates dependency injection in Blazor.
- **Event Callback Demo:** Explains parent-child communication using event callbacks.
- **Data Binding Demo:** Covers one-way and two-way data binding.
- **Lifecycle Demo:** Shows component lifecycle methods.
- **Form Validation Demo:** Demonstrates form validation using Blazor's built-in features.
- **JSInterop Demo:** Integrates JavaScript functions with Blazor using JS interop.

## Getting Started

### Prerequisites

- [.NET 9 SDK](https://dotnet.microsoft.com/download/dotnet/9.0)
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/)

### Running the Application

1. Clone the repository:
2. Open the solution in Visual Studio 2022.
3. Build and run the project (`F5` or `Ctrl+F5`).

The application will start in your browser at `https://localhost:5001` (or a similar port).

## Project Structure

- `Pages/` – Contains Blazor pages demonstrating various features.
- `Components/` – Contains reusable Blazor components.
- `Models/` – Contains data models.
- `wwwroot/` – Static files (CSS, JS).
- `Program.cs` – Application entry point and configuration.

## JavaScript Interop

The JSInterop demo uses a JavaScript function defined in `wwwroot/js/jsinteropDemo.js`. Make sure this file exists and is referenced in `index.html`:

## Styling

Each demo page has its own CSS file in `wwwroot/css/` for consistent styling.

## License

This project is licensed under the MIT License.
See the LICENSE file for more details.

---

Feel free to explore the different pages to learn more about Blazor's capabilities!