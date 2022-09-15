<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/523307766/22.1.4%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T1108437)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->

# Grid for Blazor - Customize the appearance of elements including row and cell values based on custom conditions

The [Blazor Grid](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxGrid) allows you to customize the appearance of individual UI elements based on custom conditions (conditional formatting).

This example customizes the appearance of Blazor Grid cells/rows in the following manner:
 
* Highlighted data cells: `UnitsInStock < 10`. 
* Strikethrough data rows: `UnitsInStock = 0`. 
* `UnitPrice` values are set to bold and colored based on the following conditions:  
  * If a price is lower than the average price, the font is set to red. 
  * If a price is higher than the average price, the font is set to green. 
	
    The average price is calculated within the Blazor Grid's summary item ([DxGridSummaryItem](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxGridSummaryItem)).

![Grid - Custom Element Appearance](images/grid.png)

<!-- default file list -->
## Files to Review

[Index.razor](./CS/GridConditionalFormatting/Pages/Index.razor)

## Documentation

[Custom Element Appearance](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxGrid.CustomizeElement)
