# josm-geojson

A plugin for displaying geodata stored in a [geojson](https://geojson.org/) format as a layer in JOSM.

## Status

[![Build Status](https://travis-ci.org/matthieun/josm-geojson.svg?branch=master)](https://travis-ci.org/matthieun/josm-geojson)

## Build

```
gradle josm
gradle clean build
```

## Run

The following command will build the plugin's jar file, and copy it with the proper name into your JOSM's plugin folder.

```
gradle installPlugin
```

And Josm should pick up the plugin at startup.

To Activate it, Josm Preferences > Plugins > Search geojson > Click the check box > Ok.

To open a `*.json` or `*.geojson` file, File > Open, select the file, and to make the list appear, click Windows > Geojson