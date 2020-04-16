# Using sentiment analysis to visualize character arcs in ATLA TV series
A beginner end-to-end NLP data science project.

# Motivation and project description
I was curious to see if sentiment scores could be used to visualize character arcs. If so, could sentiment analysis be used to help writers evaluate character development in their work?

For this project, I analyzed one of my favorite TV shows, *Avatar: The Last Airbender (ATLA).*

See how I:
1) Scraped the web for episode transcripts with BeautifulSoup
2) Analyzed character dialogue with VADER (a lexicon and rule-based sentiment analysis tool)
3) Visualized the sentiment scores with Plotly Express

The outcome of this project are two [interactive visualizations](https://plotly.com/~ritakalach/4/) that show the sentiment progression of six *ATLA* characters. For more information, read the accompanying [blog post.](https://medium.com/data-comet/atla-sentiment-analysis-43f26edddad2)

# Running the code
Necessary packages:
* pandas
* numpy
* statistics
* requests
* BeautifulSoup
* re
* nltk
* vaderSentiment
* plotly

You need to have [Jupyter Notebook](https://jupyter.readthedocs.io/en/latest/install.html) installed on your computer. Download [atla_sentiment_analysis.ipynb](atla_sentiment_analysis.ipynb) to current directory and open Jupyter Notebook by running `jupyter notebook` in the command line.
