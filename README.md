# Mars News Challenge
![image](https://github.com/carojasp12/Mars_News_Challenge/assets/152667250/e1914fa1-a7dc-4cbb-bcd4-c647334617ca)

## Learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup.

### Part 1: Scrape Titles and Preview Text from Mars News

We instantiate a Beautiful Soup object to parse the HTML structure of news articles, enabling extraction of titles and preview text. Subsequently, we organize the scraped data into Python dictionaries, assigning each dictionary two keys: "title" and "preview". Finally, we aggregate these dictionaries within a Python list for comprehensive storage and manipulation.

### Part 2: Scrape and Analyze Mars Weather Data

We instantiate a Beautiful Soup object to facilitate the extraction of data from the HTML table. Subsequently, the scraped data is organized into a Pandas Data Frame for structured analysis. Upon examination, the data types associated with each column are reviewed, and appropriate conversions to datetime, int, or float data types are made as necessary. Finally, we address the following inquiries:

-	How many months exist on Mars?
  
    Mars has twelve months. 
-	How many Martian (and not Earth) days’ worth of data exist in the scraped dataset?
  
    There are 1867 Martian days’ worth of data.
-	What are the coldest and the warmest months on Mars?
  
    On average, the third month has the coldest minimum temperature on Mars, and the eighth month is the warmest.
-	Find the average minimum daily temperature for all the months and plot the results as a bar chart.
  ![image](https://github.com/carojasp12/Mars_News_Challenge/assets/152667250/152b7232-2302-4fb6-a830-53d482f7c460)
-	Which months have the lowest and the highest atmospheric pressure on Mars?
  
    Atmospheric pressure is, on average, lowest in the sixth month and highest in the ninth.
-	Find the average daily atmospheric pressure of all the months and plot the results as a bar chart.
  ![image](https://github.com/carojasp12/Mars_News_Challenge/assets/152667250/f60be811-0e74-403e-98e5-8be4cb2614ea)
-	About how many terrestrial (Earth) days exist in a Martian year?
  
    A year on Mars appears to be about 675 days. 
-	Visually estimate the result by plotting the daily minimum temperature.
![image](https://github.com/carojasp12/Mars_News_Challenge/assets/152667250/a3e2ecb9-ea3b-43f1-bb27-ee948bb402bf)

Finally, we export the DataFrame to a CSV file.
