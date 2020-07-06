# #NLPrimaries

GOAL: ANALYZE TWEETS MENTIONING THE CURRENT 2020 DEMOCRATIC PRESIDENTIAL CANDIDATES

Data:
- Gathered data through the use of Twint — an advanced Twitter scraping tool (twint_scraper.ipynb)
- Used only verified accounts in efforts to limit the number of tweets scraped, while also capturing a larger range of dates
- Discluded tweets that mentioned multiple candidates, so not to interfere with analysis
- Removed links, images, stop words, and non-English tweets

Process:
- Performed sentiment (political_tweets.py) and subjectivity analysis, as well as TF-IDF on each tweet (political_tweets_atom.py)
- Created multiple visualizations, as can be seen in NLPrimaries.pdf in this repository
- Wrapped up analysis through topic modeling with the use of latent dirichlet allocation (LDA), in an attempt to see if tweets would be separated by candidate (also can be seen in NLPrimaries.pdf, with code in political_tweets.ipynb) 

Conclusions:
- Overall, the tweets mentioning the candidates were all very similar and thus, difficult to differentiate between candidates
- Twitter is oftentimes a polarized platform, with many negative and many positive opinions

Future Work:
- Would be interesting to compare these tweets with tweets about Trump around this time in 2016
- Build classification model and/or neural network to differentiate tweets by different candidates
  
 
 
 
