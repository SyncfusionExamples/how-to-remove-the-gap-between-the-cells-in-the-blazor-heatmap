# Example of removing the gap between the cells in the Syncfusion Blazor HeatMap component
In this Blazor project, we have created a sample to demonstrate how to remove the gap between the cells in the Blazor HeatMap.

In this project, we have set the [Width](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor.HeatMap.HeatMapCellBorder.html#Syncfusion_Blazor_HeatMap_HeatMapCellBorder_Width) property in the [HeatMapCellBorder](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor.HeatMap.HeatMapCellBorder.html) tag to "_0_".  In some cases, even setting the `Width` value to zero might not entirely remove the gap between cells. However, applying the `shape-rendering` CSS style to **crispEdges** directly to the SVG element helps in eliminating the gap.
