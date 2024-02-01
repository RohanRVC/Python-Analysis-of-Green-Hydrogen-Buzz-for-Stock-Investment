# Python-Analysis-of-Green-Hydrogen-Buzz-for-Stock-Investment

## Of late there has been a sudden interest in the term “Green Hydrogen”. As an investor you spend a major part of your time to find such trends and invest in it earlier than everyone else understands it. So you are required to write a python program to figure out the buzz around green hydrogen and what all are the stocks that could benefit due sudden popularity of green hydrogen

* Scraped headlines related to "green hydrogen" from CNBC's website.
* Retrieved news headlines containing "green hydrogen" keyword from Google News  RSS feed.
* Stored the results in a pandas DataFrame, including news date.
* Applied sentiment analysis using a pre-trained model from Hugging Face, adding a sentiment score column to the DataFrame.
* Produced a word cloud map highlighting the organization names identified in the news headlines.
* ![image](https://github.com/RohanRVC/Python-Analysis-of-Green-Hydrogen-Buzz-for-Stock-Investment/assets/80825254/791d0da4-1c5a-410f-832f-5a21f58acfd8)
* Created a graph illustrating the week-wise trend of average sentiment scores for all news headlines.
![image](https://github.com/RohanRVC/Python-Analysis-of-Green-Hydrogen-Buzz-for-Stock-Investment/assets/80825254/3f48ff04-6183-4afa-8dc2-e236a6bdb461)

* Utilized a Hugging Face NER model to identify organization names in news headlines.
* Generated a CSV table containing news date, headline, and source.
* Transferred the CSV table to a Google Sheet using the Google Sheets Python API with access rights set to "Anyone with the Link".
