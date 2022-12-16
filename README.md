<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/575405602/22.2.3%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T1132360)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
# Charts for Blazor - How to display the Chart based on the Grid focus

This example illustrates how to update the DevExpress Blazor [Chart](https://docs.devexpress.com/Blazor/401180/charts) component's data according to the currently focused row in the [Grid](https://docs.devexpress.com/Blazor/403143/grid).

![Blazor DxCharts update the data source](/charts.gif)

Set the Grid's [FocusedRowEnabled](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxGrid.FocusedRowEnabled) property to `true` to allow users to focus grid rows. When focus moves between rows, the Grid raises its [FocusedRowChanged](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxGrid.FocusedRowChanged) event. Handle this event to update the DxChart's [data](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxChart-1.Data) according to the currently [focused data item](https://docs.devexpress.com/Blazor/DevExpress.Blazor.GridFocusedRowChangedEventArgs.DataItem).

## Files to Review

- [Index.razor](./CS/Charts/Pages/Index.razor)

## Documentation

- [Get Started with Charts](https://docs.devexpress.com/Blazor/401769/charts/get-started-with-charts)
- [Get Started with Grid](https://docs.devexpress.com/Blazor/403625/grid/get-started-with-grid)

## More Examples

- [Chart for Blazor - Create a Drill-Down Chart](https://github.com/DevExpress-Examples/blazor-charts-create-drill-down-chart)
- [Blazor Grid - Display a Context Menu](https://github.com/DevExpress-Examples/blazor-dxgrid-show-context-menu)
