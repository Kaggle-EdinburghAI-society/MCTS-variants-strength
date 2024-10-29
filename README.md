# MCTS-variants-strength
This repository contains code and resources for predicting the game-playing strength of MCTS (Monte Carlo Tree Search) variants.
[Competition Overview on Kaggle](https://www.kaggle.com/competitions/um-game-playing-strength-of-mcts-variants/overview)

## Downloading the data
If you plan on running the code in this repository, you can download the data from the competition page on Kaggle. You can also use the Kaggle API to download the data. To do this, you need to install the Kaggle API and authenticate it with your Kaggle account. After you create an API token, you should see a kaggle.json file in your downloads directory. Make sure the file is moved it to the following path in your home `directory ~/.kaggle/kaggle.json` . 

You can then installe the kaggle CLI tool and download the data by running the following command in the terminal:
```
pip install kaggle
kaggle competitions download -c um-game-playing-strength-of-mcts-variants -p ./kaggle/input
```