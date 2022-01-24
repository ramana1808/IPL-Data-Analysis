# IPL-Data-Analysis
With the IPL getting bigger by the day, it involved Big money and the stakeholders involved are trying their best to do everything they can for their team to get an edge over the others. 
Having already completed 14 seasons, there is enough data about the players, teams and venue to work with in order to roll out statistics and predictions. 
This project revolves around being able to extract meaningful information and statistics from the data available using exploratory data analysis and trying to predict the winner and score of the match after each ball using various machine learning and deep learning algorithms.  

The data required for the project was taken from www.kaggle.com. Two datasets have been used. One for overall matches data and one for ball-to-ball data for the full 2008-2020 period. Both the datasets are linked by the ’id’ column which represents the matches uniquely. 
Both datasets have been merged into a single dataset and unnecessary columns and columns with too many missing values have been removed with the other missing values being replaced by suitable alternatives. Wrong spellings and duplicate entries were also corrected. New columns have been introduced for cumulative runs and wickets of a match, denoting a unique innings and the total score of an innings, to aid with the analysis process.
