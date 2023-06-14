## Exploratory Data Analysis

Hello Everyone,

Here is My EDA Project on IRIS Dataset where I analyzed the Data by using Seaborn and Matplotlib.

## Dataset

- This Dataset consists of 3 different types of Iris Flower (Setosa, Versicolour, and Virginica).

- The information includes its Petal Lenght, Sepal Length, Petal Width, Sepal Width, Variety of the Flower

**Link to the Dataset :** [Iris Dataset](https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html)

## Problem Statement

- The objective of this Project is to perform Exploratory Data Analysis (EDA) on the Iris dataset.

- The Iris dataset is a popular and well-known dataset in the field of machine learning and statistics.

- It consists of measurements of four features sepal length, sepal width, petal length, and petal width of three different species of iris flowers: setosa, versicolor, and virginica.

- The goal of this EDA is to gain insights into the dataset, understand the relationships between the features, and extract meaningful information that can aid in further analysis or modeling tasks.

## Table of Contents

- [Setting up the Enviroment](#setting-up-the-enviroment)
- [Libraries required for the Project](#libraries-required-for-the-project)
- [Getting started with Repository](#getting-started)
- [Steps involved in the Project](#steps-involved-in-the-project)
- [Conclusion](#conclusion)
- [Link to the Notebook](#link-to-the-notebook)

## Setting up the Enviroment

Jupyter Notebook is required for this project and you can install and set it up in the terminal.

- Install the Notebook - `pip install notebook`

- Run the Notebook - `jupyter notebook`

## Libraries required for the Project

**Pandas**

- Go to Terminal and run this code - `pip install pandas`

- Go to Jupyter Notebook and run this code from a cell - `!pip install pandas`

**Matplotlib**

- Go to Terminal and run this code - `pip install matplotlib`

- Go to Jupyter Notebook and run this code from a cell - `!pip install matplotlib`

**Seaborn**

- Go to Terminal and run this code - `pip install seaborn`

- Go to Jupyter Notebook and run this code from a cell - `!pip install seaborn`

## Getting Started

- Clone the repository to your local machine using the following command :
```
git clone https://github.com/TheMrityunjayPathak/ExploratoryDataAnalysis.git
```

## Steps involved in the Project

**Importing libraries required for Project**

**Reading CSV File**

**Exploring the Dataset**

**Checking Null Values in Dataset**

**Splitting the Dataset based on Species of Flower**

**Data Visualization**

**Count Plot on IRIS Dataset**

- A Count Plot is similar to a Bar Plot and a Histogram and provides counts of categorical values.

![download](https://github.com/TheMrityunjayPathak/ExploratoryDataAnalysis/assets/123563634/0784b5ee-33a2-4cdf-b4dc-14e5969b1c10)

**Scatter Plot on IRIS Dataset**

- Scatter plots are the graphs that present the relationship between two variables in a data-set.

![download](https://github.com/TheMrityunjayPathak/ExploratoryDataAnalysis/assets/123563634/6cd1a801-98fc-4418-aded-7ca01e8f921e)

![download](https://github.com/TheMrityunjayPathak/ExploratoryDataAnalysis/assets/123563634/caf962f1-44a3-46e1-bc99-8365c27e9121)

**Pair Plot on IRIS Dataset**

- To Plot Multiple Pairwise Bivariate Distributions in a Dataset, you can use the sns.pairplot() function.

![download](https://github.com/TheMrityunjayPathak/ExploratoryDataAnalysis/assets/123563634/d190d449-b397-4ac3-b28e-df9e9baf0be7)

**Distribution of Sepal Length and Petal Length of Different Species of Flower**

- Distribution plots show how a variable (or multiple variables) is distributed.

- To Plot distribution plots you can use the sns.displot() function.

![download](https://github.com/TheMrityunjayPathak/ExploratoryDataAnalysis/assets/123563634/395ad739-7767-467d-9f3a-672037cc66a8)

![download](https://github.com/TheMrityunjayPathak/ExploratoryDataAnalysis/assets/123563634/cd687bc4-f20c-4774-82f5-63bd2f6113da)

**Box Plot on IRIS Dataset**

- A box and whisker plot also called a box plot displays the five-number summary of a set of data. 

- The five-number summary is the minimum, first quartile, median, third quartile, and maximum.

![download](https://github.com/TheMrityunjayPathak/ExploratoryDataAnalysis/assets/123563634/39019da3-1841-409d-ab8f-dbdbb6bb9fa0)

![download](https://github.com/TheMrityunjayPathak/ExploratoryDataAnalysis/assets/123563634/0685804c-3873-4388-931a-e1d3fac2d2ad)

**Heat Map on IRIS Dataset**

- Heat Map is used to find out the Correlation between different features in the Dataset. 

- High Positive or Negative value shows that the features have high Correlation.

- A Correlation Heatmap is a graphical tool that displays the correlation between multiple variables as a color-coded matrix.

![download](https://github.com/TheMrityunjayPathak/ExploratoryDataAnalysis/assets/123563634/f87d3933-f9b9-4ce8-bc70-5a8a768c7f6b)

## Conclusion

- In conclusion, the exploratory data analysis (EDA) conducted on the Iris dataset using Seaborn and Matplotlib has provided valuable insights into the dataset's characteristics and relationships between variables.

- The EDA revealed that the Iris dataset consists of 150 samples, each representing a different Iris flower, with four features: sepal length, sepal width, petal length, and petal width.

- The dataset is balanced, with 50 samples for each of the three Iris species: Setosa, Versicolor, and Virginica.

- Using Seaborn and Matplotlib, we created various plots to explore the dataset.

## Link to the Notebook
[Exploratory Data Analysis on IRIS Dataset](https://www.kaggle.com/code/themrityunjaypathak/exploratory-data-analysis-on-iris-dataset)
