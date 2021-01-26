# US-Bikeshare-Dataset---Python

### Overview:
In this project, Python is used to explore data related to bike share systems for three major cities in the United States — Chicago, New York City, and Washington.
-	The source code takes in raw input from the user to create an interactive experience.
-	According to the input the code will import the data and will provide information by computing descriptive statistics.

### Files used:
-	chicago.csv
-	new_york_city.csv
-	washington.csv

### Libraries Used:
The libraries used in the project include time, pandas, NumPy, and DateTime.

### Software’s used:
-	Python 3, NumPy, and Pandas installed using Anaconda
-	A text editor - Atom.

### Project Code Detail:

#### How the program works:
The code developed takes in raw input to create an interactive experience in the terminal that answers questions about the dataset. The experience is interactive because depending on a user's input, the answers to the questions will change! There are four questions that will change the answers:
-	Would you like to see data for Chicago, New York, or Washington?
-	Would you like to filter the data by month, day, or not at all?
-	(If they chose month) Which month - January, February, March, April, May, or June?
-	(If they chose day) Which day - Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, or Sunday?
The answers to the questions above will determine the city and timeframe on which you'll do data analysis. After filtering the dataset, users will see the statistical result of the data, and choose to start again or exit.

#### The Datasets:
Randomly selected data for the first six months of 2017 are provided for all three cities. All three of the data files contain the same core six (6) columns:
-	Start Time (e.g., 2017-01-01 00:07:57)
-	End Time (e.g., 2017-01-01 00:20:53)
-	Trip Duration (in seconds - e.g., 776)
-	Start Station (e.g., Broadway & Barry Ave)
-	End Station (e.g., Sedgwick St & North Ave)
-	User Type (Subscriber or Customer)
The Chicago and New York City files also have the following two columns:
-	Gender
-	Birth Year

#### Statistics Computed:
The code helps users to tell about bike share use in Chicago, New York City, and Washington by computing a variety of descriptive statistics. In this project, the code output will provide the following information:
-	Popular times of travel (i.e., occurs most often in the start time):
o	most common month
o	most common day of week
o	most common hour of the day
o	Popular stations and trip:
•	most common start station
•	most common end station
o	most common trip from start to end (i.e., most frequent combination of start station and end station)

-	Trip duration:
o	total travel time
o	average travel time

-	User info:
o	counts of each user type
o	counts of each gender (only available for NYC and Chicago)
o	earliest, most recent, most common year of birth (only available for NYC and Chicago)
