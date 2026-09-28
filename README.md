# Netflix Dataset Exploratory Data Analysis (EDA)

This repository contains an Exploratory Data Analysis (EDA) investigating **Netflix movies and TV shows released from the 1960s to 2020**. The analysis focuses on understanding content trends, growth over time, and geographic distributions.

## 🚀 Project Structure

The data analysis is divided into the following core sections:

1. **Loading Dataset & Requirements**: Importing Python packages and reading the source data.
2. **Data Cleansing**: Checking for missing values, handling null data, and parsing date fields.
3. **Exploratory Data Analysis (EDA)**: Utilizing Pandas, Matplotlib, and Seaborn to uncover trends.
4. **Observations**: A deep dive into what the data tells us about Netflix's content strategy.

## 🛠️ Prerequisites & Installation
To run this project locally, ensure you have Python installed, then install the necessary dependencies:

```bash
pip install pandas numpy matplotlib seaborn
```

>>📊 Outputs & Step-by-Step Explanations

### 1. Dataset Overview & Structure
* **What this step does**: Checks the shape of the data ,verify/understand column names, and data types (`df.info()`) which are used in this dataset.
* **Output Explanation**: this data set contains 8807-rows and 12 columns and has 825.8kb memory
*                         and contains some missing values in director name ,country and cast details of film....
*                         and i replace that with unknown string 
 
### 2. Content Type Distribution (Movies vs. TV Shows)
* **What this step does**: Compares the total number of Movies versus TV Shows available on the platform.
* **Output Explanation**: total 6131 movies and 2676 tv shows present in data set ..


### 3. Release Trends Over Time (1960s – 2020)
* **What this step does**: Tracks the volume of content released across different decades.
* **Output Explanation**: in 1960's there are only movie releases but over the time the tv shows are increased

  
### 4. Top Contributing Countries
* **What this step does**: Identifies which countries produce the most content hosted on Netflix.
* **Output Explanation**: U.S has most number of movies/tv shows over 2500 and followed by india which has around 1000 

## 💡 Key Observations & Summary

* **Takeaway 1**: { the average duration of movies is 100 minutes }
* **Takeaway 2**: {from 2015 to 2021 most number of tv shows and movies are releases } and done feature engineering on runtime of tv shows

## 📂 Dataset Source
* The data used in this analysis was sourced from: https://www.kaggle.com/datasets/lovishbansal123/netflix-dataset
  

