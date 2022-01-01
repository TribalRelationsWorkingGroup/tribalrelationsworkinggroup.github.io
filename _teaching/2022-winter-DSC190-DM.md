---
title: "2022-Winter-DSC190-Introduction to Data Mining"
collection: teaching
type: "Undergraduate Class"
permalink: /teaching/2022-winter-DSC190-DM
venue: "HDSI, UCSD"
date: 2022-01-04
location: "La Jolla, CA"
---

**Class Time**: Tuesdays and Thursdays, 8AM to 9:50AM.  **Room**: ~~PETER 104~~ [https://ucsd.zoom.us/j/97017584161](https://ucsd.zoom.us/j/97017584161).  **Piazza**: [piazza.com/ucsd/winter2022/dsc190a00](https://piazza.com/ucsd/winter2022/dsc190a00)

Online Lecturing
======

Due to the COVID-19 Omicron Variant, in the first two weeks, this course will be delivered over Zoom: [https://ucsd.zoom.us/j/97017584161](https://ucsd.zoom.us/j/97017584161)


Overview
======

This course mainly focuses on introducing current methods and models that are useful in analyzing and mining real-world data. It will cover frequent pattern mining, regression & classification, clustering, and representation learning. No previous background in machine learning is required, but all participants should be comfortable with programming, and with basic optimization and linear algebra. 

There is no textbook required, but here are some recommended readings:
- The classical data mining textbook "[Data Mining: Concepts and Techniques](https://books.google.com/books/about/Data_Mining_Concepts_and_Techniques.html?id=pQws07tdpjoC&source=kp_book_description)" by Jiawei Han et al.
- The classical data mining/machine learning book "[Pattern Recognition and Machine Learning](https://books.google.com/books/about/Pattern_Recognition_and_Machine_Learning.html?id=HL4HrgEACAAJ&source=kp_book_description)" by Christopher M. Bishop
- The new "[Dive into Deep Learning](https://d2l.ai/)" book by Aston Zhang et al.


Prerequisites
======

Math, Stats, and Coding: `(CSE 12 or DSC 40B) and (CSE 15L or DSC 80) and (CSE 103 or ECE 109 or MATH 181A or ECON 120A or MATH 183)`

TAs and Tutors
======

- **Teaching Assistants**: Dheeraj Mekala (dmekala AT eng.ucsd.edu)

Office Hours
======

- Jingbo Shang
    - Office Hour: Wednesdays, 10 to 11 AM
    - Zoom link: [https://ucsd.zoom.us/my/jshang](https://ucsd.zoom.us/my/jshang)
- Dheeraj Mekala
    - Office Hour: TBD
    - Zoom link: TBD
- Zilong Wang
    - Office Hour: TBD
    - Zoom link: TBD

Note: all times are in **Pacific Time**.

Grading
======

- Homework: 8% each. Your lowest (of four) homework grades is dropped (or one homework can be skipped).
- Midterm: 26%.
- Data Mining Challenge: 25%.
- Project: 25%.
- You should complete all work individually, except for the Project.
- Late submissions are NOT accepted.

Lecture Schedule
======

**Recording Note**: Please download the recording video for the full length. Dropbox website will only show you the first one hour.

**HW Note**: All HWs due before the lecture time 9:30 AM PT in the morning. 

Week | Date        | Topic & Slides                                                  | Events
1    | 01/04 (Tue) | [Introduction: Data Types, Tasks, and Evaluations](https://www.dropbox.com/sh/qza6t2wudbeuv6c/AABDFig0I6pJl3-PEp0wc0TFa?dl=0) | HW1 out
1    | 01/06 (Thu) | Supervised - Least-Squares Regression and Logistic Regression |
2    | 01/11 (Tue) | Supervised - Overfitting and Regularization | HW1 Due, HW2 out
2    | 01/13 (Thu) | Supervised - Support Vector Machine |
3    | 01/18 (Tue) | Supervised - Naive Bayes and Decision Tree |
3    | 01/20 (Thu) | Supervised - Ensemble Learning: Bagging and Boosting | 
4    | 01/25 (Tue) | Cluster Analysis - K-Means Clustering & its Variants | HW2 Due, HW3 out
4    | 01/27 (Thu) | Cluster Analysis - "Soft" Clustering: Gaussian Mixture |
5    | 02/01 (Tue) | Cluster Analysis - Density-based Clustering: DBSCAN |
5    | 02/03 (Thu) | Cluster Analysis - Principle Component Analysis | DM Challenge out
6    | 02/08 (Tue) | Pattern Analysis - Frequent Pattern and Association Rules |
6    | 02/10 (Thu) | Midterm (24 hours on this date) |
7    | 02/15 (Tue) | Recommender System - Collaborative Filtering | HW3 Due, HW4 out
7    | 02/17 (Thu) | Recommender System - Latent Factor Models |
8    | 02/22 (Tue) | Text Mining - Zipf's Law, Bags-of-words, and TF-IDF |
8    | 02/24 (Thu) | Text Mining - Advanced Text Representations | DM Challenge due
9    | 03/01 (Tue) | Network Mining - Small-Worlds & Random Graph Models | 
9    | 03/03 (Thu) | Network Mining - HITS, PageRank, Personalized PageRank and Node Embedding |
10   | 03/08 (Tue) | Sequence Mining - Sliding Windows and Autoregression |
10   | 03/10 (Thu) | Text Data as Sequence - Named Entity Recognition | HW4 Due

Homework (24%)
======

Your lowest (of four) homework grades is dropped (or one homework can be skipped).

- **HW1: Concepts and Evaluations (8%).** This homework mainly focuses on the data mining concepts and how to evaluate different tasks.
- **HW2: Regression and Classification (8%).** This homework mainly focuses on regression and classification tasks.
- **HW3: Cluster and Pattern Analysis (8%).** This homework mainly focuses on clustering methods and frequent pattern mining methods.
- **HW4: Applications (8%).** This homework mainly focuses on recommender system, text mining, and network mining.

Midterm (26%)
======

It is an open-book, take-home exam, which covers all lectures given before the Midterm. Most of the questions will be open-ended. Some of them might be slightly more difficult than homework. You will have 24 hours to complete the midterm, which is expected for about 2 hours.

- **Start**: Feb 11, 9:30 AM PT
- **End**: Feb 12, 9:30 AM PT
- Midterm problems download: TBD
- Please **make your submissions on Gradescope**.

Data Mining Challenge (25%)
======

It is a individual-based data mining competition with quantitative evaluation. The challenge runs **from Feb 3 0:00:01 AM to Feb 24 4:59:59 PM PT**. Note that the time displayed on Kaggle is in UTC, not PT.

- Challenge Statement, Dataset, and Details: TBD
- Kaggle challenge link: TBD

Project (25%)
======

Instructions for both choices will be available soon. Project ****due on Sunday, Mar 13 EOD****.

Here is a quick overview:
- **Choice 1: Team-Based Open-Ended Project**
    - 1 to 4 members per team. More members, higher expectation.
    - Define your own research problem and justify its importance
    - Come up with your hypothesis and find some datasets for verification
    - Design your own models or try a large variety of existing models
    - Write a 4 to 8 pages report (research-paper like)
    - Submit your codes
    - Up to 5% bonus for working demos/apps towards the total course grade.
- **Choice 2: Individual-Based Deep Dive into Data Mining Methods**
    - Implement a few models learned from this course from scratch.
    - Skeleton codes will be provided soon. Your work is more like "filling in blanks" following the TODOs outlined in the Jupyter-Notebook.
    - Each model has a point associated with it. 6 points required. Points for each model is available at the end of the instruction slides.
    - Write a report (pages based on points) describing your interesting findings.
    - Up to 5% bonus towards the total course grade. Roughly 1 point, 1%.
