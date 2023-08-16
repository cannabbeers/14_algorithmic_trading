# 14_algorithmic_trading
Module 14 Challenge

## Dependencies
To run the trading bot, you need:

+ pandas
+ numpy
+ pathlib
+ hvplot
+ matplotlib
+ scikit-learn
+ watermark

If you have any trouble running code, follow instructions below to build new environment: `nn_ml` (Neural Network / Machine Learning Environment)

## Algorithmic Trading System Environment
For Windows, from your (base) env: copy and paste this code in your gitbash terminal 

        $ conda create -n nn_ml -y -v -c conda-forge --strict-channel-priority python=3.9 pandas jupyterlab matplotlib numpy pip scikit-learn

Add `hvplot`

        $ pip install pyviz hvplot
        
Add `watermark`

        $ pip install watermark

## Usage: 

In GitHub, navigate to my repo called `https://github.com/cannabbeers/14_algorithmic_trading/`

Open your Terminal or GitBash window

Create a folder using `mkdir` and `clone` the repo in your new directory

Activate your 'dev' environment for python 3.8 or higher

Enter `git pull` to import and then launch `Jupyter Lab` from Terminal/Git Bash prompt

Open the jupyter lab notebook: `machine_learning_trading_bot.ipynb` & run code from the top

## Baseline Performance
The bot uses short- and long-window Simple Moving Averages (SMAs) to generate trading signals. The SVC classifier model from Scikit-learn's SVM is implemented to fit the training data and make predictions based on the testing data.

## Tuning
Optimize the algorithm by adjusting the dataset size and tweaking the SMA input features. Experiment with different parameters to find the optimal trading outcomes.

## Evaluating New Classifier
The AdaBoost classifier is integrated into the system for testing. Compare the performance of the original SVC model against this new classifier.

## Evaluation Report

### Baseline Performance 
[Actual Returns vs. Strategy]('/actual_vs_strategy_returns.png')

### New Machine Learning Classifier Performance - AdaBoost
[Actual Strategy vs. AdaBoost]('/actual_vs_ada_strategy_returns.png')



---

## Contributors:

Mark Beers: 
[Linked In](https://www.linkedin.com/in/markwbeers/)

---

## License:

MIT License: A short and simple permissive license with conditions only requiring preservation of copyright and license notices. Licensed works, modifications, and larger works may be distributed under different terms and without source code.
