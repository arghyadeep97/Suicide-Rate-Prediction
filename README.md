## Suicide Rate Prediction
This compiled dataset pulled from four other datasets linked by time and place, and was built to find signals correlated to increased suicide rates among different cohorts globally, across the socio-economic spectrum. This dataset contains following attributes country, year, sex, age, suicides_no, population, suicides/100k pop, country-year,HDI for year, gdp_for_year($), gdp_per_capita($), generation.

![image](https://github.com/arghyadeep97/Suicide-Rate-Prediction/assets/70284387/d8ae04b5-7e37-4616-95c7-98299fc195e8)

### Univariate Analysis of Numerical Attributes


![image](https://github.com/arghyadeep97/Suicide-Rate-Prediction/assets/70284387/8fe5b930-6425-4c43-98e7-40bae95fa469)

The attribute Suicide No, distribution is extreme right skewed. Most of the observations are between 0 to 1000. Occurrence of datapoint more than 5000 is quite rare.

![image](https://github.com/arghyadeep97/Suicide-Rate-Prediction/assets/70284387/0955923a-f55f-48ed-a771-a6e2c7076166)

Population distribution is extremely right skewed.

![image](https://github.com/arghyadeep97/Suicide-Rate-Prediction/assets/70284387/a51434bf-c856-4479-87a5-8ee188ef9899)

In this dataset, GDP for Year distribution is also right skewed. Also, most of the datapoints lies between (0.00le13 - 0.60le13).

![image](https://github.com/arghyadeep97/Suicide-Rate-Prediction/assets/70284387/17f29882-6b17-4471-a497-073702215378)

The attribute of “Distribution of Year” is fairly bell-shaped with maximum data lies between the decade of the year 2000 to 2010.


![image](https://github.com/arghyadeep97/Suicide-Rate-Prediction/assets/70284387/947c728c-039a-4e58-82f8-f2708b5d242d)

The attribute of “GDP per Capita” falls under the category of extreme right skewed where few datapoints can go up to 125000$ whereas the mean is 16866$ approximately.





### Univariate Analysis of Categorical Attributes


![image](https://github.com/arghyadeep97/Suicide-Rate-Prediction/assets/70284387/10335868-17f9-4545-9511-500e5e45893e)

In this survey, number of male & female are equal.

![image](https://github.com/arghyadeep97/Suicide-Rate-Prediction/assets/70284387/01d0ebe2-b955-48df-abc0-97e3c6360e5b)

Every age group has almost equal number of datapoints.

![image](https://github.com/arghyadeep97/Suicide-Rate-Prediction/assets/70284387/593ff9fb-8bab-431f-8346-92ac8d65a874)

Most of the datapoints are in Generation X and Silent followed by Millennials, Boomers, C.I. Generation, Generation Z.


### Univariate Analysis Result

1. Suicide No: In this survey, the attribute Suicide No distribution is extreme right skewed. Most of the observations are between 0 to 1000. Occurance of datapoint more than 5000 is quite rare.

2. Population: In this survey, Population distribution is extremely right skewed.

3. GDP for Year: In this dataset, GDP for Year distribution is also right skewed. Also, most of the datapoints lies between (0.00le13 - 0.60le13).

4. GDP per Capita: GDP per Capita distribution is right skewed and most of the datapoints lies between 0 - 60000.

5. Sex: In this survey, number of male and female are equal.

6. Age: In this survey, every age group has almost equal number of datapoints.

7. Generation: In this survey, most of the datapoints are in Generation X and Silent followed by Millenials, Boomers, C.I. Generation, Generation Z.






### Bivariate Analysis

![image](https://github.com/arghyadeep97/Suicide-Rate-Prediction/assets/70284387/54ecf36f-0264-4f8a-bf01-82c0501d3ddb)

Worldwide Suicide rate per 100k Population

![image](https://github.com/arghyadeep97/Suicide-Rate-Prediction/assets/70284387/469ecba1-755b-403b-a908-3cf7fffadc66)

Continent Wise Population Percentage

![image](https://github.com/arghyadeep97/Suicide-Rate-Prediction/assets/70284387/e3ee243d-93e5-4f61-93b2-281fd4e0f48f)

Most Populated Country Wikipedia vs Dataset

![image](https://github.com/arghyadeep97/Suicide-Rate-Prediction/assets/70284387/a3251280-704f-4683-89a3-591c64b4c205)

Year vs GDP Per Capita

![image](https://github.com/arghyadeep97/Suicide-Rate-Prediction/assets/70284387/eec312e9-50ba-436f-a764-d1f41de5dffa)

Year vs Suicide per 100k

### Bivariate Analysis Result

1 . Country vs Suicide Rate per 100k: In this given data we can find Srilanka and Lithunia has highest suicide rate over the years among all the countries also Seychelles and San Mario has median 0 suicide rate over the years. Most of the country having suicide rate between 2-16.

2. Year vs GDP per Capita: In this survey, it is observed that, GDP per capita is significantly increased for all the country over the years.

3. Year vs Suicide per 100k Pop: In this dataset, initially Suicide rate had started increasing from year 1985 and reached the peak in the year 1995 then it started decreasing gradually. Also, it is observed a hike in suicide rate from the year 2015 again.

4. Age vs Sex: The total number of male and female, being suicide victim are almost same for every age group.

5. Year vs Genderwise Sucide per 100K: In this survey, we can see male suicide rate is quite higher than female suicide rate over the years.

6. Suicide rate among different age group over the years.: In the year 1995, we can notice peak in suicide rate in every age group excluding 5-14 and 15-24 years age groups. Also it is observed, with growing age people are tend to commit more suicide.

7. Suicide rate among different Generation over the Years.: In this survey, Generation GI has commited more suicide than anyother generation also Generation Z has least number of suicide commited.

8. GDP per Capita vs Suicide per 100k over Age,Sex and Generation: No such significat evidence found in GDP per capita and suicde per 100k in each graph but it has seen that,

  a. Generation Z mostly contains 5-14 years age groups.
  
  b. Generation Millenial mostly contains 15-24 and 25-34 years age group.
  
  c. Generation Boomer mostly contains 35-54 years age group it also contains 25-34 years age group and 55-74 years age group.
  
  d. Generation GI mostly contains 75+ years of age group some of them are in 55-74 years age group.
  
  e. In Generation silent most of them are 55-74years age group and some of them are 75+ years.
  
  f. Generation X mostly contains 25-34 years age group.`




