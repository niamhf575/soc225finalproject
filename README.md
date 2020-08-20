# soc225finalproject: Social Vulnerability

<h2> Introduction </h2>

When disasters occur, some communities experience worse effects and face greater struggles in recovering (CDC, 2020). The CDC refers to a community’s ability to withstand hardship as their social vulnerability, which they measure through a social vulnerability index (CDC, 2020). Issues that impact social vulnerability can be economic, demographic, or resource-related (CDC, 2020). This concept of social vulnerability can apply to individuals, as well. For example, homelessness renders a person especially vulnerable to both the elements and to further hardship. Previous research has shown that homelessness is impacted by poverty and housing shortages (Williams, 2017). This project looks at the intersection of housing and other measures of social vulnerability, particularly crowded housing. The CDC’s social vulnerability index defines a crowded household as an occupied household unit with more people than rooms (2020). My research question is: how do living conditions relate to other measures of social vulnerability? Are counties with a higher level of crowded living also poorer? Do states with larger homeless populations also have high levels of crowding? 

<h2> Data </h2>
My social vulnerabitlity dataset is from the Centers for Disease Control and Prevention (CDC). The urban/rural classification data is from the National Center for Health Statistics (NCHS). The homeless point in time (PIT) counts are from the Department of Housing and Urban Development (HUD). <br/> 
&nbsp;


Social Vulnerability dataset https://www.kaggle.com/dannellyz/2018-cdcs-social-vulnerability-index-svi?select=2018_CDC_SVI.csv

Urban Rural Classification scheme dataset
https://www.cdc.gov/nchs/data_access/urban_rural.htm

Homeless PIT counts dataset: https://www.hudexchange.info/resource/5948/2019-ahar-part-1-pit-estimates-of-homelessness-in-the-us/
<p align = "left">
<img src=https://github.com/niamhf575/soc225finalproject/blob/master/summary.png alt="crowding boxplots" width="400"/> </p>
<p align = "left">
  <img src=https://github.com/niamhf575/soc225finalproject/blob/master/summary3.png alt="crowding boxplots" width="400"/>
  </p>
Above is the summary of EP_POV (the percentage of people in a county who are in poverty), EP_CROWD (the percentage of households in a county that qualify as crowded, with more occupants than rooms), crowd_percent (the percentage of crowded households in a state), and homeless_percent (the percentage of the state population experiencing homelessness). 
<h2> Results </h2>

<p align="center">
  Figure 1
</p>
<p align="center">
<img src=https://github.com/niamhf575/soc225finalproject/blob/master/crowding_boxplot.jpg alt="crowding boxplots" width="600"/>
</p>
Figure 1 shows boxplots of crowding percentage for each category in the NCHS Urban–Rural Classification scheme. 1-4 are Metropolitan categories, while 5 & 6 are non-metropolitan. Generally, the categories go from most urban (1) to most rural (6). The average percentage is between 1 and 3 for all groups, with more spread from the mean in groups 1, 5, and 6 than 2, 3, and 4. It seems that extremely urban or extremely rural areas have the most variation. Finally, all but group 4 are skewed, with a greater spread for data above the mean than data below.

<p align="center">
  Figure 2
</p>
<p align="center">
  <img src=https://github.com/niamhf575/soc225finalproject/blob/master/poverty_v_crowding.jpg alt="crowding boxplots" width="600"/>
</p>


Figure 2 shows the percentage of people in a county living in poverty on the y-axis and the percentage of crowded households in a county on the x-axis. Each data point represents a county. Each small, numbered subplot corresponds to a different category in the NCHS Urban–Rural Classification scheme. A trendline is included for each category, most of which show a positive linear relationship. The exception is the first category, which is also the one with the highest level of crowding shown in Figure 1. 

<p align="center">
  Figure 3
</p>
<p align="center">
<img src=https://github.com/niamhf575/soc225finalproject/blob/master/homelessness_v_crowding.png alt="crowding boxplots" width="600"/>
</p>

