# How to customize chart titles


<p>With DXCharts you can fully customize the appearance and behavior of chart titles. For example, this sample illustrates how to display a group of check boxes, which control series visibility, in a chart titles area.<br />
See also:<br />
-  <a href="https://www.devexpress.com/Support/Center/p/E2409">How to display custom information in the legend</a>;<br />
- <a href="https://www.devexpress.com/Support/Center/p/E2842">How to display check boxes for legend items to control the visibility of series</a>.</p>


<h3>Description</h3>

<p>To accomplish this task, it is necessary to define a <strong>WrapPanel</strong> with a set of <strong>CheckBox</strong> elements and bind their check state to a <strong>Visible</strong> property of the corresponding series.</p><p>Then this <strong>WrapPanel</strong> can be placed as a chart title into a <strong>ChartControl.Titles</strong> collection.</p>

<br/>


