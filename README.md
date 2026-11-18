# Getting Started with the Blazor Dashboard Layout Component

## Project Overview
This sample demonstrates how to add the Syncfusion [Blazor Dashboard Layout](https://www.syncfusion.com/blazor-components/blazor-dashboard) component to a .NET 10 Blazor WebAssembly app. The application renders a four-panel dashboard and configures panel placement and size through properties such as `Columns`, `Column`, `Row`, `SizeX`, and `SizeY`. This approach shows how dashboard panels can be arranged and resized in a WebAssembly layout.

## Features
- Uses the Syncfusion Blazor `SfDashboardLayout` component to render the dashboard.
- Sets the dashboard to three columns through the `Columns` property.
- Disables panel dragging through `AllowDragging` and enables panel resizing through `AllowResizing`.
- Places four `DashboardLayoutPanel` items using the `Column` and `Row` properties.
- Sets panel size through `SizeX` and `SizeY`.
- Limits resizing through `MinSizeX`, `MaxSizeX`, `MinSizeY`, and `MaxSizeY`.
- Defines each panel header through `HeaderTemplate` and each panel body through `ContentTemplate`.
- Centers panel header and content text with component styles.

## Prerequisites
Ensure the following requirements are met before running this project:
- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with Blazor

## Installation

### Clone the Repository
Clone the repository and navigate to the project directory:
```bash
git clone https://github.com/SyncfusionExamples/getting-started-with-the-blazor-dashboard-layout-component.git
```
### Run the Application
**Visual Studio 2022**

1. Open the cloned repository folder.
2. Open the project file:

   `BlazorApp__DashBoard.csproj`

3. Restore the NuGet packages by rebuilding the solution.
4. Set the startup project to:

   `BlazorApp__DashBoard`

5. Build the solution.
6. Run the application using `Ctrl+F5`.
7. Open the application URL displayed by Visual Studio after launch.
8. Verify that the four dashboard panels are displayed in the Blazor Dashboard Layout.

**Visual Studio Code**

1. Open the cloned repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the project directory:

```bash
cd getting-started-with-the-blazor-dashboard-layout-component
```

4. Restore the NuGet packages:

```bash
dotnet restore
```

5. Run the project:

```bash
dotnet run
```

6. Open the local URL displayed in the terminal after the application starts.
7. Verify that the four dashboard panels are displayed in the Blazor Dashboard Layout.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official documentation: [Blazor Dashboard Layout getting started](https://help.syncfusion.com/chart-sdk/blazor/dashboard-layout/getting-started)

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
