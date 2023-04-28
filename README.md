# ProjectTwo
# Group Project 2 - ns_21482_7


**Team Name and Members:**

Team Name: ns_21482_7.   

Shivani Patel - https://github.com/shivupate/ProjectTwo.git   
Kalen Patel - https://github.com/kalenpatel02/Group-Project-2---ns_21482_7.git      
Luke Staggs - https://github.com/McStagger20/Group-Project-2.git  
Grayson Williams - https://github.com/graysonbw1/4610Project2.git  
Angela Dinh - https://github.com/angeladinh/Project2.git


**Describing your dataset and what data it contains:** 


The data set was acquired from Kaggle, and it contains information about various video games that have sold at least 100,000 copies. In total, there are 16,598 rows/records, and there are 11 columns.

* Rank - the overall ranking of sales.
    * Datatype: Integer
* Name - name of the game.
    *  Datatype: String
* Platform - what console the game was released on (PS3, PS4, PC, Xbox 360, Xbox One, 2600, 3D0, 3DS, DC, DS, GB, GBA, GC, GEN, GG, N64, NES, NG, PCFX, PS, PS2, PSP, PSV, SAT, SCD, SNES, TG16, WII, WIIU, WS, XB)
    * Datatype: String
* Year - the year the game was released
    * Datatype: String
* Genre - the category of the game
    * Datatype: String
* Publisher - the company that created the game
    * Datatype: String
* Sales Dimensions (measured in millions of copies sold):
    * NA_Sales - the number of copies sold in the US
        * Datatype: Decimal
    * EU_Sales - the number of copies sold in the EU
        * Datatype: Decimal
    * JP_Sales - the number of copies sold in Japan
        * Datatype: Decimal
    * Other_sales - the number of copies sold in the rest of the world
        * Datatype: Decimal
    * Global_sales - the total number of copies sold
        * Datatype: Decimal

**The 2 questions the team generated and why they are interesting and important:**
 
 1. We first want to ask which is the most sold video game genre per capita by region. This is important because it describes the social desires of the region’s video game players. By learning which genre is most desired by region, video game developers know where to market their products, or they can discover untapped markets. This dataset is perfect to answer this question because it has tracked the sales by region over time for each video game made. The time period of the data recorded is from 1980 until 2020.

2. We also want to ask which region has the highest number of sales by platform. This is interesting because we will discover which region utilizes which platform the most. This is important because platform developers can know which regions to market their platforms to, or they can discover untapped markets.This dataset is perfect to answer this question because it has tracked the sales by platform over time.The time period of the data recorded is from 1980 until 2020.


**The manipulations applied to the data set as part of the analysis:**

We manipulated the data to only show the information gathered after 2000. We did this by filtering the year on Tableau to include only more current data ranging from 2000 to 2020. The purpose of this is to make our analysis more consistent with modern day platforms and genres. 

Another manipulation we did was that we divided each region’s sales by the population in that region to get per capita sales. This was done to make each region a level playing field for comparison purposes for video game sales.

Another manipulation we did was that we determined the game systems that each game was played on based on the manufacturer of the console. The purpose of this was to determine which platform was the most popular in the modern day and see what platforms were not as successful. 

**Analysis and Results:**

The first implication is to see the sales per capita per genre in each region. This allows us to analyze which genre is most sold per region. This is a good way for the game developers to market their products heavier in the regions in which the genre has more demand. They may also choose to target their marketing to regions in which their genre is not in demand in order to expand their market reach.

As seen in the graph above, role-playing games are the most popular in Japan and have a significantly higher amount of sales than any other genre in the country. This implies that any role-playing game developers should advertise their game strongly in Japan as it would be the most appealing to that audience and any Japanese developers should focus on developing role-playing games if they are looking to appeal to their native audience. 

The second implication is the number of games bought by platform. This is a way for console manufacturers to know where they rank amongst their peer competitors. This is key data as a lot of big corporations must perform benchmarking in order to strategically plan to stay ahead of their competition. 

As seen in the graph above, Playstation game console games are the most popular in terms of global sales. This implies that Playstation is the strongest competitor in the market with Nintendo being its biggest competitor. Gameboy is the weakest in the market and they could use this information to gain a larger part of the market by observing what Playstation is doing well and using that in their strategy. 
