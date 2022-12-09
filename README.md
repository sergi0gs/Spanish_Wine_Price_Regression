# Spanish Wine Price Regression (In process)

![Image text](https://github.com/sergi0gs/Spanish_Wine_Price_Regression/blob/main/app/static/dataset-cover.jpg)

## Description
Exploratory data analysis and predictive modeling for predicting wine prices. As well as a web application to display the results performed in Flask. The following kaggle dataset is being used for this purpose: [Spanish Wine Quality Dataset](https://www.kaggle.com/datasets/fedesoriano/spanish-wine-quality-dataset)

## Kaggle Context of the dataset:
This dataset is related to red variants of spanish wines. The dataset describes several popularity and description metrics their effect on it's quality. The datasets can be used for classification or regression tasks. The classes are ordered and not balanced (i.e. the quality goes from almost 5 to 4 points). The task is to predict either the quality of wine or the prices using the given data.

## Kaggle Content of the dataset:
The dataset contains 7500 different types of red wines from Spain with 11 features that describe their price, rating, and even some flavor description. The was collected by me using web scraping from different sources (from wine specialized pages to supermarkets).

## Prepare Environment
1. Create a Virtual Environment (Recomendation Anaconda & python=3.9.13): **conda create -n [environment_name] python=[python_version]**
```bash
conda create -n wine_model python=3.9.13
```

2. Activate virtual environment
```bash
conda activate wine_model
```

3. Install **requirements.txt** libraries.
- Windows:
```bash
pip install -r requirements.txt
```
- Linux:
```bash
pip3 install -r requirements.txt
```

## Attribute Information
- `winery`: Winery name
- `wine`: Name of the wine
- `year`: Year in which the grapes were harvested
- `rating`: Average rating given to the wine by the users [from 1-5]
- `num_reviews`: Number of users that reviewed the wine
- `country`: Country of origin [Spain]
- `region`: Region of the wine
- `price`: Price in euros [€]
- `type`: Wine variety
- `body`: Body score, defined as the richness and weight of the wine in your mouth [from 1-5]
 `acidity`: Acidity score, defined as wine's “pucker” or tartness; it's what makes a wine refreshing and your tongue salivate and want another sip [from 1-5]