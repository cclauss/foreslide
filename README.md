# foreslide
Forecast landslides and then warn those who may be in warm's way.

## Forecast Landslides
* Create and maintain a GIS database of areas susceptible to landslides
  * Latitude, Longitude, Altitude
  * Slope of terrain
  * Rock type of terrain
  * History of landslides
* Gather rainfall data on each of those locations
* Run an algorithm for each location to predict the likelihood of landslides

## Warn those who may be in warm's way
* Publish a web-based red/yellow/green hotspot map 
* Warn appropriate government officials
* Send SMS and/or email messages to those subscribers who registered an interest in particular locations
* Warn the news media

A landslide forecast should always be published with a percentage of likelihood.  This is much like a weather forecast which contains a percent chance of rain.  No alerts should be sent out when conditions are green but the system should send out yellow and red alerts.  A subscriber can elect to receive:
* yellow and red alerts for an area - or -
* only red alerts for an area
* alerts of slide events after they happen

The system's predictions should always be compared against actual landslide events.  This information can be used to measure and improve the landslide prediction algorithm(s).
