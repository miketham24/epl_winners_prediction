Implemented the Random Forests Machine Learning Model using Python, pandas, and sci-kit learn on English Premier League data to predict the league winner.

Conclusion:

Model Performance:

Initial accuracy: 
- 47.46% (not the best)
- Improved accuracy after adding rolling averages: 62.5% (expected as rolling avg helps to smooth out short-term fluctuations and identify more trends)

Prediction Reliability:
- When predicting a win for one team and a loss for the other:
  - Correct 67.5% of the time
  - 27 correct predictions vs 13 incorrect
  - An accuracy of 67.5% usually isn't great but in the context of predicting soccer match outcomes, it's quite good since soccer usuaully is hard to predict as it has a low-scoring nature and huge potential for upsets. Upon reseach, I found that professional bookmakers actually operate with an accuracy of 55-65% so my model isn't actually too bad!

Key Improvements:
- Adding rolling averages for various stats significantly boosted model performance
- Grouping and comparing predictions for both teams in a match increased reliability

Potential Next Steps:
- Feature engineering: Create more advanced statistics or interactions
- Try other machine learning algorithms (e.g., gradient boosting, neural networks)
- Incorporate external factors like injuries, transfers, or team form
