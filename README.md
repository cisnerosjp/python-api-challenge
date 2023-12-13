# python-api-challenge
![image](https://github.com/cisnerosjp/python-api-challenge/assets/97692681/d779a3b9-d781-4c85-8d15-f1245270a84c)

## Purpose of WeatherPy and VacationPy
- WeatherPy: The purpose of this challenge was to use Python, APIs, and JSON to explore weather conditions closer to the equator. We were tasked to create Python scripts to visual weather conditions of over 500 cities that were differing distance close to and from the equator. We accomplish this by utilizing the "OpenWeatherMap" API which comes from OpenWeather, an online service owned by OpenWeather Ltd, that provides global weather data via API. For our purposes we utilized their free offering to accomplish our tasks, though they do have business offerings available so it can be scaled up if necessary. We were tasked to create plots to show the relationship between weather and latitude and to compare the linear regression and plot for each relationship for both the northern and southern hemispheres.
- VacationPy: The purposes of this challenge was to use the Geoapify Location Platform API to map out cities read in from a provided CSV, "cities.csv" located in the output_data folder of this repository. From there we were tasked to narrow these findings down based on requirements provided in our description such as cities with set Maximum Temperature and a distinct amount of cloudiness. Use this info to create dataframes, and then find the closest hotel with 10,000 meters of the coordinates of the cities we filtered to. Then map the city location as well as add the country the city could be find in to our previous map after adding in the hotel to our dataframe.

## The Analysis

### WeatherPy

- We were tasked with exploring the relationship between different conditions based on the cities latitude and another chosen variable i.e.: Max Temp or Humidity and then make our own analysis such as:
  -![image](https://github.com/cisnerosjp/python-api-challenge/assets/97692681/42c84cf3-dac0-440a-8f9b-16bee4bfc02d)
  -![image](https://github.com/cisnerosjp/python-api-challenge/assets/97692681/b6cc12c1-7fd8-454e-9d32-4f25ff1b8bb2)
- included examples
![image](https://github.com/cisnerosjp/python-api-challenge/assets/97692681/0a776bba-48a7-4caf-8e6f-ff2f6bacc4ac)
![image](https://github.com/cisnerosjp/python-api-challenge/assets/97692681/78062e16-cdde-4b75-8bd7-9b2f67260e9d)
![image](https://github.com/cisnerosjp/python-api-challenge/assets/97692681/9b30771b-80a9-4c1d-8d4c-59342608f2bf)

### VacationPy

- We were tasked with using a provided set of data to find certain aspects of given cities and pull said information from the Openweather API as so:
  - ![image](https://github.com/cisnerosjp/python-api-challenge/assets/97692681/edc4192c-9b1e-43f5-84be-f8df013d1837)
  - ![image](https://github.com/cisnerosjp/python-api-challenge/assets/97692681/f1de3ae0-359a-4582-a2c6-0aacd08c0252)
  - ![image](https://github.com/cisnerosjp/python-api-challenge/assets/97692681/84899376-11c1-4f2b-ac66-ebba4e34cb77)


## Navigating this repository

- The code for this repository can be found in the WeatherPy folder. From there you can view the output_data, a folder that contains files such as the above mentioned CSV as well as a set of images from our findings. The completed code in the folder can be find in the folder entitled starter_code, which contains the WeatherPy and VacationPy ipynb files. What you will not find our the necessary API keys that were used for this project. That is intentional. In order to obtain said API keys you will have to navigate to the OpenWeather and Geoapify websites, create an account, and from there generate your own unique API keys and place them in a python file entitled config.py, which was not included in this repository either.

## Data Provided

- The starter code for this repository was initially provided in the folder entitled, starter_code, during the challenge the files were configured to produce the results necessary to accomplish our tasks.
- The cities.csv which is in output_data.
- The geoapify and openweather information which can be obtained from their respective websites.

## Code Sources

-The code in this repository was sourced from the above mentioned started code provided to us as well as from in-class work and examples, activities that were previously tasked with completing, stack overflow, the documentation libraries for pandas and the two APIs used for different aspects of this challenge.

### THANK YOU FOR STOPPING BY
