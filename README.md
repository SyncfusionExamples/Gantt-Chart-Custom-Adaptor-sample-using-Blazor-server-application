# Gantt Chart Custom Adaptor Sample Using Blazor Server Application

This repository contains a Blazor Web Application that demonstrates how to use a custom adaptor with the Syncfusion Blazor Gantt Chart. The sample highlights server-side data processing for sorting, filtering, searching, and CRUD operations using a custom data binding approach.

## Project Overview

The Syncfusion Blazor Gantt Chart supports custom data binding through adaptor implementations, enabling complete control over how data is fetched, processed, and persisted. This project illustrates how a CustomAdaptor can be configured to connect the Gantt Chart component with server‑side logic in a Blazor Server application.

All data requests initiated by the Gantt Chart such as sorting, filtering, searching, and editing are routed through the DataManager pipeline and handled by the custom adaptor. This approach is especially useful when working with complex business rules, legacy data sources, or APIs that require custom request handling.

The sample demonstrates how create, update, and delete operations are processed on the server to ensure consistent data synchronization between the Gantt Chart and the underlying data source.

## Custom binding in Blazor Gantt Chart

The [SfDataManager](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor.Data.SfDataManager.html) supports custom adaptors, which enables to manually control data operations instead of relying on built‑in adaptors. It is useful for implementing custom data binding and editing operations in the [Blazor Gantt Chart](https://www.syncfusion.com/blazor-components/blazor-gantt-chart).

To implement custom data binding in the Gantt Chart, the [DataAdaptor](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor.DataAdaptor.html) class is used. This abstract class serves as a base class for the custom adaptor.

The `DataAdaptor` abstract class includes both synchronous and asynchronous method signatures, which can be overridden in the custom adaptor.

## Features

- Custom adaptor implementation for Blazor Gantt Chart
- Server-side handling of sorting and filtering operations
- Search support through custom data processing logic
- CRUD operations managed through server methods
- Integration with DataManager and Syncfusion Blazor Gantt
- Implementation based on a Blazor Web Application

## Prerequisites

- Visual Studio 2022 (or later)
- .NET SDK 8.0 or later
- Syncfusion Blazor Gantt NuGet package
- A valid Syncfusion license (Community or Trial)

## How to Run the Project

1. Clone or checkout this repository to a local folder.
2. Open the project file (.csproj) in Visual Studio 2022 or later.
3. Rebuild the solution to restore required NuGet packages.
4. Run the application.
5. Navigate to the page containing the Gantt Chart.
5. Verify that sorting, filtering, searching, and CRUD operations are handled through the custom adaptor.

## Reference

For additional details, refer to the documentation:  
https://blazor.syncfusion.com/documentation/gantt-chart/custom-binding

## Syncfusion License

This sample uses the Syncfusion Blazor components, which require a valid Syncfusion license.

- Community License: https://www.syncfusion.com/products/communitylicense
- Trial License: https://www.syncfusion.com/account/manage-trials/start-trials

Ensure the license key is registered before running the application.
