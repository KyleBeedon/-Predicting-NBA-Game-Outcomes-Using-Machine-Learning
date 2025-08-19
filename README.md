This project was my senior practicum and focuses on predicting NBA game outcomes using aggregates of advanced team statistics, such as Net Rating and Effective Field Goal Percentage (eFG%), along with other relevant details about each game, such as which team was playing at home.

Data was scraped from Basketball-Reference.com using the BoxScoreScraper.ipynb notebook, which produced box_scores.csv. The raw dataset was then cleaned and aggregated using R in the DataCleaning.Rmd file, resulting in Final.csv. Machine learning models were implemented and tested in the Practicum.ipynb notebook.

The full project report was written in OverLeaf and exported as a PDF, which can be found in the OutputPDF folder. Notably, the SVM model achieved a 69.6% accuracy in predicting games for the 2025 NBA season.
