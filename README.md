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

| Chapter | Member 1 | Member 2 |
|---|---|---|
| Ch1_2_3 | [link](https://colab.research.google.com/drive/1CYnEloJcJ4P3dNukBhwQJ6AL8GaXladQ?usp=sharing) | [link](https://colab.research.google.com/drive/1CYnEloJcJ4P3dNukBhwQJ6AL8GaXladQ?usp=sharing) |
| Ch4 | [link](https://colab.research.google.com/drive/1CYnEloJcJ4P3dNukBhwQJ6AL8GaXladQ?usp=sharing) | [link](https://colab.research.google.com/drive/1CYnEloJcJ4P3dNukBhwQJ6AL8GaXladQ?usp=sharing) |
| Ch5 | [link](https://colab.research.google.com/drive/1w2RahxxqHCaW4tTpYhG0WlU5AR8xoFk6?usp=sharing) | [link](https://colab.research.google.com/drive/1w2RahxxqHCaW4tTpYhG0WlU5AR8xoFk6?usp=sharing) |
| Ch6 | [link](https://colab.research.google.com/drive/1KndsWAMOyfjRmyVxBvI2Yza5vZhzSw5e?usp=drive_link) | [link](https://colab.research.google.com/drive/14J7b2QcvAVYODj7wtJrL_DH-JLkYHTcr?usp=sharing) |
| Ch7 | [link](https://colab.research.google.com/drive/138c88b8e_8CfrWvidRLpVLn_QzuZv6Au?usp=drive_link) | [link](https://colab.research.google.com/drive/1C8ZqFdJAQsqst22Kg6tqCG9nSQnfbIQV?usp=sharing) |
| Ch8 | [link](https://colab.research.google.com/drive/1DH5LW2qp2oN5lfA9ZvCp3tKJMVQc8EDN?usp=drive_link) | [link](https://colab.research.google.com/drive/1OU5K2KGbE_MkG0pUPfYMAyU9CnyiYEhf?usp=sharing) |
| Ch9 | [link](https://colab.research.google.com/drive/1Lp5UdOmpjlHZF7UU4MhhJLtcLtAvuKbS?usp=drive_link) | [link](https://colab.research.google.com/drive/1eNF1LGHDNNxLbhx7RCONcFZ5v_E_wrij?usp=sharing) |

## What we learned

One short paragraph per chapter, Ch1_2_3 to Ch9. Say what the chapter taught
you and what surprised you. Not what the library does, but what you understood.

(DE VILLA)
CHAPTER 1,2,3

Learning about data preprocessing changed how I look at data science because I realized most of the work happens early on since real-world data is usually messy and incomplete. In chapter 1, I understood that a good model means nothing if your data is bad, because garbage input just gives bad results faster. Chapter 2 taught me how to inspect a dataset simply by checking data types and basic summary stats. I was surprised that a simple table can already show you extreme numbers and gaps before you even draw any charts. Finally, chapter 3 showed me that fixing missing values or duplicate rows isn't just about running code automatically. I was surprised by how a quick fix, like filling missing years with an average that has decimals, can mess up the real meaning of the data if you don't double-check it yourself.

CHAPTER 4

This chapter taught me that we don't have to rely only on the raw columns given to us, because we can transform or combine them to create new ones that show better insights. I learned how to turn categories into numbers using encoding and group values using binning. What surprised me most was how much a simple formula—like dividing lemonade sales by temperature—can completely change how we see customer behavior compared to just looking at sales numbers alone.

CHAPTER 5

I learned that when different features have totally different number scales, models can easily get biased toward the bigger numbers. Scaling helps put every column on an equal playing field, whether we bring them between 0 and 1 or center them around zero. What surprised me was that even though columns like grades and study hours both matter, a model might completely ignore study hours simply because grade values are naturally larger.

CHAPTER 6

I understood that outliers are extreme values that stand out from the rest of the dataset and can easily distort our overall analysis. I learned that techniques like IQR and Z-score make it easier to detect these unusual numbers, and we can manage them by removing, transforming, or capping them. What surprised me most was realizing that we shouldn't just instantly drop an outlier, since those extreme data points might actually hold valuable insights.

CHAPTER 7 

I realized that picking the proper features matters a lot since not every variable in a dataset carries the same weight or value. I learned that checking correlation helps us spot how variables relate to one another, and feature selection techniques help us figure out which specific columns are actually useful for predicting outcomes. What surprised me most was that just because a variable connects to the result doesn't mean it's necessary when look at all the features together, some of those related variables actually end up being redundant or far less important.

CHAPTER 8

I learned that data cleaning gets way easier when you combine all the steps into one simple pipeline. It showed me that fixing missing values and scaling numbers don't need to be done separately, you can do them all in one step. What surprised me most was how you can just use that exact same process again on new data to keep things clean without starting over.

CHAPTER 9

I learned how various preprocessing methods come together in practice to get a real-world dataset ready for actual work. It made me realize that steps like data cleaning, transformation, reduction, binning, and encoding aren't isolated jobs, they actually depend on and feed into each other. What surprised me most was that preprocessing isn't just a single pass-through task, since you often have to go back and refine the data multiple times until it's properly prepared.

## Errors we found

List any mistake you found in the original notebooks, and the correct version.
There are real ones in there. Finding them earns points.

We did not encounter or notice any syntax errors when running the code snippets provided in the notebook. Everything executed as expected during our walkthrough.

## Note on AI tools

Say whether you used an AI tool, and what for. This is not a penalty.
Hiding it is.

We did not use any AI tools to generate or fix code, as we were able to run all code snippets without encountering any errors.

## References

McKinney, W. (2021). Python for Data Analysis, 3rd ed. O'Reilly.
VanderPlas, J. Python Data Science Handbook.


Any other page or article you used.
```

---
