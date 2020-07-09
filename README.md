# Stock Trading with Machine Learning

## Overview

A stock trading bot that uses machine learning to make price predictions.

## Requirements

-   Python 3.5+
-   Pipenv
-   alpha_vantage
-   pandas
-   numpy
-   sklearn
-   keras
-   tensorflow
-   matplotlib
-   python-dotenv

## Documentation

[Blog Post](https://yacoubahmed.me/blog/stock-prediction-ml)

[Medium Article](https://medium.com/towards-data-science/getting-rich-quick-with-machine-learning-and-stock-market-predictions-696802da94fe)

## Train your own model

1. Clone the repo
2. Set variable `export PIPENV_VENV_IN_PROJECT=1`
3. Create environment `pipenv shell`
4. Install required packages `pipenv install`
5. Setup `.env` File
6. Save the stock price history to a csv file `python save_data_to_csv.py --help`
7. Optional - Edit model architecture
8. Edit dataset preprocessing / history_points inside util.py
9. Train the model `python tech_ind_model.py --help` or `python basic_model.py --help`
10. Try the trading algorithm on the newly saved model `python trading_algo.py`

## License

[GPL-3.0](https://www.gnu.org/licenses/quick-guide-gplv3.html)
