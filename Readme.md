<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/523307766/23.1.3%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T1108437)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->

# Grid for Blazor - Customize cell appearance based on custom conditions

The example demonstrates how to customize appearance of [DevExpress Blazor Grid](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxGrid) elements based on custom conditions.


![Grid - Customize Element Appearance](images/grid.png)

The code example uses [summary items](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxGridSummaryItem) to calculate minimum, maximum, and average column values. Based on cell and summary item values, a [CustomizeElement](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxGrid.CustomizeElement) event handler changes cell appearance in the following columns:

**Discount Column**  
Cells that display positive values are colored green.

**Unit Price Column**  
All cell values are bold. If a cell value is lower than the column average value, the cell's font color is green; otherwise, it is red.


**Quantity Column**  
If a cell value is lower than the average column value, the cell is colored in a shade of red; otherwise, it is a shade of blue. The more a cell value differs from the average value, the brighter the color. If a cell value is equal to the average value, the color is white.


**Total Column**  
A cell displays one of the following arrows based on its value:
* A red arrow pointing down - small values.

* A yellow arrow pointing left - medium values.

* A green arrow pointing up - large values.


## Files to Review

* [Index.razor](./CS/GridConditionalFormatting/Pages/Index.razor)
* [Index.razor.css](./CS/GridConditionalFormatting/Pages/Index.razor.css)

## Documentation

* [Custom Element Appearance](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxGrid.CustomizeElement)
