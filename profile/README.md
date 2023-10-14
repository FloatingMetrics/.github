# Floating Metrics

Floating Metrics is a cloud-based, event-driven system enabling real-time wind turbine sensor data processing and visualization.

### Background and Motivation
Offshore wind energy is rapidly developing to accelerate
the green transition. Each wind turbine is a massive autonomous structure containing
high-tech and mission-critical systems that need real-time monitoring. One of the central
challenges in this context is the efficient collection, real-time visualisation, and analysis of
sensor data from these turbines.

### Project Description
This project involved the efficient handling of sensor and weather data using Kafka, an
event-driven, distributed, asynchronous messaging service that enables streaming and
real-time data processing. 

The project is structured using containerised microservices,
packaging Zookeeper, Kafka brokers, Kafka producers, and a Kafka consumer using
Docker. Additionally, weather and wave data is retrieved from external REST APIs.
The acquired data is stored in a cloud-based SQL database and visualised using Grafana.


*More to come*