In my third plot, I examined the effect of crowding on homelessness. States with a higher proportion of homeless people in their population also had a higher proportion of crowding. Figure 3 shows the percentage of crowded households in a state on the x-axis, with the percentage of the population that is homeless on the y-axis. If you view this plot in soc225_final_project.html it is interactive, and you can mouse over the points to see which state they represent. There is also a trendline, which shows a positive linear relationship. 

<h2>Discussion</h2>
My results show that crowded living conditions correlate with other elements of social vulnerability. I found crowded living conditions are associated with two other measures of social vulnerability, homelessness and poverty. On a county level, my visualizations indicate that counties with a higher proportion of crowded living space also have a greater percentage of poverty. I broke counties into 6 groups according to CDC urban/rural classifications, and I saw that this correlation mostly held across the different groups. The only exception was for the most urban counties, which showed a slightly negative trendline. This may be impacted by the small sample size, as this group has fewer counties than the other categories. The highly urban counties are also much more crowded on average than other counties, and they may tend to be crowded for different reasons then more rural areas. I also found that states with a higher percentage of homeless people in their population had more crowding.  My analysis suggests that there is a connection between crowding and homelessness. Further research could seek to establish if this is also true on a county level, and then to determine whether crowding tends to be a precursor to homelessness. Crowding could be an indicator of the type of social and economic vulnerability that might increase the risk of homelessness. Future analysis could also examine whether the correlations identified here vary by race.   <br/> 
&nbsp;


A limitation of this research is that I was only able to find PIT homeless counts for states, rather than counties. This means that I did not have the opportunity to look at my analysis in finer detail. Another limitation is that different variables in my data were collected in different years: the CDC crowding data is from 2018 while the homeless PIT counts are from 2019. I am reasonably confident in my finding that crowding and poverty have a correlation. However, I am less confident in my finding that homelessness and crowding have a correlation. States are very large areas that contain very different communities, and my visualization doesn’t make it clear if crowding and homeless are both high within individual communities. Also, it’s possible homelessness and crowding are simply higher in states that have more urban areas. In the opposite direction, homelessness may in fact be undercounted in the less-crowded rural areas, according to an NPR article (Meehan, 2019). 

<h3>Ethical Concerns </h3>
The homeless PIT counts are conducted by CoCs. A Continuum of Care (CoC) “is a regional or local planning body that coordinates housing and services funding for homeless families and individuals (What is a Continuum of Care?, 2016).”  Continuums of Care are required to annually count “people experiencing homelessness who are sheltered in emergency shelter, transitional housing, and Safe Havens on a single night (HUD).” This suggests that the PIT count may be an undercount, as it seems to only count people receiving some type of assistance. It is also unclear if the people using resources for homelessness consent to be counted or are even aware that the PIT count is occurring. Additionally, people experiencing homelessness in rural areas may be undercounted: these rural areas have fewer public homeless support resources and homeless camps are out of sight in wooded areas (Meehan, 2019).   <br/>
&nbsp;


In the social vulnerability data, some census tracts are not included due to lack of census data. Since this data set was designed to help allocate resources in emergency situations, it is concerning that some counties are not included at all due to issues with data collection. 

<h2> References </h2>
Centers for Disease Control and Prevention (CDC). (2020) CDC SVI 2018 Documentation. https://svi.cdc.gov/Documents/Data/2018_SVI_Data/SVI2018Documentation.pdf  <br/> 
&nbsp;


Williams, J. (2017, January 10). The Politics of Homelessness in the United States. Retrieved August 17, 2020, from https://www.oxfordhandbooks.com/view/10.1093/oxfordhb/9780199935307.001.0001/oxfordhb-9780199935307-e-153

Meehan, M. (2019, July 04). Unsheltered And Uncounted: Rural America's Hidden Homeless. Retrieved August 17, 2020, from https://www.npr.org/sections/health-shots/2019/07/04/736240349/in-rural-areas-homeless-people-are-harder-to-find-and-to-help

Department of Housing and Urban Development (HUD). (n.d.). Point-in-Time Count and Housing Inventory Count. Retrieved August 19, 2020, from https://www.hudexchange.info/programs/hdx/pit-hic/

What is a Continuum of Care? (2016, October 24). Retrieved August 19, 2020, from https://endhomelessness.org/resource/what-is-a-continuum-of-care/

