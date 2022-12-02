# COMP603_Assignment_IMDBwebscrapiing
In this assignment you will learn to scrape multiple web pages with Python using BeautifulSoup and requests. We’ll then perform some simple analysis using pandas, and matplotlib.  We will be scraping IMDB for the movies across a decade (2010-2020) and compare the metascore and the IMDB rating.  

To Do’s for the assignment (50 Marks)

Gather the data

●	Loop through the years_url list to vary the release_date parameter of the URL (5 Marks)

●	For each element in years_url, loop through the pages list to vary the page parameter of the URL (5 Marks)

●	Pause the loop for a time interval between 8 and 15 seconds (2 Marks)

●	Throw a warning for non-200 status codes (3 Marks)

●	Break the loop if the number of requests is greater than the 70 expected. (2 Marks)

Parse the data with Beautiful Soup

●	Convert the response‘s HTML content to a BeautifulSoup object (2 Marks)

●	Extract all movie containers from this BeautifulSoup object (3 Marks)

●	Loop through all these containers (3 Marks)

●	Extract the data if a container has a Metascore (2 Marks)

Manipulate the data with Pandas

●	Create a Pandas Dataframe to hold the info scraped (movie, years imdb_ratings, metascore, votes) (5 Marks)

●	Write the Pandas Dataframe to a CSV (3 Marks)

Visualize the data with matplotlib

●	Use matplotlib to create two histograms to visually compare the average IMDB rating to the average metascore rating (15 Marks)

