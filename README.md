# A/B Testing For Mobile Games

### Abstract
As players progress through the game they will encounter gates that force them to wait some time before they can progress or make an in-app purchase.
This sort of “time gate” is usually seen in free-to-play models, and normally contains ads that can be skipped using credits. In this case the player requires to submit a specific number of ‘Keys’, which also can be skipped in exchange of in-game purchases. The game Cookie Cats is planning to move  "time gates" from level 30 to 40, but they don’t know by how much the user retention can be impacted by this decision.
In this project, I am going to analyze the result of an A/B test where the first gate in Cookie Cats was moved from level 30 to level 40. In particular, analyze the impact on player retention.

### Walkthroughs
* Define Business Use Case 
* Define the Metrics
* Set the Hypothesis
* Data Preparation & Cleaning
* Exploratory Data Analysis
* Chi-squared test for A/B testing


### Methods
* A/B test
* Chi-squared test

### Results and Discussion
1-day retention
According to chi-squared test, there is no significant difference in retention rates between the two versions at the 5% significance level. We do not have enough evidence to reject null hypothesis that retention rate is the same for the two versions.
7-day retention
According to chi-squared test, there is a significant difference in retention rates at the 1% significance level. We reject null hypothesis and accept our alternative hypothesis that 7-day retention rate is higher when the gate is at level 30.

# 
[**CHECK IT OUT NOW !!!** 👀 ](https://github.com/kkwwym/AB-Testing-For-Mobile-Games/blob/main/project.ipynb)
