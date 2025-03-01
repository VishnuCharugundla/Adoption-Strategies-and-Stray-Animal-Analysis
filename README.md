# Adoption-Strategies-and-Stray-Animal-Analysis
Exploratory data analysis and visualization of Austin Animal Center datasets to identify key trends in animal populations and inform shelter management.

# Austin Animal Shelter Data Insights: Adoption Strategies and Stray Animal Analysis

[![Python](https://img.shields.io/badge/python-3.x-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Seaborn](https://img.shields.io/badge/seaborn-%234CB391.svg?style=for-the-badge&logo=seaborn&logoColor=white)](https://seaborn.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/matplotlib-%23E35A2C.svg?style=for-the-badge&logo=matplotlib&logoColor=white)](https://matplotlib.org/)

## Project Overview

This project analyzes data from the Austin Animal Center to gain insights into animal intakes, outcomes, and stray animal locations. By identifying key factors that influence adoptions and strays, we aim to provide data-driven insights that can help improve adoption strategies and reduce stray cases in Austin.

## Project Goals

* Identify key trends in animal intakes and outcomes.
* Analyze factors contributing to stray animal cases.
* Visualize the geographical distribution of stray animals.
* Develop data-driven recommendations to improve adoption rates and reduce stray populations.

## Team Members

* Dishant Bhansali
* Shashank Guda
* Vishnu Charugundla

## Dataset Description

The analysis is based on three datasets:

* **Intakes Dataset:** Contains information on animals brought into the shelter, including intake type, breed, and condition.
* **Outcomes Dataset:** Tracks the outcome of each animal, such as adoption, return, or euthanasia.
* **Stray Map Dataset:** Provides geographic data on stray animal locations.

## Technologies Used

* Python (pandas, matplotlib, seaborn, folium)
* Jupyter Notebook

## Analysis Performed

* **Data Cleaning and Preprocessing:**
    * Handling missing values and duplicates.
    * Data type conversions and feature extraction.
* **Exploratory Data Analysis (EDA):**
    * Distribution of intake and outcome types.
    * Analysis of animal types, breeds, colors, and ages.
    * Geographical mapping of stray animal locations using Folium.
* **Correlation Analysis:**
    * Analyzing the correlation between animal ages at intake and outcome.
* **Merged Dataset Analysis:**
    * Combining all three datasets to create a comprehensive view.
    * Analyzing the most common outcomes for strayed animals.
    * Identifying common breeds and found locations.
    * Analyzing the age distribution of strayed animals.
    * Examining the distribution of outcomes based on intake conditions.
* **Time Series Analysis:**
    * Analyzing monthly animal intakes.

## Key Findings

* Stray animals and owner surrenders are the most common intake types.
* Dogs and cats make up the majority of animals in the shelter.
* Adoption and transfers to rescue are the most common outcomes.
* Young animals are more likely to be adopted.
* Stray animals are concentrated in urban areas.
* Certain locations show a higher frequency of stray animals.
* There is a moderate positive correlation between age upon intake and age upon outcome.

## Visualizations

* Bar charts showing the distribution of intake and outcome types.
* Histograms illustrating age distributions.
* Heatmaps displaying animal type outcomes.
* Folium maps visualizing stray animal locations.
* Time series plot of monthly intakes.

## Actionable Insights

* Targeted adoption campaigns for specific animal types and age groups.
* Resource allocation based on intake conditions.
* Geographical targeting of stray animal intervention programs.
* Community outreach and education on responsible pet ownership.
* Focus on microchipping to increase return to owner rates.
* Targeted spay/neuter programs in high stray areas.
* High intake rates for certain breeds suggest the need for breed-specific adoption campaigns.
* Older animals have lower adoption rates; shelters can implement targeted incentives.

## Project Structure
Austin_Animal_Analysis/
├── data/
│   ├── Austin_Animal_Center_Intakes_20240425.csv
│   ├── Austin_Animal_Center_Outcomes_20240425.csv
│   └── Austin_Animal_Center_Stray_Map_20240425.csv
├── visuals/
│   └── (Generated plots and graphs)
├── Scripting_Major_Project_Analysis.ipynb
├── stray_animals_map.html
└── README.md


## How to Run the Project

1.  Clone the repository:
    ```bash
    git clone [repository_url]
    ```
2.  Navigate to the project directory:
    ```bash
    cd Austin_Animal_Analysis
    ```
3.  Install dependencies:
    ```bash
    pip install pandas matplotlib seaborn folium
    ```
4.  Open Jupyter Notebook:
    ```bash
    jupyter notebook Scripting_Major_Project_Analysis.ipynb
    ```
5.  Run the notebook cells to generate insights and visualizations.

## Results & Recommendations

* High intake rates for certain breeds suggest the need for breed-specific adoption campaigns.
* Geographic mapping of strays can help in better placement of rescue and outreach programs.
* Older animals have lower adoption rates; shelters can implement targeted incentives.

## Future Work

* Implement predictive modeling to forecast adoption probabilities.
* Enhance geospatial analysis to track movement patterns of stray animals.
* Develop an interactive dashboard for real-time insights.

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues to suggest improvements or report bugs.



## Acknowledgments


This project aims to drive meaningful impact by using data analytics to improve animal welfare. Feel free to contribute or reach out for collaboration!
