# Project 2

### 1. Group and Student member

+ group 12
+ Zonghan Ju 320180939841
+ juzh18@lzu.edu.cn
+ Jiachen Tang 320180940251
+ tangjch18@lzu.edu.cn
+ Haoyuan Xue 320180940421
+ xuehy18@lzu.edu.cn

### 2. Abstract

We have chosen the broken line chart of China's real-time carbon data for visual analysis. Carbon dioxide (CO2) is the main greenhouse gas that causes global warming. We analyzed the broken line chart of China's carbon dioxide emissions during the period from the outbreak of covid-19 in China at the beginning of the year until the epidemic was gradually controlled in China. We think it is very meaningful to analyze this picture. Carbon monitoring is an international initiative, and regular updating of carbon monitoring data will give us a better understanding of how policy actions and economic changes, energy prices, holidays, weekends and weather control CO2 emissions. In order to better study the impact of the epidemic on carbon dioxide emissions, we analyzed the data types, visual variables, etc., and analyzed the relevant cognitive theory. We also found some visualization problems in the graph and made some modifications to make this line chart more in line with the specification requirements of information visualization.

### 3. Introduction

According to the Convention of the past years, from the middle of January to the middle of February belongs to the Spring Festival period in China. During this period, many factories will shut down during holidays, so carbon dioxide emissions will be greatly reduced. After the middle of February, carbon dioxide emissions will gradually increase until they return to normal.

However, the covid-19 epidemic broke out in China at the end of January this year, and the Chinese government adopted strict blockade measures in early February, including factory shutdown, school suspension of offline teaching, traffic restriction, etc. These measures continued until March, when the epidemic was effectively controlled in China. As a result, China's carbon dioxide emissions this year did not return to normal until April.

In this project 2, we started from https://www.carbonmonitor.org.cn/downloads The website gets the data and filters out the data for drawing.

[chinaco2.csv](https://github.com/juzonghan/project2/blob/master/chinaco2.csv)

The data shows China's daily carbon emissions between January and October in 2019 and 2020. The original line chart shows a comparison of China's daily carbon emissions from January to October in 2019 and 2020, with dark blue representing the data for 2019 and orange for 2020.

Then we improved the picture.

### 4. Replicate the Graph

In this line chart, the x-axis represents time and the y-axis represents carbon emissions. The dark blue line represents the data for 2019, while the orange line represents the data for 2020.

The visual variables：colour,position and value.

This is the original picture:

![Image text](https://github.com/juzonghan/project2/blob/master/china.png)

This is the copy picture:

![Image text](https://github.com/juzonghan/project2/blob/master/copypic.png)

### 5. Improve the picture

According to the following visualization criteria: 

+ Create the simplest graph that conveys the information you want to present.
+ Every bit of ink requires a reason. Nearly always, that reason should be to present new information
+ Information visualisation ought to be colorblind-friendly,blue–yellow color blindness.
+ Remove unnecessary background.

we modified the original image:

+ Let the line be thinner to avoid blocking the data reading.
+ Delete the meaningless inks of 2019 and 2020.
+ Change blue and orange to blue and red to avoid red green color blindness and yellow blue color blindness.
+ We deleted 16 and 36 scale marks.

This is the improved picture:

![Image text](https://github.com/juzonghan/project2/blob/master/fixpic.png)

### 6. Conclusion

This time, we analyzed the broken line chart of China's carbon dioxide emissions, and improved it on the basis of the original map to make it more in line with the criteria of data visualization. Although we have encountered some difficulties in the process, we have overcome them through our unremitting efforts.

Through this project, we have a more in-depth understanding of visualization, and have mastered many visualization criteria. In the future, we will promote these guidelines in our study and life.

