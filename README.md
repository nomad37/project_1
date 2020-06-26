# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1


### Problem Statement
College Board is a testing company known for administering the SAT, a standardized college-entry exam. The ACT, another standardized test produced by a different company, are the direct competitors. In 2017 and 2018, the ACT had a higher participation rate in more states compared to the SAT. I have been tasked to analyze data from 2017 and 2018 in order to make recommendation to College Board for the purpose of improving state-wide participation levels.

### Executive Summary
I started out by cleaning some of the data before merging them the 2017 ACT data and the 2017 SAT data. I just needed to fix some issues with different capital letters and deleting some extra rows. After merging the two data sets on state, i renamed the subject colums by adding a prefix to denote the test that the colum belonged to and the year. I did the same with the 2018 SAT data and the 2018 ACT data before merging all the data together. After that, I looked into the correlations for each variable, but didn't find anything useful. I then looked at how much the participation level had changed from 2017 to 2018 and found out that Illinois, Colorado, and Rhode Island had a huge leap in participation levels. I started to search online for a reason as to why that might be.

### Data Dictionary

|Column|Type|Description|
|---|---|---|
|state|object|name of the state|
|act17_participation|int|ACT participation percentage in 2017|
|act17_english |float| ACT english score in 2017|
|act17_math |float | ACT math score in 2017|
|act17_reading |float | ACT reading score in 2017|
|act17_science |float | ACT science score in 2017|
|act17_composite |float |ACT composite score in 2017|
|sat17_participation |int |SAT participation percentage in 2017|
|sat17_ebrw|int| SAT evidence-based reading and writing score in 2017|
|sat17_math|int| SAT math score|
|sat17_total|int| SAT total score |
|act18_participation|int| SAT participation in 2018|
|act18_composite|float| ACT composite score in 2018|
|sat18_participation|int| ACT participation in 2018 |
|sat18_ebrw|int| SAT evidence-based readning and writing score in 2018|
|sat18_math|int| SAT math score in 2018|
|sat18_total|int| SAT total score in 2018|

---

### Conclusions and Recomendations

States that have high participation rates in either the SAt or the ACT are likely to have contracts with the company that administers that test. A contract with the state's board of education essentially shuts out your competitor because your test becomes mandatory in high schools. It's the test that every high schooler will need to prepare whereas the ACT is optional because only one of the tests is required for entrance into a four-year college. The recoommenation is to negotiate more of these contracts successfully. Another recommendation is to sell test prep to the younger high school students. The more money and time spent on preparing for your test, they more likely they will take the test when the time comes.

