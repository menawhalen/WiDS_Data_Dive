# Overview

Welcome to the WiDS Data Dive, in partnership with the Chicago/Illinois Red Cross.

You will have **90 minutes** to complete the following task. 

Below is a plot of number of incidents per month from 2014-2018 that the Illinois Red Cross responded to. As you can see, even ignoring seasonality, we observe a *drop* in total incidents in 2018. Our questions is simple: **Why**?

![](motivating_plot.png)


The data is described more below in the [the data](#the-data). We will give you access to: 
* Red Cross incident data
* Shapefile for zip codes in Chicago, along with a R file that will join the latitude/longitude in the Red Cross data
* blah blah data cleaning
* Weather data


## Goal
Your team will need to create 2-3 slides (keep it simple) with your best visualization and text takeaways. 

Please email your 2 slides to als1@u.northwestern.edu by 6:45 pm. Winner gets...bragging rights and eternal WiDS-dom and fame. 


# The Data
We give you access to shapefile data for Chicago, 

## Codebook
The code book will list each variable name with a description followed by the variable type in italics. If variable is categorical responses will be listed.

  * Date - The date of the incident *Date dd/mm/yyyy*
  * Incident_num - A unique incident number for the specific incident from the last two numbers of the year - four numbers *Character*
  * Incident_type - The type of situation that lead to an incident *Character*
      + Blizzard
      + Building Collapse
      + Explosion
      + Fire
      + Flood
      + HazMat
      + No response needed - Arrived on scence and assistance was not needed presently
      + Police
      + Search and rescue 
      + Storm
      + Tornado
      + Transportation
      + Vacate
  * City - Location city of incident *Character*
  * State - Location state of incident *Character*
  * ZIP - ZIP Code of where the incident occured. *Numeric*
  * County - The county where the incident occured *Character*
  * Latitude - Latitude of incident *Numeric*
  * Longitude - Longitude of incident *Numeric*
  * Destroyed - 
  * Major - 
  * Minor - 
  * Affected - 
  * Injured - Number of people injured from the incident *Numeric*
  * Hospitalized - Number of people hospitalized from the incident *Numeric*
  * Desceased - Number of people that died from incident *Numeric*
  * Adults - 
  * Children - 
  * Families - 
  * Assistance - The amount of money given to those affected during the incident *Numeric* 
  * Verified - When an incident was verified by the Red Cross *Timestamp dd/mm/yyyy 00:00:00 AM*
  * Dispatched - When the Red Cross sent someone to the incident *Timestamp dd/mm/yyyy 00:00:00 AM*
  * Responders_ID - When the responders to be dispatched from the Red Cross were identified *Timestamp dd/mm/yyyy 00:00:00 AM*
  * On_scene - When the responders from the Red Cross were on the scene of the incident *Timestamp dd/mm/yyyy 00:00:00 AM*
  * Departed - When the responders left the incident *Timestamp dd/mm/yyyy 00:00:00 AM*

## Download


# Let's Get To Work
## Cleaning
## Spatial Data