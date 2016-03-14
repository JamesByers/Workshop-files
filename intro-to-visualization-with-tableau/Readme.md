### Intro to Visualization with Tableau - links and files

### Link to a Tableau Public workbook that you can use to continue exploring the Coffee Company data, experience more Tableau techniques and follow a series of Tableau worksheets to discover more insights

Link: [Coffee Company Sales Viz3](https://public.tableau.com/profile/moving.electron#!/vizhome/CoffeeCompanySalesViz3/Totalsales)

This Tableau workbook contains eight tabs:

worksheet name | insight | Tableau techniques
--- | --- |  --- 
**Total Sales** |main summary view of this KPI as requested by our Sales Manager | line chart, date filter with quick filter user control, trend line
**Caffiene vs non-caffiene** | sales "sliced" into caffiene and non-caffienne products | using the color card to slice the data into separate lines
**Sales Dashboard** | dashboard combining the two sales line charts into one tab. This dashboard report tab delivers that "our Sales Manager" Requested | Combines two worksheets into a dashboard, sets the filter control (Quick filter) to affect all workbooks using that data source, Adds a textbox for the title, adds info on who to contact at the bottom, adjusts spacing of filter by inserting a blank type object into the dashboard.
**Sales and Profit by quarter** | provides an initial comparison of sales and profit over two years | Used the Show Me capability to create an intial clustered column chart.  When you download the file and open it with the Tableau app on you laptop you will see Show Me in the upper left hand corner of the visualization edition screen.  Note that this is done by putting the dimension "Measure Names" on the Column shelf and the measure "Measure Values" on the row shelf. Then the "Measure Values" are filtered to display only the Sales and Profit dimensions. In this worksheet I also changed the date grouping to display by Quarter. Try changing the order of profit and sales by clicking and dragging the color in the color legend to change the order.
**Sales by market and quarter** | Slices the data into the Markets so we can take a compare performace by market | Adds the market dimension to the column shelf to do the additional slicing of the data 




**Research Design and Exploratory data analysis**|
3/15: [L01 Introduction to Data Science](#class-1) | 3/17: [L02 Research design and Pandas](#research-design)
3/22: L03 Statistics fundamentals (with Pandas) | 3/24: [L04 Command Line and Version Control](#command-line) **Project Discussion Deadline**
3/29: [L05 Fetching Data](#fetching-data) **Project Discussion Deadline** |
**Foundations of data modeling**|
 | 3/31: [L06 Intro to Regression](#intro-to-regression) **Project Question and Dataset Due**
4/5: L07 Evaluating Model Fit | 4/7: [L08 Intro to Classification - K nearest neighbor](#knn)
4/12: [L09 Classifying with Logistic Regression](#logistic-regression) | 4/14: [L10 Advanced model evaluation](#advanced_model)
4/19: [L11 Regularization and Clustering](#class-11-regularization-and-clustering)| 4/21: L12: **First Project Presentations** + bonus topics
**Data science in the real world**|
4/26: [L13 Natural Language Processing](#nlp) | 4/28: L14 Dimensionality reduction, **Draft Paper Due**
5/3: [L15 Decision Trees](#decision) | 5/5: [L16 Ensembling, Bagging and Random Forests](#ensemble)
5/10: L17 Modelin

#### Workshop data files

Right click on the file links below and save them to your laptop.  Keep track of the location of the downloaded location on your laptop. We will be referring to these files in class.

* [The Coffee company data Excel file](https://github.com/JamesByers/Workshop-files/raw/master/intro-to-visualization-with-tableau/Coffee%20Chain.xlsx)
  * You ***do not*** need to have Excel on your laptop to download this file.  Tableau will be able to access the data even without Excel being loaded on your laptop.
* [US airline on-time performance data](https://raw.githubusercontent.com/JamesByers/Workshop-files/master/intro-to-visualization-with-tableau/284334620_T_ONTIME.csv)
  * Note that this is a 45Mb file that is too big to open with Excel.  It can be opened in Tableau however without issue.  The file can be examined with a text editor such as Notepad (Windows) or TextEdit (Mac).
