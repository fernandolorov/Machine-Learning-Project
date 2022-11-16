# Machine-Learning-Project



Project developed for the course Statistical Foundations of Machine Learning during the realization of the Master of Applied Sciences and Engineering: Applied Computer Science at the Vrije Universiteit Brussels.
This project consists of the performance of two supervised learning tasks (classification and regression) over two different types of datasets (synthetic and real-world datasets).

The project is written in Python programming language using Python Notebooks. This repository contains two Python Notebooks files one for each of the tasks:

### **SFML Classification Task.ipynb:** 
  In this notebook, you can find three classifications over three different datasets:

  * **Synthetic 1:** 
    - 2 Classes
    - 4 Features (All of them are informative)
    - 100 Samples
    - 0 % Of randomly assigned class
    - With a high class separation
    - 1 Cluster per class
    - Perfectly balanced

  * **Synthetic 2:**
    - 2 Classes
    - 4 Features (3 of them are informative and 1 of them is irrelevant)
    - 100 Samples
    - 20 % Of randomly assigned class
    - With a low class separation
    - 2 Cluster per class
    - Class unbalance of around 30/70

  * **Pokémon Dataset [[1]](#1) (real-world dataset):**
    - This dataset is a list of all pokémons with their Pokédex information such as Attack Points, Type, Color, etc. In this case, the classification problem consists of predicting the Pokémon Type based on the others features. There exists a total of 18 pokémon types making it a complex classification problem due to the elevated number of classes.

	The machine learning algorithms used for the classification problem are Random Forest and K Nearest Neighbours.

### **SFML Regression Task.ipynb:** 
  In this second notebook, you can find two regressions over two different datasets:

  * **Synthetic 1:** 
    - 50 Samples
    - 4 Features (3 of them are informative)
    - 1 Dimensional target variable
    - Gaussian Noise

  * **Pokémon Dataset [[1]](#1) (real-world dataset):** 
    - The dataset contains the list of all pokémons with their Pokédex information such as Attack Points, Type, Color, etc. In this case, the regression problem consists of predicting the Pokémon Attack Points based on the others features.
  
  The machine learning algorithms used for the regression problem are Linear Regression and Random Forest Regressor

## References
<a id="1">[1]</a> 
Asier López Zorrilla (2017). 
Pokémon for Data Mining and Machine Learning. 
https://www.kaggle.com/datasets/alopez247/pokemon. Last Accessed:
16/11/2022.

