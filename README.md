# MLB_SpendingVsWinAnalysis
Using data science to analyze each individual team's spending vs their winning rate in the MLB since 1990
https://aparyavi.github.io/MLB_SpendingVsWinAnalysis/

## Payroll vs Year
<img width="339" alt="Screenshot 2023-11-15 at 11 07 44 AM" src="https://github.com/aparyavi/MLB_SpendingVsWinAnalysis/assets/62215723/95ecccdc-251a-443f-9f27-a74cd28a785f">

Based on the graph, the total payroll has increased over the years 1990-2014 and has a negative skewness. This means the total payroll has been increasing on average (central tendency) throughout these years.

We also see fewer outliers in the first 10 years, that might be due to the fact that, even if there were any outliers it wouldn't show themselves as much considering the amount of growth the payrolls have had.

<img width="347" alt="Screenshot 2023-11-15 at 11 07 21 AM" src="https://github.com/aparyavi/MLB_SpendingVsWinAnalysis/assets/62215723/ad6228d3-c8b4-4e14-ab55-4c9d94d83d15">

## Average Winning Percentage vs Average Payroll
<img width="239" alt="Screenshot 2023-11-15 at 11 29 13 AM" src="https://github.com/aparyavi/MLB_SpendingVsWinAnalysis/assets/62215723/af33016b-0560-49ac-90aa-cb74cbab548f">
<img width="256" alt="Screenshot 2023-11-15 at 11 29 44 AM" src="https://github.com/aparyavi/MLB_SpendingVsWinAnalysis/assets/62215723/6f09fc5a-f79d-42b9-bf95-400d125975bd">

One thing we can see is that the winning rate vs payroll changes constantly through time. But we can definitely say that the winning rate usually increases based on payroll all throughout these years, however, I would expect the payroll to have a larger effect but even though it does increase the average winning rate in the years 1990-1995 it did not have a drastic effect as we can see based on the regression line. We can best see the correlation between payroll and winning rate in the years 1995-2000 where teams with lower salaries didn't get nearly as good results as teams with higher salaries. This correlation is also good in the years 2005-2010.

However, this does not mean that teams with lower payrolls have not gotten good results. We can in fact see many teams throughout these periods getting results with much lower payrolls. From the years 1990-1995, team MON was in the top 5 in winning rate with the absolute lowest salary. In the years 2000-2005, teams were not too good at spending efficiently, because teams with higher salaries got better results. In years 2000-2005, OAK was probably the best with spending efficiency getting second place in terms of winning rate and having close to a third of the spending of the highest. In the years 2005-2010 again teams were not that efficient in their spending. However, in the last five years (2010-2015), teams like TBA, OAK, and ATL were among the most efficient of those years having low spending and getting good results. However, NYA has consistently been one of the highest payers and has also consistently gotten good results.

OAK has not been consistent throughout this entire timeline, but they have been one of the better teams in terms of spending efficiency after the year 2000. Before that, however, in years 1990-1995, they were among the high spenders and they were only 6th in winning rate. And in the years 1995-2000 they were among the lowest spenders and they also got very poor results. However, from years 2000-2005 and 2010-2015, they have managed to get very good results with low wages. Their best years were from 2000-2005 becoming 2nd in winning rate, while having one of the lowest spending.

## Expected Wins
<img width="656" alt="Screenshot 2023-11-15 at 11 47 00 AM" src="https://github.com/aparyavi/MLB_SpendingVsWinAnalysis/assets/62215723/6945a9b4-a38e-4b3c-9346-b8ba05b01861">

## Spending Efficiency
<img width="691" alt="Screenshot 2023-11-15 at 11 47 27 AM" src="https://github.com/aparyavi/MLB_SpendingVsWinAnalysis/assets/62215723/1120b003-43f7-4219-8c5f-eaf5d8bc101d">

One main difference between this plot and the previous plots in questions 2 and 3 is that in this plot we have the plot of spending efficiency which is very useful for interpretation and actually analyzing the data. In the other two questions, we saw the spending of each team vs their winning percentage which can be very useful in certain circumstances, but the efficiency is way more helpful in drawing conclusions by looking at the plot.

One fact for sure that we can say by analyzing the plots from both questions 2 and 3 we can say that money does play a huge role in the winning rate, but winning efficiency is also extremely important in the real world for teams to thrive by spending less and getting good results. We can see that teams such as Oakland have spent very efficiently, especially since the year 2000 based on the plots.
