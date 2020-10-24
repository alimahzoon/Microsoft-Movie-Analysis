## Microsoft-Movie-Analysis

Group Members: Ali Mahzoon, and Stephen Enke

---
### Business Problem
Microsoft wants to get in on the fun by deciding to create a new movie studio, but the problem is they don’t know anything about creating movies. We are here to help them out by exploring data, sharing our findings and actionable insights, and providing key recommendations.

---

### Questions:
1. What are the most profitable companies in movie industry from 2015 to 2020?
2. What relationship, if any, is there between popularity among movies and profitability?
3. What are the most Profitable genres in the market?
4. What are the most popular genres around the world?
5. Is there a strong positive correlation between popular genres and profitable genres?
6. What markets are most profitable based on origin of production?
7. what markets outside of the U.S.A are more Profitable?
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
In our dataset there were a lot of movies from 1915 to 2020 with a large number of companies, So we decided to narrow it down to 2015 to 2020. now we can find out Our most profitable companies in a more comprehensive way.

![PComp_profit](https://github.com/alimahzoon/Microsoft-Movie-Analysis/blob/Ali-wip/IMGS/PComp_Profit_Bar.png "Profitable Companies")

---

Based on our hypothesis popularity is an important factor among movies that every company should take into consideration. However, calculation says something different.

 ![Corr_pcomp_pop](https://github.com/alimahzoon/Microsoft-Movie-Analysis/blob/Ali-wip/IMGS/Profit%2BPop_Scatter.png "Correlation between most profitable companies and popularity of movies")

 ---

 Genres also play a vital role in movie industry. By all respect to all genres, and based on our at-hand data, most popular genres are visualized like this.

 ![Popular_genres](https://github.com/alimahzoon/Microsoft-Movie-Analysis/blob/Ali-wip/IMGS/I2.png "Popular Genres")

---
Based on the summation of profit of each genre we can calculate the most profitable genres. And again these Statistics are based on our at-hand data.

![Popular_genres](https://github.com/alimahzoon/Microsoft-Movie-Analysis/blob/Ali-wip/IMGS/I1.png "Profitable Genres")

---
We dug a little deeper and find out about the strong positive correlation between popularity and profitability in genres. (the exact number is .92)

![Popular_genres](https://github.com/alimahzoon/Microsoft-Movie-Analysis/blob/Ali-wip/IMGS/I3.png "Correlation between Profit and popularity")

---
Market is another major factor for this business being successful. Domestic, foreign, and worldwide markets all are important for all companies around the world. Profitability of global markets by country from 2015 to 2020 is categorized like the following picture, as we can see U.S.A has the largest share among all other countries.

![Popular_genres](https://github.com/alimahzoon/Microsoft-Movie-Analysis/blob/Ali-wip/IMGS/44.png "Profitability of global markets by country from 2015 to 2020")


To have a better understanding of other shares all over the world let's visualize the above plot as follows.

![Popular_genres](https://github.com/alimahzoon/Microsoft-Movie-Analysis/blob/Ali-wip/IMGS/55.png "Profitability of global markets by country from 2015 to 2020 except USA")


As we can see China is a large market. Moreover, Taiwan, and Hong Kong are within the top markets as well, so let's combine them under the column 'Greater China'.

![Popular_genres](https://github.com/alimahzoon/Microsoft-Movie-Analysis/blob/Ali-wip/IMGS/66.png "Profitability of global markets by country from 2015 to 2020 except USA ")

This is the most profitable country after the countries that their native language is English. so observing its profit during the last three decades must be interesting.

 ![Popular_genres](https://github.com/alimahzoon/Microsoft-Movie-Analysis/blob/Ali-wip/IMGS/77.png "Profitability of global markets by country from 2015 to 2020 except USA ")

 ---
 And last but not least, let's study the most profitable month in the year to realize what periods of the year are more profitable to release a movie.

![Popular_genres](https://github.com/alimahzoon/Microsoft-Movie-Analysis/blob/Ali-wip/IMGS/MY.png "Profitability of global markets by country from 2015 to 2020 except USA ")

---
### recommendations
Based on our findings, we all now know that most profitable companies work on specific genres. For example universal studio and its action genres, on the other hand we know the most popular genre and its strong correlation with profit will make it easier for Microsoft to choose a genre and start collaborating and cooperating with an appropriate company and release the movie at the start of summer to 4th of July or at December before Christmas.
