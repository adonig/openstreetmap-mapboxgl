# openstreetmap-mapboxgl
A Mapbox GL style for OpenStreetMap

Build instructions (in a Docker container) are forthcoming but here's the short of it:

1. Follow the instructions here to import a compatible OSM DB: https://github.com/geofabrik/openstreetmap-carto-vector-tiles/blob/master/README_VECTOR_TILES.md
Ubuntu 16.04 works, as long as you upgrade to node4 
Add to /etc/apt/nodejs.list and then sudo apt-get update; sudo apt-get upgrade:

deb https://deb.nodesource.com/node_4.x xenial main

deb-src https://deb.nodesource.com/node_4.x xenial main

2. Once Tessera is running, get an OpenLayers/Leaflet website up and running which can pull PBFs from Tessera. Use osm-v1.json as your style, possibly modifying the IP in the first few lines to point to your Tessera server.

3. Start reading https://github.com/gravitystorm/openstreetmap-carto and styling away! Please generate pull-requests.
