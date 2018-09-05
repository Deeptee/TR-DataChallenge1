# Data Challenge I- Reuters News Classification & Summarization

## Introduction 

![alt text](https://github.com/katherine-shiqi/TR-DataChallenge1/blob/master/git_image/1.png)

As a multinational mass media and information firm, Thomson Reuters delivers quality news and latest stories to the world driven by intelligent technologies. With numerous news coming up each day, it’s resource-intensive to manually categorize them. As a leader in the information technology field, TR highly emphasizes Artificial Intelligence to harness the world’s content.

Thomson Reuters is challenging you today to leverage machine learning and natural language processing to build an algorithm that can automatically classify news into different categories. To earn more points, we encourage you to take the bonus problem to build a news headline summarization based on news body, which might require Deep Learning. 



## Problem 1: News Category Classification

### Problem1-Description

Given news headlines, build a model to classify them into one of the three news categories.  <br>

### Problem1-Data

For problem 1, please only use train1.csv and test1.csv under 1-Title_Classification folder for model building and result predicting. You are not allowed to use other training or testing dataset.

(I) Training dataset:  7916 rows, 3 columns

ID     -    unique identifier for each news <br>
TITLE  -    news headline<br>
TOPIC  -    one of the three topics (0/1/2) (our y label)

(II) Testing dataset:   3392 rows, 3 columns

ID     -    unique identifier for each news <br>
TITLE  -    news headline<br>
TOPIC  -    your predicted result (None)


## Problem 2: News Headline Summarization

### Problem2-Description

Given news bodies, build a model to generate their titles.  <br>

### Problem2-Data

For problem 2, please only use train2.csv and test2.csv under 2-Title_Summarization folder for model building and result predicting. You are not allowed to use other training or testing dataset.

(I) Training dataset:  17142 rows, 3 columns

ID     -    unique identifier for each news <br>
BODY   -    news content<br>
TITLE  -    news headline (our y label)

(II) Testing dataset:   1904 rows, 3 columns

ID     -    unique identifier for each news <br>
BODY   -    news content<br>
TITLE  -    your predicted summary (None)


## Submission 

(I) You can use one of the five coding languages (Python, R, Java, C, C++) for this competition. <br>

(II) Zip your code and predicted result file in the following format and send it to thomsonreuters_GHC@thomsonreuters.com with a title of firstname-lastname-challenge2 (such as 'bill-smith-challenge2') <br>

<li>For Problem 1, fill out the TOPIC column with your predicted result on test1.csv under folder 1-Title_Classification. Name this result CSV file firstname-lastname-result1.csv (such as bill-smith-result1.csv). Participants should assign the best topic for each headline, which means that only one predicted topic for each row is allowed. Example: bill-smith-result1.csv</li>
<br>

| ID      |                   TITLE                         | TOPIC |
| ------- | ------------------------------------------------| ----- |
| 0       | INDONESIAN COFFEE PRODUCTION MAY FALL THIS YEAR | 2     |
| 1       | INTERNATIONAL BUSINESS MACHINE CORP             | 0     |
| ...     | .........                                       | ...   |
<br>
<li>For Problem 1, put all your code into a folder named firstname-lastname-code1</li>

<li>For Problem 2, fill out the TITLE column with your predicted result on test2.csv under folder 2-Title_Summarization. Name this result CSV file firstname-lastname-result2.csv (such as bill-smith-result2.csv). Example: bill-smith-result2.csv</li>
<br>

| ID      |                   BODY                          |             TITLE                  |
| ------- | ------------------------------------------------| ---------------------------------- |
| 0       | Jill Considine, New York State................. | headline generated by my machine   |
| ...     | .........                                       | ................................   |
<br>
<li>For Problem 2, put all your code into a folder named firstname-lastname-code2</li>


## Evaluation and Score

(I) Problem 1 (100 points)<br>

You will get up to 100 points totally based on the accuracy rate of the submission CSV (firstname-lastname-result1.csv). The formula is listed below:

Accuracy rate =  (correctly predicted class / total testing class) × 100%

We will review your code to check plagiarism. If we find a high similarity between your code and other participants' code or code published online such as on Github, Kaggle, etc, you won't earn points. 

(II) Problem 2 (50 points)<br>

This is a bonus problem which is not required. You will get up to 50 points based on the code review and results review. Review committee at Thomson Reuters will determine the score for Problem 2.

If we find a high similarity between your code and other participants' code or code published online such as on Github, Kaggle, etc, you won't earn points. 


## Rules
<li>You agree not to transmit, duplicate, publish, redistribute or otherwise provide or make available the Competition Data to any party not participating in the Competition. </li>
<li>One person cannot participate with more than one user accounts.  You can’t resubmit and resend your result to our email. </li>
<li>Hand-labelling is not allowed on the testing dataset</li>
<li>Competition Timeline.  Start Date: Sep-10-2018.  End Date: Sep-15-2018 11:59 PM CST. </li>
<li>You agree to only use our provided training dataset for model building. Using other sources is prohibited.</li>
<li>Thomson Reuters reserves the right of final decision on the interpretation of these Terms and Conditions.</li>