# Audiovisual-Analytics
Interactive javascript-based visualization and sonification of NYPD Motor Vehicle Collisions

This prototype presents the publically available NYPD Motor Vehicle Collision data (https://data.cityofnewyork.us/Public-Safety/NYPD-Motor-Vehicle-Collisions/h9gi-nx95) using visuals and sound. It was build for participation in the BTW Data Science Challenge (http://btw2017.informatik.uni-stuttgart.de/?pageId=CallForDSChallenge&language=en).

Authors: Tobias Hildebrandt, Conrad Indiono

Demo: http://btw.lab.indygemma.com/tobias/vis

The audiovisual user interface requires a database loaded with the data set as well as a server running the the data handling service by Conrad Indiono (link will follow). Alternatively, the code regarding the data access can be modified to query the public API of the data set (see https://dev.socrata.com/foundry/data.cityofnewyork.us/qiz3-axqb) - see comments in the code.

Required libraries:
* Leaflet
* d3
* jquery
