# [Covid-19 World Vaccination Progress](https://jdelva2.github.io/Covid-19-World-Vaccination-Progress/)

## Purpose
The Covid-19 event has been a very troubling time for all of us around the world. Due to this, I plan to use this project to conduct a study on the amount of people getting vaccinated and leverage off fear that some people have about the virus. With this I hope to share this with family members and close friends that getting fully vaccinated is one step closer to helping combat the virus.

## Questions worth discovering
- How has the Covid Vaccination Process progressed throughout the year?
- What does the total vaccination progress for certain countries look like? i.e U.S, Mexico, Canada, China, UK, etc.



## Covid features scatterplot matrix
 Here we will view the correlation between some of the variables. i.e the 2nd box. (1st row, 2nd column)
 we see as people_vacc increases, the number of total_vacc also increases. This is intuitive, but its good to know it is a very strong positive correlation. We may do the same with the others. In general they all have an upward trend leading to positive correlations as well. When one feature increases, the other feature increases as well.
 
![](https://github.com/jdelva2/Covid-19-World-Vaccination-Progress/blob/main/Plots%20and%20Graph%20Results/covid_features_pairplot.png?raw=true)

## US Covid Cases

Here we will track the number of covid cases over time.

![](https://github.com/jdelva2/Covid-19-World-Vaccination-Progress/blob/main/Plots%20and%20Graph%20Results/num_cases_line_plot.png?raw=true)

## US Covid Deaths
Here we can track the number of deaths that occurred in the US.
![](https://github.com/jdelva2/Covid-19-World-Vaccination-Progress/blob/main/Plots%20and%20Graph%20Results/num_deaths_line_plot.png?raw=true)

## Log Covid Cases vs Covid Deaths
The growth of the number of cases far exceeded the number of covid deaths. Thus a log transform was conducted to better get a results of this pattern.

![](https://github.com/jdelva2/Covid-19-World-Vaccination-Progress/blob/main/Plots%20and%20Graph%20Results/log_cases_deaths_line_plot.png?raw=true)

## US Total Vaccinations

It's important to note that the first set of US vaccines rolled out in Dec 2020. As the years continue, we can see the quick upward trend that follows confirming that people are getting vaccinated. However, we can also notice that there seems to be some leveling off. This could be due to people or regulations being lenient or not want to get vaccinated.

![](https://github.com/jdelva2/Covid-19-World-Vaccination-Progress/blob/main/Plots%20and%20Graph%20Results/US_total_vacc_scatterplot.png?raw=true)


## Total Vaccinations for major Countries

Looking at this graph. There is a heavy surge in vaccinations in China beginning in April/May 2021. Here we see that they have done a very good job getting people vaccinated. However, Other countries can be seen struggling to keep up to vaccinate thier citizens. 

![](https://github.com/jdelva2/Covid-19-World-Vaccination-Progress/blob/main/Plots%20and%20Graph%20Results/total_vacc_for_six_countries.png?raw=true)



