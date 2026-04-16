# Gantt Chart Custom Adaptor Sample Using Blazor Server Application

This repository contains a Blazor Server sample that demonstrates how to use a custom adaptor with the Syncfusion Blazor Gantt Chart. The sample highlights server-side data processing for sorting, filtering, searching, and CRUD operations using a custom data binding approach.

## Project Overview

The Syncfusion Blazor Gantt Chart supports custom data binding through adaptor implementations. This project illustrates how a CustomAdaptor can be configured to connect the Gantt Chart component with server-side logic in a Blazor Server application. All data requests initiated by the Gantt Chart are processed on the server and returned through the DataManager pipeline.

The sample focuses on handling sorting, filtering, and searching operations through custom server-side methods. Create, update, and delete actions are also routed through the adaptor to ensure consistent data synchronization between the Gantt Chart and the underlying data source. This approach provides full control over data access and processing logic.

## Custom binding in Blazor Gantt Chart

The [SfDataManager](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor.Data.SfDataManager.html) supports custom adaptors, enabling manual operations on data. It is useful for implementing custom data binding and editing operations in the [Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor Gantt Chart](https://www.syncfusion.com/blazor-components/blazor-gantt-chart).

To implement custom data binding in the Gantt Chart, the [DataAdaptor](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor.DataAdaptor.html) class is used. This abstract class serves as a base class for the custom adaptor.

The `DataAdaptor` abstract class includes both synchronous and asynchronous method signatures, which can be overridden in the custom adaptor.

## Features

- Custom adaptor implementation for Blazor Gantt Chart
- Server-side handling of sorting and filtering operations
- Search support through custom data processing logic
- CRUD operations managed through server methods
- Integration with DataManager and Syncfusion Blazor Gantt
- Implementation based on a Blazor Server application

## Prerequisites

- Visual Studio 2026
- .NET SDK with Blazor Server support
- Syncfusion Blazor Gantt NuGet package

## How to Run the Project

1. Clone or checkout this repository to a local folder.
2. Open the solution file in Visual Studio 2026.
3. Rebuild the solution to restore required NuGet packages.
4. Run the application and navigate to the page containing the Gantt Chart.
5. Verify sorting, filtering, searching, and CRUD operations handled through the custom adaptor.

## Reference

For additional details, refer to the documentation:  
https://blazor.syncfusion.com/documentation/gantt-chart/custom-binding
