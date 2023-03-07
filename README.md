# Final-Project-Tableau

## Project Goals

Understanding and analyzing the causes of Death all around the world by visualization

## Process
### - Data Collection
I decided to go with option 2 and data set number 5 about death causes all around the world
### - Cleaning and QA
As I was analyzing data, I realized that despite having a clean file from kaggle I had to do more data cleaning. I have explained more in Challenges
### - Questions I answered:
- How is the death trend over the years?
- Comparing countries in death statistics
- Top 10 Death Causes in all countries
- What are the death causes in Canada and what is the trend in each cause?
- Execution statistics in top 20 countries

### - Visulizing and analyzing
I used Tableau to visualize data

## Results
(Fill in which Option you chose, either 1 or 2. List the dataset you selected for the project if you selected Option 2. Also, discuss the visualizations you created, and why. For Option 2, also identify what your data question was, and how you went through the prompts.)

## Challenges 
The biggest challenge was realizing that the clean data file I had downloaded from Kaggle was not accurate! While trying to create a horizontal bar chart showing the countries that had the most execution over time, I noticed that China's number was way lower than what I had inspected in the raw csv. Over the years, according to the raw file, China's execution number was denoted by **">1000"**. By digging more into it, I realized that in the cleaning process, this number had been converted to Null, impacting all the statistics and charts. As a result, instead of being kept as null and resulting in 0 in Tableau, I put **"1000"** for those values!


## Future Goals
If I had more time, I would have looked for more up to dated data, especially the data for Covid 19 statistics. It must be very engaging to know what happened during the pandemic!

Furthermore, I would get more detailed data about the death causes in different age groups and genders.

Last but not least, I would dig more into the data to categorize them into main categories such as:

- Different diseases such as heart-related illnesses or cancer!
- Natural Disasters
- Terrorism
- Suicide and hemocide



