# Optimizing Customer Conversion Rates in E-Commerce

**Problem:**
Customers who successfully converted from all people who visited the company website were 15.5%, with an average conversion of 14.45 per month. Shop Ease as one of the e-commerce platforms still wants to maintain and improve this conversion rate. However, the company still does not have a deep understanding of the factors that affect customer conversion. Without an understanding of conversions and predictive tools, the company risks missing opportunities to optimize marketing strategies and facing a potential decline in customer conversions.

**Goal:**
1. Identify factors that affect customer conversion
2. Increase company sales
3. Anticipate further decline in sales

**Dataset:**
* Numerical Features: 
1. Administrative:= Number of administrative pages visited by users during the session
2. Administrative Duration:= The total duration spent by the user on the administrative page during the session (in seconds)
3. Informational:= The number of informative pages visited by the user during the session
4. Informational Duration:= The total duration spent by the user on the informative page during the session (in seconds)
5. Product Related:= The number of product-related pages visited by the user during the session
6. Product Related Duration:= The total duration spent by the user on product-related pages during the session (in seconds)
7. Bounce Rates:= The percentage of visitors who enter the page and immediately leave the website (“bounce”) during the session
8. Exit Rates:= The percentage of exiting the website after visiting a particular page during a session
9. Page Value:= The average value of the web pages that users visit before completing an e-commerce transaction
* Categorical Features:
1. Special Day: = An indicator that shows the proximity of site visit times to certain special days (e.g., Mother's Day, Valentine's Day) where sessions are more likely to complete with transactions
2. Month:= The month of the visit
3. Operating Systems:= The operating system used by the user
4. Browser:= The web browser used by the user
5. Region:= User's geographical area
6. Traffic Type:= The type of traffic that brings users to the website
7. Visitor Type:= Type of visitor, whether a new visitor or a returning visitor.
8. Weekend:= An indicator of whether the visit occurred on a weekend or not (True if weekend, False if not)
* Label: Revenue:= Class label, an indicator of whether the user generates revenue (True if yes, False if no)

**Business Question:**
1. So what is the company's conversion trend?
2. What influences visitor conversion to generate revenue?
3. How can Machine Learning increase the company's conversion rate?
4. What can be done to increase the company's conversion rate?

**Insight and Recommendation:**
1. Identify factors that affect customer conversion
> Based on the results of identifying factors that affect customer conversion, the 5 factors that have the most significant impact are administrative, product related, page value, month, and product related duration. Thus, we need to prioritize focusing on these 5 factors to increase the conversion rate.
2. Increase company sales
> Insight:
  * Page Value, Product Related, and Administrative features significantly increase visitors' chances of making a purchase.
  * Returning visitors dominate website traffic with low visitor conversion low visitor conversion indicates that some visitors are happy browsing products, but the products they find do not match their preferences.
  * There is an increase in conversions in May and November, as well as on weekends.
> Recommendation:
  * Focus on increasing Page Value and Product Related by providing relevant and engaging content to drive conversions.
    1. Product description optimization
    2. Utilize company data (visitor activity) to implement product recommendations according to each visitor's preferences.
  * Take advantage of weekends, months approaching May and November (months leading up to holidays or year-end) to optimize marketing.
3. Anticipate further decline in sales
