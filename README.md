This is a bot using nltk and vader_lexicon to analyze the sentiment of Elon musk tweets and use it as a signal to trade.

We first download the CSV data and use encoder latin1 to make it readable.

Then we import the analyse sentiment function from nltk.

We code the if condition on our function depending on the score it returns we consider it positive or negative.

We iterated through the tweets and only saved the ones with either TESLA or TSLA in them.

We apply our function to the tweets and get a positive or negative sentiment depending on what words are used in the tweet.

Then with that signal, we buy or sell the stock Tesla depending on the sentiment of the tweet.
