# Time-to-event analysis ld.chin

A survival analysis of lexical decision data of Mandarin Chinese with R.

_Lexical decision data for Mandarin Chinese (Tsang et al., 2018). Participants were shown a stimulus on the screen and were asked to indicate if this stimulus was a word or nonword._


### Structure overview: <br>
* (enviroment prepare)
* data overview and inspect through objective functions
* models with each individual predictor:
  1. Categorical predictor: comlexity[defined by number of (square) strokes of each word]
  2. categorical predictor: word length
  3. numerical predictor: (log) word frequency
* A model with mulutiple predictors:
  * categorical predictor: word length
  * numerical predictor: (log) word frequency
  * numerical predictor: (square) number of strokes


Originally built as Kaggle notebook. View the project:

* [HTML output](https://github.com/JINHXu/ld.chin_t2e/blob/master/__results__.html)
* [code JupyterNotebook](https://github.com/JINHXu/ld.chin_t2e/blob/master/t2e-ld-chin.ipynb)
* [@xujinghua on Kaggle](https://www.kaggle.com/xujinghua/t2e-ld-chin/data)

