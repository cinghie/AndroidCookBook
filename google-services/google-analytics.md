Google Analytics
-----------------

 - Add to you Googla Analytics an Account like My APPS
 
 - Check the guide: https://developers.google.com/analytics/devguides/collection/android/v4/?configured=true
 
 - Update your project's AndroidManifest.xml file to include the INTERNET and ACCESS_NETWORK_STATE permissions  
 
 - Update Gradle adding the plugin to your project by updating your top-level build.gradle and your app-level build.gradle: https://developers.google.com/analytics/devguides/collection/android/v4/?configured=true#set-up-your-project)
 
 - Remember to generate google-services.json selecting Google Analytics Account: https://developers.google.com/analytics/devguides/collection/android/v4/?configured=true#get-config)
 
 - Copy the google-services.json file you just downloaded into the app/ or mobile/ directory of your Android Studio project
 
 - Provide a helper method that returns your application's tracker: https://developers.google.com/analytics/devguides/collection/android/v4/?configured=true#application
 
 - Open the Activity that you'd like to track. You could also track a Fragment, but ensure that it correctly represents a screen view: https://developers.google.com/analytics/devguides/collection/android/v4/?configured=true#activity-or-fragment
 
 - To send an event, set the screen field values on the tracker, then send the hit: https://developers.google.com/analytics/devguides/collection/android/v4/?configured=true#send-an-event