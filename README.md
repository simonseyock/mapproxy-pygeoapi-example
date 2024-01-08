Example configuration for using MapProxy with pygeoapi
======================================================

This is an example on how to expose MapProxy layers via pygeoapi.

Every layer needs to configured separately.

To use the OGC Api Maps, MapProxy has to be requested via WMS with the WMSFacadeProvider.

To use the OGC Api Tiles, MapProxy has to be requested via WMTS with the WMTSFacadeProvider.

MapProxy
--------

* http://localhost:8080
* Has one source WMS with cache configured
* Has WMS and WMTS enabled
* Config: `mapproxy.yaml`


pygeoapi
--------

* http://localhost:8181
* Has OGC Api Maps and OGC Api Tiles for the mapproxy layer enabled
* Config: `pygeoapi-config.yaml`
