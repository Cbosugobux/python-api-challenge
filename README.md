Citations:

Real Python. (n.d.). Python matplotlib guide. Retrieved from https://realpython.com/python-matplotlib-guide/

Stack Overflow. (2013, April 19). Box around text in matplotlib. Retrieved from https://stackoverflow.com/questions/17086847/box-around-text-in-matplotlib

Stack Overflow. (2011, October 5). Putting text in top-left corner of matplotlib plot. Retrieved from https://stackoverflow.com/questions/8482588/putting-text-in-top-left-corner-of-matplotlib-plot

Williams, S. (11/25/2024). Helped me on Slack.


This assignment asked us to use the skills we have learned over the past several classes to use APIs and JSONify it.  We then had to filter the data and generate plots for the different comparisions
the instructions asked us to generate.  

Following the WeatherPy activity, we were asked to work on a notebook called VacationPy.  In this notebook, we were asked to load up our cities.csv file we generated in WeatherPy.  From the random list of cities 
in the cities.csv, we were asked to filter for specific condition that would make an ideal vacation spot.  I used the given parameters initially in the filtering process, but it returned no cities.  
I had to adjust the Wind Speed parameter and that returned a short list of cities.  From this, we were asked to find hotels within 10000 meteres.  I identified this and use the /places api to pull hotel information 
for the cities left in the DataFrame.  I then searched for hotels and only several returned a hotel within 10000 meteres.  We then were asked to add the Hotel Name and Country to the dictionary that showed 
when we hovered over the city.  I did this using the hvplot syntax and was able to successfully generate the plot.

I did confer with Sunil Williams on this Module Challenge and we both learned that hvplots is a little particular when it comes to the order of arguments while setting the plot up.  Together we worked through this
and were able to successfully navigate to the correct code sequence.
