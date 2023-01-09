# machine_learning_trading_bot

The **machine_learning_trading_bot** will enhance the existing trading signals with machine learning algorithms that can adapt to new data.

--

## Technologies

This project leverages python 3.8.15 with the following packages:

* [pandas](https://pandas.pydata.org/) - For data analysis
* [scikit-learn](https://scikit-learn.org/stable/) - For Machine Learning in Python
* [tensorflow](https://www.tensorflow.org/) -  For creating machine learning models


---

## Installation Guide

Before running the application first install the following dependencies in conda dev environment.

```python

    conda create -n dev python=3.8 anaconda

    python -m ipykernel install --user --name dev

    conda activate dev

    conda install pandas
    pip install -U scikit-learn==1.1.0   
    pip install tensorflow

    conda deactivate 
  
```

---


## Usage

To use the machine_learning_trading_bot  application simply clone the repository and run the **machine_learning_trading_bot.ipynb** with jupyter lab:

```python
    conda activate dev

    jupyter lab

    conda deactivate 
```


Plot of actual returns versus the strategy returns

![actual_returns_versus_the_strategy_returns](Images/actual_returns_versus_the_strategy_returns.png)


---

## Contributors

Kausar Hina

---

## License

MIT


