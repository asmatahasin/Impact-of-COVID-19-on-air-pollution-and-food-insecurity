# Impact of COVID-19 on Air Pollution and Food Insecurity

This project investigates the effects of the COVID-19 pandemic on air pollution levels and food insecurities in the United States. 


## Introduction

Since the outbreak of Covid-19 in December 2019, the global pandemic has had significant societal and daily life impacts. Its effects on food security and air quality have been particularly noteworthy, leading to increased food insecurity rates and improved air quality. This project investigates these impacts specifically within the United States.

---

## Prerequisites

The following Python libraries are required to run the code:
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

Install these libraries using the following command:
```
pip install -r requirements.txt
```

---

## Aim

This project aims to:

1. Analyze the impact of COVID-19 on air pollution in the USA.
2. Investigate how COVID-19 has affected food insecurity in the USA and predict similar situations in the future.

## Data Collection

Data for this project was collected from the following sources:

1. [US counties COVID-19 dataset](https://github.com/nytimes/covid-19-data/tree/master/live)
2. [Covid-19 Food Insecurity Data](https://www.kaggle.com/datasets/jackogozaly/pulse-survey-food-insecurity-data?resource=download)
3. [US-Environment air pollution: United States Environmental Protection Agency](https://aqs.epa.gov/aqsweb/airdata/download_files.html)
4. [Trips by Distance: U.S. Department of Transportation](https://data.bts.gov/Research-and-Statistics/Trips-by-Distance/w96p-f2qv)

Download the datasets used [here](https://drive.google.com/file/d/1oo0rM7vc0oKXfJ4ACQOGy6xXMQVc_TOP/view?usp=share_link)

## Data description:
##### Air Pollutants merged with Covid 19: 

* This dataset consists of information related to date, state, number of Covid cases, pollutants, meteorological features, population staying and not staying at home, number of Trips effecting AQI.

##### Food Insecurity merged with Covid 19:

* This dataset consists of survey information such as  “Enough of the kinds of food wanted”, “Enough Food, but not always the kinds wanted”, “Sometimes not enough to eat”, “Often not enough to eat” across different gender, race etc. along with Covid 19 cases.

## Model Building:
Model building was performed on both unbalanced and balanced datasets of Air pollution and Food Insecurities using `SMOTE` technique for balancing.

`Air Pollution Dataset`:

##### Supervised Machine learning Algorithms:
###### Regression
    * Multiple Linear Regression
    * Support Vector Linear Regression
    * Decision Tree
    * Random Forest

##### Unsupervised Machine learning Algorithms:
###### Clustering
    * K Means
    * Hierarchical Clustering
    
`Food Insecurities Dataset`:

    * ARIMA ( Time Series Forcasting )


## Results Summary

### Air Pollution

Our analysis indicated a significant impact of the increase in COVID-19 cases on the reduction in air pollution. Furthermore, an uptick in COVID-19 cases predicts the Air Quality Index (AQI) (p=0.0088).

### Food Insecurities

Our analysis indicated that COVID-19 has had a significant impact on food insecurity in various demographic groups in the USA (p=0.00009755).


## Project Structure

The repository contains the following structure:

* `data/`: Contains raw data files for the project.
* `models/`: May contain trained machine learning models.
* `notebooks/`: Contains Jupyter notebooks for data exploration, cleaning, visualization, and machine learning.
* `reports/`: Holds any generated reports or detailed analyses.


Each directory may contain two sub-directories `Air Pollution` and `Food Insecurities`:

1. **Air Pollution**: Analysis and prediction of the impact of Covid-19 on Air Pollution within the USA.
2. **Food Insecurities**: Analysis and prediction of the impact of Covid-19 on Food Insecurities within the USA.

---


## Getting Started

Follow these steps to replicate the project:

1. Clone this repository.
2. Install the necessary Python libraries listed in `requirements.txt`.
3. Navigate to the respective project directory (covid_19_air_pollution_food_insecurities).
4. Run the Jupyter notebooks in the `notebooks/` directory.

## Contributors

This project was carried out by:

- Mohammed Asmatahasin
- Dinesh Vennapoosa
- Kavya Gustala
- Varshini Singamaneni
- Surat Srinivasa 
- Oludare Odewenwa
- Tanneru Naga Shalini 

---

## License

This project is licensed under the terms of the MIT license.

---

For detailed information on the project, please refer to project report file in the `report/` directory


## Contact

For any queries or further discussions, feel free to reach out
