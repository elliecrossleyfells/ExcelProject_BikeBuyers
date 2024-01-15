This dataset consists of 1027 rows and shows the details of individuals with different characteristics  and whether or not they choose to buy a bike when visiting a bike shop.
The task is to analyse which characteristics suggest someone is most likely to purchase a bike when visiting the shop.

This tab details an overview of tasks undertaken in this project, and is for anyone wishing to review or replicate this project. 


The dataset: https://github.com/AlexTheAnalyst/Excel-Tutorial/blob/main/Excel%20Project%20Dataset.xlsx
Under a General Public License. 

In this project:
1. Data cleaning 
2. Analysis and evaluation of characteristics that effect bike purchase using pivot tables
3. Creation of a dashboard to visualise data.
4. Conclusions 
<br>
<b><u>1. Data cleaning </b></u><br>
Please see the Data Working Sheet yab for final, clean dataset.
- Created a new working sheet, so the raw data can be kept unchanged and can be referred back to if required.<br>
- Removed duplicate data rows (26 duplicates found)<br>
- Changed data terms, making the data easier to understand for dashboard and visualization purposes. <br>
- For the “Marital Status” and “Gender” columns, the letters S, M, M and F are used, when visualizing the data in the dashboard, this could appear confusing. Use Find & Replace (ctrl + H) > search by columns, find “M” and replace with “Married”.
<i>*In Excel 365 this does not work. It will replace all instances of the To Find value, and change all values in the entire the sheet. Firstly the format of the cell must be changed so that it is different to the rest of the worksheet (E.g: change the colour of the column.) This can be revertec back to its original state once the Find and Replace has been completed. *</i><br>
- Ensure columns are correctly formatted: columns containing currency is set currency, ect. (for purposes of this data analysis project, I have changed the currency to pounds to improve relvance, however this is NOT something to bedone  during a real-word analysis project, it could obviously have significant impact on the data. <br>
- Number of children, income, number of cars and age have been formatted to show NO decimal places, because all these values must be integers. 
- Spell check run (we can also check the individual filter tabs and ensure the unique values are spelled correctly) 
- Binning: Using a nested IF function for binning ages into the categories “young adult” (<31), “middle age” (31-59) and “older adult” (60>)
<br><br>
<b><u>2. Simple analysis and visualisation - Pivots tables and charts - Identifying and evaluating characteristics that could affect bike purchase. </b></u><br>
We can investigate some characteristics of buyers, and analyse them against number of bike purchases made. 
Please see the yellow Pivot Tables tab for tables and description of findings.
<br><br>
<b><u>3. Dashboard </b></u><br>
Please see the Dashboard tab.
- Removed gridlines for clearer display
- Use of slicers: Select a chart on the dashboard > Add slicer
This will only work on one chart, so go to slicer tab > report connections > select all pivot tables.
<br><br>
<b><u>4. Conclusions</b></u><br>
1. Higher income is associated with more bike purchases, with the exception of the Europe region, where the Females who did not buy  bike had slightly higher salary than those who bought a bike. 
2.  Commutes of 0-1 miles are, by far,associated with more bike purchases on average. However in the Pacific region, the most common commute distance where people purchase a bike is 5-10 miles.
3. Middle age adults buy more bikes out of all other ages across all regions. 
4. People with a Bachelor's education are the most likely to buy a bike across all regions. 
