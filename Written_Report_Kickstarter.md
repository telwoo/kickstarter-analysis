# Kickstarting with Excel

## Overview of Project
Louise had a play called *Fever* that did well in meeting fundraising goals in a short period of time. In reviewing this revenue generation, Louise decided to investigate how theater outcomes correlated with their fundraising goals. We will be reviewing how kickstarters, a new and upcoming business that is viewed as a platform for new ideas, demonstrates different outcomes and how those outcomes meet fundraising goals. This is what I used as a base for kickstarter definition using [Kickstarter 101]([https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#links](https://help.kickstarter.com/hc/en-us/articles/115004996453-What-is-Kickstarter-#:~:text=Kickstarter%20is%20full%20of%20ambitious,will%20be%20produced%20by%20it.).   

### Purpose
Within this project, we are analyzing the data to outline what the results of the campaign outcomes were, based on their fundraising goals and launch dates. This project is restricted to Parent Category, theater; the theater's outcomes; and those overall outcomes' fundraising goals. The outcome details are listed as: canceled, failed, and successful. *Live* outcomes was not utilized within he scope of this project. 


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The outcomes that were used in this graph were: canceled, failed, and successful. The grand total of overall counts within the theater were 1,369 showings. Out of the 1,369 showings in the theater, 37 shows were canceled; 493 shows failed; and 839 shows were successful. The year was not specified, so these figures are the raw counts. The month that had the largest grand total of shows (regardless of canceled, failed or successful) was May with 166 showings. The month that had the least grand total of shows (regardless of canceled, failed or successful) was December with 75 showings. The month that had the largest amount of cancelations was January with 7. The month that had the least amount of cancelations was October with 0. The month that had the largest amount of failed showings was May with 52. The month that had the least amount of failed showings was November with 31. The month that had the largest amount of successful showings was May with 111. The month that had the least amount of successful showings was December with 37. See graph below for details on analysis:
![This is an image] (/Users/Chauntel/Desktop/MSU Bootcamp/Week 1/Challenges/Resources/Outcomes_vs_Goals.png)


### Analysis of Outcomes Based on Goals
The outcomes that were used in this graph were: canceled, failed, and successful. The "Kickstarter" worksheet was utilized, which meant the overall showings, totaling 4,064 shows, was outlined for this data analysis. The overall number of successful showings was 2,185. The overall number of failed showings was 1,530. The overall number of canceled showings was 349. Within the number of successful showings, there were more projects that met a financial goal of less than $1,000, totaling 322 showings (or 71% of overall projects within that financial goal range). Within the number of failed showings, there were more projects that met a financial goal of more than $1,000 but less than $4,999, totaling 420 showings (or 66% of overall projects within that financial goal range). Within the number of canceled showings, there were more projects that met a financial goal of $50,000 or more, totaling 100 showings (or 19% of overall projects within that financial goal range). See graph below for details on analysis:
![This is an image] (/Users/Chauntel/Desktop/MSU Bootcamp/Week 1/Challenges/Resources/Theater_outcomes_vs_Launch.png)


### Challenges and Difficulties Encountered
There were two main topics that were reviewed in order to process the data: outcomes based on launch date and outcomes based on fundraising goals. In compiling graphs and pivot tables, I encountered two main challenges. One of the challenges that I encountered while creating the "Outcomes by Launch Date" graph was that the count for overall outcomes did not add up. I realized that this was due to an additional outcome category being included in my calculation; the additional category was 'Live.' The 'Live' category had an additional 50 counts that were not outlined in the data that Louise needed. I was able to determine the difference by taking the grand total of the count of the outcomes within the "Outcomes by Launch Date" worksheet pivot table and subtract it by the summed total of outcomes within the 'Outcomes' column within the "Kickstarter" worksheet. After subtracting, I got the exact number of 50, which I saw had a commonality of the 'Live' outcome. Once I determined that, I was able to readjust the table to display the correct outcomes by date. The other challenge was within the "Outcomes Based on Goals" worksheet, with the COUNTIFS formulas. COUNTIFS formulas was a new concept for me that I never had the opportunity to use, and with that, I found it difficult to outline the greater than, less than, and between features that the report looked for. After writing and deleting the formula multiple times, I realized that I didn't lock the cell to grab the correct data within the ''Kickstarter'' worksheet. After I locked the column, I was able to get the results I needed. 


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  1. If Louise wanted to generate the most sells in the future, to have the best outcomes, hold theater shows in the spring and summer months, May, June, and July. And make sure to stay away from large shows in December, as these show to be the least successful timing.
  
  2. Overall, January will have the most canceled shows and second least amount of successful shows, so if Louise could put his main focus in the summer months, the theater will do well. There are a large number of failed shows in those summer months as well, but hopefully those successful show's revenues will outweigh the failures. 

- What can you conclude about the Outcomes based on Goals?
  1. The number of successful  projects that had goals within the $1,000 to $4,999 had the most amount of successful projects, with a total of 932. Therefore, projects should aim for this goal to be sustainable. In contrast, the number of failed projects that had goals within the $1,000 to $4,999 had the most amount of failed projects, with a total of 420.
  2. Overall, there was a very small amount of canceled project in the number of kickstarters, not outlining the specific year, totaling 349. Thankfully, not too many projects are canceling themselves out and losing out on all that revenue. 

- What are some limitations of this dataset?
  There could be a limitation in the reliability of this data. It's unsure of whether this data that was outline showed the most accurate set of details. I'm not sure if overall, across numerous years, that only 4,064 shows were reviewed worldwide. I'd believe there should be more taking place; therefore the sample size could be an additional limitation.

- What are some other possible tables and/or graphs that we could create?
  1. Graph on amount of shows in a specific country within a specific timeframe
  2. Graph that shows only the amount of successful shows, in a specific year, that had a goal greater than $20,000 (could create different variations of this same scenario, but with canceled or failed showings). 
