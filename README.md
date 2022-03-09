# Surfs_up Analysis
Overview
The purpoe of this project was to determine if the weather on Oahu, Hawaii is conducive to an ice cream/surfboard rental business. For this analysis, June and December were the months looked at since they are at the mid and end points of the year, and the start of the summer and winter seasons respectively. Note: this analysis only looked at temperature, not at precipitation, and looked at years 2010-2017.

Results: June
June had over 1700 datapoints to look at. Here are the following stats:
![image](https://user-images.githubusercontent.com/94264746/157368527-3ce1415a-c081-4fea-9f33-869d81eabd26.png)
As you can see, June is a very mild month in Oahu with: 
•	an average temperature of about 75 degrees Fahrenheit (~24 Celsius)
•	The lowest temperature recorded in June was still 64 degrees Fahrenheit (~18 Celsius)
•	The highest temperature recorded was 85 Fahrenheit (~30 Celsius)

Results: December
December had just over 1500 datapoints to look at.
![image](https://user-images.githubusercontent.com/94264746/157369141-42b86c7e-3d01-4e20-a832-5aa6cf0805ed.png)
December is a colder month than June but not by a lot.
•	The average temperature in December is around 71 degrees Fahrenheit (~22 Celsius)
•	The lowest December temperature recorded was 56 degrees Fahrenheit (~13 Celsius)
•	The highest temperature recorded was close to June's highest at 83 Fahrenheit (~28 Celsius)

Summary:

Overall Oahu seems like an excellent spot to set up an ice cream and surfboard rental shop, at least temperature wise. Temperatures at both times of year never get close to freezing nor do they get to be too hot. However I would also do a couple additional queries:
1. I would use df = pd.DataFrame(results, columns=['date','precipitation']) to figure the amount of rainfall
2. I would gather additional data to determine ocean conditions per time of year.
