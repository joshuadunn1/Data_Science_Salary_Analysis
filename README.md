# Australia Data Science Salary Analysis

## Introduction
As a beginner learning data science and coding, this is a project that I started following Ken Gee's Data Science From Scratch YouTube video. While I was following, I soon realised there was a lot of code and files that were deprecated. Because of this I had to research external resources to debugging the code, which I will outline further later. However, due to all the troubleshooting this turned out to be a great learning experience, gaining knowledge of the selenium package, XPath, and some HTML.
In this project I:
* Debugged depracated code to scrape 1000 job descriptions from Glassdoor using python and selenium.
* Data cleaning
* Exploratory analysis of our dataset to attain insights into the field of data science in Australia
* I am currently working on machine learning models to estimate salaries

## Results  
Results of data scraped from 1000 job ads on glassdoor.
### Job Counts  
I summarised the counts of various job postings in Australia found on glassdoor. I found that there was the most amount of job openings for data scientests, then data analysts, and then machine learning engineers. Though It is important to note that job openings was found by searching with the key words, data scientist so the website would most likely prioritise data scientist openings.  
I also found that employers were most looking for mid level employees, and data science related roles were most sought after by companies from the information techonology and finance sectors.  
Finally, I found that Sydney was the best place to be for anyone looking for a data science related role.  
![Image_1](https://github.com/joshuadunn1/ds_salary_proj/blob/main/Counts_figure_cropped.png)  
Here I summarised the salaries of data science related roles in Australia.  
I calculated the pearson's correlation of the relationship between 3 variables; age, average salary, and company rating to see how they correlate with eachother. The correlation matrix shows that, typically the older companies had a higher rating on glassdoor.  In terms of salary, the company rating did not have much infuence on the average salary, where there was only a small amount of positive correlation. However, here we saw that the age of the company was negatively correlated with average salary. This makes sense as people are probably more likely to work at older companies for a lower salary due to the established brand name associated with them. Conversly, new companies would have to offer higher rumeneration to draw experienced employees in to work for them.  
Unsuprisingly, data engineers and data scientest were the highest paid positions, where the average salary for those were $124,000 and $129,000, respectively. From those, employees from Sydney would be the highest paid compared to every other major city in Australia, followed by Brisbane and then Melbourne. I then found that by far technology related industries offered the highest salaries to data scientists.  
![Image_1\2](https://github.com/joshuadunn1/ds_salary_proj/blob/main/salary_figure_cropped.png)  

## Code, Resources, and Reference  

_Python Version:_   3.9.13  
**Packages:**   pandas, numpy, matplotlib, seaborn, selenium  
**For Web Framework Requirements:**   ```pip install -r requirements.txt```  
**Scraper Github:**  https://github.com/arapfaik/scraping-glassdoor-selenium  
**Scraper Article:**   https://towardsdatascience.com/selenium-tutorial-scraping-glassdoor-com-in-10-minutes-3d0915c6d905  
**Kenjee Github:**   https://github.com/PlayingNumbers/ds_salary_proj  
**KenJee Youtube Playlist:**  https://www.youtube.com/watch?v=MpF9HENQjDo&list=PL2zq7klxX5ASFejJj80ob9ZAnBHdz5O1t&index=1  
