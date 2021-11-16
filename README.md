# UniversitiesRankingsRationality
This project is to help under stand Why top 30 universities are top 30? By using Quantitative analysis on rankings of universities by using Python.

---
## Description
First, we manually loaded the page https://www.usnews.com/best-colleges/rankings/national-universities in a browser. This is a search page that loads more results when scrolling. We noticed that many of the lower ranked universities were missing information, so we decided to only look at the top 150 universities.

Now we can scape data about each college. The pages are mostly in the same format, so we can just look for the target description text and the field is usually in the next sibling. We describe these simple targets that we can get from various pages in a dictionary. The academics page has graphs and is harder to scrape, so we scrape these seperately along with the college name.

Then, data visulizations and find out the reasons. 

We found that great universities with high overall scores have high six-year gradutation rates, high tuition, low student-faculty ratios, low acceptance rate, and small classes. We also found out that prohibiting alcohol on campus has little effect on a school's ranking.

In future work, it could be interesting to look at a lot of additional factors for the universities such as student clubs, percentages for different majors, results after graduation, fraternities, greek life, and demographics. Additionally, it would be nice to find a large sample of student reviews of the universities, in which we could persue text analysis.
