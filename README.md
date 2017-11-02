# The Redesign Project - We are Social!
## Project Statement:
“When I took office, only high energy physicists had ever heard of what is called the World Wide Web... Now even my cat has its own page.” -bill Clinton

Why this topic?  For all of us, internet is a pervasive, fundamental part of daily life that continues to be a major driver of the way society accesses and views information, no matter where we are. The recent growth of the Internet and the World Wide Web makes it appear that the world is witnessing the arrival of a completely new technology. So, It would be interesting to know the facts about the evolution of internet around the globe from 2000 to 2015. 
The Data source is Knoema World Data Atlas, the data gives us information about the percentage of Internet users per 100 people as per the country and year.

Data source - https://knoema.com/ITUKGTI2015/international-telecommunication-union-key-global-telecom-indicators

Following is the visualization that is to be redesigned.

![Alt text](https://github.com/Tanushreechaudhary/Data_Visualization/blob/master/screenshots/Internet_Usage.png)

https://public.tableau.com/en-us/s/gallery/internet-coverage-across-globe?gallery=votd

#### Critique for the Visualization:
The Author of this Visualization has created bar charts for each country which shows how for a country, Internet usage changed in the span of 15 years. He has given the filter option to highlight a country and check the statistics. However, the viz sums up the data for all the countries at one place but displaying it using this approach, is a bit overwhelming. Having to flick through the countries to see how usage is changing prevents us from seeing the change over time.
Though bar charts are never a bad option but here the main focus should have been on giving the audiences a clear idea that pops out of the visual at very moment of looking at it. 
So, to redesign it in a better way, I would want to create something easy to understand. So, I would take the raw data from the source mentioned and analyze the data to see what is the clear usage trend it is showing. What claims I can make with the data? Is there a need to add more data to show the visual I perceived. As I analyzed the data, I came up with the claim "We are Social!". It means that after 15 years of invention of Internet, finally major part of the world has access to internet.

#### Audience:
The first Target Audience for my visualization is government because internet access or usage can be directly linked to the economic growth of a country. As we will see, developed countries have more percentage of Internet users. So, government of countries like India, Pakistan where this percentage is very low, can work on improving it. Also, another audience could be the internet Service Provider companies, which can target the countries with low percentage of internet users, for their services and know the reasons and reform their services if needed.

---

## "Making of" the Project:
### 1. Data Analysis:
I exported the visualization to be redesigned in Tableau and tried to analyze the data by changing the visuals. This gave me an understanding about what all arguments I can make with this data. What part of the world showed major growth in internet usage in all these years and what are the reasons for it. So, I developed the following two visualizations.

What could be a better way than a line graph to show increasing numbers? So, First visualization shows the Average number of increasing internet users per 100 people per year. 

![Alt text](https://github.com/Tanushreechaudhary/Data_Visualization/blob/master/screenshots/Internet_Usage1.png) 

Second Visualization shows how Internet usage is different for Developed and Developing nations. Norway, being a developed country started with a mark of 52% Internet Users in 2000 and showed 92.61% in 2015, which clearly gives an idea that Developed nations are way too ahead in technology. According to National Human Development Report(NHDR), Afghanistan is the fifth least developed country and the Statistics presented in the Visualization clearly supports that. In 2000, there were zero Internet Users and even after 15 years, they have just reached to 8.26%. 


![Alt text](https://github.com/Tanushreechaudhary/Data_Visualization/blob/master/screenshots/Internet_Usage2.png)

### 2. Data Wrangling:
The raw data I downloaded from Knoema.com, did not require much cleaning. I had to drop some of the columns that were not providing any information as they would obstruct the actual point of the visualization. I dropped some rows also, that were blank. Renamed columns for consistency. I applied the learnings gained by wrangling data in the lab sessions.

Here is the link to my Jupyter notebook: https://github.com/Tanushreechaudhary/Redesign-Project---Data-Viz/blob/master/Redesign_Project_JupyterNotebook.ipynb

### 3. Intermediate Visualization Prototypes:
#### Intermediate 1:
In the first version, I tried to show the gap between the developed and developing nations, taking into view some major countries. The dawn of Internet has widen the gap between developed and developing nations. As we can see, United Kingdom has shown tremendous growth in a span of 15 years, from 26.82% to 92% and so does other developed countries. But this leaves out the details about the journey of undeveloped nations. So, In the next version, I am going to show the stats about Undeveloped countries.

![Alt text](https://github.com/Tanushreechaudhary/Data_Visualization/blob/master/screenshots/Internet_Usage4.png)


Disadvantages of Viz: I have used circles to display each country against Internet usage, but this doesnot give a clear idea as the sizes for the circles are almost same and have to put the percentage of users as the label.

#### Intermediate 2:
In the second version, we look at the statistics for Internet Usage in Undeveloped nations like Iraq, Nigeria, Somalia and many more, they were almost at zero in 2000 and in 2015, they have shown a little bit of growth. Since, these nations don't have a strong economy and less access to technology, they are lacking behind. So, we can say that economic factors certainly influence the access and content divide in the field of technology.

![Alt text](https://github.com/Tanushreechaudhary/Data_Visualization/blob/master/screenshots/Internet_Usage3.png)

Disadvantages of Viz: This version gives an understanding about the undeveloped countries but here we are analyzing data about how the internet usage has changed around the world. So, instead of bar graphs and circles, in the next iteration, I would make use of the latitudes and longitudes feature of tableau to show it on a map country-wise.

#### Intermediate 3:
In this version, I have put the data in the form of latitudes and longitudes on a map. This visualization allows us to evaluate which countries have Highest number of Internet users and which have the lowest.

![Alt text](https://github.com/Tanushreechaudhary/Data_Visualization/blob/master/screenshots/Internet_Usage5.png)

Advantages: Since, it is giving a map view, we can easily see the details country wise. Light areas show the countries with advent of Internet and low percentages of users while the dark areas display high percentage. 

Disadvantages: It is not showing how Internet usage changed over the years, which is the actual claim. So, there should be a differentiating factor about the years. Like how was it in 2000 and how it has changed in 2015. So, my final version will be taking this point into consideration.

---

## Final Visualization:

![Alt text](https://github.com/Tanushreechaudhary/Data_Visualization/blob/master/screenshots/FinalImage.png)

Link to Tableau Public: https://public.tableau.com/profile/tanushree3514#!/vizhome/WeareSocial_0/WeareSocial

In the final Version, As per the year the color green keeps spreading in different parts of the world and as we see for 2015, Green is the major color. It is showing which countries have improved and which are still lagging behind(the white ones). The increasing growth of the Internet makes it appear that the developing world accepted the arrival of the new technology in just 15 years while the developed countries took around 50 years to invent the technology. Though some parts of the world still do not have access to internet or very little access, but on the whole, over the years this percentage has certainly increased. 
There are more than five times as many Internet users now as there were in 2000. The internet has not just become larger, it has also become more spread out, more global and more Social!

So, from this, government can learn about the current stats in their countries and know the reason why they are lagging behind and how can they educate their citizens about it. Also, Internet providers can know in what countries should they introduce their services and can lower down the rates for poor countries.

---
## RoadMap to future enhancements:
1. Can explore data on the effects of the Internet on Education and Healthcare, how these two services have been influenced by the internet.
2. Can compare GDP reports of Developed and Undeveloped nations to see how is Internet's contribution related to GDP growth.
3. Can know about the content people mostly access via internet and the source of accessing it, like via laptops, smartphones etc.
4. Can explore data about how increase in mobile phone users is related to Internet usage.

#### Also, there are some key findings for 2017 about Internet that I would like to share:
1. Internet penetration increased by 10% in the last 12 months to hit 3.773 billion, or 50% of the world’s population.

2. Global social media use has increased by 21% in the last 12 months, reaching 2.8 billion users globally.

3. Mobile social media use has increased by 30% year-over-year to surpass 2.5 billion users globally, with 91% of social media users  accessing social from mobile.























