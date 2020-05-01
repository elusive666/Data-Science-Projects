# Project Overview

You have a dataset of news headlines sourced from the reputable Australian news source ABC (Australian Broadcasting Corp.) over a period of 15 years. If you dig into the keywords, you will see all the important episodes shaping the last decade and how they evolved over time. Ex: financial crisis, iraq war, multiple US elections, ecological disasters, terrorism, famous people, Australian crimes etc. A much better way to comprehend these topics would be using topic modelling to find out relevant topics within a particular time frame.

**Problem Statement**

The main goal of this problem is to leverage the power of techniques like LSA (Latent Semantic Analysis) and LDA (Latent Dirichlet Allocation) to assign topics to unseen news headlines.

## Description

The dataset includes the entire corpus of articles published by the ABC website in the given time range. With a volume of 200 articles per day and a good focus on international news, we can be fairly certain that every event of significance has been captured here. In total there are 331100 instances of data available with two columns.

The columns in this dataset are:

1. publish_date: Date of publish of the news headline
2. headline_text: Headline of the news published on that particular date
