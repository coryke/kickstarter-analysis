# Kickstarting with Excel

## Overview of Project

### Purpose
The following analysis in intended to provide actionable information regarding Kickstarter projects, especially projects in the "Theater" category or the "Plays" subcategory. The two primary analyses below evaluate the success to failure ratio of Kickstarter projects based on (1) date launched, and (2) goal amount set.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Kickstarter (hereafter: KS) projects appear to experience a range of success to failure ratios based on the month of the project creation date throughout the year. The following chart shows the n-count of projects in the "Theater" category by month delineated by outcome: success, failure, canceled.

[Imgur](https://i.imgur.com/k796JVN.png)

Canceled KS projects make up a small minority all Theater projects overall, and do not appear to be affected significantly by the month of launch date. Successful and failed KS Theater projects generally move parallel to one another with the successful projects being more numerous. There are two notable exceptions to this generality. First, there is a peak beginning in April or May and lasting through August where successful Theater projects make up a larger percentage of the overall Theater projects. That is, the ratio between successful and failed Theater KS projects swings towards more successful during the summer. Secondly, the converse phenomenon occurs in December. The ratio between successful and failed Theater KS projects is roughly one to one. There are an almost equal number of successful and failed projects at this time, and only at this time, of year.

### Analysis of Outcomes Based on Goals
KS projects in the "Plays" subcategory set a wide range of goals for these projects, from less than $1000 to significantly more than $50,000. The following chart shows the percentage of KS projects in the "Plays" subcategory by goal amount in $5000 increments, delineated by outcome: success, failure, canceled.

[Imgur](https://i.imgur.com/ju2weDl.png)

There were no canceled KS projects in the subcategory of plays for our analysis. All projects in the "Plays" subcategory that have reached the conclusion of their fundraising deadline (thus, currently live projects will not be found in this dataset), were either successful or failed. The data are less straightforward than the data based on launch date, above. The overall trend, though, is that the lower the goal amount for the KS project, the more likely the project succeeded. At the lower goal amounts (under $5000), successful projects acount for nearly 80% of all projects. At the highest goal amounts (over $50,000), successful projects make up a mere 10%. There is a notable exception for KS projects that set a fundraising goal between $35,000 and $45,000. Up to 60% of all "Plays" subcategory KS projects succeeded. This is contrary to the general downward trend based on funding goals.

### Challenges and Difficulties Encountered
There were no particular difficulties with this data set. The data were clean and there appear to be no significant outliers that would affect our analysis in these two categories.

## Results

### Launch Date Recommendations
My recommendations regarding a launch date for your upcoming KS project would be:  
1. The best time of year to launch a KS project appears to be in May or early summer.  
2. The worst time of year to launch a KS project is in December.  

### Goal Amount Recommendations
My recommendatsion regardin Goal amounts:  
Consider carefully the goal amount for the project. Goal amounts that account for 50% success or greater fall into two categories: less than $20,000, and $35,000 to $45,000.  

### Limitations
The limitations of our data include the following:  
1. The n-count of all KS projects in the "Plays" subcategory is a little only over 1000. More data would prove helpful in this analysis.  
2. The data come from all over the world. We have not included country of origin as a component in this analysis. It is unclear at this moment if there are trends or details in the data that would be clear from such analysis.
3. This analysis does not take into account the genre of the play or the notoriety of the play itself or the entity that launch the KS project since these data points were not available in the dataset.

### Further analysis
A more fine-grained analysis is possible regarding both launch date and goal amount if that would prove helpful. Also, as noted in the limitations section, further analysis might be possible based on the existing dataset. Additional data could be gathered to answer questions pertaining to the play or theater companies themselves.
