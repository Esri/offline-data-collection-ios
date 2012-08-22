ArcGIS-iOS-Offline-Inspections-Sample---UC-2011-Plenary-Demo
============================================================

Offline Inspections Sample - Shown at the User Conference 2011 Plenary Demo

This sample demonstrates how you can build a complete, custom application that allows users to collect features when the device does not have network connectivity, and then synchronize those changes when connectivity is restored.

The Inspections application works in both connected and disconnected environments.  Both environments allow the user to perform inspections on features within a user-defined inspection layer. The user will download the feature data while connected and can then bring the application into an offline mode.  The application will populate an inspection form with any related data from the feature being inspected. The application persists any collected data until the user regains network connectivity and can post the inspections to their server.
 
The sample uses a local tiled layer to display map contents of a tile package (Imagery.tpk) included within the application bundle. Tile package is a new format available from ArcGIS 10.1 onwards.

For more information about the ArcGIS Runtime SDK for iOS, please visit the Resource Center.
If you would like to contact the iOS Development Team to provide feedback on this or any other code sample, please email your questions to iOSDevTeam@esri.com.