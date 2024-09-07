# Weather Forecasting System

A simple Java-based console application to simulate a weather forecasting system. The application allows users to check the maximum and minimum temperatures, current weather conditions, and humidity levels for the day.

## Features

- **Temperature Information:** Displays the maximum and minimum temperatures of the day.
- **Weather Condition:** Shows the current weather condition (e.g., Sunny, Rainy).
- **Humidity Level:** Provides the current humidity level.

## Project Structure

- **Main.java:** Contains the main method and user interface logic for interacting with the weather forecasting system.
- **DailyForecast.java:** Extends the `ForeCast` class and contains methods to display weather details.
- **ForeCast.java:** A base class that stores and retrieves weather data like temperature, climate, and humidity.

## Usage

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/weather-forecasting-system.git
   cd weather-forecasting-system

2.**Compile and Run the Program**

  ```bash
  javac Main.java
  java Main
  ```
**Output**

    ```bash
    
    **** Welcome to Weather Forecasting System ****
    Choose your Options 
     1. Maximum-Temperature & Minimum-Temperature 
     2. Today's weather 
     3. Humidity 
     4. Exit
    
    1
    Minimum temperature = 30 Celsius
    Maximum temperature = 41 Celsius
    
    2
    Today's weather is = Sunny
    
    3
    Today's Humidity is = 10 (grams/m3)
    
    4
    Thank you for visiting .....^_^

  


**Dependencies**

Java SE Development Kit (JDK) - Make sure you have JDK installed on your system.
