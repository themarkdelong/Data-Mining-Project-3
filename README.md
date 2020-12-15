# College Scorecard Data

This data comes from the U.S. Government's College Scorecard Database. While sources such as IPEDs (Integrated Postsecondary Education Data System, from the U.S. Department of Education's National Center for Education Statistics) are explicit about when the data is from, the Scorecard data does not offer a specific timeframe for this data. This dataset was created in 2015 with its metadata last updated in September 2020. Personal knowledge leads me to believe the institution-level data we'll use below is at least a few years old.

Source: <a href="https://catalog.data.gov/dataset/college-scorecard">Data.gov's College Scorecard Data</a>

![Instititions by Type](https://github.com/themarkdelong/Data-Mining-Project-3/blob/main/Charts/1%20-%20HE%20Institions%20by%20Type.png)

The graphic above (interactive in the full report) shows the breakdown of institutions by type (public/private), HBCU or not, gender served (co-ed, male, female), in-person/distance, and highest degree offered. Of note, there are no single-gender institutions among the publics, which are largely PWIs (predominately white institutions) and in-person. The largest number of public institutions award an associate's degree or less, while among privates, doctoral institutions are the majority. Among for-profit institutions there are no HBCUs or single-gender institutions.<br><br>Given the static nature, a few pie charts are included below to show the individual types of colleges in the dataset.

![Institions by Type-Pie](https://github.com/themarkdelong/Data-Mining-Project-3/blob/main/Charts/2%20-%20Colleges%20by%20Type.png) 
![Institions by Type-Pie2](https://github.com/themarkdelong/Data-Mining-Project-3/blob/main/Charts/2a%20-%20by%20type.png)
![Institions by Instruction](https://github.com/themarkdelong/Data-Mining-Project-3/blob/main/Charts/2b%20-%20by%20instruction.png)
![Institions by HBCU](https://github.com/themarkdelong/Data-Mining-Project-3/blob/main/Charts/2c%20-%20by%20HBCU.png)
![Institions by Gender](https://github.com/themarkdelong/Data-Mining-Project-3/blob/main/Charts/2d%20-%20by%20gender.png)

# Who is attending college?
First, let's take a look at enrollment - overall numbers plus gender, racial, and standardized test scores for schools in our dataset. Then, we'll look at costs and admit and graduation rates.
![Undergraduate Enrollment](https://github.com/themarkdelong/Data-Mining-Project-3/blob/main/Charts/3%20-%20Undergraduate%20Enrollment.png)

This doesn't give much detail, but we do see that most institutions enroll fewer than 20,000 students (perhaps closer to 10,000 or fewer) with only a few spiking near or above 80,000.

Let's look at the gender and racial breakdowns across all colleges in our dataset.
![Gender Breakdown](https://github.com/themarkdelong/Data-Mining-Project-3/blob/main/Charts/4%20-%20Gender%20Breakdown.png)
![Racial Breakdown](https://github.com/themarkdelong/Data-Mining-Project-3/blob/main/Charts/5%20-%20Racial%20Breakdown.png)

# Next up, who gets into college? A look at rates of admission
![Admit Rates by Type](https://github.com/themarkdelong/Data-Mining-Project-3/blob/main/Charts/6%20-%20Admit%20Rates%20by%20Type.png)
![Admit Rates by Multi-type](https://github.com/themarkdelong/Data-Mining-Project-3/blob/main/Charts/7%20-%20Admit%20Rates%20by%20Multitype.png)

What is the range of standardized test scores submitted by applicants to 4-year institutions?
![Test Scores](https://github.com/themarkdelong/Data-Mining-Project-3/blob/main/Charts/8%20-%20Test%20Scores.png)

# Now to look at college costs
We'll look at overall tuition and fees of 4-year institutions, then their net price (overall and by family income levels).
![Cost of Attendance](https://github.com/themarkdelong/Data-Mining-Project-3/blob/main/Charts/9%20-%20Average%20Cost%20of%20Attendance.png)

Let's examine the average net price and net price by income brackets for 4-year colleges.
![Net Price](https://github.com/themarkdelong/Data-Mining-Project-3/blob/main/Charts/10%20-%20Net%20Price%20by%20Income%20Band.png)

A negative net price indicates that the average grant or scholarship aid exceeded the cost of attendance, per the <a href="https://collegescorecard.ed.gov/data/glossary/">U.S. Department of Education</a>.

# To understand success, we turn to graduation rates
Admit rates are great to know, but how do students succeed when in college? Let's turn to graduation rates. From here on, we'll just look at 4-year institutions (highest degree of bachelor's or doctoral). The typical measure is a 6-year completion rate (or 150% of the expected time to finish a 4-year degree). First, we'll take a quick look at the average 6- and 8-year rates before diving deeper into the 6-year data.

Average 6- and 8-year graduation rates: 51.14%, 51.44%

As we can see, there's not much improvement between the 6- and 8-year rates, so we'll focus on the 6-year rate going forward. The data set also provides a breakdown of that rate by race, which we'll examine later. For now, let's see how completion rates vary by state. (This graphic is interactive in the full report.)
![Grad Rate by State](https://github.com/themarkdelong/Data-Mining-Project-3/blob/main/Charts/11%20-%20Avg%20Grad%20Rate%20by%20State.png)

Let's look at how the 6-year grad rate varies by type of institution.
![Grad Rate by Type](https://github.com/themarkdelong/Data-Mining-Project-3/blob/main/Charts/12%20-%20Grad%20Rates%20by%20Type.png)

Women's colleges have the highest 6-year graduation rates of all types of colleges listed here, while men's colleges and HBCUs are among the lowest. How do HBCU women's colleges compare to their PWI sister schools?
![Women's College Grad Rates](https://github.com/themarkdelong/Data-Mining-Project-3/blob/main/Charts/13%20-%20Women's%20College%20Grad%20Rates.png)

Interesting, so while PWI women's colleges have a grad rate near 62%, their HBCU sister schools are just below 54%. Taking a look at the data, there are only 2 HBCU women's colleges, Spelman and Bennett Colleges, and their graduation rates differ drasticly. Spelman, which sits in downtown Atlanta and shares a campus with Morehouse (a men's college), Clark Atlanta (co-ed), and the Morehouse School of Medicine (graduate-only), has a 75% 6-year graduation rate. That's compared to Bennett's 32% rate in Greensboro, North Carolina.<br><br>Now let's take a look at men's colleges and see how their graduation rates compare for HBCUs and PWIs.
![Men's College Grad Rates](https://github.com/themarkdelong/Data-Mining-Project-3/blob/main/Charts/14%20-%20Men's%20College%20Grad%20Rates.png)

So HBCU men's colleges graduate students at higher rates than PWI men's colleges. An interesting twist to the women's colleges data above. As Morehouse College is the only HBCU men's college, there is clearly power in being a "Morehouse Man."

Let's look at racial differences in graduation rate across different types of 4-year colleges.
![Grad Rates by Race](https://github.com/themarkdelong/Data-Mining-Project-3/blob/main/Charts/15%20-%20Grad%20Rates%20by%20Race.png)

# Black Students Have the Lowest Graduation Rates of all Races.<br>What Institutions Outperform Their Peers Here?
Let's look at institutions with higher-than average graduation rates for Black students, starting with all four-year institutions, then looking to HBCUs.

- 969 institutions are in the top 50% of 6-year graduation rates for Black students, with at least a 38.63% grad rate.
- At 819 institutions, the Black grad rate is above the national average for all students (51.14%).
- 484 institutions are among the top 25% of 6-year graduation rates for Black students, with a rate of at least 56.8%.
- There are 87 institutions with a 6-year graduation rates for Black students at 90% or higher.

Let's look at those 87 institutions. (This graphic is interactive in the full report.)
![Black Grad Rates Over 90](https://github.com/themarkdelong/Data-Mining-Project-3/blob/main/Charts/16%20-%20Grad%20Rates%20Over%2090.png)

While there may be some issues with the data as reported to the U.S. Dept. of Education, these institutions should be applauded for their apparent efforts and colleges that fall behind in average graduation rates should consult with them for ideas to help boost their numbers, especially for Black students who drop out at higher rates than other minorities.

How do these institutions compare on their black and overall graduation rates? The chart below shows the difference.
![Difference in Black and Overall Grad Rates](https://github.com/themarkdelong/Data-Mining-Project-3/blob/main/Charts/17%20-%20Difference%20in%20Black%20and%20Overall%20Grad%20Rates.png)

Now let's zoom in on HBCUs with higher than average graduation rates for Black students. (This graphic is interactive in the full report.)
![HBCU Grad Rates](https://github.com/themarkdelong/Data-Mining-Project-3/blob/main/Charts/18%20-%20Top%20HBCU%20Grad%20Rate.png)

Seen above, 27 HBCUs provide higher-than-average graduation rates for Black students; 9 of them perform at or above the overall average graduation rate for all undergraduate students. Again, other institutions should seek their advice on how to best help Black students in their quest for a college education.

# Before we close out, where does GW sit?
![GW Grad Rates](https://github.com/themarkdelong/Data-Mining-Project-3/blob/main/Charts/19%20-%20GW%20Grad%20Rates.png)

The bars above show GW's overall, white, and black 6-year graduation rates, with the salmon line on each bar representing the national average for each group (that average is also the basis for the deltas on the right). Fortunately, GW does better than average in all categories, with its graduation rate for Black students less than 6 points behind the average in this Scorecard data.

# In closing, how is all of this related?
First, a look at a correlation matrix for test scores, admit rate, retention, completion, and price.
![Correlation Matrix](https://github.com/themarkdelong/Data-Mining-Project-3/blob/main/Charts/20%20-%20Sample%20Correlation%20Matrix.png)

There's a lot of data in the correlation matrix for the entire dataset (which is too big to show here) - some more relevant and some stronger than others. At a quick glance, here are a few standout pairings:
- There is a strong positive correlation between SAT and ACT scores - perhaps not surprising, as there are correlation tables to help translate scores between the two and predict results.
- Net price has a few strong correlations. First is net price and control (1=public, 2=private, 3=for-profit) - another unsurprising result as public schools are typically more subsidized by state taxpayer dollars and charged with a mission to offer an education to the public (especially in-state residents).
- Next is a strong correlation between net price and both primary and highest degree awarded (2=associate's, 3=bachelor's, 4=doctoral). Given the data we saw earlier, this is not surprising. Associate-granting institutions are often public and provide a more affordable option for a student's first two years of college than 4-year institutions. The doctoral institutions often carry more prestige and recognition and, perhaps because of that, can command a higher price for an education.
- The final strong positive correlation is between net price and loan recipients. Another not surprising find, but a good reminder when considering college costs.

Finally, two negative correlations stand out to me: first, that of both Pell and loan recipients to test scores, meaning that an institution that enrolls more Pell Grant or loan recipients is more likely to report lower standardized test scores. Less advantaged students not only lack access to expensive test prep but also suffer from the bias of standardized tests to white males.

One large area of negative correlation is with the admit rate and most measures (noticeably test scores, completion rates, and costs), which is why that matrix is included above. From this, we see that each of these factors are negatively correlated to the admit rate - which means that a school with higher test scores, retention rates, graduation rates, and cost is more likely to be more selective in their admissions. Test scores are strongly correlated to each other (not surprisingly) and retention and graduation rates, indicated that students who score higher on standardized tests are more likely to retain and graduate within 6 years; similiarly, the net cost increases at these institutions too.

Will this hold true across racial completion rates? Pulling in those columns highlights the racial bais of standardized testing, with a school's higher scores being tied to higher completion rates primarily among Whites, with Blacks 10 percentage points behind and other racial minorities even further behind. It also shows that the 6-year graduation rate for Whites is fairly strongly correlated to the rates for other minorities - with Blacks, Hispanics, 2+, and Unknowns all with correlations in the 60-70th percentile. There is a weak correlation overall with net price, but note that it is strongest when compared to the completion rate for White students - more than double that of American Indians or Native Hawaiians).

# Conclusions and Learning Outcomes
This project gave me greater insight into the higher education landscape in the United States. Contrary to popular opinion, the average (and vast majority) of colleges admit far more students than they decline, with an average admit rate just over 67%. That often gets lost in our obsession over highly selective institutions. It also served as a reminder of the breadth and depth of educational offerings and the diversity of students served. Soon whites will no longer be a majority of college students in the country. While the students served by higher education are getting more diverse, it will be more important than ever to continually consider the cost to attend college (both published "cost of attendance" and "net price" paid by families), keeping a higher education within reach for as many families as possible.

Just as important as affordability is college completion. Colleges and those who support students must do more to help students graduate on-time or nearly on-time. Especially for those students who borrow money to earn their degree, it's vitally important to complete the degree to get an earnings boost (and help pay back those loans). As Black students have the lowest graduation rate, instititions should focus on helping them attain a bachelor's degree (and thus boosting their own completion numbers).

The Scorecard dataset and IPEDS have much more data available on college admissions, retention, and completion - all of which is well worth further exploration to improve the college-going experience for the next wave of diverse students.
