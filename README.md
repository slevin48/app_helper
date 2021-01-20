# app_data

A Helper App for Python Data Projects with Streamlit
 
consumes a csv, returns a pandas pickle

![demo](demo.gif)

original article:
https://towardsdatascience.com/an-app-to-optimize-a-pandas-dataframe-with-streamlit-759a270a6d0e

App Link: 
https://share.streamlit.io/justinhchae/app_helper/main/app.py

## Data
To test and develop app, I wrote another function that creates some perfectly imperfect data to the tune of 500,000 rows and 58 MB on disk as a CSV file ([available here](https://raw.githubusercontent.com/justinhchae/app_helper/main/data/source.csv)). I like the 58 MB size because I think it’s right at the threshold of being too much to handle both on disk and in memory.

