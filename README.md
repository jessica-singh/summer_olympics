# Gender Representation and Equality in Olympic Sports

## Overview
This project analyzes trends in gender representation and equality in Olympic sports. It explores the proportions of male and female athletes over time, the gender ratio, and the distribution of medals won by each gender. The goal is to understand how gender equality in the Olympics has evolved over the years.

## Dataset
The dataset used for this analysis includes information on Olympic events from 1976 to 2008. It contains the following columns:
- `City`: The host city of the Olympic Games.
- `Year`: The year of the Olympic Games.
- `Sport`: The sport in which the event took place.
- `Discipline`: The discipline within the sport.
- `Event`: The specific event within the discipline.
- `Athlete`: The name of the athlete.
- `Gender`: The gender of the athlete (Men or Women).
- `Country_Code`: The country code of the athlete.
- `Country`: The country of the athlete.
- `Event_gender`: The gender category of the event (M or W).
- `Medal`: The medal won (Gold, Silver, Bronze).

## Files
- `Olympic_Medals_1976_to_2008.csv`: The dataset containing Olympic medal information.
- `analysis_notebook.ipynb`: The Jupyter notebook with code and analysis of gender representation and equality trends.

## Analysis
The analysis consists of:
1. **Proportion of Male vs. Female Athletes**: Visualizing the percentage of male and female athletes each year.
2. **Gender Ratio**: Calculating and plotting the ratio of male to female athletes over time.
3. **Medal Distribution by Gender**: Comparing the number of medals won by male and female athletes each year.

## Requirements
To run the analysis, you need:
- Python 3.x
- Pandas
- Matplotlib
- Seaborn

You can install the required packages using pip:
```bash
pip install pandas matplotlib seaborn
