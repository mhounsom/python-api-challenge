This assignment is broken down into two separate parts where we create a Python script visualize weather of 500+ cities across the world and also using Jupyter-Gmaps and Google Places API to visualize a map for where to take the ideal vacation at. 

The first part we create scatter plots and create/calculate linear regression from city weather information that was retreived via an API call. To take a look at the code for the first part, you will want to open the "WeatherPy.ipynb" file and if you want to run the code on it, then open the file up on Jupyter Notebook. Note that you will need to enter your own API key from Open Weather Map to run the code properly. Screenshots of the scatter plots and linear regression plots can be seen in the "scatter_plots" and "linear_regression_plots" folders.

The second part we created a heatmap from Jupyter-Gmaps where we used cities humidity as the heatmap indicator. Using the cities generated from part 1, we filtered out just under 20 cities to use for the map based on temperature, humidity, cloudiness, and wind speed. The Google API was used to locate the closest hotel to each of the cities that were chosen and the hotels were added to the map on top of the heatmap. We To take a look at the code, you will want to open the "VacationPy.ipynb" file and if you want to run the code on it, then open the file up on Jupyter Notebook. Note that you will need to enter your own API key from Google API to run the code properly. Screenshots of the maps can be seen in the "vacationpy_maps" folder.





