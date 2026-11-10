# Advanced Drag and Resize Events in Blazor Scheduler

A quick start Blazor project that helps you learn the options available with drag and drop and resize actions in [Blazor Scheduler](https://www.syncfusion.com/scheduler-sdk/blazor-scheduler). This sample demonstrates how to enable, configure, and customize dragging and resizing functionality for appointments within a Blazor-based scheduling application.

## Features

* **Drag and Drop Support**: Easily move appointments within the scheduler by dragging them to different time slots and resources
* **Resize Functionality**: Adjust appointment duration by resizing from the appointment borders
* **Dynamic Updates**: Real-time synchronization of appointment changes across the scheduler view
* **Multiple View Support**: Works seamlessly with different scheduler views (day, week, month, etc.)
* **Resource Grouping**: Support for dragging and resizing appointments across multiple resources
* **Responsive Design**: Fully responsive scheduler interface that adapts to different screen sizes

## Prerequisites

- Visual Studio 2026 or Visual Studio Code
- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0)

## How to run the project

**Visual Studio 2026**:

* Checkout this project to a location in your disk.
* Open the project (`DragResizeOptions.csproj`) file.
* Restore the NuGet packages.
* Run the project.

**Visual Studio Code**:

* Open the repository folder in Visual Studio Code.
* Open the integrated terminal.
* Navigate to the repository root.

```bash
cd drag-and-resize-options-in-blazor-scheduler
dotnet restore
dotnet run
```

Open the URL displayed in the terminal after the application starts.

## Usage

Once the project is running, you can:

* Click and drag appointments to move them to different dates or time slots
* Hover over appointment edges to reveal resize handles
* Drag appointment edges to extend or reduce the appointment duration
* Drop appointments on different resources if resource grouping is enabled

## Documentation

For comprehensive information about Blazor Scheduler and its features, refer to the following Syncfusion documentation:

* **Blazor Introduction**: https://blazor.syncfusion.com/documentation/introduction
* **Scheduler Getting Started**: https://help.syncfusion.com/scheduler-sdk/blazor/schedule/getting-started-with-server-app
* **Scheduler Appointments**: https://help.syncfusion.com/scheduler-sdk/blazor/schedule/appointments

## Live Demo

**Example**: https://blazor.syncfusion.com/demos/scheduler/local-data

## Additional Resources

* Explore more Blazor scheduler samples and demos at the official Syncfusion website
* Check out the comprehensive API documentation for advanced customization options
* Review best practices for implementing drag and drop interactions in web applications