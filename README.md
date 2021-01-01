# Using Sentiment Analysis to Visualize Character Arcs in Avatar: The Last Airbender
End-to-end data science project in Python: 1) data scraping, 2) sentiment analysis, 3) and data visualization.

# Motivation and project description
[<img src="media/medium_article.png" align="right" width = 200>](https://medium.com/data-comet/atla-sentiment-analysis-43f26edddad2)
I was curious to see if sentiment scores could be used to visualize character arcs. If so, could sentiment analysis help writers evaluate character development in their work?

For this project, I analyzed one of my favorite TV shows *Avatar: The Last Airbender.* I used Jupyter Notebook for documentation. Follow along to see how to:
1) Scrape the web for episode transcripts with *Beautiful Soup*
2) Manipulate data with *pandas* and analyze character dialogue using *VADER*
3) Create interactive visualizations of the sentiment scores with *Plotly Express*

See the accompanying [Medium blog post](https://medium.com/data-comet/atla-sentiment-analysis-43f26edddad2) for detailed project tutorial.


# Interactive visualizations

[<img src="media/atla_running_total_of_sentiment.gif" width = 500>](https://chart-studio.plotly.com/~ritakalach/4/#/)
[<img src="media/atla_sentiment_per_episode.gif" width = 500>](https://chart-studio.plotly.com/~ritakalach/2/#/)

Without prior knowledge of the series, I could've guessed Azula is the villain by looking at the “Sentiment per episode” plot. Her trend line increases before a sharp decline towards the finale (typical for stories where the good guys win). See [Medium blog post](https://medium.com/data-comet/atla-sentiment-analysis-43f26edddad2) for further discussion. 

In conclusion, I don't think sentiment progression is a perfect proxy for character arcs, but in the future it might be part of a larger algorithm that’ll help writers evaluate their work.

# Running the code
You must have [Jupyter Notebook](https://jupyter.readthedocs.io/en/latest/install.html) installed on your computer. Download [atla_sentiment_analysis.ipynb](atla_sentiment_analysis.ipynb) to current directory and open Jupyter Notebook by running `jupyter notebook` in the command line.
