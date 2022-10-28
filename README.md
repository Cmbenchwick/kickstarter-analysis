# Kickstarting with Excel

## Overview of Project

### Purpose
    The overall purpose of this "Kickstarter Analysis" is the help Louise make the best decision with her kickstarter campaign based on launch date and outcomes goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

- Created Pivot Table from Kickstarter data set, then filtered Pivot Table based on "Parent Category, (Theater)" and "Years" 
- Created link chart from the pivot table to visualize the relationship between outcomes and launch month
/Users/carissabenchwick/Desktop/OSU Bootcamp Projects/Analysis Projects/CrowdFunding Analysis/Pictures/Outcomes_vs_Goals.png
### Analysis of Outcomes Based on Goals
- Created a new sheet to count outcomes of the Kickstarter dataset after filtering subcategory to "plays" and organized the new sheet by goal range (>=1000 - 50000).
- Used CountIfs formula to calculate each range by success, failure, or canceled. Forexample=COUNTIFs(Range"<Goal",Range,"Outcome",Range,"Subcategory"). 
- Then, used the =sum() to find a total count of "Successful, Failed, and Canceled total projects" for each goal range.
- Next, calculated the percentages of Succees, Failed, and Canceled projects by (=number of "successful or failed or canceled"/total projects). Lastly, changed data to percentage. 
- Lastly, created a line chart to visualize the outcomes based on goal amount.
/Users/carissabenchwick/Desktop/OSU Bootcamp Projects/Analysis Projects/CrowdFunding Analysis/Pictures/Theater_Outcomes_vs_Launch.png
### Challenges and Difficulties Encountered:
- I had two issues: first, I tried to drag the formulas without locking them in with a $ and recieved a bunch of zeros. Lastly, I had an issue with the final countifs with the canceled column, but realized it wasn't an issue afterall.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    - Successful campaigns are launched in May or June.
    - Failed campaigns are launched in May, July, and October. 

- What can you conclude about the Outcomes based on Goals?
    - Successful campagins have goals less than 5,000 and between 35,000/45,000
    - Failed campaigns have goals between 20,000/35,000 and over 45,000 (most failures)

- What are some limitations of this dataset?
    - Other factors that could influnce the data for launch dates, including both success and failures. For instance, why is the month of May both the best and the worst? I think there is something else to be said about that data that is not includeded and/or studied. 
    
- What are some other possible tables and/or graphs that we could create?
    - Probably combining the last two data sets we worked with to show the correlation between time launched and goals. 
