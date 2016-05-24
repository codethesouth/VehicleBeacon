#Vehicle Beacon 
originally 
# HSV Transit Beacont from trolley-tracker-agent

Android app for reporting the current location of device with this application installed.

Written by the Code for Greenville NC CfA Brigade, it has been adapted to track the Huntsville 
Trolley and Shuttle Buses by the Code the South CfA Brigade.

## Dependencies
- Development
 - Android Studio (IDE)
 - Android API Level 19 (4.4.x KitKat)
- Running the App
 - Android KitKat or newer
 - Functional GPS Hardware
 - Google Play Services (Google Location Services)

## Functionality
This app uses Google Location Services API to request high-precision location updates. This version also uses Socket.io, so when the tablet is turned on the app will try to make a connection to the server URL listed in the app settings  <code>ServerIP</code> When it receives a location update, the service will issue a <code>socket.emit()</code>.

<b>Note: </b><i>This application will need to be rewritten as the Google Play Service API has changed and has been deprecated!</i> 
