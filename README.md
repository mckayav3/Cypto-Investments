# Module_10_Challenge: Cypto Investments

This application analyzes cryptocurrencies and their performances over different periods of time. After analyzing the cryptocurrencies their results are then plotted to make a comprehensive assessment of the visualizations of the data.

---

## Technologies


This was run on a pc using Windows 10

This project leverages python 3.8.8 with the following packages:


* [pandas](https://pandas.pydata.org/docs) - For manipulating the DataFrame.

* [Jupyter Lab](https://jupyterlab.readthedocs.io.en/stable) - For code and visualizations.

* [hvplot](https://hvplot.holoviz.org/user_guide/Introduction.html) - For creating the visualization of our data from the DataFrame.

* [KMeans](https://scikit-learn.org/stable/modules/clustering.html#k-means) - For separating samples in n groups of equal variance

* [PCA](https://scikit-learn.org/stable/modules/decomposition.html#principal-component-analysis-pca) - PCA is used to decompose a multivariate dataset in a set of successive orthogonal components that explain a maximum amount of the variance.

* [Standard Scaler](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html) - Standardize features by removing the mean and scaling to unit variance

---

## Installation Guide

In gitbash after you have activated your dev environment, install the following:

```python
  pip install jupyter lab
```

*Pyviz Hvplot

    `conda install -c pyviz hvplot`
    
![install pyviz hvplot](https://github.com/mckayav3/Module7_Challenge/blob/main/images/install_pyviz_hvplot.JPG)


*Scikit Learn

    `conda install -U scikit-learn`
    
![install scikit-learn](https://github.com/mckayav3/Module_10_Challenge/blob/main/images/install_scikitlearn.png)

---

## Examples

The images below show the different types of charts and graphs that should be a result from running the code in the Crypto Investments application. By reviewing the charts and graphs we can conclude the best outcome for the Crypto Investment portfolio.

![market dataframe](https://github.com/mckayav3/Module_10_Challenge/blob/main/images/df_market_data.png)

![hvplot market dataframe](https://github.com/mckayav3/Module_10_Challenge/blob/main/images/hvplot_df_market_data.png)

![scaled market data](https://github.com/mckayav3/Module_10_Challenge/blob/main/images/scaled_df_market_data.png)

![scatter plot](https://github.com/mckayav3/Module_10_Challenge/tree/main/images)

![elbow curve](https://github.com/mckayav3/Module_10_Challenge/blob/main/images/elbow_hvplot.png)

