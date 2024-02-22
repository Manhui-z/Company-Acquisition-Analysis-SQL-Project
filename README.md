# Company-Acquisition-Analysis-SQL-Project
The company is considering to acquire a small paper company, Parch and Posey. Run an Exploratory data analysis (EDA) to help educate the leadership team before they make their final decision.

## Here are some questions considering in EDA process to help make decision:
1. How big is the customer base of Parch and Posey (how many customers/ accounts does the company have?)
2. How many areas do they sell at?
3. Look into the revenue streams:
   
   a. How many types of paper do they sell and what percentage each one of them makes out of the          total quantity sold?
   
   b. What percentage of revenues comes from which type of paper?

4. Is the business growing?

   a. How have revenues been year over year? For this, only take into account years with full data (2017 just started, so we don’t know how yearly revenues will be and 2013 seems to have data only from December). 

   b. How have units sold evolved year over year? Here too, only take into account the past years’ data.

5. How many sales representatives do they have in each region?
6. a. From Parch and Posey’s leadership team you know that North, South and International are 3          newly added regions. If Dunder Mifflin decided to buy Parch and Posey, they would need to          jump start sales in those areas. How to reallocating sales reps from the old regions to the        new regions to cover the needs of the latter. To answer this question, we only including           data from the last year (year 2016):
      - the total number of orders per region name
      - the number of reps per region name
      - the number of accounts per region name
      - the total revenues per region name
      - the average revenues per region name

   b. Based on the previous result, compute also by region:
      - average number of orders per representative (across all representatives)
      - average number of accounts handled per representative (across all representatives)
      - average revenues per representative (across all representatives)
  
   c. Based on your calculations above, how would you recommend reallocating sales_reps to cover         the new regions?
   
7. It seems that accounts with the word ‘group’ at the end of their name are likely to bring in more revenues, since they may represent a group of multiple businesses. This would be useful to know, in order to try to understand if these accounts should be given more attention after a possible acquisition by Dunder Mifflin. To answer if this is true, create a new column in your output that is:
    - ‘group’ if the name of the account ends with the word ‘group’
    - ‘not group’ otherwise

   Then, based on the above result, compute the average (per account) revenues that came       respectively from ‘group’ and from ‘not group’ accounts. Finally, comment on the result and on     whether this assumption was correct.

8. The Marketing team needs to focus on channels for the newly added sales regions, and because of its limited resources, it will have to deprioritize/deactivate temporarily some channels in the old areas. Specifically it decided to deactivate, for every old region, the channel that is used the least for web events in that region. Which channels should they deactivate in each region?
