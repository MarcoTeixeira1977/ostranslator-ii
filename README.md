# ostranslator-ii
A graphical QGIS plugin for loading Ordnance Survey MasterMap into PostGIS.

![QII](OSTranslatorII/images/icon.png "OS Translator II")

## Supported Formats

* MasterMap
	* Topography Layer
	* Integrated Transport Network™ (ITN) Layer - Road Network and Road Routing Information
	* Integrated Transport Network™ (ITN) Layer - Urban Paths Layer


Planned formats include:

* MasterMap
	* Networks - Water Layer (Beta release)
	* Sites Layer
	* Building height attribute
	
	
## Limitations

There are currently the following limitations:

* No support for `nilReason` attribute of elements indicated as being *voidable* - this appears to be a limitation of the OGR library and will most likely be resolved in future OGR releases.

## Installation and Help

see [Official Help](http://www.lutraconsulting.co.uk/products/ostranslator-ii/)

1. Download the [latest release](https://github.com/OrdnanceSurvey/OSMM-Topography-Layer-stylesheets/releases) of the OS styles
2. Install the font, `OSMasterMap.ttf`
3. Add `osmmsymbols` to `QGIS Settings > Options > SVG paths`
