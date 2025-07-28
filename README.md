# Education Infrastructure & Dropout Trends in Kalimantan (2021–2024)

## Overview

This project explores the state of primary to upper secondary education in Kalimantan, Indonesia, from 2021 to 2024. Using publicly available data from Kemendikbud, we analyzed dropout trends, student-teacher ratios, and student-facility distributions across the five Kalimantan provinces.

## Problem Statement

Despite national progress in education, remote regions like Kalimantan still face inequality in access and quality. Dropout rates, classroom shortages, and overstretched teaching staff reflect systemic problems. This project aims to identify key patterns and bottlenecks to inform potential policy or resource decisions.

## Dataset

* **Source**: [Opendata kemdikbu](data.go.id)
* **Years Covered**: 2021–2024
* **Levels**: SD, SMP, SMA/SMK
* **Regions**: Kalimantan Barat, Kalimantan Timur, Kalimantan Tengah, Kalimantan Selatan, Kalimantan Utara

## Key Questions

* How have dropout rates changed over the years?
* What are the student-teacher ratios across provinces?
* Is there a correlation between facility shortages and dropout rates?

## Insights

* **Dropout Trends**: Kalimantan Barat had the highest spike in dropouts in 2022, especially at the SD (Primary school) level.
* **Teacher Shortage**: Some provinces had >25 students per teacher, higher than the recommended national average of 20:1 ([UNESCO, 2023](https://uis.unesco.org/)).
* **Facility Ratios**: Classroom and rombel (study group) shortages are most severe in Kalimantan Utara and Kalimantan Tengah, contributing to overcrowding.

## Visualizations

* Dropout trends over time
* Student-teacher ratio bar plots on each province
* Student-facility ratios

## Folder Structure

```
education-analysis-kalimantan/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   └── indonesian-school-analysis-notebook.ipynb
├── images/
│   └── *.png
├── README.md
├── requirements.txt
```

## Future Work

* Build predictive models for dropout risk
* Correlate with socioeconomic indicators
* Conduct time series forecasting

## Credits

* Data: Kemendikbud (data.go.id)
* Tools: Python (Pandas, Matplotlib, Seaborn)

