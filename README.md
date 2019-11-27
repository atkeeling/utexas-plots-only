# University of Texas at Austin Building Energy Dashboard



## Project Proposal Summary

I will create a visualization dashboard that displays energy consumption of the buildings on the main campus of the University of Texas at Austin. Currently we have 

### Inspiration

My goal for this project is something I've been wanting to do for a couple years, and was a main motivation for me wanting to take this class. 

Currently, as Demand Side Energy Manager of UT, I manage a team of engineers and energy stewards who are responsible for managing and reducing the energy use in UT buildings. 

We have tons of data! Over 90% of the buildings are metered for a variety of utilities including electricity, chilled water, steam, gas, hot water, and domestic water. Most buildings on campus are fed by the UT power plant, and mainly consume electricity for lighting and plug loads, chilled water for cooling, and steam for heating. A small number of buildings use gas, mostly in kitchens, and a few buildings use hot water instead of steam for heating. To keep things simple, I will focus on the main utilities - electricity, chilled water, and steam. 

We already have a dashboard called the "Energy Portal" that was made by a third party vendor a few years ago. I'm going to recreate it. The Energy Portal can be found at the [UT Utilites website](https://utilities.utexas.edu/)

[Direct Link to Energy Portal](https://energyportal.utilities.utexas.edu/IWS80/?screen=startup.sg&guestuser=1&_ga=2.218719961.1187759209.1574210255-754672287.1569254792)

Note: It is only accessible when on campus using the "utexas" network.

Screenshots of Energy Portal

  ![EnergyPortalMap](dashboard/Images/Energy_portal_map.png)

  ![EnergyPortalCHW](dashboard/Images/Energy_portal_CHW_plot.png)

  ![EnergyPortalSTM](dashboard/Images/Energy_portal_STM_plot.png)

### Data and Source

Building energy data is not publicly available. I will be borrowing it from the UT historian that I have access to through work.

There are over 130 buildings on campus. Because data collection from the historian is somewhat tedious on a local network, I will probably focus on a small subset of 20 or so to get started.

One challenge I foresee is that I do not have a database of coordinates for the buildings which I will have to find.

Some building metadata can be found on the [UT Facilities site](https://utdirect.utexas.edu/apps/campus/buildings/nlogon/facilities/)

### Tools

D3 plotly for the plots  
D3 leaflet for the map  
SQLite for data storage  

### Future project

There is quite a bit of functionality we would like to add. Rather than trying to communicate requested changes to the vendor and pay a large amount of money to get the added functionality, I would like to add these features myself in this recreated version.


