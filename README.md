# Crypto-Portfolio-Proposal-Prototype

A KMeans Cluster analysis on crypto market data to determine the best k value to use in order to cluster cryptocurrencies based on profitability.

---

## Technologies

This application runs on python version 3.7, with the following add-ons:

* [Jupyter](https://jupyter.org/) - A development tool for interactive programming.

* [Pandas](https://pandas.pydata.org/) - A python librart for data analysis and manipulation.

* [Scikit-learn](https://scikit-learn.org/stable/) - A python library for machine learning models.

* [hvplot](https://hvplot.holoviz.org/) - A high level API for plotting data.

---

## Installation Guide

Download and set up Jupyter Lab with Anaconda: [Click here](https://www.anaconda.com/products/individual)

Run the following commands in your terminal

Build and activate a conda environment:

    conda create -n dev python=3.7 anaconda

    conda activate dev

Install pyviz and set up jupyter to show hvplot:

    conda install -c plotly plotly=4.13.

    conda install -c pyviz hvplot

    jupyter labextension install jupyterlab-plotly@4.13.0

    jupyter labextension install @jupyter-widgets/jupyterlab-manager plotlywidget@4.13.0

    jupyter labextension install @pyviz/jupyterlab_pyviz

    jupyter lab build

Install pandas and SciKit-Learn:

    pip install pandas

    pip install -U scikit-learn

Open Anaconda and run Jupyter lab. Go to project directory and open the file named:

    crypto_investments.ipynb

Click on each cell to run individually:

    Shift + Enter

---

## Example

Running this cell provides a plot of the KMeans clusters for the market data with k=4

![Code Example](https://github.com/talibkateeb/Crypto-Portfolio-Proposal-Prototype/blob/main/Example.png)

---

## Contributors

*  Talib Kateeb

---

## License

[Click Here To View](https://github.com/talibkateeb/Crypto-Portfolio-Proposal-Prototype/blob/main/LICENSE)
