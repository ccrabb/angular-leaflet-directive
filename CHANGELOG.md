angular-leaflet-directive changelog
===================================

## angular-leaflet-directive (trunk)
* Splitted the project in multiple sub-directives, children of the main "<leaflet>" directive.
* Added a leafletData service, where all the registered Leaflet object will be stored.
* Added a leafletHelpers factory.
* Added a leafletLayerHelpers factory.
* Added a leafletMapDefaults factory.
* Added a leafletEvents factory.
* Using protractor as E2E framework.
* Working with the lastest versions of AngularJS and Leaflet.

## angular-leaflet-directive (0.5.1)
* fix: wrap marker click event broadcast in scope apply

## angular-leaflet-directive (0.5.0)
* add options for setting doubleClickZoom
* add options for setting callbacks on map events

## angular-leaflet-directive (0.4.0)
* broadcast marker click event

## angular-leaflet-directive (0.3.3)
* add binding for main marker
* add minZoom option

## angular-leaflet-directive (0.3.2)
* add binding for markers' icons

## angular-leaflet-directive (0.3.1)
* add width, height attributes
* support for boundingbox binding

## angular-leaflet-directive (0.3)
* Add multiple paths binding support. Now path attribute is discarded and paths should be used instead. See path-example.html for more details.
