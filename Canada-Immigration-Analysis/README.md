# Canada Immigration Analysis
## Overview
This project aims to analyze immigration data to Canada. The data is visualized using Python libraries such as Pandas, NumPy, Seaborn, and Matplotlib.

## Dataset
The dataset is sourced from [IBM Developer Skills Network](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0101EN-SkillsNetwork/Data%20Files/Canada.xlsx) and contains information on immigration to Canada by country of origin.

## Installation
To run this project, you need to have Python installed along with the following libraries:
`pandas, numpy, seaborn, matplotlib`

## Output of treemap
````python
fig = px.treemap(df,
                path= ["Continent", "Region"],
                values= "Total",
                title= "Immigrants from all over the world")
fig.show()
````

![Immigrant from all over the world](newplot1.png)

````python
fig = px.treemap(df_asia,
                 path=["Region", "index"],
                 values="Total",
                 title="Asian Immigrants")

fig.show()
````
![Immigrant from Asia](newplot2.png)


## Conclusion
This project provides insights into immigration trends to Canada, revealing patterns and changes over time. The visualizations help in understanding the data better and can be used for further analysis.


Feel free to modify and expand upon this draft to better suit your project's needs.
Happy coding! 
