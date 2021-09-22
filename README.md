# Content: # EV Sales in Spain
## Project: Wrangle and Analyze Data

How EV sales have increased in the past decade in Spain? Which are the main players? This project tries to answer these very questions.

### Install

This project requires **Python 3.7.6** and the following Python libraries installed:

- [Requests](https://www.pythonforbeginners.com/requests/using-requests-in-python)
- [io](https://docs.python.org/2/library/io.html)
- [bs4](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [os](https://docs.python.org/2/library/os.html)
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [chartstudio&plotly](https://plotly.com/chart-studio/)


You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](https://repo.anaconda.com/archive/) distribution of Python, which already has the above packages and more included. Specify the python version by running:

```bash
conda install python=3.7.6 anaconda=custom
```

### Code

Template code is provided in the `evSalesSpain.ipynb` notebook file.


## Data

The data is wrangled from ANIACAM (Asociación Nacional de Importadores de Automóviles, Camiones, Autobuses y Motocicletas) website, an Spanish association that collects data about car registrations in the whole Spanish territory, including the Canary Islands, since 1977. The data is extracted from monthly xls files, *Modelos* page, from January 2011 to December 2019.
