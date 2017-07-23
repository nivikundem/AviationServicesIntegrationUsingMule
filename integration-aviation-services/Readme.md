# Implementing the Aviation services API Integration

This API allow us to request the aviation data for the Airports list and weather condition list.

API : https://www.icao.int/safety/iStars/Pages/API-Data-Service.aspx


AviationPIIntegrationUsingMule


Demo for integrating the Aviation API

In this project the following end points/operations been implemented.



Airport List By Country Name [http://{{host}}:{{port}}/esb/v1-{{env}}/{{basePath}}/aviation/airportsList?countryName=Spain]
Weather Condition List By Country Code [http://{{host}}:{{port}}/esb/v1-{{env}}/{{basePath}}/aviation/weatherConditionsList?countryCode=ESP]



Mule components
Dataweave
Context property place folders
Object-to-string-transformer
Http Consumer
Exception Strategies
Custom interceptor for logging


Technologies and tools
J2E
MULE ESB 3.8
Maven
ICAO
Postman
SOAPUI