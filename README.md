# JMAAA-Assignment

The Pdfs contained Insurance Policy Documents collected randomly. My Task was to extract key components such as policy number, premium amount etc from the Pdfs and then convert it into csv/excel sheet. So the data can be maintained in other format and also visualization can be done.

What are the files about?
------------------

Firstly I worked in a Jupyter Notebook and worked on how to extract the data from the pdf files.

Link to the file:- [Making CSV.ipynb](https://github.com/sameertak/JMAAA-Assignment/blob/master/Making%20CSV.ipynb) 

The File mainly has a function defined extracts data from the pdf using [tabula](https://pypi.org/project/tabula-py/) library.

After Extracting, I've saved the pdf files as individual csv datasets namely:-

   1. [one](https://github.com/sameertak/JMAAA-Assignment/blob/master/one.csv)
   
   2. [two](https://github.com/sameertak/JMAAA-Assignment/blob/master/two.csv)
   
   3. [three](https://github.com/sameertak/JMAAA-Assignment/blob/master/three.csv)
   
   4. [four](https://github.com/sameertak/JMAAA-Assignment/blob/master/four.csv)
   
   5. [five](https://github.com/sameertak/JMAAA-Assignment/blob/master/five.csv)

Then I called the files and concat them to make a full csv file.I applied Transformation techniques, Cleared irrelevant columns, Filled missing values.(Such as removing the unnecesary columns, re-arranging the columns, filling values (by addition or substraction of two/more columns)).Also splitted the dates so that it will be easy to visualize in dataset.


Then I worked on the [Visualization Part](https://github.com/sameertak/JMAAA-Assignment/blob/master/Visualizing%20Datas.ipynb)
Here I imported basic visualization tools such as matplotlib, seaborn.
Plotted required graphs and charts.

Then finally I worked on the csv file [Final Csv](https://github.com/sameertak/JMAAA-Assignment/blob/master/Final.csv). Here I harmonized tha data and saved as an excel sheet named [Harmonized Sheet](https://github.com/sameertak/JMAAA-Assignment/blob/master/Harmonized_Sheet.xlsx)

The sheet contains 2 sub sheet. First one contains the dataset. Another contains some graphs.

In the First Sheet, I've added a Conditional Column, which would make easier to visualize whoose Insurance is at deadline.
And also applied some relevant colors to make data more visually appealing.

I enjoyed the difficulties faced during the codes. Looking forward to make the code more efficient so that the pdf to csv journey can be completed faster.
