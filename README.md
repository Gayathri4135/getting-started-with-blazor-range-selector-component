# Getting Started with the Blazor Range Selector Component

## Overview

This sample demonstrates the Syncfusion [Blazor Range Selector](https://www.syncfusion.com/forums) component in a hosted Blazor WebAssembly application. The implementation uses the `SfRangeNavigator` component to visualize stock price data and enable interactive date-range selection. Users can focus on a specific portion of a larger dataset by selecting a range directly within the navigator. The sample also illustrates tooltip configuration, area-series rendering, and customization of grid and tick lines.

## Key Features

- Uses the `SfRangeNavigator` component for interactive range selection.
- Binds stock price data using the `DataSource="StockDetails"` property.
- Configures date-based navigation with `ValueType="RangeValueType.DateTime"`.
- Formats axis labels using `LabelFormat="MMM-yy"`.
- Defines an initial selected range through the `Value` property using dates.
- Customizes major grid lines using `RangeNavigatorMajorGridLines`.
- Customizes major tick lines using `RangeNavigatorMajorTickLines`.
- Enables range selection tooltips using `RangeNavigatorRangeTooltipSettings`.
- Keeps tooltips visible using `DisplayMode="TooltipDisplayMode.Always"`.
- Renders stock data using `RangeNavigatorSeries`.
- Demonstrates strongly typed data binding through the `StockPrice` model containing `Date` and `Close` properties.
- Uses an area-series visualization to display stock performance over time.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the `GettingStarted.sln` solution file.
3. Restore NuGet packages.
5. Build the solution.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the project directory.

```bash
dotnet restore
dotnet run
```

4. Open the URL displayed in the terminal after the application starts.

## Project Structure

- `GettingStarted.sln` — Visual Studio solution file containing the sample projects.

- `Client/Pages/Index.razor` — Main sample page demonstrating notification badges integrated within a Syncfusion Toolbar.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For implementation details, see the [relevant official Syncfusion documentation](https://blazor.syncfusion.com/documentation/badge/getting-started).

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.