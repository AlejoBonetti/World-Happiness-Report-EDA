# World Happiness Report EDA (2015-2019)

This project analyses the data from the **World Happiness Report** between **2015** and **2019**, using datasets from Kaggle.
The main objective is to understand how the Happiness Score evolves globally, which are the variables that explain it the best and how do countries change through time.


## Dataset
**Source**: Kaggle - *World Happiness Report*
Datasets include variables such as:
- **Happiness Score**
- **GDP per Capita**
- **Family / Social Support** (Excluded)
- **Life Expectancy**
- **Freedom to make life choices**
- **Generosity**
- **Perceptions of Corruption**
- **Dystopia Residual**

*Link:* https://www.kaggle.com/datasets/unsdsn/world-happiness

**Objectives**

1. Evaluating the change in the Happiness Score between 2015 and 2019.
2. Identifying the variables that best explain the score and their relative relevance.
3. Detecting the countries that rise or fall the most over the years.
4. Finding the consistently happiest countries.

## Dataset Cleaning and Structure
During this step it was found that certain variables were not consistent through years:

- Family and Social Support were not present in every year so they were excluded for consistency purposes.
- Some columns presented slight changes on their names.

## Analysis

##### 1. **Stability of the Happiness Score**

The global distribution of the Happiness Score remains relatively stable over the five years.
Most countries show only mild fluctuations, suggesting that national happiness changes slowly over time. There was a small shift in distribution probably because of the introduction of **Social Support**.

##### 2. **Strongest Predictors of Happiness**

The variables showing the strongest and most consistent correlation with Happiness Score are **GDP per Capita** and **Life Expectancy**. These two dominate the explanatory power of the score across all years.
**Freedom to make life choices** also shows a moderate and stable correlation.

##### 3. **Weak or Noisy Predictors**

**Perceptions of Corruption** displays the highest dispersion across countries and the weakest correlation with the score. This suggests it plays a secondary role compared to economic or social factors.

##### 4. **Ranking Movements**

While some countries experience huge rises or falls, the overall ranking structure is quite rigid.
Nordic countries —especially **Denmark**, **Norway** and **Iceland**— remain consistently at the top.

## Visualizations Included

The notebook contains visual analyses such as:

- Year-to-year Happiness Score distributions
- Correlation matrix
- Ranking changes by country
- Distributions and scatter plots for key variables

## Conclusions

The analysis shows that the strongest predictors of the Happiness Score between 2015 and 2019 were GDP per Capita, Life Expectancy and Freedom.
The ranking of countries tends to remain stable, and overall happiness levels exhibit slow long-term change.
Institutional factors like corruption show weaker and noisier relationships with the score.