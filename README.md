My version of the companion Android application for Google's Android course
Sunshine is a weather app that gives you weather data from the Open Weather Map API

4 Major steps: 1 - Connect to the cloud (initiate network io and connect/uery for data from Open Weather Map API, move network data transfers off main UI thread), \
2 -  Added more activities (implicit/explicit intents, broadcast intents/receivers), 
3 - Content Providers to persist and recover data (Android's CP system that provides abstraction between data and UI, using Loaders, JUnit testing, using adapters to bind UI to CP's), 
4 - Services and notifications (efficient data transfer using SyncAdapter and GCM, background services and alarms to schedule background tasks)

Some screenshots: Main activity http://i.imgur.com/2qehiJ5.png, Details http://i.imgur.com/UVmSCHa.png

To dos (possibly..)
- use GPS instead of inserting location manually, 
- adding "number of forecast days" to Settings, 
- adding "synchronization time" to the Settings, 
- adding "Themes" to Settings, 
- providing swipe gesture to the Detail's screen, 
- adding a widget