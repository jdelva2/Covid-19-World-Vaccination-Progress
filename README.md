# [Covid-19 World Vaccination Progress](https://jdelva2.github.io/Covid-19-World-Vaccination-Progress/)

## Purpose
The Covid-19 event has been a very troubling time for all of us around the world. Due to this, I plan to use this project to conduct a study on the amount of people getting vaccinated and leverage off fear that some people have about the virus. With this I hope to share this with family members and close friends that getting fully vaccinated is one step closer to helping combat the virus.

## Questions worth discovering
- How has the Covid Vaccination Process progressed throughout the year?
- What does the total vaccination progress for certain countries look like? i.e U.S, Mexico, Canada, China, UK, etc.



## Covid features scatterplot matrix
  Here we will 
  ```Markdown
  
  ```
![](https://github.com/jdelva2/Covid-19-World-Vaccination-Progress/blob/main/Plots%20and%20Graph%20Results/covid_features_pairplot.png?raw=true)

## US Total Vaccinations

![](https://github.com/jdelva2/Covid-19-World-Vaccination-Progress/blob/main/Plots%20and%20Graph%20Results/US_total_vacc_scatterplot.png?raw=true)

## Total Vaccinations for major Countries
```markdown
#Subsets United States data from the original data set.
US_data = sub_data.loc[sub_data["country"] == "United States"]

#Subsets Mexico data from the original data set.
Mexico_data = sub_data.loc[sub_data["country"] == "Mexico"]

#Subsets Canada data from the original data set.
Canada_data = sub_data.loc[sub_data["country"] == "Canada"]

#Subsets UK data from the original data set.
UK_data = sub_data.loc[sub_data["country"] == "United Kingdom"]

#Subsets China data from the original data set.
China_data = sub_data.loc[sub_data["country"] == "China"]

#Subsets India data from the original data set.
India_data = sub_data.loc[sub_data["country"] == "India"]

#Combines all the 5 countries' data into one dataframe (vertically/row wise)
world_countries = pd.concat([US_data, Mexico_data, Canada_data, UK_data, China_data, India_data], axis = 0)

 #Scatterplot
plt.figure(figsize = (12,6))
plt.title("Total Vaccines per country")
sns.scatterplot(x = world_countries['date'], y = world_countries['total_vaccinations'], hue = world_countries['country'])
ax = plt.gca()
ax.get_yaxis().get_major_formatter().set_scientific(False)
plt.xticks(np.arange(0, len(x), step = 5), rotation = 45)
plt.xlabel("Date")
plt.ylabel("Total Vaccinations")
#plt.legend()
```
![](https://github.com/jdelva2/Covid-19-World-Vaccination-Progress/blob/main/Plots%20and%20Graph%20Results/total_vacc_for_six_countries.png?raw=true)



