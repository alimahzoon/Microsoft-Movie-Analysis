## Microsoft-Movie-Analysis

Group Members: Ali Mahzoon, and Stephen Enke

---
### Business Problem
Microsoft wants to get in on the movie madness with their own studio. The problem is they don’t know anything about creating movies. We are here to help them out by exploring data, sharing our findings and actionable insights, and providing key recommendations.

---

### Questions:
1. What are the most profitable companies in movie industry from 2015 to 2020?
2. What relationship, if any, is there between popularity among movies and profitability?
3. What are the most profitable genres in the market?
4. What are the most popular genres around the world?
5. Is there a strong positive correlation between popular genres and profitable genres?
6. What markets are most profitable based on origin of production?
7. What markets outside of the U.S.A are more Profitable?
8. What months of the year are more profitable?

---

### Dataset and Approach
* Dataset and Tools:
   * Data gathered via API from TMDB website
   * TMDB library
* Approach:
   * Feature Engineering
   * Data visualized by Seaborn and Matplotlib
---

### Findings
In our dataset there were a lot of movies from 1915 to 2020 with a large number of companies, So we decided to narrow it down to 2015 to 2020. Now we can view our  most profitable companies in a meaningful way.

![PComp_profit](https://github.com/alimahzoon/Microsoft-Movie-Analysis/blob/Ali-wip/IMGS/PComp_Profit_Bar.png "Profitable Companies")

---

Our hypothesis was that popularity is an important factor for movie success that every company should take into consideration. However, we only calculated a weak relationship between profit and popularity of production company films.

 ![Corr_pcomp_pop](https://github.com/alimahzoon/Microsoft-Movie-Analysis/blob/Ali-wip/IMGS/Profit%2BPop_Scatter.png "Correlation between most profitable companies and popularity of movies")

 ---

 Genres also play a vital role in the movie industry. Based on our at-hand data, most popular genres are visualized like this.

 ![Popular_genres](https://github.com/alimahzoon/Microsoft-Movie-Analysis/blob/Ali-wip/IMGS/I2.png "Popular Genres")

---
Based on the summation of profit of each genre we can calculated the most profitable genres. And again these statistics are based on our at-hand data.

![Popular_genres](https://github.com/alimahzoon/Microsoft-Movie-Analysis/blob/Ali-wip/IMGS/I1.png "Profitable Genres")

---
We dug a little deeper and found a strong positive correlation between popularity and profitability in genres. (the exact number is R^2 = .92)

![Popular_genres](https://github.com/alimahzoon/Microsoft-Movie-Analysis/blob/Ali-wip/IMGS/I3.png "Correlation between Profit and popularity")

---
Market is another major factor for the success of this endeavor. Domestic and foreign markets is an important consideration in an increasingly global civilization. Profitability of global markets by country from 2015 to 2020 is displayed in the following picture. We see U.S.A has the largest share of profitability compared to all other countries.

![Popular_genres](https://github.com/alimahzoon/Microsoft-Movie-Analysis/blob/Ali-wip/IMGS/44.png "Profitability of global markets by country from 2015 to 2020")


To have a better understanding of shares all over the world let's look a plot excluding the U.S.A.

![Popular_genres](https://github.com/alimahzoon/Microsoft-Movie-Analysis/blob/Ali-wip/IMGS/55.png "Profitability of global markets by country from 2015 to 2020 except USA")


As we can see, China is a large market. Moreover, Taiwan, and Hong Kong are within the top markets as well, so let's combine them under the column 'Greater China'.

![Popular_genres](https://github.com/alimahzoon/Microsoft-Movie-Analysis/blob/Ali-wip/IMGS/66.png "Profitability of global markets by country from 2015 to 2020 except USA ")

This is the most profitable market after the English-speaking countries. Considering the rapid growth of these three nations, observing its profit during the last three decades could be interesting.

 ![Popular_genres](https://github.com/alimahzoon/Microsoft-Movie-Analysis/blob/Ali-wip/IMGS/77.png "Profitability of global markets by country from 2015 to 2020 except USA ")

 ---
 And last but not least, let's study the profitability of months to see what time periods are most profitable for movie releases in the last decade from 2010 to 2019.

![Popular_genres](https://github.com/alimahzoon/Microsoft-Movie-Analysis/blob/Ali-wip/IMGS/MY.png "Profitability of global markets by country from 2015 to 2020 except USA ")

---
### Recommendations
We recommend that Microsfot leverages key studio partnerships specializing in action and light-hearted animation to produce Holiday-timed releases using Microsoft’s in-house Xbox Game Studios content to create films using our unique selling position.

---
We dug a little deeper and found a strong positive correlation between popularity and profitability in genres. (the exact number is R^2 = .92)

![Popular_genres](https://github.com/alimahzoon/Microsoft-Movie-Analysis/blob/Ali-wip/IMGS/I3.png "Correlation between Profit and popularity")

---
Market is another major factor for the success of this endeavor. Domestic and foreign markets is an important consideration in an increasingly global civilization. Profitability of global markets by country from 2015 to 2020 is displayed in the following picture. We see U.S.A has the largest share of profitability compared to all other countries.

![Popular_genres](https://github.com/alimahzoon/Microsoft-Movie-Analysis/blob/Ali-wip/IMGS/44.png "Profitability of global markets by country from 2015 to 2020")


To have a better understanding of shares all over the world let's look a plot excluding the U.S.A.

![Popular_genres](https://github.com/alimahzoon/Microsoft-Movie-Analysis/blob/Ali-wip/IMGS/55.png "Profitability of global markets by country from 2015 to 2020 except USA")


As we can see, China is a large market. Moreover, Taiwan, and Hong Kong are within the top markets as well, so let's combine them under the column 'Greater China'.

![Popular_genres](https://github.com/alimahzoon/Microsoft-Movie-Analysis/blob/Ali-wip/IMGS/66.png "Profitability of global markets by country from 2015 to 2020 except USA ")

This is the most profitable market after the English-speaking countries. Considering the rapid growth of these three nations, observing its profit during the last three decades could be interesting.

 ![Popular_genres](https://github.com/alimahzoon/Microsoft-Movie-Analysis/blob/Ali-wip/IMGS/77.png "Profitability of global markets by country from 2015 to 2020 except USA ")

 ---
 And last but not least, let's study the profitability of months to see what time periods are most profitable for movie releases.

![Popular_genres](https://github.com/alimahzoon/Microsoft-Movie-Analysis/blob/Ali-wip/IMGS/MY.png "Profitability of global markets by country from 2015 to 2020 except USA ")

---
### Recommendations
We recommend that Microsfot leverages key studio partnerships specializing in action and light-hearted animation to produce Holiday-timed releases using Microsoft’s in-house Xbox Game Studios content to create films using our unique selling position.
