# AllInOneBuffet
My project is called the "All In One Buffet." This tailors both of my interests and uses it for societal and personal impact/growth. These 2 areas include stocks and Covid-19. The four programs I developed include Covid19 Visualization, Stock Price prediction using linear regression, Stock Sentiment Analysis using news headlines, and Covid19 Twitter sentiment analysis. These 4 programs are combined together in a console-based project which is demonstrated in the video. Stocks and Covid-19 include many numbers, data, and a lot of other statistics but I wanted to create a way that will make this entire process easier. Through sentiment analysis, it provides such a simple way to interpret key trends and stigma surrounding it without having to read through all the articles and understanding all the numbers. The visualization portion helps increase the understanding of the user in terms of stock growth and Covid19 in perspective. I plan on building it through the Tweepy API, Quandl API, NLTK Vader for sentiment analysis, Pandas for data frames, Beautiful Soup to parse HTML Data, and MatplotLib for beautified visualizations to put it all in retrospect.

What Problem it Addresses: This All In One Buffet addresses problems socially and helps personally. Usually, people have a tough time understanding the context of the problems around them and there is a lot of information on social media and the internet. This takes time to read through and analyze and form your own opinion. Personally, it is very hard for me to understand all the stock trends and decide whether to buy or not. It is also hard for me to generalize all Covid-19 data because there is always new news and data that is misinformed in the wrong way because of politics (Example: Fox News and CNN). Through sentiment analysis, you are able to easily interpret the charts generated by understanding the trends for each day, trends for each topic, and what society thinks about it simply on a scale of -1 to 1. -1 means that it is very negative and 1 means it is very positive. The societal impact comes from the covid-19 part and personal impact comes from the stocks part. The covid-19 visualization allows people to put the Covid-19 journey in perspective and visualize all the data from the past year in many different ways rather than always believing the media opinions (Daily US cases and deaths stacked upon each other, worldwide cases trends, and US vs Worldwide cases trends). The personal impact comes from stock predictions as it allows you to make better forecasts in the future and this can lead to greater financial independence. 

How it Works: This is a console-based program so all of the activity comes from the console. It starts by entering what you want to do today (StockSentiment, CovidSentiment, CovidVisualization, Stock Prediction). 
StockSentiment Use Case: After you say you want to do StockSentiment, it asks you what stocks you want to apply sentiment analysis on (Ex: AAPL AAL AMZN TSLA). Then, it generates a bar chart with a compound value of the stock news for the past month. You can compare and contrast the sentiment analysis with multiple stocks and this can help you make a decision and find daily trends without scraping through the multiple news articles every day. 
CovidSentiment Use Case: After you say you want to see CovidSentiment, it generates 2 different charts and word cloud to have 3 different perspectives upon the same topic for extended societal impact. First, it shows you the sentiment of tweets by Covid-19 and the frequency of each category. (Ex: 120 tweets in 0.0 sentiment, 40 tweets, in 0.1 sentiment, etc.).  In the Daily Average graph in the middle, it shows you roughly the last month daily averages through a beautifully generated chart. This can give the person a general overview of how Covid-19 was that day and whether it was a bad day, such as setting a new deaths record or a good day, such as vaccine distribution increasing, without having to read through all the news articles and form your own opinion. Finally, it shows a Wordcloud and this shows “What is on Society’s mind” as it generates a list of the most used words by Covid-19 to find the current stigma surrounding it. This is not predefined data and always updates as more tweets by Covid-19 are posted.
CovidVisualization Use Case: After you say you want to see CovidVisualization, it generates 3 different charts to interpret upon based on different scopes. One is based on the country’s daily cases and deaths stacked upon each other, another compares world cases types (confirmed, recovered, deaths), and another compares US vs world total cases. This helps create a generalization upon the larger context of the world while also understanding the true nature of Covid-19.
Stock Prediction Use Case: After you say you want to see Stock Prediction, it asks you what stock you want to predict upon (Ex: Apple = AAPL). After you input this value, it generates 2 different charts. The 1st chart just shows the graph of the stock in its max value (from its IPO to 2018). The 2nd chart is the one where linear regression is applied on. The green part is the actual data of the stock pulled from Quandl and the yellow part is the model generated after applying the algorithm (linear regression) to find the stock price 730 days in the future.


What Technologies it Uses:
•	NLTK Vader – Sentiment Analysis
•	Web Scraping to extract Data – Beautiful Soup
•	MatPlotLib – display visualizations of several different graphs
•	Tweepy API – extract Covid 19 information
•	Quandl API – receive stock data till 2018 to perform linear regression on
•	Pandas – dataframes for raw github data 

