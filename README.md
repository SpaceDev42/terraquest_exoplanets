# 🔭 Project: Analysis of Habitable Exoplanets

## ✨ Introduction

The exploration of the universe and the search for planets beyond our solar system is one of the most fascinating fields of modern science. As an astronomy enthusiast, I have always been captivated by the idea that somewhere in the cosmos there may be worlds yet to be discovered, potentially habitable or even terraformed in the future. This project arises from that curiosity and the desire to contribute, through data analysis, to the human dream of **exploring and conquering new worlds**.

Thanks to missions like **Kepler**, **TESS**, and other scientific initiatives, thousands of exoplanets have been discovered. These celestial bodies have been recorded with detailed data on their size, mass, temperature, distance from their stars, and more. By analyzing this information, it is possible to classify, visualize, and prioritize those worlds that appear most promising for future observation, exploration, or even colonization missions.

---

## 🎯 Project Objectives

This notebook aims to perform an exploratory data analysis (EDA) focused on the habitability of exoplanets. In particular, it will seek to:

- Identify planets that lie within the **habitable zone**, based on their equilibrium temperature.  
- Filter and analyze planets with **Earth-like characteristics**, such as mass and radius.  
- Study the **distribution of distances** from Earth to discovered planets, to highlight which are closest and would be accessible candidates for future missions.

---

## 📚 About the Dataset

The data used comes from the **NASA Exoplanet Archive**, a public repository of data collected by space missions, ground-based observatories, and scientific studies. In this case, we use the main catalog known as the **Planetary Systems (PS) Table**, which contains standardized information on thousands of confirmed exoplanets.

Some of the most relevant variables in this dataset include:

- `pl_name`: planet name  
- `pl_rade`: planet radius (in Earth radii)  
- `pl_bmasse`: planet mass (in Earth masses)  
- `pl_eqt`: planet equilibrium temperature (in Kelvin)  
- `st_teff`: host star temperature  
- `sy_dist`: distance from the planetary system to Earth (in parsecs)  

The dataset is in CSV format and is accessed directly via a URL that queries the file’s TAP (Table Access Protocol) system. This ensures the information is **up-to-date and complete** at the time of analysis.

---

## 🛠️ Tools Used

To carry out this analysis, we use Python data-science ecosystem tools such as:  
- **Pandas** for tabular data manipulation and analysis  
- **NumPy** for numerical computations  
- **Matplotlib** and **Seaborn** for data visualization  
---

