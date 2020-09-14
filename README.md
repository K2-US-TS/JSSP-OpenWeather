# JSSP-OpenWeather
 
 ## JSSP Broker for OpenWeather API
 Sample K2 JSSP Broker connecting K2 to Open Weather services based on **Open Weather API Version 2.5** (http://api.openweathermap.org/data/2.5/weather)
 

This is only a sample broker and is not supported by the product team.
 
 ***Use this code at your own risk, Happy Coding.***
  
 ## Features
 This broker currently supports the followings:
 
 ### Current Weather data
 - GetCurrentWeather: Input city name and units (imperial/metric/kevin) and return current weather information (condition, temperature, and feels like temperature).
 
Additional Information:  [API Reference](https://openweathermap.org/current)

## What is required to create a K2 Service Instance:
- API Key from open weather

You'll need to create a developer account on [OpenWeather website](https://openweather.org)


## To deploy the broker to a K2 Nexus platform
To deploy this broker you can use the bundled JS file under dist folder. Follow the [product documentation here](https://help.k2.com/onlinehelp/platform/userguide/current/default.htm#../Subsystems/Default/Content/Extend/JS-Broker/JSSPRegister.htm%3FTocPath%3DDevelop%7CExtending%2520the%2520K2%2520Nexus%2520Platform%7CCustom%2520Service%2520Types%2520with%2520the%2520JavaScript%2520Service%2520Provider%2520(JSSP)%7C_____8) to deploy the bundled js file to your K2 Nexus instance

## To modify this broker for your use cases:
1. Download this repository
2. Run "npm install"
3. Modify the code in index.ts under the src folder
4. Then run "npm run build" to generate a new bundled JS file for deployment.
