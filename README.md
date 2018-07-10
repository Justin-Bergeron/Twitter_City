# Twitter_City
A sentiment analysis based on twitter keywords

This program will return a Vader sentiment analysis for a given keyword based on tweets 
referencing that keyword in the largest 1000 cities in the United States. 
It takes about 6 hours to run due to twitter API limitations. 


 1. Youll have to install plot.ly for the map: pip install plotly.  
 2. Add your Twitter keys.  
 3. Download the JSON file and put it in the same directory as this notebook https://gist.github.com/Miserlou/c5cd8364bf9b2420bb29  Shoutout to this human for making the cities json file.  
 4. Make your output directory for the CSV.  
 5. Change jsonlen to the number of cities that you want to do, full list is 1000 test it with five first.  
 6. Change search_term to your search term.  
 7. Run the code. should take about 6 hours. Nothing will show up in the CSV file till it's done. just let it do its thing.  
 7. In next cell change the csv file to your output file for pandas.  
 8. In the plotly cell just change the title of the map. there should be a new window that opens with the map.   
 9. In the top righthand corner of the window there is a button to download it as a PNG.   
 10. Profit.  
