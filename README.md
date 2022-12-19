### Hi there 👋

<p>I'm Steve. My current activity:</p> 

# [Run Log](https://github.com/sbogucki12/workoutdata)

## December 19, 2022: 

* The UI now fetches data from the cloud database via (development) Web API 
![ui-fetch-gif.gif](https://raw.githubusercontent.com/sbogucki12/workoutdata/main/images/ui-fetch-gif.gif "ui-fetch-gif.gif")

## December 12, 2022: 

* Sidetracked. 
  * Which day of the week do I typically run the farthest? 
  * How have my distances changed over time?  
![runDistances](https://raw.githubusercontent.com/sbogucki12/workoutdata/main/images/runDistances.jpg "runDistances.jpg")
*[notebook](https://github.com/sbogucki12/workoutdata/blob/main/.ipynb_checkpoints/run-analysis-checkpoint.ipynb)*


## workoutdata

### Objective

I want to rebuild [www.dailyrun.net](https://www.dailyrun.net/). 

#### Problem

The data in my runlog, as seen via the UI, isn't what it appears to be...

![runlogUI-original.jpg](https://raw.githubusercontent.com/sbogucki12/workoutdata/main/images/runlogUI-original.jpg "runlogUI-original.jpg")
![runlogUI-original-detail.jpg](https://raw.githubusercontent.com/sbogucki12/workoutdata/main/images/runlogUI-original-detail.jpg "runlogUI-original-detail.jpg")

In laziness, when initially developing my runlog two years ago, I wasn't precise with my data types.  For example, to avoid unnecessary mental exercise at the time, I occasionally used strings instead of numerical or date time data.  

![data-problem-pace.jpg](https://raw.githubusercontent.com/sbogucki12/workoutdata/main/images/data-problem-pace.jpg "data-problem-pace.jpg")

1. First things first, I want to convert those data into their appropriate types to allow me to perform some data analysis. (DONE)

2. Later, I'll build a new database aligned with those data types and use the transformed data to seed the database. (DONE) 

3. Next, I'll migrate the local database to Azure. (DONE) 

4. After that, I'll build out a backend - just some controllers, basically, via .NET probably. (DONE)

5. Finally, I'll build a UI. 


[Cont...](https://github.com/sbogucki12/workoutdata)
  
