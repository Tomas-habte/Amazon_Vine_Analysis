# Amazon Vine Analysis  

## Overview
The purpose of this analysis is to determine if there is any bias toward favourable reviews from Amazon Vine members in a dataset. To conduct this analysis, we used PySpark, AWS RDS, and pgAdmin. 

## Results 
- The total number of Vine reviews were 2,252 and the total number of non-Vine reviews were 394,223. 
- There were 570 five star Vine reviews and 216,295 five star non-Vine reviews
- 25% of Vine reviews were 5 stars while 55% of non-Vine reviews were 5 stars 

| Total Paid Reviews = 2,252 | Total Unpaid Reviews = 394,223 |
| ------------- | ------------- |
| ![Paid total ](https://user-images.githubusercontent.com/111667387/209035592-5f0e2e46-bea6-42bd-ac71-558618d458ca.jpg)|![Unpaid total ](https://user-images.githubusercontent.com/111667387/209035621-c37363c7-5744-41bb-8680-135b20491b4b.jpg)|
|**Total Five Star Paid Reviews** | **Total Five Star Unpaid Reviews** |
|![Five star paid ](https://user-images.githubusercontent.com/111667387/209039321-be44cb8d-f6fc-4027-ba3a-c5e243b5a60b.jpg)|![Five star unpaid ](https://user-images.githubusercontent.com/111667387/209039350-9ee3045b-f682-4169-85fc-4c1a2022069e.jpg)|
| **Five Star Paid Percentage** | **Five Star Unpaid Percentage** |
|![Paid percentage ](https://user-images.githubusercontent.com/111667387/209039745-49d92105-7078-48ff-8cd9-2d2cb677f312.jpg)|![Unpaid percentage](https://user-images.githubusercontent.com/111667387/209039769-766ce2c2-f07b-4ca9-90e9-20b82058380e.jpg)|

## Summary
According to our analysis, there was no positivity bias for reviews in the Vine program for this dataset. This is because there was a significantly higher percentage of five star unpaid reviews (55%) than Vine reviews (25%). An additional analysis that could be conducted with this dataset to support our conclusion is to perform a sentiment analysis of the reviews. 
