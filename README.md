# UKRAINE CONFLICT

## ANALYSIS REPORT FOR UKRAINE CONFLICT

### INTRODUCTION

The dataset under consideration focuses on the Ukraine conflict, providing valuable insights into the dynamics of the conflict, actors involved, and associated casualties. The dataset includes key variables such as 'Deaths A’ (The side A of the conflict: The government of Ukraine & Supporters of independence for Eastern Ukraine), 'Deaths B' (The side B of the conflict: DPR, LPR, Maidan & United Armed Forces of Novorossiya), 'Deaths Civilians,' and 'Deaths Unknown'.

### ABOUT THE DATA/DATA COLLECTION

It is a structured data, and it is a secondary data collected. The data contains a table in csv file. It contains 2990 rows and 49 columns.
The analysis to be carried out is to answer the following questions:

1.	What is the total number of deaths that occur under the side A of the Ukraine conflict?

2.	What is the total number of deaths that occur under the side B of the Ukraine conflict?
   
3.	What is the percentage of fatalities in the Ukraine conflict, considering total number of civilian deaths, unknown deaths, and affected and killed individuals?
	
4.	How is the Ukraine conflict distributed across different coordinate locations in the dataset?

5.	What are the overall trends in the number of death (Deaths A and Deaths B) over the years?
	
6.	What is the total number of sources for each conflict name?
 
7.	How has the reliability of sources evolved over the years?

### TOOLS
The tool used is Microsoft excel for data cleaning and Microsoft power BI for analysis.

### DATA CLEANING AND TRANSFORMATION

The following are the different cleaning procedures:

•	The data contained no blanks and no duplicates.

•	The second row of the dataset contained another heading which was deleted because it was not necessary and some of the text was added to the main heading of the dataset.

•	The first letter of every word in the dataset heading was capitalized. The ‘_’ was also removed in between.

•	Renamed the iso3 to ‘Country Code’.

•	Renamed the gwnoa to ‘Genoa.’

•	The column with ‘gwnob’ as heading was removed. It has empty cells. 

•	Replaced the one blank space under ‘Genoa’ to Not Stated.

### DESCRIPTIVE DATA ANALYSIS(DDA) 

For the analysis to be understood and the questions to be answered, charts were created for it to properly analyzed for insights. The following consist of questions, its analysis and insight for each:

#### 1.	What is the total number of deaths that occur under the side A of the Ukraine conflict?

Revealing a total of 3355 casualties is the number of deaths that has occurred under the side A of the conflict (The government of Ukraine & Supporters of independence for Eastern Ukraine).

