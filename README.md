# MediStormSeeker

This software allows to identify different sensitive weather event in the Mediterranean Sea; in fact you will be able to locate a storm with a specific polygon. This polygon will have its own pop-up where insert a specific weather label on leaflet map. 
The user can watch different parameters :
A) cloud,
B) temperature at 2m,
C) rain,
D) snow,
e) wind.

These data are provided thanks to ajax calls in the meteo-uniparthenope library: this library belogs to "Università degli studi di Napoli Parthenope".

1 - Configuration:

- It is necessary to install mongodb and create a collection for users with unique username:
you type this command "db.UserCollection.createIndex( { "username": 1 }, { unique: true } )"
- You must insert web app user on mongodb shell:
you type this command "db.UserCollection.insert({"username":"YOUR_USERNAME","password":"YOUR_PASSWORD"})"

2 - Requirements:

A) Client Side:

meteo-uniparthenope.js,
jQuery,
bootstrap,
leaflet,
leaflet.pm,
query-ui,
leaflet-velocity,
geojson-tiles,
leaflet.groupedlayercontrol,
spin,
Control.Loading,
leaflet-easybutton.

B) Server side:

mongodb,
python 2.7.
Python Module:
flask
pyMongo
