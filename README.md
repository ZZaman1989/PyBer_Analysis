# PyBer_Analysis

## Overview of Project
Isualize has given you and Omar a brand-new assignment. Using your Python skills and knowledge of Pandas, you’ll create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, you’ll create a multiple-line graph that shows the total weekly fares for each city type. Finally, you’ll submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

## Resources and Before Start Notes:

* Data Source: `PyBer_Challenge_starter_code.ipynb` named later as `PyBer_Challenge.ipynb`
* Data File: file.csv
* Software: Jupyter Notebook 6.1, Pandas, Python 3.9, Visual Studio Code 1.69.0, Anaconda 4.13, matplotlib

## Deliverable 1:  A Ride-Sharing Summary DataFrame by City Type
### Deliverable Requirements:

1. The total number of rides for each city type is retrieved. 
2. The total number of drivers for each city type is retrieved.
3. The sum of the fares for each city type is retrieved.
4. The average fare per ride for each city type is calculated.  
5. The average fare per driver for each city type is calculated. 
6. A PyBer summary DataFrame is created.
7. The PyBer summary DataFrame is formatted as shown in the example.
 
### Results with detail analysis:

**1. The total number of rides for each city type is retrieved.**

**Code and Image**

![name-of-you-image](https://github.com/ZZaman1989/PyBer_Analysis/blob/main/Resources/Deliverable%20%231%20-%20The%20total%20number%20of%20rides%20for%20each%20city%20type%20is%20retrieved.jpg)

**2. The total number of drivers for each city type is retrieved.**

**Code and Image**

![name-of-you-image](hhttps://github.com/ZZaman1989/PyBer_Analysis/blob/main/Resources/Deliverable%20%231%20-%20The%20total%20number%20of%20drivers%20for%20each%20city%20type%20is%20retrieved.jpg)

**3. The sum of the fares for each city type is retrieved.**

**Code and Image**

![name-of-you-image](https://github.com/ZZaman1989/PyBer_Analysis/blob/main/Resources/Deliverable%20%231%20-%20The%20sum%20of%20the%20fares%20for%20each%20city%20type%20is%20retrieved.jpg)

**4. The average fare per ride for each city type is calculated.**

**Code and Image**

![name-of-you-image](https://github.com/ZZaman1989/PyBer_Analysis/blob/main/Resources/Deliverable%20%231%20-%20The%20average%20fare%20per%20ride%20for%20each%20city%20type%20is%20calculated.jpg)

**5. The average fare per driver for each city type is calculated.**

**Code and Image**

![name-of-you-image](https://github.com/ZZaman1989/PyBer_Analysis/blob/main/Resources/Deliverable%20%231%20-%20The%20average%20fare%20per%20driver%20for%20each%20city%20type%20is%20calculated.jpg)

**6. A PyBer summary DataFrame is created.**

**Code and Image**

![name-of-you-image](https://github.com/ZZaman1989/PyBer_Analysis/blob/main/Resources/Deliverable%20%231%20-%20A%20PyBer%20summary%20DataFrame%20is%20created.jpg)

**7. The PyBer summary DataFrame is formatted as shown in the example.**

**Code and Image**

![name-of-you-image](https://github.com/ZZaman1989/PyBer_Analysis/blob/main/Resources/Deliverable%20%231%20-%20The%20PyBer%20summary%20DataFrame%20is%20formatted%20as%20shown%20in%20the%20example.jpg)

### Deliverable 2: A multiple-line chart of total fares for each city type
### Deliverable Requirements:

1. A DataFrame was created using the `groupby()` function on the "type" and "date" columns, and the `sum()` method is applied on the "fare" column to show the total fare amount for each date and time.
2. A DataFrame was created using the `pivot()` function where the index is the "date," the columns are the city "type," and the values are the "fare."
3. A DataFrame was created using the `loc` method on the date range: 2019-01-01 through 2019-04-29.
4. A DataFrame was created using the `resample()` function in weekly bins and shows the sum of the fares for each week.
5. An annotated chart showing the total fares by city type is created and saved to the "analysis" folder. 

### Results with detail analysis:

**1. A DataFrame was created using the `groupby()` function on the "type" and "date" columns, and the `sum()` method is applied on the "fare" column to show the total fare amount for each date and time.**

**Code and Image**

![name-of-you-image](https://github.com/ZZaman1989/PyBer_Analysis/blob/main/Resources/Deliverable%20%232%20-%20A%20DataFrame%20was%20created%20using%20the%20groupby()%20function.jpg)

**2. A DataFrame was created using the `pivot()` function where the index is the "date," the columns are the city "type," and the values are the "fare."**

**Code and Image**

![name-of-you-image](https://github.com/ZZaman1989/PyBer_Analysis/blob/main/Resources/Deliverable%20%232%20-%20A%20DataFrame%20was%20created%20using%20the%20pivot()%20function%20.jpg)

**3. A DataFrame was created using the `loc` method on the date range: 2019-01-01 through 2019-04-29.**

**Code and Image**

![name-of-you-image](https://github.com/ZZaman1989/PyBer_Analysis/blob/main/Resources/Deliverable%20%232%20-%20A%20DataFrame%20was%20created%20using%20the%20loc%20method.jpg)

**4. A DataFrame was created using the `resample()` function in weekly bins and shows the sum of the fares for each week.**

**Code and Image**

![name-of-you-image](https://github.com/ZZaman1989/PyBer_Analysis/blob/main/Resources/Deliverable%20%232%20-%20A%20DataFrame%20was%20created%20using%20the%20resample()%20function.jpg)

**5. An annotated chart showing the total fares by city type is created and saved to the "analysis" folder.**

**Code and Image**

![name-of-you-image](https://github.com/ZZaman1989/PyBer_Analysis/blob/main/Resources/Deliverable%20%232%20-%20An%20annotated%20chart%20showing%20the%20total%20fares%20by%20city%20type%20is%20created%20and%20saved%20to%20the%20analysis%20folder.jpg)

## Deliverable 3: A written report for the PyBer Analysis
### The analysis should contain the following:

1. **Overview of the analysis** 
* Explain the purpose of the new analysis:

    > Isualize has given you and Omar a brand-new assignment. Using your Python skills and knowledge of Pandas, you’ll create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, you’ll create a multiple-line graph that shows the total weekly fares for each city type. Finally, you’ll submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.


2. **Results** 
* Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types:

    > * The Suburban fares started around $700, fares dropped in March.  
    > * The Rural fares started at around $200, fares increased April.  
    > * The Urban fares start with around $1,700 with an increase to roughly 2,400. 
    
    > The PyBer summary DataFrame, 
    ![name-of-you-image](https://github.com/ZZaman1989/PyBer_Analysis/blob/main/Resources/Deliverable%20%231%20-%20The%20PyBer%20summary%20DataFrame%20is%20formatted%20as%20shown%20in%20the%20example.jpg)

     > A multiple-line chart of total fares for each city type,
    ![name-of-you-image](https://github.com/ZZaman1989/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.png)

       

3. **Summary** 
* Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types:

    > **1)** Expand the business in rural and suburban cities.
   
    > **2)** The Urban cities fare is the highest and consistent, try to get more drivers.  

    > **3)** Think about discounting fares for rural to help expand.

