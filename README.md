# A survival analysis of lexical decision data of Mandarin Chinese.

Lexical decision data for Mandarin Chinese (Tsang et al., 2018). Participants were shown a stimulus on the screen and were asked to indicate if this stimulus was a word or nonword.


Project Structure: <br>
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

* [HTML output]()
* [JupyterNotebook]()
* [@xujinghua on Kaggle](https://www.kaggle.com/xujinghua/t2e-ld-chin/data)

