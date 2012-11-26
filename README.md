# offline-data-collection-ios

Offline Inspections Sample - Shown at the User Conference 2011 Plenary Demo

This sample demonstrates how you can build a complete, custom application that allows users to collect features when the device does not have network connectivity, and then synchronize those changes when connectivity is restored.

The Inspections application works in both connected and disconnected environments. Both environments allow the user to perform inspections on features within a user-defined inspection layer. The user will download the feature data while connected and can then bring the application into an offline mode. The application will populate an inspection form with any related data from the feature being inspected. The application persists any collected data until the user regains network connectivity and can post the inspections to their server.

The sample uses a local tiled layer to display map contents of a tile package (Imagery.tpk) included within the application bundle. Tile package is a new format available from ArcGIS 10.1 onwards.

![App](https://raw.github.com/ArcGIS/offline-data-collection-ios/master/picture.png)

## Features
* Offline data collection.
* Offline provisioned Maps
* Adds features to map without network connectivity

## Instructions

1. Download and unzip the .zip file or clone the repo.
2. Open with xCode and replace it with your provision file.

[New to Github? Get started here.](https://github.com/)

## Requirements

* xCode 4.3 and above
* A little background with iPhone development and Objective-C
* Experience with the [ArcGIS Runtime SDK for iOS](http://www.esri.com/) would help.

## Resources

* [ArcGIS Runtime SDK for iOS](http://resources.arcgis.com/en/communities/runtime-ios-sdk/)
* [ArcGIS Blog](http://blogs.esri.com/esri/arcgis/)
* [twitter@arcgis_runtime](http://twitter.com/arcgis_runtime)

## Issues

Find a bug or want to request a new feature?  Please let us know by submitting an issue.

## Contributing

Anyone and everyone is welcome to contribute. 

## Licensing
Copyright 2012 Esri

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

A copy of the license is available in the repository's [license.txt]( https://raw.github.com/Esri/switch-basemaps-js/master/license.txt) file.

