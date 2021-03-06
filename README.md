# Google Store Customer segmentation

## What is this?
  *This is a case study prepared using [Kaggle Google Analytics Customer Reviews](https://www.kaggle.com/competitions/ga-customer-revenue-prediction/data) database.*
## What I can find here?
  This project show cases a variety of **data science** routine tasks on a dataset of nearly **1 million** records. Namely, you will find the following:
   * Data cleaning, merging, transforming, pre-processing.
   * Nesting/unnesting JSON queries.
   * Missing value analysis.
   * Various bar charts, scatterplots, etc.
   * Variable selection using LASSO Regression.
   * Customer clustering using K-means clustering.
   * Time series analysis and sales forecast.
    
# Where I can find this?
Here's the description of each file and folder in the project:

* Analysis folder: This colder contains the data analysis markdown and html files. Each RMarkdonw file is knitted to an html document which shows the code chunks that are used in the analysis along with the explanations and visulations. Please feel free to re-run the .Rmd files if you want. All files should be run in a reasonable amount of time but the assessment.Rmd and customerProfiles.Rmd can be heavier as they have too many modeling and visulizations in them. Here are the files
  + [prepareData.html](https://htmlpreview.github.io/?https://github.com/sajjaddehnoei/Customer-Segmentation-with-Google-Analytics-Data/blob/main/Analysis/prepareData.html): data cleaning and processing.
  + [assessment.html](https://htmlpreview.github.io/?https://github.com/sajjaddehnoei/Customer-Segmentation-with-Google-Analytics-Data/blob/main/Analysis/assessment.html): my personal assessment and visulization before starting the analysis
  + [consumerProfiles.html](https://htmlpreview.github.io/?https://github.com/sajjaddehnoei/Customer-Segmentation-with-Google-Analytics-Data/blob/main/Analysis/consumerProfiles.html).: customer clustering using LASSO Regression and K-means clustering
  + [salesTrend.html](https://htmlpreview.github.io/?https://github.com/sajjaddehnoei/Customer-Segmentation-with-Google-Analytics-Data/blob/main/Analysis/salesTrends.html): sales trends analysis and forecast using time series analysis
* Data folder: includes data as downloaded from kaggle
* Images folder: includes images that are used in the presentation
* Presentation: a powerpoint presentation about the data, customer groups, and sales and trends.
* MLSEAnalysis.Rproj: the R project tha tcontains everything in this case study.
* .gitignore: files that are to be ignored when version controling using github.
* caseStudy.html: the description of the case as received from the team and found on kaggle.
