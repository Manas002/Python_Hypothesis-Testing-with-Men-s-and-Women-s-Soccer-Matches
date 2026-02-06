# Python_Hypothesis-Testing-with-Men-s-and-Women-s-Soccer-Matches

<img width="1434" height="731" alt="image" src="https://github.com/user-attachments/assets/f9c178a0-6ce5-4ef7-aef8-454f3d41a5f4" />

Time to begin applying my statistical testing skills to historical data of men's and women's international soccer matches!
I'll work at a major online sports media company specializing in soccer analysis and reporting.
I will test the hypothesis to determine if women's international soccer matches result in more goals scored than men's.

While scoping this project, I acknowledge that the sport has changed a lot over the years, and performances likely vary a lot depending on the tournament, so I decide to limit the data used in the analysis to only official FIFA World Cup matches (not including qualifiers) since 2002-01-01.

I create two datasets containing the results of every official men's and women's international football match since the 19th century, which I scraped from a reliable online source. This data is stored in two CSV files: women_results.csv and men_results.csv.

**The question I are trying to determine the answer to is:**

**# Are more goals scored in women's international soccer matches than men's?**

I assume a 10% significance level, and use the following null and alternative hypotheses:

Ho : The mean number of goals scored in women's international soccer matches is the same as men's.

Ha : The mean number of goals scored in women's international soccer matches is greater than men's.

**The p-value and the result of the test must be stored in a dictionary called result_dict in the form:**

**result_dict = {"p_val": p_val, "result": result}**

where p_val is the p-value and result is either the string "fail to reject" or "reject", depending on the result of the test.

**How to approach the project :**

1. Exploratory data analysis

2. Filtering the data

3. Choosing the correct hypothesis test

4. Performing the hypothesis test

5. Interpreting the result of the hypothesis test


