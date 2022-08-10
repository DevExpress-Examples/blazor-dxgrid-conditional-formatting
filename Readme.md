<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/523307766/22.1.4%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T1108437)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->


# Grid for Blazor - Conditional Formatting

The Blazor Grid allows you to customize appearance of UI elements based on custom conditions. 

This example customizes grid cells and rows in the following way.

* Data cells with UnitsInStock < 10 are highlighted.
* Data rows with UnitsInStock = 0 are strikethrough.
* UnitPrice values are bold and colored depending on the following condition: 
		* if a price is lower then the average price, the font is red;  
		* if a price is higher then the average price, the font is green.
	The average price is calculated in the grid's summary item (DxGridSummaryItem).

![Grid - Custom Element Appearance](images/grids.png)

<!-- default file list -->
## Files to Look At

[Grid.razor](./CS/GridConditionalFormatting/Pages/Grid.razor)

## Documentation

[Custom Element Appearance](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxGrid.CustomizeElement)
