![image](https://github.com/MrKiasu/DSI_39-Project_3/assets/142147568/52b1471c-30a2-4f61-be75-10fdfb8970c4)# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 3: A self-help tool for couples to understand attachment style

### Problem Statement

Comparing between 2018-2022 and 2013-2017, there has been a 4.6% drop in annual average marriage registered. In the last 10 years, average crude divorce rate is at 1.9 per thousand population. It was also reported that more couples, especially those recently married, are getting divorce. 
The recent trends in declining number of marriages and earliers divorces are a cause for concern. Communication is cited as one common reason for divorce. A strong and lasting relationship requires healthy communications. And the way we communication with one another is influenced by our attachment styles. 

The objective of our project is to develop a tool which users can use to recognise and understand both theirs and their partner's attachment style. Attachment styles can be flexible and evolve over time with self-awareness and personal growth. Recognizing each other's attachment style and working on developing communication strategies can be beneficial for building healthier and more satisfying relationships.

---

### Data Used

Source: Reddit 
* [`Anxious Attachment Subreddit`](https://www.reddit.com/r/AnxiousAttachment/): A subreddit for individuals with anxious attachment style to learn more about the style, share experiences and find support.
* [`Avoidant Attachment Subreddit`](https://www.reddit.com/r/AvoidantAttachment/): A subreddit about and for individuals with avoidant atatchment style.

---

### Data Dictionary

|Feature|Type|Description|
|---|---|---|
|**class**|*integer*|Class 0: Avoidant<br>Class 1: Anxious|
|**title**|*string*|Title of the subreddit post|

---

### Notebook description

* [`01_scrapping`](/code/01_scrapping.ipynb): Scrapping data from the respective subreddits using PRAW
* [`02_clean_eda_modelling`](/code/02_clean_eda_modelling.ipynb): Data preprocessing, exploring and visualizing the data and modeling. 
* [`03_Modelling_final`](/code/03_Modelling_final.ipynb): Data modelling, conclusions and recommendations

---

### Conclusion

- Developed an app that can classify individuals and their partner as either anxious or avoidant attachment style with 0.9 accuracy.
- Recommendations are provided based on the attachment style.

---

### Recommendations


---