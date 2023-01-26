# Smart Home Dashboard - Top 3 Best Projects of the Cohort

<p align="center">
  <img alt="Dashboard Picture" src="/ReadMePictures/DashboardPicture.png">
</p>
  
## Inspiration

This Smart Home Dashboard was the developed in the context of our Internet of Things class. This project is supposed to mimic the functionalities of a real smart home dashboard in terms of displaying room temperature, humidity, light level, and much more. The application was developed in conjecture with actual sensors and IoT devices in order to show accurate information. 



## What it does

The Dashboard will display room Temperature, Humidity, and Light information with the use of temperature, humidity, and light sensors. The user will be able to input a temperature threshold which will start spinning a motor connected to an arduino whenever the threshold is met. The user will also be able to set a light threshold which will activate light bulbs whenever the threshold is met. The Dashboard can also display the number of bluetooth devices near you with a specified RSSI threshold, which means it will only detect devices in a certain radius. On top of all of those features, the Dashboard is equiped with proper authentication with the use of an RFID card. Multiple accounts were created and connected to a card which saved the values of every threshold to the user and if an invalid tried to log in, it would activate a buzzer. Finally, the application sent emails to the users email whenever a light or temperature threshold was met.


## How we built it

The full UI was built using Node-RED which is a tool used to create IoT Dashboards. The backend was developed using Python, C++, and Arduino. All the sensors and electronic components were linked to many different devices including ESP8266's and Raspberri Pi's using breadboards, cables, and resistors. All the devices were communicating with each other using the MQTT protocol which made it possible for all the components to run on different machines and still communicate with each other.



## Challenges we ran into

Working with physical components on top of software showed itself challenging seeing that we were very comfortable with the software development aspect of the project but connecting it to physical objects made it difficult for us to manage.



## Accomplishments that we're proud of

The final product was very elegant and had strong error checking and management. The application was very robust and had multiple extra features which put us ahead of other projects realized in the class.



## What we learned

We learned an incredible amount of things in terms of electrical components and how to make multiple computers communicate and properly manage information received from different devices. We learned how to design fully fledged Dashboards connected to real components in a nice and robust way.



## Built With

Python, C++, Arduino, Raspberri Pi, Node-RED, IoT
