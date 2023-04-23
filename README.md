# Final-assignment

## 🚩 Table of Contents


- [Introduction](#-Introduction)
- [Requirements](#-requirements)
- [Data_Analysis](#-Data_Analysis)
- [Todo](#-todo)

### Introduction
In the past couple months, we’ve witnessed doctors, nurses, paramedics and thousands of medical workers putting their lives on the frontline to save patients who are infected. And as the battle with COVID-19 continues, we should all ask ourselves – What should we do to help out? What can we do to protect our loved ones, those who sacrifice for us, and ourselves from this pandemic?

### The question :

- **First :**
The first question is Which diet helps immunity against Corona?
- **Next :**  
whether there is a relationship between the protein levels and the fat levels of foods consumed by covid patients?
- **Finally :**
Which countries have a better diet? and Which countries have less confirmed covid patients?


### About Data:
This dataset selected from the kaggle website. (link mentioned)

https://www.kaggle.com/datasets/mariaren/covid19-healthy-diet-dataset?select=Food_Supply_Quantity_kg_Data.csv

In this dataset, I have combined data of different types of food, world population obesity and undernourished rate, and global COVID-19 cases count from around the world in order to learn more about how a healthy eating style could help combat the Corona Virus. And from the dataset, we can gather information regarding diet patterns from countries with lower COVID infection rate, and adjust our own diet accordingly.

In each of the 4 datasets below, I have calculated fat quantity, energy intake (kcal), food supply quantity (kg), and protein for different categories of food (all calculated as percentage of total intake amount). I've also added on the obesity and undernourished rate (also in percentage) for comparison. The end of the datasets also included the most up to date confirmed/deaths/recovered/active cases (also in percentage of current population for each country).

### Requirements
- Python
- Pandas (library)
- numpy (library)
- bokeh (library)
- seaborn (library)
- matplotlib (library)
- folium (library)

### Data_Analysis
food_df contains the amount of each type of foods consumption. SO for answering the first question we should find the relation between each type of food values and patients.
- X for this question is Food category
- Y is 2 column 1.Number of confirmed patients 2.Number of Patients who were infected with corona and recovered

Now we find correlation between X and Y values to find which food category is more related to getting the disease and recovery

As chart shows we find 2 food categories with more relation
- Animal products (**possitive** correlation with **infection**) and (**negetive** correlation with **recovery**)
- Vegetal products (**negetive** correlation with **infection**) and (**possitive** correlation with **recovery**)
<img src =""/>

In animal products The ratio of consumption with protein and fat is positive while in vegetal products this ratio is opposite
<img src =""/>

In order to find out which countries were infected with the corona disease and how much they used herbal products, I drew a thermal graph on the map.
<img src =""/>
