# Manga-Metrics-Visualizing-Anime-Data
____
![img_anime](<img/manga_img.png>)


##  📌 Index
-  [About the Project](#-about-the-project)  
-  [Main Features](#-main-features)  
-  [Current Issues](#-current-issues)
-  [Folder Structure](#-folder-structure)
-  [Possible Improvements](#-possible-improvements)   
-  [Technologies Used & Dependencies](#-technologies-used-&-dependencies)   
-  [Installation and Usage](#-installation-and-usage)   
-  [Collaborators](#-collaborators)   

---

##  About the Project  

This project focuses on **data cleaning and exploratory data analysis (EDA)** of manga-related data sourced from Kaggle, originally collected from [MyAnimeList](https://myanimelist.net/). The dataset consists of **14,966 rows and 24 columns**, covering manga published from **1961 to March 2025**. The project aims to infer missing values, remove unnecessary columns, and conduct hypothesis-driven analysis. Additionally, a **storytelling approach** and a final **analysis report** have been created to summarize key findings.

---

##  Main Features  
✅ Data preprocessing: cleaning, handling missing values, and feature selection.  
✅ Hypothesis testing and exploratory analysis to uncover trends.  
✅ Data visualization for deeper insights into manga trends.  
✅ Storytelling-driven report to communicate findings effectively.  
✅ Dataset sourced from Kaggle and MyAnimeList for reliable data.  

---

##  Current Issues  
❌ Dataset updates are not automated beyond March 2025.  
❌ Limited metadata on user interactions and ratings.  

---

##  Possible Improvements  
✅ Integrate additional datasets for richer insights.  
✅ Develop an automated pipeline for data updates.  
✅ Enhance visualizations with interactive dashboards.  
✅ Implement machine learning models for trend prediction.  

---
## Folder Structure

```bash
📂 Manga-Data-Analysis/  
├── 📂 data/                    
│   ├── cleaned_data.csv  
│   └──top_anime_dataset_v2.csv          
│
├── 📂 eda/                 
│   ├── analysis_anime.ipynb
│   ├── clean_data.ipynb  
│   └── statistical_hypothesis.ipynb  
│
├── 📂 img/    
│   └── manga_img.png
│  
│
├── 📜 .gitignore      
├── 📜 informe_EDA.pdf
├── 📜 pyproject.toml  
├── 📜 README.md
├── 📜 requirements.txt 
```
---

## Technologies Used & Dependencies

![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)  
![Jupyter](https://img.shields.io/badge/-Jupyter-FF3C00?logo=jupyter&logoColor=white)  
![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?logo=matplotlib&logoColor=white)  
![Plotly](https://img.shields.io/badge/-Plotly-3F4B8F?logo=plotly&logoColor=white)  
![Seaborn](https://img.shields.io/badge/-Seaborn-FF5851?logo=seaborn&logoColor=white)  
![Pandas](https://img.shields.io/badge/-Pandas-150458?logo=pandas&logoColor=white)
![Numpy](https://img.shields.io/badge/-NumPy-013243?logo=numpy&logoColor=white)  
![Scipy](https://img.shields.io/badge/-SciPy-8C150D?logo=scipy&logoColor=white)  
![Scikit-learn](https://img.shields.io/badge/-Scikit--learn-F7931E?logo=scikit-learn&logoColor=white)  
---

## Installation and Usage  

### 1️⃣ Clone the Repository  
```bash
 git clone https://github.com/Yael-Parra/Manga-Metrics-Visualizing-Anime-Data.git # Better check the correct link in the code button
 cd Manga-Metrics-Visualizing-Anime-Data
```

### 2️⃣ Setting up the environment and dependencies  
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the code
```bash
jupyter notebook eda/clean_data.ipynb
jupyter notebook eda/analysis_anime.ipynb
jupyter notebook eda/statistical_hypothesis.ipynb
```

---
## 🧑‍💻 Collaborators  
This project was developed by the following contributors:  
- [Yael Parra](https://www.linkedin.com/in/yael-parra/)  
- [Orlando Alcalá](https://www.linkedin.com/in/orlando-david-71417411b/)   
- [Noheli Salazar](https://www.linkedin.com/in/nhoeli-salazar/)   
- [Fernando García](https://www.linkedin.com/in/fernandogarciacatalan/)   

If you have any feedback or suggestions, feel free to reach out!

