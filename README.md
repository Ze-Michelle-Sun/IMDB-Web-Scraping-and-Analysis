![image](https://github.com/Ze-Michelle-Sun/IMDB-Web-Scraping-and-Analysis/assets/110506170/f58a2151-ebb4-4572-ab99-a15901fba1ad)
# IMDB Webscraping and Analysis
In this project, scrape multiple web pages with Python using BeautifulSoup and requests. Then perform some simple analysis using pandas and matplotlib.
Scraping IMDB for the movies across a decade (2010-2020) and compare the metascore and the IMDB rating.  

## Gather the data

●	Loop through the years_url list to vary the release_date parameter of the URL

●	For each element in years_url, loop through the pages list to vary the page parameter of the URL

●	Pause the loop for a time interval between 8 and 15 seconds

●	Throw a warning for non-200 status codes

●	Break the loop if the number of requests is greater than the 70 expected

## Parse the data with Beautiful Soup

●	Convert the response‘s HTML content to a BeautifulSoup object

●	Extract all movie containers from this BeautifulSoup object

●	Loop through all these containers

●	Extract the data if a container has a Metascore

## Manipulate the data with Pandas

●	Create a Pandas Dataframe to hold the info scraped (movie, years imdb_ratings, metascore, votes)

●	Write the Pandas Dataframe to a CSV file

## Visualize the data with matplotlib

●	Use matplotlib to create two histograms to visually compare the average IMDB rating to the average metascore rating

