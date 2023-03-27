<h1> City Data App </h1>

This app was built to display the current weather and a brief description of a city.

## Technology stack
* Spring Boot
* Spring MVC
* Thymeleaf
* Bootstrap
* OpenAI API
* OpenWeatherMap API
* Maven

## Setup

#### 1. Clone the repository

> git clone https://github.com/vitoorsm/city-data-api

#### 2. Set API keys

> src/main/java/com/citydata/services/CityDataService.java\
> OPEN_WEATHER_MAP_API_KEY = "YOUR KEY"\
> OPEN_AI_API_KEY = "YOUR KEY"\

#### 3. Run the application

> mvn clean spring boot:run

The application will run on port 8090.

## Explore the App

* Once the App is started, the default page will look like this.

![default_page](https://user-images.githubusercontent.com/111457616/227644895-4de5c3ca-9dd7-44fc-8c98-67447273bb00.png)

* Here the fields should be filled, so it may look this way.

![inputs](https://user-images.githubusercontent.com/111457616/227645458-a5830bc5-669c-40a8-bedb-637e39aaf59c.png)

* Final result.

![result](https://user-images.githubusercontent.com/111457616/227645828-59fce4ca-bc0e-4a06-ad49-71c00e310379.png)

* Since the "About" is being generated by the GPT, the text is changed for each request.

![result_2](https://user-images.githubusercontent.com/111457616/227646100-e4cc5581-9c79-47d6-9b7b-03f7d729562d.png)


