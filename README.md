# The Redesign Project - How Internet usage has increased around the globe since 2000!
## Project Statement:
Why this topic?  For all of us, internet is a pervasive, fundamental part of daily life that continues to be a major driver of the way society accesses and views information, no matter where we are. The recent growth of the Internet and the World Wide Web makes it appear that the world is witnessing the arrival of a completely new technology. So, It would be interesting to know the facts about the evolution of internet around the globe from 2000 to 2015. 
The Data source is World Data Atlas through Knoema.com, which had data about percentage of Internet users as per the country and year.

Data source - https://knoema.com/ITUKGTI2015/international-telecommunication-union-key-global-telecom-indicators

Following is the visualization that is to be redesigned.

![Alt text](https://github.com/Tanushreechaudhary/Data_Visualization/blob/master/screenshots/Internet_Usage.png)


https://public.tableau.com/en-us/s/gallery/internet-coverage-across-globe?gallery=votd

The Author of this Visualization has created bar charts for each country which shows how for a country, Internet usage changed in the span of 15 years. He has given the filter option to highlight a country and check the statistics. However, the viz sums up the data for all the countries at one place but displaying it using this approach is a bit overwhelming. 
Though bar charts are never a bad option but here the main focus should have been on giving the audiences a clear idea that pops out of the visual at very moment of looking at it. 


So, to redesign it in a better way, I would take the raw data from the source mentioned and analyze the data to see which are the countries that have not evolved much since 2000. What is the difference in internet growth between Developed nad Developing countries?

The first Target Audience for my visualization is government because internet access or usage can be directly linked to the economic growth of a country. As we will see, developed countries have more percentage of Internet users. So, government of countries like India, Pakistan where this percentage is very low, can work on improving it. Also, another audience could be the internet Service Provider companies, which can target the countries  with low percentage of internet users, for their services and know the reasons and reform their services if needed.

---

## "Making of" the Project:
### Data Analysis:
I exported the visualization to be redesigned in Tableau and tried to analyze the data by changing the visuals. This gave me an understanding about what all arguments I can make with this data. What part of the world showed major growth in internet usage in all these years. So, I developed the following two visualizations.

First visualization shows the Average number of increasing internet users per 100 people per year. 

![Alt text](https://github.com/Tanushreechaudhary/Data_Visualization/blob/master/screenshots/Internet_Usage1.png)

Link to Tableau Public: 

This Visualization shows how Internet usage is different for Developed and Developing nations. Norway, being a developed country started with a mark of 52% Internet Users in 2000 and reached until 92.61% in 2015, which clearly gives an idea that Developed nations are way too ahead in technology. According to National Human Development Report(NHDR), Afghanistan is the fifth least developed country and the Statistics presented in the Visualization clearly supports that. In 2000, there were zero Internet Users and even after 15 years, they have just reached to 8.26%. 


![Alt text](https://github.com/Tanushreechaudhary/Data_Visualization/blob/master/screenshots/Internet_Usage2.png)

Link to Tableau Public: 


### Data Wrangling:
The raw data I downloaded from Knoema.com, did not require much cleaning. I had to drop some of the columns that were not providing any information as they would obstruct the actual point of the visualization. I dropped some rows also, that were blank. Renamed columns for consistency. I applied the learnings gained by wrangling data in the lab sessions.

Here is the link to my Jupyter notebook: 

### Intermediate Visualization Prototypes:
#### Intermediate1:

![Alt text](https://github.com/Tanushreechaudhary/Data_Visualization/blob/master/screenshots/Internet_Usage4.png)




























