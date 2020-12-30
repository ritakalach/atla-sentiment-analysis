# Using Sentiment Analysis to Visualize Character Arcs in Avatar: The Last Airbender
End-to-end data science project in Python: 1) data scraping, 2) sentiment analysis, 3) and data visualization.
<img src="media/zuko_art.jpg" height = 400>

# Motivation and project description
I was curious to see if sentiment scores could be used to visualize character arcs. If so, could sentiment analysis help writers evaluate character development in their work?

For this project, I analyzed one of my favorite TV shows *Avatar: The Last Airbender.* I used Jupyter Notebook to document my project. Follow along to see how to:
1) Scrape the web for episode transcripts with *Beautiful Soup*
2) Analyze character dialogue using *VADER*
3) Create interactive visualizations of the sentiment scores with *Plotly Express*

See the accompanying [Medium blog post](https://medium.com/data-comet/atla-sentiment-analysis-43f26edddad2) for detailed tutorial and discussion of project takeaways.


# Visualizations
Below are the two interactive visualizations created with *Plotly Express*. (Click image to interact.)
<div>
    <a href="https://plotly.com/~ritakalach/4/" target="_blank" title="atla_total_sentiment" style="display: block; text-align: center;"><img src="https://plotly.com/~ritakalach/4.png" alt="atla_total_sentiment" style="max-width: 100%;width: 475px;"  width="475" onerror="this.onerror=null;this.src='https://plotly.com/404.png';" /></a>
</div>

<div>
    <a href="https://plotly.com/~ritakalach/2/" target="_blank" title="atla_sentiment" style="display: block; text-align: center;"><img src="https://plotly.com/~ritakalach/2.png" alt="atla_sentiment" style="max-width: 100%;width: 475px;"  width="475" onerror="this.onerror=null;this.src='https://plotly.com/404.png';" /></a>
</div>


# Running the code
You need to have [Jupyter Notebook](https://jupyter.readthedocs.io/en/latest/install.html) installed on your computer. Download [atla_sentiment_analysis.ipynb](atla_sentiment_analysis.ipynb) to current directory and open Jupyter Notebook by running `jupyter notebook` in the command line.
