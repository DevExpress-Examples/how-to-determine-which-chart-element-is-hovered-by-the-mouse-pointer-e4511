<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/DetermineHoveredChartElement/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/DetermineHoveredChartElement/MainWindow.xaml))
* [MainWindow.xaml.cs](./CS/DetermineHoveredChartElement/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/DetermineHoveredChartElement/MainWindow.xaml.vb))
<!-- default file list end -->
# How to determine which chart element is hovered by the mouse pointer


<p>This example demonstrates how to calculate the hit information for the chart element over which the mouse pointer is hovering. </p><p>To accomplish this, handle the <strong>ChartControl.MouseMove</strong> event, obtain the current chart element via the <a href="http://help.devexpress.com/#WPF/DevExpressXpfChartsChartControl_CalcHitInfotopic"><u>ChartControl.CalcHitInfo</u></a> method, and if the element is not <strong>null</strong> (<strong>Nothing </strong>in Visual Basic), display its information.</p><p><br />
</p>

<br/>


