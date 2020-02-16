# Credit Analysis

## Introdução

O objetivo desta análise é construir um modelo de classificação que retorne a probabilidade que um cliente tem de ser enviado para análise de crédito dado que ele foi pré-aprovado para um empréstimo com garantia de automóvel. Esta probabilidade será utilizada para priorizar o atendimento aos clientes, de forma que aqueles que tenham uma maior probabilidade de serem enviados para análise de crédito sejam atendidos primeiro.

## Dependências

A análise foi desenvolvida utilizando Python 3.7.3 com [Jupyter Notebook](https://jupyter.org) 5.7.8.

 Adicionalmente, os seguintes pacotes foram utilizados:

- [gensim](https://radimrehurek.com/gensim/) 3.8.1
- [ipywidgets](https://ipywidgets.readthedocs.io/en/stable/user_install.html) 7.5.0
- [nltk](http://www.nltk.org) 3.4.1
- [numpy](https://numpy.org) 1.16.4
- [pandas](https://pandas.pydata.org) 0.24.2
- [seaborn](https://seaborn.pydata.org) 0.9.0
- [sklearn](https://scikit-learn.org/stable/) 0.22.1
- [spacy](https://spacy.io) 2.2.2
- [textacy](https://github.com/chartbeat-labs/textacy) 0.9.1
- [XGBoost](https://xgboost.readthedocs.io/en/latest/index.html) 0.90

## Instruções

Para rodar o notebook, execute `jupyter notebook` no terminal e navegue até o diretório contendo o arquivo `solution.ipynb`. O arquivo `dataset.csv`, contendo os dados utilizados na análise, deve ser colocado dentro de um diretório `data`, localizado no mesmo diretório do arquivo do notebook.
