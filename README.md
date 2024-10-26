# Netflix-Data-Analysis-using-Machine-Learning-Algorithms

### Project Overview

This project explores a dataset of international TV shows to perform three main tasks:

1. **Data Visualization**:
   - Various visualizations are employed to analyze the distribution and relationships between different features of the dataset, such as show genres and popularity.
   - Tools like `matplotlib` and `seaborn` are used to create these visualizations, including bar plots, heatmaps, and pie charts.
  
2. **Classification**:
   - Several machine learning models are implemented to classify TV shows based on their characteristics.
   - Algorithms used include Logistic Regression, Decision Trees, and Support Vector Machines.
   - The models are evaluated using techniques like accuracy scores, confusion matrices, and classification reports.
  
3. **Association Rule Mining**:
   - Using the Apriori algorithm, frequent itemsets of genres are discovered in the dataset.
   - The analysis reveals common genre combinations in international TV shows, such as Crime TV Shows and Romantic TV Shows.
  
### Notebooks

1. **Visualization.ipynb**:
   - Focuses on visual exploration of the dataset to derive key insights.
   - Generates plots for distributions, correlations, and categorical breakdowns of TV show genres.

2. **Classification.ipynb**:
   - Implements machine learning classifiers to predict categories of TV shows.
   - Performance evaluation includes confusion matrices and accuracy scores for each model.

3. **Association.ipynb**:
   - Applies the Apriori algorithm for association rule mining.
   - Discovers frequent co-occurring genres in international TV shows, showing the popularity of certain genre combinations.

### Results

- **Visualization**: 
   - Key visual insights show the distribution of genres, with Drama being the most popular.
  
- **Classification**:
   - The Decision Tree model showed the best performance, with an accuracy score of around 85%.
   - Confusion matrices helped analyze the correct and incorrect predictions for each class.

- **Association**:
   - "International TV Shows" co-occur most frequently with Drama and Crime genres, highlighting trends in international TV viewing preferences.

### Requirements

- Python 3.x
- Jupyter Notebook
- Required libraries: `matplotlib`, `seaborn`, `scikit-learn`, `mlxtend`

To install the necessary libraries, run:
```bash
pip install -r requirements.txt
```

### Conclusion

This project provides a comprehensive analysis of TV shows using visualization, classification, and association rule mining techniques. The findings give meaningful insights into genre popularity and classification models' effectiveness for predicting show categories.
