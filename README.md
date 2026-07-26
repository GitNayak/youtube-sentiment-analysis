# YouTube Data Analysis Project

This is my data analysis project where I analyzed YouTube comments and trending video data using Python.

## What I did in this project:
- Loaded and cleaned the comments dataset (handled missing values).
- Done sentiment analysis on comments using TextBlob to see if they are positive, negative, or neutral.
- Created word clouds to see what words people use the most in positive vs negative comments.
- Counted and plotted the top 10 most common emojis.
- Combined trending video datasets from different countries.
- Checked the relationship between views, likes, and dislikes using correlation and heatmaps.
- Analyzed if punctuation in video titles has any relation to views.

## How to run it:
To run the notebook, you will need to install these libraries first:
```bash
pip install pandas numpy seaborn matplotlib textblob wordcloud emoji plotly nbformat sqlalchemy
```
Then just open `youtube_sentiment_analysis.ipynb` in VS Code or Jupyter Notebook and run the cells.
