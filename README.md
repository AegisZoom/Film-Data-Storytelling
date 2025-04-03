# Data Visualisation Presentation: Are movies decreasing in quality? 

## MATH2270: Data Visualisation and Communication

### Grade: 92.5%

## Introduction

This repository contains my work for the third and final assignment of MATH2270 in my Graduate Diploma of Data Science. The assessment was worth 40% of the final grade, 
and required that I develop a 10-slide presentation that used data visualisations to tell a story. There was significant emphasis placed on exploring creative topics 
(otherwise grades would be lowered), so I decided to rigourously assess the popular opinion that ***"movies used to be so much better!"*** using aggregate film ratings from IMDb and Rotten Tomatoes.

A total of three datasets were used, and they are referenced below. The second reference actually features two datasets from the same source. Only one was uploaded to this repository due to file size constraints.

- rakkesharv. (2022). *IMDb 5000+ Movies & Multiple Genres Dataset* [Dataset]. Kaggle. https://www.kaggle.com/datasets/rakkesharv/imdb-5000-movies-multiple-genres-dataset
- Villa, A. [andrezaza]. (2023). *Massive Rotten Tomatoes Movies & Reviews* [Dataset]. Kaggle. https://www.kaggle.com/datasets/andrezaza/clapper-massive-rotten-tomatoes-movies-and-reviews?select=rotten_tomatoes_movies.csv

*These datasets were shared without modification, and applied under the **Creative Commons CC0 1.0 Universal License (Public Domain)**, which can be accessed in the following link: https://creativecommons.org/publicdomain/zero/1.0/*

## Skills Used

- 💾 **Programming**:
Used R 📉 as the programming language for the RMarkdown file, with RStudio as the IDE, and the Readr, Stringr, Dplyr, Tidyr, Lubridate, GGplot2, Plotly, and Magrittr libraries for development.
- 📈 **Data Analysis**:
Performed background statistical measurements to gauge aggregate film trends with time dependence. Performed significant multivariate analysis to identify trends in the data relating to the topic.
- 📊 **Data Visualisation**:
Constructed interactive scatter plots that allowed users to customise filters and reveal information on films of interest. Designed the visualisations to constructively develop understanding of the topic
and its misconceptions by highlighting subtle trends in film ratings. Designed the visualisations to avoid overwhelming the user with too much information.
- 🧼 **Data Cleaning**:
Corrected datatypes of many variables between datasets, identified outliers using univariate and multivariate techniques, dealt with missing values, applied data transformations, processed unit conversions, and merged/separated variables and data frames. Addressed errors and compatibility issues resulting from these merges.
- 📧 **Data Retrieval**:
Browsed online (especially Kaggle) for high-quality datasets of IMDb and Rotten Tomatoes reviews that covered a large and diverse array of films. Converted data files to appropriate formats for cleaning and exploration.
- 📐 **Problem-Solving**:
Needed to use a wide variety of techniques to implement interactivity in data visualisations. Frequently needed to use creative strategies to solve bugs and issues stemming from interactive elements.
- 🔍 **Debugging/Attention to Detail**:
Devoted extensive time to eliminating errors so the visualisations would operate as designed. Exercised thorough investigation of the datasets to identify multivariate trends (notably review polarity) that explained changes in movie reviews across the decades.
- 📝 **Written Communication**:
Submitted a 10-slide presentation designed to immerse users in a captivating narrative that would challenge strong and popular opinions on the film industry. Specifically designed the presentation with a pace that would allow users to digest the information thoughtfully.
- ⏰ **Time Management**:
Organised weekly schedules and deadlines for individual milestones with leeway for unexpected obstacles both related to and outside of the assessment.
- 🔬 **Research**:
Extensively investigated techniques and solutions online to add advanced features and interactivity to data visualisations. Researched and scrutinised public datasets to meet the needs of the project.

## Presentation Access

The presentation can be accessed online by clicking the following link:

[https://rpubs.com/JPLosebrick/1241329](https://rpubs.com/JPLosebrick/1241329)

The page should look like this when you first open it:

![Example](https://github.com/AegisZoom/Film-Data-Storytelling/blob/main/Presentation_Slide.PNG)

⚠️ **Note**: I used the pseudonym J.P. Losebrick when I published this presentation online to protect my identity.

## Files and Specifications

*Data Visualisation and Communication Submission.Rmd* is the original file that was linked to RPubs to publish my presentation online. All visualisations can be reproduced using the code and datasets referenced. There is one limitation however: although *IMDb_All_Genres_etf_clean1.csv* and *rotten_tomatoes_movies.csv* were uploaded
to this repository, *rotten_tomatoes_movie_reviews.csv* was unable to be uploaded due to exceeeding a file size of 40MB. As a result, to run the code you will
need to download the missing csv file from the relevant link at the top of the page. Finally, *Presentation_Slide.png* is just for the screenshot of the presentation.
