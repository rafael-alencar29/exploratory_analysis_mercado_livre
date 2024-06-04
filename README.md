# Exploratory Analysis Mercado Livre API

This project is an exploratory analysis of the data present in mercado livre public API, which is located in this address: https://api.mercadolibre.com/sites/MLB/search?q=cofre

The script functions in the following way: A search of a product is initialized by informing its name in variable ‘product’ then a connection to the mercado livre end-point is established, then a json file is returned.

All the data analysis is done in the information present in the json file, which is converted to a dataframe object.

## 1. How the script was built

The script was constructed in the Google Colab environment, but it can also be runned in computers with Linux OS.

## 2. How to run

Google Colab or Linux Environment.

## 3. Linux Environment steps

- create a virtual environment with: python<version> -m venv virtual-environment-name
- activate virtual environment: source env/bin/activate
- pip install -r requirements.txt
- add the virtualenv as a jupyter kernel: ipython kernel install --name "local-venv" --user
- in the jupyter notebook select the kernel
