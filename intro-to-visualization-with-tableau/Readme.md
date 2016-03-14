### Intro to Visualization with Tableau - links and files

** You have access to a Tableau Public workbook that you can use to continue exploring the Coffee Company data, experience more Tableau techniques and follow a series of Tableau worksheets to discover more insights
Link: [Coffee Company Sales Viz3](https://public.tableau.com/profile/moving.electron#!/vizhome/CoffeeCompanySalesViz3/Totalsales)

The Coffee Company Sales Viz3 Tableau workbook contains eight tabs:

worksheet name | insight | Tableau techniques
--- | --- |  --- 
**Total Sales** |main summary view of this KPI as requested by our Sales Manager | line chart, date filter with quick filter user control, trend line
**Caffiene vs non-caffiene** | sales "sliced" into caffiene and non-caffienne products | using the color card to slice the data into separate lines
**Sales Dashboard** | dashboard combining the two sales line charts into one tab. This dashboard report tab delivers that "our Sales Manager" Requested | Combines two worksheets into a dashboard, sets the filter control (Quick filter) to affect all workbooks using that data source, Adds a textbox for the title, adds info on who to contact at the bottom, adjusts spacing of filter by inserting a blank type object into the dashboard.
**Sales and Profit by quarter** | provides an initial comparison of sales and profit over two years | Used the Show Me capability to create an intial clustered column chart.  When you download the file and open it with the Tableau app on you laptop you will see Show Me in the upper left hand corner of the visualization edition screen.  Note that this is done by putting the dimension "Measure Names" on the Column shelf and the measure "Measure Values" on the row shelf. Then the "Measure Values" are filtered to display only the Sales and Profit dimensions. In this worksheet I also changed the date grouping to display by Quarter. Try changing the order of profit and sales by clicking and dragging the color in the color legend to change the order.
**Sales by market and quarter** | Slices the data into the Markets so we can take a compare performace by market | Adds the market dimension to the column shelf to do the additional slicing of the data 
**Sales by product** | Provides a look at sales by product in order to look for any anomolies | On the Marks card the chart type is set to "bar" otherwise nearly identical to what we did to create a line chart
**Profit by product** | Whoa! Green tea is barely profitable!  We are excellent data analytics people so we need to look into this insight further! | Identical to the Sales by product chart except that the Sales field is replaced by the Profit measure
**Profit and loss by Market and Market Size | The profit issue is in predominantly in the West market although there are appear to be some issue in Central.  The issue is in Small markets within those Markets.  We will alert the Sales Manager to this issue and move this workboot into a Dashboard so we can share a final version with them.  |  Market and Market Size are both added to the column shelf.  Product is added to the Filter card and the filter set to allow just Green Tea.  A "Profit indicator" Calculated field was is created and used to slice the data into loss and profit bars that show loss if the **sum** of the Profit is a profit or a loss.  Not that the formula in the Calculated Field uses a SUM in several places.  This is very typical of a Calculated field since most often you want to use the aggegate results.  However there are times where you will not sum in the logic.  Try to remove the SUMs from the calculated field and you will see the chart change into a bar chart where each bar is broken down into a color coding of profit and loss

** Data files provided for the class **

Right click on the file links below and save them to your laptop.  Keep track of the location of the downloaded location on your laptop. We will be referring to these files in class.

* [The Coffee company data Excel file](https://github.com/JamesByers/Workshop-files/raw/master/intro-to-visualization-with-tableau/Coffee%20Chain.xlsx)
  * You ***do not*** need to have Excel on your laptop to download this file.  Tableau will be able to access the data even without Excel being loaded on your laptop.
* [US airline on-time performance data](https://raw.githubusercontent.com/JamesByers/Workshop-files/master/intro-to-visualization-with-tableau/284334620_T_ONTIME.csv)
  * Note that this is a 45Mb file that is likely too big to open with Excel on your laptop.  It can be opened in Tableau however without issue.  The file can also be examined with a text editor such as Notepad (Windows) or TextEdit (Mac).


** Additional resources **
* The Visual Display of Quantitative Information – Edward Tufte
 * Arguably the most influential book ever on visualization.  Available Seattle Public Library
* Information Dashboard Design – Stephen Few
* How to Lie With Statistics - Darrell Huff
 * Excellent read and only $7.  Helps you see how **not** to inadvertantly mislead.  [Amazon link](http://www.amazon.com/How-Lie-Statistics-Darrell-Huff/dp/0393310728)
*Tableau On-Demand video training link: [](http://www.tableausoftware.com/learn/training)
*Tableau your data (book) – Dan Murray  [Be sure to get the new Second edition!)
 [Amazon link](*http://www.amazon.com/Tableau-Your-Data-Analysis-Software/dp/1119001196/)


