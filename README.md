# Map Cache

A repository for the configuration of the MapCache Server for ADAGUC

# Map Tile Server

```
http://ec2-18-184-73-242.eu-central-1.compute.amazonaws.com:8080/adaguc-services/adagucserver?DATASET=noaa&SERVICE=WMS&&version=1.3.0&service=WMS&request=GetCapabilities
```

Precipitation Layer

```
http://ec2-18-184-73-242.eu-central-1.compute.amazonaws.com:8080/adaguc-services//wms?DATASET=noaa&SERVICE=WMS&&SERVICE=WMS&VERSION=1.3.0&REQUEST=GetMap&LAYERS=precip&WIDTH=1035&HEIGHT=396&CRS=EPSG%3A4326&BBOX=-42.597769852705,101.12041627023899,-3.3342778821287773,203.7409066478814&STYLES=precipitation%2Fshadedcontour&FORMAT=image/png&TRANSPARENT=TRUE&&time=2021-02-07T21%3A00%3A00Z&0.7067997392710763
```
