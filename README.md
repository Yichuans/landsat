# Prototype Landsat 8 application for natural World Heritage 

## Natural World Heritage Watch

The new app supercedes previous works on the Landsat 8 archive project, which becomes obsolete thanks to readily available Landsat data in the cloud in the form of easily consumable web services. In light of this, the focus has shifted to developing a prototype that makes use of such services and demonstrates the potential in using Landsat 8 for monitoring natural World Heritage sites.

The prototype is designed to answer only one question: what does the site look like from space *now*? Previously, one would consults Google Earth time series imagery in the first instance, in hope that remote sensed images over the areas of interest have been collated. Most often this isn't the case. Then, one needs to scour through USGS's Glovis web site to manually search, download, mosaic and visualise - a much tiresome and time-consuming task. In this regard, the prototype offers a considerably simpler, and more efficient alternative on the web, without the need of any special software.

To aid visual intepretation, a few additional functionalities have been added. These include multiple time series images (updated once the satellite captures new ones) and band combinations (dynamically generated on the fly).

## To-do list

- Improved landing page with live search and descriptive introductions
- Additional contextual information on the best images shown on the map
- Abilities to pick and choose if multiples images meet the time and quality requirements on each map
- Refactor code base...
