# MotoMApp
Motorcycle Map App

Yet another application for motorcyle map navigation.

## Note
The application is under development and it could be unstable.

Not all functionality are completed.

Use at your own risk.

## Cockpit Page
Actually Cockpit page is intended for testing.

## Map Page
Map page is intended for live navigation.

The map center is automatically updated with the current position, except if there's a user manual modification of the map position or zoom.

If the map zoom/position is manually changed by the user, the top right 'locate' button reactivate autocentering functionality.

On the top left the permanent zoom buttons + and - are useful for increasing and decreasing zoom level leaving map autocentering active.

On the center left there's the gpx file loading button; it contains the loading button, which loads waypoints and tracks from a gpx file, and the delete button, for removing loaded data from map. The loaded track and waipoint are shown in purple.

On the bottom left there're the saving functionality:

* blue square: track saving is disabled. Click on it for marking a new waypoint or start track saving.

* red circle: track saving is enabled and when required a new trackpoint is added connecting it with the previous one. Click on it for marking a new waypoint or stop track saving. The marked waypoints are black and the saved track is red.

* green square: track saving is disable but a track was saved. Click on it for marking a new waypoint, restart track saving, downloading saved track or delete it. Delete button clear saved track without storing it; download button opens a popup for choosing saving format, full data JSON and standard GPX format. The downloaded file is stored in standard smartphone Download directory.

The the waypoint mark button stores a waypoint using the last trackpoint arrived. Clicking on it appears a popup for choosing the waypoint name and description. Waypoints can be marked even if the track saving is not active and are saved inside the JSON and GPX file.

## Configuration
Configuration page contains different sections:

* user settings, with the user home coordinates;

* live tracking settings, with the configuration of the IBM IoT Service or the MQTT over WebSocket service;

* debugging setting, with possibility to start and stop logging system, clear and save to file log messages.


More details about project development [here](https://bitbucket.org/michelebonacina/motomapp/wiki/Home).