![CHART 1](https://github.com/Elizabhettie/Ukraine-Conflict/assets/153202306/4285d965-68b4-4bb8-b334-05f62af04dfd)

The image above is the text box and card chart created to show the total number of death that occur in the Side A.


#### 2.	What is the total number of deaths that occur under the side B of the Ukraine conflict?

A total number of 1371 deaths is the number of death that has occurred under the side B of the conflict (DPR, LPR, Maidan & United Armed Forces of Novorossiya).

![CHART 2](https://github.com/Elizabhettie/Ukraine-Conflict/assets/153202306/3d066cce-d829-46be-a2d6-dfae58d5487a)

The above image is the text box and card chart created to show the total number of deaths that occur in the Side B.

#### 3.	What is the percentage of fatalities in the Ukraine conflict, considering total number of civilian deaths, unknown deaths, and affected & killed individuals? 

The resulting pie chart indicated that civilian deaths numbered 1240, unknown deaths were 1916, and 'affected & killed' totaled 7882. This distribution corresponded to percentages of 11.23%, 17.36%, and 71.41% respectively. Notably, majority of fatalities were in the 'affected & killed' category, accounting for a higher percentage.

![CHART 3](https://github.com/Elizabhettie/Ukraine-Conflict/assets/153202306/653fd4d9-f466-4ccb-8a12-17484382268f)
 
A pie chart was created to show the percentage of fatalities in the Ukraine conflict considering total number of civilian deaths, unknown deaths, and affected & killed individuals.

#### 4.	How is the Ukraine conflict distributed across different coordinate locations in the dataset?

Featuring the fields 'coordinates locations,' 'Id,' 'latitude,' and 'longitude' the total number of cases in the coordinate locations was calculated. The top three locations with the highest number of cases were the Donetsk Basin Area with 350 cases, followed by Donetsk Oblast with 223 cases, and lastly, Novokaterynivka Village with 139 cases. Among the locations with the least number of cases are Podgorodnoye Village, Bakhchevik Village, Klishchiivka Village, Oktyabvske Village, and Komsomolskoye Village.

![CHART 4](https://github.com/Elizabhettie/Ukraine-Conflict/assets/153202306/6a73a975-e554-4b90-98ae-a6fa2764965a)

Above is a map created to show the distribution of Ukraine conflict cases across all coordinate location.


#### 5.	What are the overall trends in the number of death (Deaths A and Deaths B) over the years?

Side A reached its peak in 2014, recording the highest number of deaths during the specified years. In contrast, 2020 marked the lowest point with 75 deaths. This variation illustrates fluctuating patterns in mortality rates over the specified period.

Furthermore, a positive correlation is evident between the total number of Side A Deaths and the total number of Side B Deaths, suggesting a consistent relationship between these two variables.

 ![CHART 5](https://github.com/Elizabhettie/Ukraine-Conflict/assets/153202306/51453de8-ea8e-4d85-bd54-52a6c930d176)

The Line chart above was created to show the trends in the number of death (Deaths A and Deaths B) over the years.


#### 6.	What is the total number of sources for each conflict name?

Integrating the data from the 'conflict name' and 'number of sources' fields, it revealed that the category encompassing Government Supporters of independence for Eastern, Supporters of Ukrainian unity, Donetsk, Lugansk, and Novorossiya which exhibited the highest concentration of sources, totaling 2943. This visual representation offers insights into the distribution of information sources across different conflict names.

![CHART 7](https://github.com/Elizabhettie/Ukraine-Conflict/assets/153202306/7086d02b-7745-4865-8fd5-97c75a940916)
 
The stacked bar chart above was created to show the total number of sources for each conflict name.


#### 7.	How has the reliability of sources evolved over the years?

The data reveals a considerable variation in the number of sources, ranging from a minimum of 154 to a maximum of 1642. This visual depiction allows for a clear comparison of sourcing patterns over time, offering valuable insights into the dynamics of information availability within the dataset. 
The year 2014 with 1642 number of sources stands out as having the highest number of sources, indicating a significant surge in information gathering or reporting activities during that specific period. 

 ![CHART 6](https://github.com/Elizabhettie/Ukraine-Conflict/assets/153202306/14d97ead-1a74-4f36-ad4c-6ce0101ef2bf)

The clustered column chart above was created to show how the reliability of sources evolved over the years.


### RECOMMENDATION
 
Despite the decrease in both the number of deaths from 2016 to 2021, it is essential to remain vigilant and continue efforts to address the Ukraine conflict. While a reduction in conflict-related fatalities is a positive sign, it's crucial to investigate whether this decrease is due to effective peace-promoting actions, alterations in conflict patterns, or the likelihood of underrepresentation.

Furthermore, given the decrease in the number of information sources, there is a need for persistent initiatives to improve data collection methods and verify the credibility of the existing information. This entails partnering with local communities, utilizing advanced analytical tools, and promoting transparency in reporting.


### VISUALIZATION

![UKRAINE CHART 2](https://github.com/Elizabhettie/Ukraine-Conflict/assets/153202306/fa49830c-099a-43da-ac22-20eeee20e68e)

![UKRAINE CHART](https://github.com/Elizabhettie/Ukraine-Conflict/assets/153202306/96fe06f8-7a00-49de-8fb5-11512611f65b)


