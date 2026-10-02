# Student Performance Analysis

Exploratory analysis of the Python and Database exam scores of 77 students.

**Dataset:** "BI intro to data cleaning, EDA and machine learning" by Walekhwa Tambiti Leo Philip (Kaggle, CC0).

## What I did
- Cleaned inconsistent labels: 6 gender spellings merged into 2, 10 misspelled previous-education labels merged into 5
- Removed 2 records with missing scores (77 to 75 students)
- Calculated an average score and a pass/fail result (assumption: pass = 40 or more in both subjects; the dataset has no official pass mark)
- Compared scores by gender and previous education, and plotted histograms, box plots, bar charts and a correlation heatmap

## Findings (75 students)
- Pass rate: 93.3%
- Average score by previous education: Masters 79.1, Bachelors 75.4, Doctorate 72.7, Diploma 69.5, High School 65.4
- Correlation between Python and DB scores: 0.45
- Small sample, so these are observations and not general conclusions

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Google Colab
