# Examining Trends in Teen Birth Rate, Access to Early Prenatal Care, and Babies with Low Birth Weight in Maryland, 2010-2017

## Background
According to [March of Dimes](https://www.marchofdimes.org/Peristats/ViewTopic.aspx?reg=24&top=1&lev=0&slev=4), in an average week in Maryland, 1,406 babies are born, 139 babies are born preterm, 120 babies are born at a low birth weight, and nine babies die before the age of one. In 2018, the low birth weight rate of Maryland was [8.8%](https://www.marchofdimes.org/Peristats/ViewTopic.aspx?reg=24&top=4&lev=0&slev=4), which did not reach the Healthy People 2020 goal of a rate of 7.8% or lower. According to the same source, black babies were about two times as likely as white babies to be born at a low birth weight from 2016 to 2018, on average. In 2018, in Maryland, [74.6%](https://www.marchofdimes.org/peristats/ViewTopic.aspx?reg=24&top=5&lev=0&slev=4) of live births were to women receiving early prenatal care, 18.8% were to women starting prenatal care in their second trimester, and 6.6% were to women who received late or no prenatal care at all. About one in six infants was born to a mother receiving inadequate prenatal care in Maryland at the time. 

It is [known](https://www.ncbi.nlm.nih.gov/books/NBK219236/) that teenage pregnancy is linked to many adverse outcomes for both the mother and child, including low birth weight, health problems from poor perinatal outcomes, increased risk of perinatal death, and poor academic achievement in the child. Babies born with low birth weight have a [higher risk](https://www.marchofdimes.org/complications/low-birthweight.aspx.) of heart disease, diabetes, high blood presusure, intellectual and developmental disabilities, obesity and metabolic syndrome. [Research](https://www.womenshealth.gov/a-z-topics/prenatal-care) has also shown that access to prenatal care is very important for a healthy pregnancy, and the babies of mothers who do not have access to prenatal care are three times more likely to have low birth weight and five times more likely to die. 

## Abstract

This report examines trends in reproductive health in Maryland from 2010 to 2017. The report explores teenage birth rate, access to early prenatal care, and babies with low birth weight as it is known that there can be negative consequences associated with these factors, or a lack thereof. The report identifies three counties for the Maternal and Child Health Bureau of the Maryland Department of Health to place focus on: Prince George’s, Garrett, and Somerset Counties. Public health initiative recommendations for the Bureau to implement for these three ounties include access to free contraceptives, improved sex and pregnancy education, increased funding for prenatal care centers and transportation to the centers, and partnerships with local county health departments. 

## Business Question 
How have teen birth rate, access to early prenatal care, and the number of babies with low birth weight impacted the population of Maryland? How can trends and patterns in these variables inform local and/or state policy?

## Metrics 
1. Teen Birth Rate 
2. Low Birth Weight
3. Early Prenatal Care 

## Data Sources
 - We used data from the [Maryland Open Data Portal](https://opendata.maryland.gov/) to examine these three variables
   - We used health data from the SHIP program-- which falls under Human and Health Services-- because it was fairly consistent across variables
      - SHIP is the State Health Improvement Process
   - Sources
      - [SHIP Teen Birth Rate from 2010-2017](https://opendata.maryland.gov/Health-and-Human-Services/SHIP-Teen-Birth-Rate-2010-2017/t8wg-hb7j)
      - [SHIP SHIP Early Prenatal Care 2010-2017](https://opendata.maryland.gov/Health-and-Human-Services/SHIP-Early-Prenatal-Care-2010-2017/48en-6hyz)
      - [SHIP Babies with Low Birth Weight 2010-2017](https://opendata.maryland.gov/Health-and-Human-Services/SHIP-Babies-with-Low-Birth-Weight-2010-2017/cyet-5jd3)

## Data Analysis Methods
1. Trends in the three selected variables: [Python/Google Colaboratory](https://colab.research.google.com/drive/1rCYgMpQ4OhVQOAhwA8zNrKPrlClOcgUA?usp=sharing)
2. Percent Change in the three selected variables: [Python/Google Colaboratory](https://colab.research.google.com/drive/1QUmTvWJn7qQ4KBY9saS84pE6xG56tdcX?usp=sharing)
3. Cluster Analysis: Excel (see attached files, labeled 'Final project Cluster Analysis') 

## Overview of Data Findings 

Several counties within Maryland displayed relatively high teen birth rates, high low birth weight, and low early prenatal care based on the trends, percent change, and cluster analyses, but emphasis for improvement can be placed to Prince George's, Garrett, and Somerset Counties.

## Data Visualizations 

### **Teen Birth Rate** 

![teen_BR_top5](https://user-images.githubusercontent.com/70858878/102546489-b49dca80-4085-11eb-9c94-2395c384a639.png)
Teen birth rate has declined significantly in the five largest counties in Maryland from 2010 to 2017. Of the five counties, Baltimore City has the highest teen birth rate, at 53.3 in 2010 and 28.9 in 2017. The second highest teen birth rate was for Prince George’s County, which was at 33.1 in 2010, and dropped down to 19.3 by 2017. Anne Arundel and Baltimore County were fairly comparable, at 25.8 and 22.5 in 2010, respectively, and eventually falling to 11.9 and 11.0 in 2017. Montgomery County had the lowest teen birth rate, at 17.4 in 2010 and 9.5 in 2017. 

![teen_BR_bot5](https://user-images.githubusercontent.com/70858878/102546539-cb442180-4085-11eb-8841-f9bae7e77e76.png)
There was a lot of variability over the years in teen birth rate for the five smallest counties in Maryland. All five counties ended with a lower birth rate in 2017 compared to when the study began collecting data in 2010. Dorchester County had the highest teen birth rate, at 55.1 in 2010 and 21.4 in 2017. In 2010, Caroline County had the second highest birth rate (41.4), then Somerset County (31.6), then Garrett County (30.7), and finally Kent County at 15.5. From 2010 to 2014, there did not appear to be an overarching trend as teen birth rate fluctuated considerably for all five counties. Something to note here is that Somerset County appeared to have a large spike in teen birth rate from 2011 at a rate of 24.4 to 2013 at 39.9. All five counties presented a spike in 2015, with a rate of 50.7 in Dorchester, 31.8 in Garrett, 27.0 in Caroline, 22.5 in Somerset, and 18.2 in Kent. In 2017, all counties except Kent reached their lowest point, at 21.4 for Dorchester, 17.9 for Garrett, 13.0 for Somerset, and 8.5 for Kent. 

![alt_text](change-tbr-big.png) 
![alt_text](change-tbr-small.png) 

These trends can be seen more easily through these percent change visualizations. These charts show the change in teenage birth rates for the five biggest and five smallest counties from 2010 to 2017. All ten counties showed at least a 0.6% decrease in teen birth rates from 2010 to 2017, indicating progress for this particular health outcome. Caroline and Dorchester Counties, which are both among the smallest five, displayed the most decrease, with approximately 1.6% of a drop. The next highest decrease was 1.2%, displayed by Anne Arundel County, which is one of the biggest five counties. 

Although all the counties’ teen birth rates decreased from 2010 to 2017, the Maternal and Child Health Bureau should still focus on a few counties with the least amount of reduction in rates. These would be Prince George’s County (~0.7% decrease), Garrett County (~0.7% decrease), and Kent County (~0.8% decrease). 

### **Low Birth Weight** 

![lbw_top5](https://user-images.githubusercontent.com/70858878/102546683-ffb7dd80-4085-11eb-80a7-328255c0223e.png)
The percentage of babies with low birth weight had less variability for the five largest counties in Maryland. In 2010, the rates were the largest for Baltimore City (11.7%), then Prince George’s County (10.2%), then Baltimore County (8.4%), then Anne Arundel County (8.2%), and finally Montgomery County (7.7%). The percentage of babies with low birth weight were actually higher by 2017 for both Baltimore City (12.4%) and Baltimore County (9.5%). In 2017, the percentage of babies with low birth weight was 12.4% for Baltimore City, 9.8% for Prince George’s County, 9.5% for Baltimore County, 7.8% for Anne Arundel County, and 7.5% for Montgomery County. 

![lbw_bot5](https://user-images.githubusercontent.com/70858878/102546687-0181a100-4086-11eb-939b-041e356c99b4.png)
There was much more variability in babies with low birth weight for the five smallest counties in Maryland. In 2010, the percentage of babies with low birth weight was 11.2% for Dorchester County, 10.8% for Kent County, 8.6% for Caroline County, 7.9% for Garrett County, and 7.4% for Somerset County. In 2011, Somerset County appeared to have a small spike at 10.1%; Somerset County had its lowest percentage in 2013 at 5.3% but then had its lowest percentage two years later at 8.6%. In 2012, Kent experienced a large spike in the babies with low birth weight at 16.9%. In 2017, the percentage of babies with low birth weight was higher than from when the study started for two counties: Somerset (13.2%) and Garrett (11.0%). The percentage of babies with low birth weight was lower than from when the study started for the remaining three counties: 10.4% for Kent, 7.3% for Dorchester, and 7.4% for Caroline. 

![alt_text](change-lbw-big.png) 
![alt_text](change-lbw-small.png) 

These percent change charts visualize this information more clearly. Four out of the ten counties experienced an increase in low birth weight: Baltimore City (+0.06%), Baltimore County  (+0.12%), Garrett County (+0.3%), and Somerset County (+0.4%). It is interesting that it was the smaller counties, Garrett and Somerset, that displayed a larger increase in low birth weight, rather than the larger, more metropolitan areas like Baltimore City and Baltimore County. This suggests that the Maryland Department of Health should focus on Garrett and Somerset Counties when developing solutions for this particular metric.

### **Early Prenatal Care** 
![pnc_top5](https://user-images.githubusercontent.com/70858878/102546728-11998080-4086-11eb-99f3-19ee2e9b492d.png)
Access to early prenatal care varied from county to county in the five largest counties in Maryland. In 2010, access was at 78.2% for Anne Arundel County, 69.3% for Montgomery County, 68.4% for Baltimore County, 64.9% for Baltimore City, and 54.0% for Prince George’s County. By 2017, access to early prenatal care actually fell for Anne Arundel at 71%. Access to early prenatal care fluctuated over the years considerably for Baltimore City, dropping slightly in 2011, rising slightly in 2012, dropping significantly in 2013 (56.7%), and slowly rising to 67.1% in 2017. Access to early prenatal care rose slightly for the three remaining counties by 2017, at 70.9% for Montgomery, 69.0% for Baltimore County, and 59.1% for Prince George’s.

![pnc_bot5](https://user-images.githubusercontent.com/70858878/102546727-11998080-4086-11eb-9fd5-2d816bbc6728.png)
Access to early prenatal care stayed relatively high for the five smallest counties in Maryland. In 2010, access to early prenatal care was 82.1% for Garrett County, 77.3% for Kent County, 75% for Caroline County, 73.6% for Somerset County, and 73.5% for Dorchester County. Access increased and decreased between 2010 and 2017, but overall, the percentages did not change very much for all five counties. However, Kent did experience a drop in access in both 2013 (72.7%) and 2016 (72.9%), before eventually reaching 80.3% in 2017. In 2017, access to early prenatal care was 80.3% for Kent County, 78.9% for Garrett County, 78.4% in Dorchester County, 76.4% in Somerset County, and 71.3% in Caroline County. 

![alt_text](change-epc-big.png) 
![alt_text](change-epc-small.png) 

Looking at the percent change visualizations, it is clear that most of the counties improved their prenatal care services, with seven out of the ten counties having a positive percent change. However, the change was not very large; all seven counties showed less than 0.1% of a change. This suggests that even though the counties had an improvement, they still have more to work to do. While it is still important that they continue to address the issue, the three counties that showed a decrease in early prenatal care (Anne Arundel, Caroline, and Garrett) require the most attention. Caroline and Garrett Counties (among the five smallest counties) decreased by approximately 0.04%, while Anne Arundel County’s prenatal care decreased as much as 0.1%. 

## Recommendations for Maternal and Child Health Bureau
1. Free Contraceptives in Public Secondary Schools 
2. Strengthened Sex & Pregnancy Education 
3. Increased Funding for Prenatal Care Centers 
4. Increased Transportation to Prenatal Care Centers 
5. Partnerships with Local County Health Departments





