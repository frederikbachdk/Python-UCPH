# Model project

Our project is titled **Markowitz' Portfolio Selection & Extensions** which is a static model of an investor seeking to maximize expected risk-weighted returns given a known distribution of returns and a given degree of risk aversion. The project shows how the risk aversion affects the optimal weighting of risk and return, and lastly we extend the model to show how allowing for dynamics changes the performance of the portfolio over time.

The **results** of the project can be seen from running [modelproject.ipynb](modelproject.ipynb).

This project **does not load any datasets**, but works with the **Yahoo! Finance API** in order to get historical return data from the Dow Jones Index. 

**Dependencies:** Apart from a standard Anaconda Python 3 installation, the project requires the following installations:

``!pip install pandas-datareader``
``!pip install scipy``
``!pip install pandas``
``!pip install pipywidgets``
``!pip install datetime``

Have fun with optimizing your portfolio of Dow Jones stocks! 
