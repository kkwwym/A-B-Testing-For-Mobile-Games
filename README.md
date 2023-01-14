# A/B Testing For Mobile Games

### Abstract
As players progress through the game they will encounter gates that force them to wait some time before they can progress or make an in-app purchase.
This sort of "time gate" is usually seen in free-to-play models, and normally contains ads that can be skipped using credits. In this case the player requires to submit a specific number of "Keys", which also can be skipped in exchange of in-game purchases. The game Cookie Cats is planning to move  "time gates" from level 30 to 40, but they don’t know by how much the user retention can be impacted by this decision.
In this project, I am going to analyze the result of an A/B test where the first gate in Cookie Cats was moved from level 30 to 40. In particular, analyze the impact on player retention.

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

### Here are some thoughts  that I would like to share....
I was really surprised when I first heard that the A/B test is based on Statistics a few years ago.  As a student who graduated from the Department of Statistics, I have never heard of this principle.
After conducting some deep research, I found out that the principle behind A/B test it is actually very easy to understand, just like solving different types of hypothesis test problems .
Starting from the establishment of the null hypothesis and the alternative hypothesis, controlling the significant level, calculating the p-value by using statistical software, confirming the sample size, and finally deciding whether we should accept or reject the null hypothesis.
It is easy to design how to apply A/B test if you already understand the principle. I think the real difficulty is what data metrics we have to determine. I realized that this domain knowledge is another important ability after having statistical knowledge and programming ability.  Therefore, I will explore different fields and topics whenever I do a new project. On the one hand, I can expose different domain knowledge and get to know new definitions of data metrics. Moreover, I will relentlessly remain curious about unknown fields.
In this case, even though I am a person who rarely plays games in my daily life, the biggest advantage of this is that how to explain this project in a way that an amateur can understand easily. Besides,  I can let  someone who is not interested in games like me be attracted as well. It is a good way to increase retention rate. Don‘t you think so?




# 
[**CHECK IT OUT NOW !!!** 👀 ](https://github.com/kkwwym/AB-Testing-For-Mobile-Games/blob/main/project.ipynb)
