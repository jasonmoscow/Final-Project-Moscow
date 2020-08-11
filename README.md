# Police Shootings 2015-2020
>Written by Jason Moscow on August 8th, 2020.


## I downloaded this data set from Kaggle. The data was collected by the Washington Post. The Washington Post is compiling a database of every fatal shooting in the United States by a police officer in the line of duty since January 1, 2015. In 2015, The Post began tracking more than a dozen details about each killing — including the race of the deceased, the circumstances of the shooting, whether the person was armed and whether the victim was experiencing a mental-health crisis — by culling local news reports, law enforcement websites and social media and by monitoring independent databases such as Killed by Police and Fatal Encounters.I did not clean the data myself. The data was cleaned and reposted by a user named Ashin Nazir. Here is the CSV of the data.
[Police Shootings from 2015-2020 Raw](shootings.csv "Title")

## Police Shootings by Race 2015-2020 
The data below demonstrates what percentage of each race has been killed by on duty police officers. White civilians have died almost twice as frequently as black civilians. Black civilians die at almost twice as high of a rate as hispanic civilians. Native and Asian Americans account for about 1.5% of the deaths by police officers. Initially, I was very surprised by these statistics. I considered throwing this data visualization out, but then I realized that similar statistics are often misrepresented in the media. Yes, this data communicates clearly that far more white people are killed by police officers than black people. That, however, is not meaningful data unless it is contextualized with demographic data that allows us to make sense of proportionalities. That is why this visualization is meant to be accompanied by the 2010 census visualization that appears further down. 

![alt text](Police&#32;Shootings&#32;by&#32;Race&#32;2015-2020&#32;(2).png "My Chart!")  


## 2010 US Census Demographics 
This data visualization exists to bring meaning and context to the visualization above. This does not come from the Washington Post data. It was pulled from the 2010 US Census. Because the census is taken every ten years, this is the most recent collection of demographic information by the US census. Using this data, in coordination with the last visualization, a very different story comes to light. Notably, while Black civilians accounted for 28.5% of deaths at the hands of police, Black people only account for 13.4% of the population. This means that the percentage of  Black deaths at the hands of police more than doubles their percentage of the population. Alternatively, White people account for 60.1% of the population, but they only account for 51.5% of police-caused shootings. Hispanic people account for 18.5% of the population and about 16.4% of the victims of police shootings, making their category relatively more proportional. Given the fact that Asians account for 5.9% of the population, the percentage of Asians murdered by police, 1.4%, is proportionally the lowest. 

![alt text](Race&#32;Percentages&#32;USA&#32;from&#32;2010&#32;Census&#32;Data.png "My Chart!")  


## Percentage of US Police Shooting Victims Armed (with gun)  vs. Unarmed US Police Shooting Victims 2015-2020
In order to conduct this data analysis, I created a pivot table with race as the rows and armed vs. unarmed as the column. I changed the values of the columns to “countunique”. Initially, the pivot table was confusing and hard to follow. I made the choice to eliminate data on Asian, Native, and other because each of those races had less than 50 data points, whereas White, Black, and Hispanic had hundreds of data points. At that point, the data was still jumbled and confusing because there was a very loose definition of what it meant to be “armed”. Some victims were noted to be armed with household tools, air conditioner units, and other ambiguous items. In order to receive more concrete information from the data set, I decided to narrow the columns to only included armed with a gun or unarmed. I decided to depict this data as a stacked chart because I found it aesthetically pleasing.  

![alt text](Percentage&#32;of&#32;Armed&#32;vs.&#32;Unarmed&#32;US&#32;Police&#32;Shooting&#32;Victims&#32;2015-2020&#32;(1).png "My Chart!")  
The data tells a clear story. Of the civilians shot by police, White people are most likely to be armed; Hispanic people are second most likely to be armed; and Black people are least likely to be armed. 86.10 percent of black people killed by police were armed, whereas 90.86% of white people killed by police were armed. Alternatively, 13.9% of Black people killed by police were unarmed, whereas only 9.14% of white people killed by police were unarmed. 



This is the pivot table I used to extract the prior data and create the graphics. 
![alt text](pivotTable.png "My Chart!")  
