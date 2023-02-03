# challenge14
The purpose of this project is use build a trading algorithm which uses machine learning to adapt to new data.  Multiple Algorithms were made and tested over 2 different machine learning protocols.

The original algorithm left much to be desired.
![Original Setup](/images/originalsetup.png)

Reducing the training period slightly impoved results.
![Reduced Training](/images/offset3days505dma.png)

We found much better results by changing the signal to rely on closing price and one moving average, as opposed to just two moving averages.
![SMA Over Close](/images/output.png)

However it still very slightly underperformed the market due to falling behind in the learning stage.
Our model closely followed the performance of the market, so adjusting the time period affected the model similarly to how it affected the market <br>
![2020](/images/2020.png)

## Technologies
This project was created with on JupyterLab with python v3.7.13.  It also uses the packages pandas, sklearn and hvPlot

[pandas](https://pandas.pydata.org/) is an open source data analysis and manipulation tool.

[hvPlot](https://hvplot.holoviz.org/index.html)  high-level API for data exploration and visualization

[scikit-learn](https://scikit-learn.org/stable/) is a simple and efficient machine learning tool for predictive data analysis.

---
## Strategy Results 
We found that the Adaboost classifier performed better than the SVM classifier, however the market performance of both was very similar
![Classification Results](/images/classreport.png)
![Market Performance](/images/output2.png)
## Installation Guide

Be sure to have python, jupyterlab, sklearn, and pandas installed before running the data.  To download Python, visit (https://www.python.org/downloads/).  Pandas and sklearn can be installed with the pip in terminal.  

---

## Usage
To use this data, download the machine_learning_trading_bot.ipynb file from the repository at (https://github.com/jeffreycrabill/challenge14.  Open up the venture_funding_with_deep_learning.ipynbS file in VS Code or a Juypter Lab Kernel.  <br>



---

## Contributors
Created by Jeffrey Crabill  
jeffreycrabill@gmail.com  
[twitter](twitter.com/jeffcrabill)  
[linkedIn](linkedin.com/jeffreycrabill)  

---

## License

GNU