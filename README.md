### Hi there 👋

<p>I'm Steve. My current activity:</p> 

# [Run Log](https://github.com/sbogucki12/workoutdata)

## workoutdata

### Objective

I want to rebuild [www.dailyrun.net](https://www.dailyrun.net/). 

#### Problem

The data in my runlog, as seen via the UI, isn't what it appears to be...

![runlogUI-original.jpg](https://raw.githubusercontent.com/sbogucki12/workoutdata/main/images/runlogUI-original.jpg "runlogUI-original.jpg")
![runlogUI-original-detail.jpg](https://raw.githubusercontent.com/sbogucki12/workoutdata/main/images/runlogUI-original-detail.jpg "runlogUI-original-detail.jpg")

In laziness, when initially developing my runlog two years ago, I wasn't precise with my data types.  For example, to avoid unnecessary mental exercise at the time, I occasionally used strings instead of numerical or date time data.  

![runlogUI-original.jpg](https://raw.githubusercontent.com/sbogucki12/workoutdata/main/images/data-problem-pace.jpg "data-problem-pace.jpg")

* First things first, I want to convert those data into their appropriate types to allow me to perform some data analysis. 

  * Complete: 

*Transformed data into usable data types*

![datatypes_transformed](https://raw.githubusercontent.com/sbogucki12/workoutdata/main/images/datatypes_transformed.jpg "datatypes_transformed.jpg")

*Created a local database and table via SQL Server Management Studio* 

![sql_table](https://raw.githubusercontent.com/sbogucki12/workoutdata/main/images/sql_table.jpg "sql_table.jpg")

* Later, I'll build a new database aligned with those data types and use the transformed data to seed the database.  

**Update:** *Nov 27, 2022:* 

  * Local database created and seeded with transformed data.   

![seeded_database](https://raw.githubusercontent.com/sbogucki12/workoutdata/main/images/seeded_database.jpg "seeded_database")

* Next, I'll migrate the local database to Azure. 
*
* Finally, I'll build a UI. 

### Background

When I originally developed my runlog, in my daily professional life, I was working more directly in the webdev space.  Since then, I have moved more into enterprise data management, and acquired an interest in data science, especially data engineering.  Through work, I'm enrolled and working through eCornell's 35 week Python and Machine Learning course.  

My runlog is dated, so it needs to be revised.  I want to take the opportunity in rebuilding it in a way that's educational for me, especially in support of my data science learning, and job responsibilities around enterprise data management at work.  

[Cont...](https://github.com/sbogucki12/workoutdata)
  
