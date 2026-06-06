# NavWatch - Navigation to Boat Xtend

Sends Google Maps turn-by-turn directions to your Boat Xtend as notifications.

## What appears on your watch:
```
<-- TURN LEFT
Turn: 80 m  |  Dest: 12.3 km
```

## How to build (5 minutes):

### Step 1 - Install Android Studio
Download free from: https://developer.android.com/studio

### Step 2 - Open Project
File > Open > select this NavWatch folder

### Step 3 - Build APK
Build > Build Bundle(s) / APK(s) > Build APK(s)
APK will be at: app/build/outputs/apk/debug/app-debug.apk

### Step 4 - Install on Phone
Connect phone via USB, enable USB debugging
Run: adb install app/build/outputs/apk/debug/app-debug.apk
OR copy APK to phone and open it

## Setup on Phone:
1. Open NavWatch app
2. Tap "Enable Accessibility Permission" -> find NavWatch, enable it
3. Tap "Enable Notification Permission"
4. In Boat Wave app: Settings > Notification Alerts > ON
5. Tap "START NAVWATCH"
6. Open Google Maps, set destination, start navigation
7. Watch your Boat Xtend!

## Direction format (plain text, no emoji):
- ^ GO STRAIGHT
- <-- TURN LEFT
- TURN RIGHT -->
- <- SLIGHT LEFT
- SLIGHT RIGHT ->
- <<- SHARP LEFT
- SHARP RIGHT ->>
- U-TURN <>
- O-> ROUNDABOUT
- ** ARRIVED **

## Requirements:
- Android 8.0 (API 26) or higher
- Google Maps installed
- Boat Wave app with Notification Alerts enabled
