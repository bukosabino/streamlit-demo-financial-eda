# Automated EDA on financial dataset

Just a simple way to get automated Exploration Data Analysis from financial dataset (OHLCV) using [Streamlit](https://github.com/streamlit/streamlit) and [ta](github.com/bukosabino/ta).

To use this library you need a financial time series dataset including “Timestamp”, “Open”, “High”, “Low”, “Close” and “Volume” columns.


# Requirements

* python3.7 version


# Run

```sh
pip install --upgrade streamlit ta
streamlit run https://raw.githubusercontent.com/bukosabino/streamlit-demo-financial-eda/master/app.py
```


# TODO

* Use cache streamlit system
* Heatmap: Visualize the correlation coefficient in between ta features.
* Web application user can load a .csv file


# Contact

Developed by Darío López Padial (Bukosabino).

Please, let me know about any comment or feedback.
