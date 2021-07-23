# MY DATA
**I’m @KevinMCerqueira**
*I’m interested in learning more programming and sharing what I've already learned.*
*I’m currently learning to program for mobile phones in Android Studio.*
~~So far this is it guys.~~

**_MY FIRST PROJECT ON GITHUB_**

# Speedometer

*An app to measure what's your speed and your acceleration.*

## Technology

- Here are the technologies used in this project.

**Android Studio version 4.2.2**

## App's Main Screen
[Click Here](https://github.com/KevinMCerqueira/KevinMCerqueira/blob/main/Main%20Screen%20App.jpeg)

# How to make the App

- First you need to request to have the location permission to can use the GPS functions in the onResume function.
[Click Here](https://github.com/KevinMCerqueira/KevinMCerqueira/blob/main/Location%20Permission.png)

- After that you need to implement on the MainActivity the libraries of LocationListener and SensorEventListener to use the GPS functions and the sensor's functions.
[Click Here](https://github.com/KevinMCerqueira/KevinMCerqueira/blob/main/Libraries%20Implements.png)

- You need to create variables to the LocationManager, SensorManager, Sensor and to set this data to view in the App's FrontEnd (with the TextView).
[Click Here](https://github.com/KevinMCerqueira/KevinMCerqueira/blob/main/Variables%20Sensor%20and%20Location.png)

- You will need to get the GPS data to use in the App. For this you will call the getSystemService and request the LOCATION_SERVIDE and the SENSOR_SERVICE. 
After this call you will to set the TYPE_LINEAR_ACCELERATION and register that data in the Sensor.
[Click Here](https://github.com/KevinMCerqueira/KevinMCerqueira/blob/main/onCreate%20Function.png)

- In the onLocationChanged function you will to create a variable to measure the speed and converter it to Km/h. After this, you will set the converted speed 
in the textView variable to put in the Apps's FrontEnd.
[Click Here](https://github.com/KevinMCerqueira/KevinMCerqueira/blob/main/onLocationChanged%20Function.png)

- Now you will to set the Sensor functions what it needs. The "values[0]" for the acceleration on the X vector. The "values[1]" for the acceleration on the Y vector. 
The "values[2]" for the acceleration on the Z vector. And i used the DecimalFormat function to format the values to get only one decimal place of the number. 
And i set in xText, yText and zText the corresponding data to X, Y and Z .
[click Here](https://github.com/KevinMCerqueira/KevinMCerqueira/blob/main/onSensorChanged%20Function.png)

- Finally, you will create the App's FrontEnd with the Main Screen and the corresponding textViews to show speed and acceleration values.
[Click Here](https://github.com/KevinMCerqueira/KevinMCerqueira/blob/main/FrontEnd%20App.png)

Thank you
See you next project
