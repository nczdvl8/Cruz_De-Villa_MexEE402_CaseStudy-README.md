# MexEE 402: Data Preprocessing Case Study

MexEE Elective 2: Data Science and Machine Learning
Batangas State University, Alangilan Campus
1st Semester, AY 2026-2027

## Members

| Name | Student Number | Section |
|---|---|---|
| Cruz, Alliah Brent |22-09037 |MEXE-4103 | 
| De Villa, Jhon Nicoz |22-02085 |MEXE-4103 |

## Notebook links

| Chapter | Links | 
|---|---|
| Ch1_2_3 | [link](https://colab.research.google.com/drive/1CYnEloJcJ4P3dNukBhwQJ6AL8GaXladQ?usp=sharing) | 
| Ch4 | [link](https://colab.research.google.com/drive/1CYnEloJcJ4P3dNukBhwQJ6AL8GaXladQ?usp=sharing) | 
| Ch5 | [link](https://colab.research.google.com/drive/1w2RahxxqHCaW4tTpYhG0WlU5AR8xoFk6?usp=sharing) | 
| Ch6 | [link](https://colab.research.google.com/drive/1KndsWAMOyfjRmyVxBvI2Yza5vZhzSw5e?usp=drive_link) | 
| Ch7 | [link](https://colab.research.google.com/drive/138c88b8e_8CfrWvidRLpVLn_QzuZv6Au?usp=drive_link) | 
| Ch8 | [link](https://colab.research.google.com/drive/1DH5LW2qp2oN5lfA9ZvCp3tKJMVQc8EDN?usp=drive_link) | 
| Ch9 | [link](https://colab.research.google.com/drive/1Lp5UdOmpjlHZF7UU4MhhJLtcLtAvuKbS?usp=drive_link) | 

## What we learned

_One short paragraph per chapter, Ch1_2_3 to Ch9. Say what the chapter taught
you and what surprised you. Not what the library does, but what you understood._

**(CRUZ)**

**CHAPTER 1_2_3**

This chapters helped me understand how to use Python and Pandas to load CSV datasets, examine their structure using "head()", "info()", and "describe()", and identify data quality issues. I also learned to handle missing values through imputation, deletion, or prediction, as well as remove duplicates, irrelevant columns, and noisy data. Working with the Video Game Sales dataset taught me to clean data carefully because changing or removing values can affect the information available for analysis and machine learning.

**CHAPTER 4**

I learned how feature engineering creates useful variables from existing data, such as dividing sales by temperature to examine their relationship. I also studied binning, interaction features, polynomial features, and categorical encoding, including one-hot encoding for unordered categories and ordinal encoding for ordered categories. These techniques taught me to choose transformations based on the meaning of the data so that machine learning models can identify useful patterns.

**CHAPTER 5**

This chapter showed me that data scaling and normalization help make numerical features comparable, especially when their values differ greatly, as in study hours and grades. Using Scikit-learn, I explored StandardScaler, which adjusts data to a mean of 0 and standard deviation of 1, and MinMaxScaler, which scales values between 0 and 1. I also understood that scaling is not necessary for every algorithm, so the method should depend on the dataset and model being used.

**CHAPTER 6**

This chapter gave me a better understanding on how to identify outliers using the Z-score and Interquartile Range (IQR) methods and understand how unusual values can affect data analysis. I also explored ways to handle them, including capping and flooring, log transformation, and removal when appropriate. The main lesson was to determine whether an outlier is an error or meaningful information before deciding how to treat it.

**CHAPTER 7**

I understood how feature selection identifies the variables that contribute most to predicting a target, while correlation helps show positive, negative, or no linear relationships between variables. I explored filter, wrapper, and embedded methods, including correlation analysis with Pandas, RFECV for selecting features through cross-validation, and LassoCV for reducing the influence of less useful features. These methods showed me how selecting relevant inputs can simplify a model and improve its effectiveness.

**CHAPTER 8**

Through the Titanic dataset, I learned how to build a preprocessing pipeline using the Titanic dataset by examining the data with Pandas and separating the features from the target variable. I explored that SimpleImputer is for replacing missing values, StandardScaler is for standardizing numerical features, and ColumnTransformer is for applying preprocessing steps to selected columns such as Age and Fare. This chapter taught me how pipelines organize preprocessing steps, reduce repetitive work, and make data preparation easier to reuse.

**CHAPTER 9**

I learned how to prepare the Titanic dataset by handling missing numerical values through median imputation, filling categorical missing values with a constant, and applying StandardScaler and OneHotEncoder. I also studied how  Pipeline and ColumnTransformer organize these operations, while data reduction removes unnecessary columns and discretization groups numerical values such as age into categories. Finally, I learned to check the processed data using missing-value checks, histograms, box plots, count plots, and correlation heatmaps to evaluate data quality and identify patterns before further analysis.

**(DE VILLA)**

**CHAPTER 1_2_3**

<p align="justify">
Learning about data preprocessing changed how I look at data science because I realized most of the work happens early on since real-world data is usually messy and incomplete. In chapter 1, I understood that a good model means nothing if your data is bad, because garbage input just gives bad results faster. Chapter 2 taught me how to inspect a dataset simply by checking data types and basic summary stats. I was surprised that a simple table can already show you extreme numbers and gaps before you even draw any charts. Finally, chapter 3 showed me that fixing missing values or duplicate rows isn't just about running code automatically. I was surprised by how a quick fix, like filling missing years with an average that has decimals, can mess up the real meaning of the data if you don't double-check it yourself.

**CHAPTER 4**

<p align="justify">
This chapter taught me that we don't have to rely only on the raw columns given to us, because we can transform or combine them to create new ones that show better insights. I learned how to turn categories into numbers using encoding and group values using binning. What surprised me most was how much a simple formula—like dividing lemonade sales by temperature—can completely change how we see customer behavior compared to just looking at sales numbers alone.

**CHAPTER 5**

<p align="justify">
I learned that when different features have totally different number scales, models can easily get biased toward the bigger numbers. Scaling helps put every column on an equal playing field, whether we bring them between 0 and 1 or center them around zero. What surprised me was that even though columns like grades and study hours both matter, a model might completely ignore study hours simply because grade values are naturally larger.

**CHAPTER 6**

<p align="justify">
I understood that outliers are extreme values that stand out from the rest of the dataset and can easily distort our overall analysis. I learned that techniques like IQR and Z-score make it easier to detect these unusual numbers, and we can manage them by removing, transforming, or capping them. What surprised me most was realizing that we shouldn't just instantly drop an outlier, since those extreme data points might actually hold valuable insights.

**CHAPTER 7**

<p align="justify">
I realized that picking the proper features matters a lot since not every variable in a dataset carries the same weight or value. I learned that checking correlation helps us spot how variables relate to one another, and feature selection techniques help us figure out which specific columns are actually useful for predicting outcomes. What surprised me most was that just because a variable connects to the result doesn't mean it's necessary when look at all the features together, some of those related variables actually end up being redundant or far less important.

**CHAPTER 8**

<p align="justify">
I learned that data cleaning gets way easier when you combine all the steps into one simple pipeline. It showed me that fixing missing values and scaling numbers don't need to be done separately, you can do them all in one step. What surprised me most was how you can just use that exact same process again on new data to keep things clean without starting over.

**CHAPTER 9**

<p align="justify">
I learned how various preprocessing methods come together in practice to get a real-world dataset ready for actual work. It made me realize that steps like data cleaning, transformation, reduction, binning, and encoding aren't isolated jobs, they actually depend on and feed into each other. What surprised me most was that preprocessing isn't just a single pass-through task, since you often have to go back and refine the data multiple times until it's properly prepared.

## Errors we found

**Chaper 7** 
blob:https://www.messenger.com/1166b31f-e545-4111-bc29-7ed77ce50216

_List any mistake you found in the original notebooks, and the correct version.
There are real ones in there. Finding them earns points._

* We did not encounter or notice any syntax errors when running the code snippets provided in the notebook. Everything executed as expected during our walkthrough.

## Note on AI tools

_Say whether you used an AI tool, and what for. This is not a penalty.
Hiding it is._

* We did not use any AI tools to generate or fix code, as we were able to run all code snippets without encountering any errors.

## References

McKinney, W. (2021). Python for Data Analysis, 3rd ed. O'Reilly.
VanderPlas, J. Python Data Science Handbook.


Any other page or article you used.
```

---
