# PA-4
Python Version: 
For starters: import seaborn, pandas and matplot library for the following problems
```
import pandas as pd

import seaborn as sns

import matplotlib.pyplot as plt
```
# 1) Create the following data frames based on the format provided:
> Example: Vis = [“Name”, “Gender”, “Track”, “Math<70”]; hometown is constant as Visayas

> a) Filename: Instru = [“Name”, “GEAS”, “Electronics >70”]; where track is constant Instrumentation and hometown Luzon

> b) Filename: Mindy = [ “Name”, “Track”, “Electronics”, “Average >=55”]; where hometown is constant as Mindanao and gender Female

- In this problem, it is supposed to return only certain data in the data frame along with the given conditions
- I then tried using conditional statements using conditional operators such as `&` and `==` and `>` to set conditions and meet the required data
- For the second part of this problem, I used the same process as I did with the first part but this time I had a hard time trying to analyze how to get the average, but after experimenting on a few syntax, I finally learned that you can put a feature at the end of the line of code such as `.join()` , `.copy()` , and etc.
- Another thing is that I keep getting a warning message after running the "Mindy" filename which really bugged me since I don't know what the warning is all about and what's causing it. Then, after a little research, I found out that it was warning me that my code could have unintended consequences, which I resolved by using `.copy()` syntax.

# 2) Create a visualization that shows how the different features contributes to average grade. Does chosen track in college, gender, or hometown contributes to a higher average score?
- For this part of the problem, I had a hard time learning seaborn and matplotlib since this is all new to me, and there are a lot of syntax that I need to be wary of.
- I first then tried to figure out how to make a boxplot since I thought this was the most appropriate graph for the necessary data. I created a line of code that will compute the average grades.
- I then created a boxplot from the library of Seaborn then I manipulated the features to make it more presentable and readable

### Challenges
- Learning the conditional statements in data wrangling
- Learning matplotlib and seaborn graphs
- Manipulating the graphs

### Learnings
- Manage to get a grasp of data wrangling
- Learned a few on how to make a graph using matplotlib and seaborn
- I learned a few things on how to create and manipulate the graphs

#### Version History:
##### [v1.1.0] - 9/17/2024
##### [v1.2.0] - 9/21/2024
###### Changes:
- Improved the title of the graphs
- Updated the style of the graph
- Adjusted the font sizes
- Added labels to the x and y axis
