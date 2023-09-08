
# Bankruptcy prediction using big data techniques

Description:Predicting corporate bankruptcy holds immense practical significance, prompting the exploration of big data techniques for this purpose. Strategic implementations of machine learning models using big data techniques utilizing publicly available datasets from American and Taiwanese companies. Leveraging financial statements from over 5,000 firms, we employ Spark-driven machine learning algorithms to ensure scalability. This effort is underpinned by the backdrop of the 2008 global housing market collapse, which precipitated widespread bankruptcy in both Taiwan and the US. The contribution of this research extends beyond methodology to encompass cross-country insights.
Throughout the analysis, we employ exploratory data analysis, generating various graphs including correlation plots, heat maps, and box plots. These visualisations serve as the foundation for our subsequent studies. to ready the datasets for modelling, a methodical pre-processing regimen is applied. This involves Hyperparameter tuning for best parameters estimation, SMOTE to address imbalances, and principal component analysis (PCA) for dimensionality reduction. 
In tandem with our predictive modelling, I’ve adopted Speedups, Scaleups, and Sizeups metrics to holistically assess model performance. These metrics allow us to gauge how well our models perform under varying data volumes, ensuring their scalability and adaptability as we deal with large datasets. I’ve evaluated the models using the F1 score and ROC-AUC metrics. Augmenting this quantitative assessment, classification reports and informative graphs provide a detailed understanding of each model's strengths and weaknesses. 
Overall, this research advances the field of bankruptcy prediction by offering a comprehensive approach to bankruptcy prediction. Moreover, the cross-regional comparison enhances our understanding of bankruptcy prediction factors across diverse economies. This research contributes to the broader domain of financial risk assessment and informs strategic decision-making for investors and financial professionals. By meticulously analysing these datasets, we uncover patterns indicative of imminent bankruptcy strategies.


Getting Started
These instructions will guide you on how to execute the notebooks in this repository.

Prerequisites
Ensure you have the following installed:

Python 3.x
Jupyter Notebook
Libraries
Before running the notebooks, make sure to install the required libraries.

Datasets
The datasets required for these notebooks are provided in the repository. When you run the code, a resampled dataset will be created.

Running the Notebooks
There are three main notebooks in this repository:

Final file US data set.ipynb: This notebook contains the analysis for the US dataset.
Final file Taiwan dataset.ipynb: This notebook focuses on the Taiwan dataset.
Final file US data set.ipynb: This notebook works with the collabed data.
To run a notebook:

Navigate to the directory containing the notebook.
Start Jupyter Notebook by running:

jupyter notebook
In the Jupyter Notebook dashboard, click on the desired notebook to open it.
Execute the notebook cells in sequence.
