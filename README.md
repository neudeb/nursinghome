# NHSN Covid-19 Nursing Home Data Analytics

Analysis of data submitted by several nursing homes to the CDC's National Healthcare Safety Network (NHSN) COVID-19 Long Term Care Facility Module from 2020 to 2022.

The data is openly available at [CMS](https://data.cms.gov/covid-19/covid-19-nursing-home-data)

The data dictionary is available [Here](https://data.cms.gov/sites/default/files/2022-09/COVID-19%20Nursing%20Home%20Data%20Dictionary%209.1.22.pdf)


- Author: Debanjan Saha
- PI: Prof. S. Radhakrishnan
- Affiliation: College of Engineering, Northeastern University, Boston, MA

![](https://img.shields.io/badge/Made%20with-Colab-orange?style=for-the-badge&logo=GoogleColab)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-blue.svg?style=for-the-badge&logo=matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-blueviolet.svg?style=for-the-badge&logo=seaborn&logoColor=black)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)

![Python](https://img.shields.io/badge/Python-3.10-blue)
![License](https://img.shields.io/github/license/mashape/apistatus.svg)


## Notebook Organisation
1. Data Investigation
    * Memory Optimization
    * Data Cleaning
2. Data Processing
3. Data Analytics at various levels
    * Facility Level Analysis
        - Shortage Analysis
    * City Level Analysis
        - Shortage Analysis
    * County Level Analysis
        - Shortage Analysis
    * State Level Analysis 
        - Shortage Analysis
    * Patient Level Analysis

## Observations

### Memory Optimization:

- In this notebook, we showed how to use data type assignment in Python based on data size to reduce the amount of latent memory used for processing.
- We also noticed a massive 26% memory savings from 2.6 GB to 1.9 GB while doing so.
- We also published a Medium [article](https://medium.com/@MLdebanjan/pandas-memory-optimization-6ca1b7cef02f) in which we discussed this phenomenon in greater depth. Avid users are encouraged to read the article.

### Data Analysis

We conducted various levels of data analysis based on the performance of different types of shortages in relation to their medians.
Because the shortage data is highly skewed, using the median as an inflection point provides us with information about the actual conditions on a more generalized basis.

### Facility Level

#### Key Takeaways:

1. From 2020 to 2022, there has been a gradual decrease in the number of unique facilities reporting their data.
2. There has been a significant shortage of nursing staff and aides, with a much lower shortage of clinical and other staff members.
3. A relatively low shortage of supplies, N95 masks, face masks, eye protection equipment, gowns, and gloves, implying that these critical items were restocked on a regular basis, resulting in effective care.


### City Level

#### Key Takeaways:

1. Chicago, LA, Cincinnati, Houston, San Antonio were the top 5 states with the largest number of facilities.
2. Almost equal levels of shortages noticed for all states for various staffs and aides
3.  A relatively low shortage of supplies, N95 masks, face masks, eye protection equipment, gowns, and gloves, but in general these shortages were more than individual facility averages. 


### County Level

#### Key Takeaways:

1. LA had the highest number of facilities with nearly double of that of the second place Cook County, IL.
2. Equal amount of shortages of nursing staff, aides and other staff were noticed whereas a relatively lower amount of Clinical staff shortages were noticed
3. A relatively moderately low shortage of supplies, N95 masks, face masks, eye protection equipment, gowns, and gloves, but in general these shortages were more than individual city averages. 


### State Level

#### Key Takeaways:

1. Texas, California and Ohio were the top 3 states with the largest number of facilities
2. Moderate shortages of staff and aides noticed when aggregated on state levels
3. Significant amount of shortages of upplies, N95 masks, face masks, eye protection equipment, gowns, and gloves noticed at state levels


### Individual Patient Level

#### Key Takeaways:

1. It was around the month of May-2020 that many facilities were unable to cope with the spread of Covid.
2. It was also around that time, April-2020, that the percentage of confirmed deaths was at its highest.
