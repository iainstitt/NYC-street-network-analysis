# NYC-street-network-analysis

In this notebook I have defined a graph theoretical measure that quantifies the redundancy (or overlap) of taxi trips along certain routes in New York City. This measure can be used to assess the degree of redundancy for certain routes in the city. Routes that have a high degree of redundancy have a greater capacity for imporoved efficiency, and therefore represent a more viable market for ride sharing services. 

- Taxi trips that originate and end within Astoria displayed a similar distribution of redundancy, when compared to rides from the upper east side. Given that ride sharing services are successful in the upper east side, it may be expected that a similar service will be viable in the Astoria as well.  

- Trips from Astoria to Manhattan, and from Manhattan to Astoria displayed a large degree of overlap/redundancy. Indicating that these journeys represent viable targets for the ride sharing model.

- There was especially high redundancy for trips that originate in La Guardia, and drop off passengers in either Astoria and Manhattan. Further exploration of the data revealed that this may be in part due to the tendency of many taxi trips from La Guardia to drop off passengers at the Astoria Blvd train station. 

- Trips from Manhattan to La Guardia Airport (and back) display a large degree of overlap/redundancy with trips to La Guardia from Astoria. This suggests that Astoria services to both Manhattan and La Guardia could be integrated within the current framework of servicing La Guardia Airport from Manhattan. 

- The demand for service in Astoria more generally follows the demand for taxis between Manhattan and La Guardia Airport. This is great, because it means that the demand for ride share trips within Astoria will cofluctuate with the amount of vehicles traveling through the neighborhood either to or from La Guardia Airport. 

- While there is indeed variation in the demand for service across the days of the week, I believe that the magnitude of these fluctuations do not justify restricting service to certain days. Since restriting service may lead to increased churn. 
