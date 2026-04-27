---
# Do not edit the text between these lines!
layout: default
---

# This is a big header

<!-- This is a comment. Below, you'll see code for inserting an image. To make this image appear, update <custom-path>. To add an image, save it inside the imgs folder of this repository. -->
<img src="<custom-path>/static/imgs/logo.png" alt="Image of Comp110 rainbow logo. "  width="500"/>

## This is a small header

This is basic paragraph text.
# Quiz Reviews in Comp 110!

I want to analyze the "qz_effective" column from the data to see whether or not it supports my idea.

First, I will use my helper functions to isolate the "qz_effective" column. I use the head function to make sure my functions are working as intended. I use read_csv_rows to collect the data from my class. Columnar sorts the data into distinct columns, and select narrows down want columns I want to potentially draw data from. Count sorts the data from the "qz-effective_data" column based on the response number.

Next, I will produce a countplot, histplot, and boxplot with seaborn. The convert_columns_to_int function turns the columns we want to analyze into a format that can be graphed.

<img src="ex09qz_effective/static/imgs/countplot.png" alt="This graph contains variables count and qz_effective, with the highest count at qz_effective value 6."
width="500">

<img src="ex09qz_effective/static/imgs/histplot.png" alt="This graph contains variables count and qz_effective, with the highest count at qz_effective value 6."
width="500">

<img src="ex09qz_effective/static/imgs/boxplot.png" alt="This graph contains variables qz_effective and difficulty, with qz_effective values generally high regardless of difficulty."
width="500">

The graphs suggest that reviews prior to the quizzes are helpful for students. The countplot and histplot show the largest number of students answered option 6, which is close to the "strongly agree" response. On the boxplot, students who found the class very difficult found the quiz reviews to be somewhat effective, on average, although the responses varied greatly. Overall, most students regardless of how they answered for difficulty level found the quiz reviews more effective than not. My idea is supported by the data. I recommend implementing one lesson plan before each quiz that is dedicated to review. This means the curriculum will have to be condensed slightly to accomodate these dedicated review days. However, I think this trade-off is worth it. Also, the idea could be refined by having less quiz days throughout the semester so there would in turn need to be fewer review days and the curriculum would not need to be as condensed.