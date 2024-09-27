# SCCountiesPopulation_SQL

In this project, I used data provided by the United States Census Bureau to analyze the population for the population of the counties throughout South Carolina from 2020 until 2023. I created a database in PostgreSQL and answered the following questions:

    1. What was the total population of South Carolina in 2020, 2021, 2022, and 2023?
    2. What was the average population per county in South Carolina in 2020, 2021, 2022, and 2023?
    3. Which 5 counties experienced the most growth over the 4 years?
    4. Which 5 counties experience the least growth over the 4 years?
    5. What are the top 5 most populous counties in South Carolina?
    6. What is the total population by region?

<p align="center"> 
Creating table in PostreSQL for data pulled from Census Bureau
<br/>
<img src=https://imgur.com/IgD6SaX.jpeg/ height="50%" width="50%">

<p align="center"> 
Imported formatted CSV file with data from United States Census Bureau
<img src=https://imgur.com/3wLqT7o.jpeg/ height="50%" width="50%">
<br/>

<p align="center"> 
Proof of data being imported into table
<br/>
<img src=https://imgur.com/d4iJntm.jpeg/ height="50%" width="50%">


1. What was the total population of South Carolina in 2020, 2021, 2022, and 2023? Using the SUM() function I was able to determine the total population in SC for 2020, 2021, 2022, & 2023 </br>
- Population in 2020 = 5,132,151 </br>
- Population in 2021 = 5,193,848 </br>
- Population in 2022 = 5,282,955 </br>
- Population in 2023 = 5,373,555 </br>
</br>
<p align="center"> 
<img src=https://imgur.com/ZzvA5GS.jpeg/  height="50%" width="50%"> 

2. What was the average population per county in South Carolina in 2020, 2021, 2022, and 2023? Using the AVG() function I was able to determine the average populatin in SC for 2020, 2021, 2022, & 2023. I have rounded each to the nearest whole number.</br>
- Average county population in 2020 = 111,569 </br>
- Average county population in 2021 = 112,910 </br>
- Average county population in 2022 = 114,847 </br>
- Average county population in 2023 = 116,816 </br>
<br>
<p align="center"> 
<img src=https://imgur.com/Keutk43.jpeg/  height="50%" width="50%"> 

3. Which 5 counties experienced the most growth over the 4 years?<br> Based on the data provided the 5 counties that experienced the most growth from 2020 to 2023 is Horry, Greenville, Spartanburg, Berkeley, and Lexington.
- Horry County = 43,713 </br>
- Greenville County = 30,787 </br>
- Spartanburg County = 27,319 </br>
- Berkeley County = 23,684 </br>
- Lexington County = 14,481 </br>
<br>
<p align="center"> 
<img src=https://imgur.com/jpXHgtK.jpeg/  height="50%" width="50%"> 



