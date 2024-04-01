# Amazon Fine Food Reviews Analysis
![](https://storage.googleapis.com/kaggle-datasets-images/18/18/default-backgrounds/dataset-cover.jpg)

Data Source: https://www.kaggle.com/snap/amazon-fine-food-reviews <be>

The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon. The data span a period of more than 10 years, including all ~500,000 reviews up to October 2012. Reviews include product and user information, ratings, and a plain text review. It also includes reviews from all other Amazon categories.

<table border="0">
 <tr>
   <td>
  Data includes:
  
  - Reviews from Oct 1999 - Oct 2012
  - 568,454 reviews
  - 256,059 users
  - 74,258 products
  - 260 users with > 50 reviews
</td>
 <td><img src="https://nycdsa-blog-files.s3.us-east-2.amazonaws.com/2016/04/AmazonReview-768x483.png"  width="600" height="250""></td>
</table>



Attribute Information:

1. Id
2. ProductId - unique identifier for the product
3. UserId - unqiue identifier for the user
4. ProfileName
5. HelpfulnessNumerator - number of users who found the review helpful
6. HelpfulnessDenominator - number of users who indicated whether they found the review helpful or not
7. Score - rating between 1 and 5
8. Time - timestamp for the review
9. Summary - brief summary of the review
10. Text - text of the review



### Objective:
> Given a review, determine whether the review is positive (Rating of 4 or 5) or negative (rating of 1 or 2).

