# Spotify-Sentiment-Analysis
Data Source
This dataset was collected from the Google Play Store, containing 31,500 Indonesian-language reviews of the Spotify app. Spotify was chosen due to its large user base in Indonesia, resulting in a high volume of diverse reviews that reflect user sentiment toward the app’s services.

Scraping Method
Reviews were scraped using the google-play-scraper library with the package name com.spotify.music. Parameters were configured to retrieve reviews in Indonesian and from the Indonesian region. Reviews were collected using relevance-based sorting to capture the most representative user experiences.
The scraped data was processed with pandas to create a DataFrame, and the most relevant fields were selected for analysis: review text, rating score, review date/time, and username. The final dataset was exported as a CSV file for further sentiment analysis.
