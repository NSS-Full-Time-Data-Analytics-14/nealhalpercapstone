# USDA_production

## Canva presentation
Link: [https://www.canva.com/design/DAGZen89edQ/epyagQ9bqRyFCcXAO3sxdQ/edit?utm_content=DAGZen89edQ&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton]

## Tableau Dashboard
Link: [https://public.tableau.com/authoring/DistributionofProduceOperationsintheUnitedStates/Story1#1]

## Table of Contents
* [Canva Presentation](#canva-presentation)
* [Tableau Dashboard](#tableau-dashboard)
* [Motivation](#motivation)
* [Questions](#questions)
* [Problems and Hurdles](#problems-and-hurdles)
* [Technologies Used](#technologies-used)
* [Data Sources](#data-sources)
* [Conclusion](#conclusion)

## Motivation

I chose this project because my career path before attending Nashville Software School was in
agriculture. Specifically, I worked at small farms/companies that grew fruits, vegetables and specialty
crops. Since all of the companies I worked with interacted with the USDA, I wanted to leverage their 
data colllection to gain insight on the scale at which the majority of the produce in the United States is grown. 

## Questions 

1) For all farm commodity sales, which income brackets sell the most goods? 
2) Are the farms bringing in the most money also the largest farms? 
3) What organization types are reperesented in production of fruit and vegetables?
4) How many fruit and vegetable farms are corporate, partnerships, research/institution based, or family & individual owned? 
5) How do different organization types rank in terms of land operated? Has this changed over the past 10 years?
6) Are there certain states in the USA that are dominated by corporate, partnership, or family & individually owned fruit and vegetable farms?

## Problems and Hurdles

## Technologies Used

1) Python/Pandas - used for data exploration, cleaning, exporting to tableau and generating visualizations
2) Tableau - used for creating State level maps to show the distribution of farms and states with the most farms per 100 sq miles 
3) Canva - project presentation

## Data Sources
https://quickstats.nass.usda.gov/ </br>

1) Census (Program) -> Economics (Sector) -> Income (Group) -> Commodity Totals (Commodity) -> State (Geographic Level) </br>
2) Census (Program) -> Demographics (Sector) -> Vegetable Totals (Commodity) -> State (Geographic Level) </br>
3) Census (Program) -> Demographics (Sector) -> Berry Totals (Commodity) -> State (Geographic Level) </br>
4) Census (Program) -> Demographics (Sector) -> Citrus Totals (Commodity) -> State (Geographic Level) </br>

https://en.wikipedia.org/wiki/List_of_U.S._states_and_territories_by_area </br>

## Conclusion

For all farm commoditities, the bulk of the market share is held by large farms with above $500,000 in income. However, between the years 2012-2022 there is trend of growth for smaller farms. Compared to partnerships or family/individually owned farms, corporate producers are experiencing more growth in terms of acreage in production, the number of corporate operations and total sales. The average number of family and individual farms per 100 square miles by state is higher in most of the United States when compared to the same parameters for corporate farms. However, the disparity in production acreage suggests that while the number of corporate farms is smaller they operate more land.   
