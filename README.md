# Overview

Welcome to the WiDS Data Dive, in partnership with the Chicago/Illinois Red Cross.

You will have **90 minutes** to complete the following task. 

Below is a plot of number of incidents per month from 2014-2018 that the Illinois Red Cross responded to. As you can see, even ignoring seasonality, we observe a *drop* in total incidents in 2018. Our questions is simple: **Why**?

![](motivating_plot.png)

**NOTE**: This is not a question that we or the Red Cross definetively know the answer to. Feel free to be as creative as time allows!

The data is described more below in the [the data](#the-data). We will give you a zip file to [download](#download) that has: 
* Red Cross incident data
* Shapefile (spatial data) for zip codes in Chicago, and a [script](#spatial-data) that merges this with the Red Cross data or Census data (both with zip codes)
* [Data cleaning](#basic-cleaning) script in R
* Weather data
* ECON DATA?


## Goal
Your team will need to create 2-3 slides (keep it simple) with your best visualization and text takeaways. 

Please email your 2 slides with the email subject: "DATA DIVE", and a list of team members names to <als1@u.northwestern.edu> by 6:45 pm. 

Winner gets...bragging rights and eternal WiDS-dom and fame. 


# The Data

## Codebook
The code book will list each variable name with a description followed by the variable type in italics. If variable is categorical responses will be listed.

  * Date - The date of the incident *Date dd/mm/yyyy*
  * Incident_num - A unique incident number for the specific incident *Character*
  * Incident_type - The type of situation that lead to an incident. *Character*
      + Blizzard
      + Building Collapse
      + Explosion
      + Fire
      + Flood
      + HazMat
      + No response needed - Arrived on scence and assistance was not needed presently.
      + Police
      + Search and rescue 
      + Storm
      + Tornado
      + Transportation
      + Vacate
  

## Download




# Let's Get To Work... in R!

## Basic Cleaning

## Spatial Data 