# How to stop refreshing a chart


<p>When a chart is bound to a pivot, it may cause performance issues with some chart diagrams. There is a way to prevent a chart from updating, while the user is selecting cells in the pivot. <br />
1)  Use the PivotGrid and IList interfaces, which provide access to the current PivotGridControl's data. <br />
2)  Copy this data from this list to any IList data source and bind the ChartControl to it.<br />
3)  Execute these steps when you need to rebind the ChartControl to data.</p>

<br/>


