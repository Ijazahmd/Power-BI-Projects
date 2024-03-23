# Sales Analysis Report



## Problem Statement

This dashboard helps the Technoedge to  understand their sales better. It helps the Technoedge know if their sales are better with going years. Through different ratings, they get to know their improvement area, & thus they can improve their profit by identifying these area. It also lets them know the average profit and sales, thus since by using this dashboard they have identified this problem, they can further work on factors responsible for these loss on specific region.

Since, sum of sales in home office (18.7),corporate (30.74),consumer (50.56) improved their sales.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present except column named "Category".
- Step 5 : For calculating total profit, null values were not taken into account as only less than 1% values are null in this column(i.e column named "Category") 
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : Since the data contains various regions, thus in order to represent sales with respect to it. 
- Step 8 : Visual filters were added for four fields named "Subcataegory", "Regions", "State" & "Year".
- Step 9 : Four card visuals were added to the canvas, representing "Total sales","Total profit","Total discount","Total quantity"..
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
           
           Although, by default, while calculating average, blank values are ignored.
- Step 10 : A bar chart was also added to the report design area representing the Sub-category & Sum of sales. While creating this visual, field named "Sum of sales by sub-category".  
- Step 11 : Sub-category Visual was used to represent different categories mentioned below,

  (a) Phones

  (b) Chairs
  
  (c) Storage
  
  (d) Tables
  
  (e) Binders
  
  (f) Machines

  (g) Accessories
  
  (h) Copies
  
  (i) Book cases
  
  (j) Appliances
  
  (k) Furnishings
  
  (l) Paper
  
  (m) Supplies

  (n) Art  

  (o) Envelops

  (p) Labels

  (q) Fasteners
