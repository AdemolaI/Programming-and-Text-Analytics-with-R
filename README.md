# Sentiment-Analysis-of-TED-Talk-Data-with-R

The project is aimed at analysing TED Talk data from two speakers to observe patterns and draw useful insights about each speaker's talk, especially on how they may be perceived by a listening audience.
This project was executed using R programming.

## Major processes in the project.

📌 The TED Talk data was Tidied and tokenised for the two speakers with stopwords removed using the tidytext package.

📌 Sentiment data was generated using the get sentiment function from the tidytext package and the NRC lexicon.

📌 The odd ratio and logarithm of the sentiment words were computed and visualised to observe patterns.

## Key Findings 
📍 Sentiments such as joy, positive, trust, surprise and anticipation were found more in the second speaker's words (Ted Halstead's transcript) than in the first speaker's words (Laurie Garrett).

📍 Sentiments such as disgust, anger, sadness, negative, and fear were found more in the first speaker's words (Laurie Garrett's transcript) than in the second speaker's words (Ted Halstead). 

📍 Ted Halstead's talk was about a solution where everyone wins and this makes it more on the positive side than Laurie Garrett who spoke about a pandemic that could have stirred up urgency and some level of fear for actions to be taken.
