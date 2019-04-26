# college-student-EDA
## An exploratory data analysis for US college student

### 1. US Earning Map
![US Earning Map](/figures/map-usa.png)

### 2. Student Debt between 2007 and 2017
Figure 2 shows the debt remaining in 2007 and 2017. Note that the debt in each surveying year reflects the median debt of the students 10 years after their graduation. We can see from the chart that there is a increasing trend in the debt from all states. Students from **South Dakota** secure the highest debts in both 2007 and 2017 with \$17,000 and \$25,000, respectively. On the other side, Wyoming students remain lowest debts after 10 years of graduation of in 2007 and 2017 with \$6,500 and \$8,500, respectively.

![Student Debt](/figures/student-debt.png)
*Figure 2: Student Debt in 2007 and 2017*

### 3. Student Debt across Regions
In the previous section, we have discussed the general trend in student debts across states. However, it is also captivating to explore insights among groups where the states in the same group are believed to share similar economic and social status. The US is divided into 4 geographical regions, West, Northeast, North Central, and South. The Figure~\ref{fig:debt-in-regions} illustrates sorted state's debts grouped by each region. Wyoming and Mississippi, as we have noticed earlier, have lowest student debts in their regions. Vermont has the highest student debt in **Northeast** followed by Rhode Island and Massachusetts. In the North Central, South Dakota tops the charts with roughly \$25,000 debts. On the other hand, its neighboring state -- North Dakota has lowest student debt of around \$12,000, which is pretty interesting.

![Student Debt Regions](/figures/debt-in-regions.png) 
*Figure 3: Debt among Regions*

### 4. SAT Median Scores
Figure 4 shows the  distributions of SAT score within US divisions. Note that these scores are median SAT scores collected from all colleges in the survey. In general, the median of median SAT scores are relatively similar of around 1,050. The **Pacific** and **New England** divisions have the highest interquartile ranges where their 75th percentile scores are greater than 1,200. For the rest of divisions, their upper outliers fall into 1,300-1,500 range and lower outliers are less than 900 with West North Central, East North Central, and East South Central.

![SAT Median Score](/figures/SAT.png)
*Figure 4: SAT median scores across divisions*

### 5. ACT Score Density Plot
Figure 5 shows the density plot of ACT scores over US regions. Most of the scores fall into 20-25 score range with North Central has highest density in this range. In addition, North Central also has plenty of students with ACT scores of less than 10, which is comparatively low compared to other regions in the nation. Looking at the right side of the plot, student applying to Northeast universities tend to perform better where they have highest portions of students with ACT scores of 30 or more. One plausible explanation might be the universities in Northeast are generally more competitive than others therefore they can attract some of the best students in nation to apply to.

![ACT Density](/figures/ACT-density.png)
*Figure 5. ACT Density Plot*

### 6. Correlation between Admission Rates and Earnings
There is a negative correlation between admission rates and earnings. The higher the admission rates are, the less money graduated student will make. This trend is most reflected in **Northeast** area.

![correlation](/figures/admission-rate-earnings.png)
*Figure 6: Correlation between Admission Rates and Earnings*

### 7. Earning among States
The dataset contains student salaries after their graduation. We calculate the median salaries of each state then use map data to plot the Figure~\ref{fig:student-earning}. The median salaries of US states range approximately from \$50,000 to \$90,000. Maryland has the highest median earnings of students with more than \$80,000 per year followed by New York, Massachusetts, and California with more than \$75,000 in median earnings. This result is not surprising because these states have some of the most selective universities in the US therefore the student can supposedly get highly-paid jobs after graduation. In addition, these states have some of the places with highest cost of living. As the result, employers often pay more to compensate for the costly expenses. In contrast, Nevada, Arkansas, and North Carolina are at the bottom with median salaries of less than \$60,000. The reasons maybe that the majority of the students from these state pursue low-demanding jobs, which possibly leads to more difficult job hunting. Again, cost of livings in these states may be complement factor when it comes to deciding the salary rates.

![State Earnings](/figures/state-earnings.png)
*Figure 7: Student Earnings within States*


### 8. Southearn States Earnings
The plot shows earning data plotted with points in 5 Southern States including Tennesse, Arkansas, Alabama, Mississippi and Louisiana. We can see that most-paid graduates come from medical schools, which is unsprising. The least-paid students graduted from Beauty School.
![Southern State Earnings](/figures/southern-earning.png)
*Figure 8: Graduate Salaries in Southern State*

### 9. Unemployment Rates after Graduation
**Montana** has the highest unemployment rate (>5\%). This may due to the students pursuing low-demanding majors.
![Unemployment Rates](/figures/state-unemployment.png)
