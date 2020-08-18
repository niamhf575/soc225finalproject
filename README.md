# soc225finalproject: Social Vulnerability

<h2> Introduction </h2>

When disasters occur, some communities experience worse effects and face greater struggles
in recovering (CDC, 2020). One way of measuring a community’s ability to withstand hardship 
is by their social vulnerability. Issues that impactsocial vulnerability can be economic, 
demographic, or resource-related (CDC, 2020). This concept of social vulnerabilitycan apply 
to individuals, as well. In particular, some people are more vulnerable to experiencing 
homelessness, and homelessness also renders a person especially vulnerable to both the elements 
and to further hardship. It is already well-documented that homelessness is impacted by poverty
and housing shortages (Williams, 2017). According to Williams, homelessness is impacted by a 
lack of affordable housing, as “housing supply has not kept pace with the numbers of people
whose incomes require low cost housing if they are to remain stably housed, putting them at 
severe risk for homelessness(2017).” This project looks at the intersection of housing and 
other measures of social vulnerability, particularly crowded housing. The CDC’s social 
vulnerability index defines crowding as the number of occupied household units with more 
people than rooms (2020). My research question is: how do living conditions relate to other
measures of social vulnerability? Are counties with a higher level of crowded living also 
poorer? Do states with larger homeless populations also have high levels of crowding? 

<h2> Data </h2>
Social Vulnerability dataset https://www.kaggle.com/dannellyz/2018-cdcs-social-vulnerability-index-svi?select=2018_CDC_SVI.csv

Urban Rural Classification scheme dataset
https://www.cdc.gov/nchs/data_access/urban_rural.htm

Homeless PIT counts dataset

<h2> Results </h2>

![crowding boxplots](soc225finalproject/crowding_boxplot.jpg?)

Figure 1

Figure 1 shows boxplots of crowding percentage for each category in the NCHS Urban–Rural Classification scheme. 1-4 are Metropolitan categories, while 5 & 6 are non-metropolitan. Generally, the categories go from most urban (1) to most rural (6). The average percentage is between 1 and 3 for all groups, with more spread from the mean in groups 1,5, and 6 than 2, 3, and 4. It seems that extremely urban or extremely rural areas have the most variation. Finally, all but group 3 are skewed, with a greater spread for data above the mean than data below. In my third plot, I examined the effect of crowding on homelessness. States with a higher proportion of homeless people in their population also had a higher proportion of crowding. 

Figure 2 shows the percentage of people in a county living in poverty on the y-axis and the percentage of crowded households in a county on the x-axis. Each data point represents a county. Each small, numbered subplot corresponds to a different category in the NCHS Urban–Rural Classification scheme. A trendline is included for each category, most of which show a positive linear relationship. The exception is the first category, which is the one with the highest level of crowding shown in Figure 1. 

Figure 3 shows the percentage of crowded households in a state on the x-axis, with the percentage of the population that is homeless on the y-axis. The plot is interactive, and you can mouse over the points to see which state they represent. There is also a trendline, which shows a positive linear relationship. 

