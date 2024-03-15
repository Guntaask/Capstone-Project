# Capstone-Project

  
# ✨ Predicting Small Businesses Success & Failure ✨
---
Understanding the Reasons Behind Small Business Failures and Leveraging Machine Learning for Enhanced Success

<center><img src="https://localiq.com/wp-content/uploads/2020/11/small-business-saturday-marketing-ideas-1.png" alt="memes" width="600" /></center>

---

## 📝 Table of Contents 📝 <a class="anchor" id="toc"></a>
- [Project Overview](#overview)
    - [Introduction](#intro)
    - [Story Behind](#story)
    - [Problem Statement](#problem)
    - [Objectives](#objective)
    - [Potential Impact](#impact)
- [Dataset](#dataset) 
    - [Data Description](#desc)
    - [Data Dictionary](#data-dict)
    - [Data Source](#data-source)
    - [Data Coverage](#data-coverage)
- [Project Roadmap](#roadmap)
    - [Data Cleaning](#cleaning)
    - [Modelling](#mod)
 - [Conclusion](#conclusion)


---

## 👀 Project Overview 👀 <a class="anchor" id="overview"></a>

### Introduction 📋 <a class="anchor" id="intro"></a>
Starting a business isn't easy. You've got a lot of costs to think about, like how much you're spending upfront, the ongoing expenses, and any loans you might need. Success means different things, but it often boils down to growing, making money, keeping customers happy, and managing your finances well.

But the most important thing for any business is just staying open. That's what everyone wants—to know if a business will keep its doors open or shut them for good.

This topic matters to businesses who want to stick around and to customers who want reliable services. It's also a big deal in finance because lenders need to decide if they should give out loans, and sometimes they have to explain why they say yes or no.

So, the big question we're asking here is: Can we figure out if a business will keep going or not? And what are the main things that tell us if it will?


<center><img width=600 src="https://i0.wp.com/warmandtoteonline.blog/wp-content/uploads/2022/10/time-management.png?w=1080&ssl=1" alt="memes" width="200"/></center>

### Problem Statement 😩 <a class="anchor" id="problem"></a>

So, the big question we're asking here is: 

Can we figure out if a business will keep going or not? 
And what are the main features that tell us if it will?

Understanding the Reasons Behind Small Business Failures and Leveraging Machine Learning for Enhanced Success




### Objectives 🎯 <a class="anchor" id="objective"></a>
Analyze factors contributing to business success and failure
Develop predictive models to forecast business outcomes.
Identify key indicators for success and failure.
Optimize strategies for small business success using machine learning techniques.Provide actionable insights and recommendations for business

### Potential Impact 💥 <a class="anchor" id="impact"></a>

 By accurately predicting the likelihood of a business closing or remaining open, our findings have the potential to revolutionize decision-making processes for entrepreneurs, investors, and stakeholders alike.

With this predictive insight, entrepreneurs can make more informed decisions when launching or managing their businesses, allocating resources strategically, and mitigating risks effectively. Investors can leverage this information to make smarter investment choices, minimizing their exposure to potential losses and maximizing returns on investment. Furthermore, stakeholders in the business ecosystem, including policymakers and industry analysts, can use these insights to foster a more resilient and sustainable business environment.

Ultimately, the potential impact of our data science project lies in its ability to empower individuals and organizations with the knowledge they need to navigate the complexities of the business landscape, driving innovation, fostering growth, and contributing to economic prosperity.

[Back to top](#toc)

---
## 🔠 Dataset 🔢 <a class="anchor" id="dataset"></a>

### Dataset Description 🔤 <a class="anchor" id="desc"></a>

<img src="https://s3-media0.fl.yelpcdn.com/assets/public/960x225_dataset@2x.yji-6d323fc75cb1bec53d1c9851d45e204c.png">

In this project, we're going to use the Yelp Dataset, which has a ton of info about local businesses in the USA and Canada. It's got:

<li>Reviews: There are 6,990,280 reviews in the dataset. These reviews contain valuable feedback and ratings from customers who have visited various businesses.</li>

<li>Businesses: The dataset includes information on 150,346 businesses. These businesses span different industries and categories, providing a diverse representation of establishments.</li>

<li>Pictures: There are 200,100 pictures included in the dataset. These images may offer visual insights into the appearance and offerings of the businesses listed.</li>

<li>Metropolitan Areas: The dataset covers 11 metropolitan areas, indicating geographical diversity and representation across different urban regions.</li>

<li>Tips: Users have provided 908,915 tips in total. These tips can offer additional insights, recommendations, and experiences shared by users about specific businesses.</li>

<li>Users: The dataset includes tips from 1,987,897 unique users. This indicates significant user engagement and interaction with the platform.</li>

<li>Business Attributes: There are over 1.2 million business attributes available in the dataset. These attributes cover various aspects such as hours of operation, parking availability, and ambience, providing detailed information about each business.</li>

<li>Check-ins: The dataset includes aggregated check-in data over time for each of the 131,930 businesses listed. Check-in data can provide insights into foot traffic and popularity trends for individual businesses.</li>

Overall, these features highlight the richness and breadth of the Yelp Dataset, offering a wealth of information for analysis and research purposes.

### Data Dictionary 🔖 <a class="anchor" id="data-dict"></a>

Sure, here's a simplified version of the data dictionary for the Yelp Dataset:

<b>Businesses:</b>

Business ID: Unique identifier for each business.<br>
Name: Name of the business.<br>
Address: Address of the business.<br>
City: The city where the business is located.<br>
State: State where the business is located.<br>
Postal Code: Postal code of the business.<br>
Latitude: Latitude coordinates of the business location.<br>
Longitude: Longitude coordinate of the business location.<br>
Stars: Average rating of the business.<br>
Review Count: Number of reviews the business has received.<br>
Is Open: Indicates if the business is currently open (1 for open, 0 for closed).<br>
Attributes: Additional attributes or features of the business.<br>
Categories: Categories or types of services offered by the business.<br>
Hours: Operating hours of the business.<br>

<img src="https://miro.medium.com/v2/resize:fit:1083/0*QXNZVCSHE41DxWAG.png">

<b>Reviews:</b>

Review ID: Unique identifier for each review.<br>
User ID: Unique identifier for the user who wrote the review.<br>
Business ID: Unique identifier for the business being reviewed.<br>
Stars: Rating given by the user (1 to 5 stars).<br>
Text: The text content of the review.<br>
Date: The date when the review was written.<br>

<b>Users:</b>

User ID: Unique identifier for each user. <br>
Name: User's name.<br>
Review Count: Number of reviews written by the user.<br>
Average Stars: Average rating given by the user.<br>
Yelper Since: Date when the user joined Yelp.<br>

<b>Tips:</b>

User ID: Unique identifier for the user who wrote the tip.<br>
Business ID: Unique identifier for the business the tip is about.<br>
Text: The text content of the tip.<br>
Date: The date when the tip was written.<br>

### Data Source  <a class="anchor" id="data-source"></a>
Dataset can be found on Yelp
(https://www.yelp.com/dataset)

### Data Coverage 📆 <a class="anchor" id="data-coverage"></a>
    
- Geospatial Coverage 
    - North America (Canada and the United States)

[Back to top](#toc)

---

## 🏃 Project Roadmap / Framework 🏃 <a class="anchor" id="roadmap"></a>

### ✅ Data Cleaning / Preprocessing 🛁 <a class="anchor" id="cleaning"></a>  

<b>Exploding Nested Attributes:</b>

We began by examining columns containing nested attributes, such as the 'attributes' column, which contained JSON-like strings representing various business features.
To unpack these nested attributes, we employed Python's json.loads() function to convert the JSON-like strings into dictionaries.
Utilizing pandas' pd.json_normalize() function, we then expanded these dictionaries into separate columns, enabling a more granular analysis of each business feature.<br>

<b>Engineering Categorical Variables:</b>

Upon identifying categorical variables within our dataset, such as 'NoiseLevel', we recognized the need to convert these qualitative descriptors into numerical representations for analysis.
To achieve this, we crafted a mapping dictionary to translate each categorical value to its corresponding numerical counterpart. For instance, 'quiet' was mapped to 0, 'average' to 1, 'loud' to 2, and 'very_loud' to 3.
Leveraging pandas' functionality, we applied this mapping to the 'NoiseLevel' variable, ensuring a seamless transition from qualitative descriptors to quantitative values, facilitating further analysis and modeling.



### 💬 Modelling 💬 <a class="anchor" id="mod"></a>

<b>Logistic Regression:</b>

Logistic Regression can serve as the foundational model for binary classification, where it can learn to predict the probability of a business being open or closed. It can dynamically adjust class weights or employ regularization techniques to ensure robust performance, particularly in handling imbalanced classes.

<b>Decision Tree:</b>

Decision trees can be instrumental in providing interpretable insights into the underlying data patterns. By recursively partitioning the feature space, they will uncover significant predictors of business openness. Techniques such as pruning will be applied to prevent overfitting, ensuring the generalization of the model to unseen data while maintaining transparency in decision-making.

<b>XGBoost:</b>

XGBoost plays a pivotal role as a sophisticated ensemble learning algorithm, capable of capturing complex relationships within the data. It can be extensively fine-tuned, optimizing hyperparameters like scale_pos_weight to effectively handle class imbalance. Through iterative training, XGBoost will strive to achieve superior predictive accuracy and resilience to imbalanced data distributions.


<b>Handling Imbalance in 'is_open' Target Variable:</b>

For imbalanced classification of 'is_open', where one class (e.g., open businesses) may be significantly more prevalent than the other (e.g., closed businesses), several strategies can be applied:
<b>Resampling Techniques:</b> Use techniques like oversampling (e.g., SMOTE), undersampling, or a combination of both to balance the class distribution.<br>
<b>Algorithmic Approaches: </b>Algorithms like XGBoost, decision trees, and random forests often provide parameters to adjust class weights or explicitly handle class imbalance.<br>
<b>Ensemble Methods:</b> Ensemble techniques like bagging and boosting can help improve the model's performance on imbalanced data by combining predictions from multiple models trained on balanced subsets.<br>
<b>Evaluation Metrics: </b>Instead of accuracy, consider using evaluation metrics like precision, recall, F1-score, or area under the ROC curve (ROC-AUC) to assess the model's performance, especially in the context of class imbalance.<br>


### 💬 Conclusion 💬 <a class="anchor" id="conclusion"></a>

<img src="https://i.pinimg.com/736x/fa/66/3f/fa663ff7492b725b04a1f7d9f25192d9.jpg">

In conclusion, our data science project has shed light on a crucial question for entrepreneurs: the likelihood of a business closing or remaining operational. Leveraging machine learning techniques, we've identified key features that contribute to this prediction, providing valuable insights for business owners and investors.

In essence, our project paves the way for informed decision-making in the entrepreneurial landscape, arming businesses with the knowledge they need to navigate uncertainties and thrive in a competitive market environment.

[Back to top](#toc)

---
