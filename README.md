# YoutubeChannelSubscribeAndroid

If you want to make your YouTube channel app and add subscribe functionality on this app then you must read this tutorial. you get add subscribe youtube channel functionality using few steps.

Check the link for youtube channel videos in android – https://tutorialstack.in/integrate-youtube-channel-videos-in-android/

Below we are defining few steps to implement subscribe youtube channel in android.

Subscribe youtube channel
Step 1. In the starting create an android application from an android studio.

https://tutorialstack.in/android-first-application/

Step2. Open the app build.gradle file of your app module for add support library.

Step3. add YouTubeAndroidPlayerApi.jar file in libs folder of application.
You can download the library from below link and add an app -> libs folder of the application.
https://developers.google.com/youtube/android/player/downloads/
Step4. Add Your Project into console.developers.google.com or https://console.firebase.google.com

You need to add SHA-1 key in firebase profile, find the link for your application debug and release key.
https://tutorialstack.in/get-sha1-key-for-android-app-debug-and-release

Step5. Create OAuth key of youtube api.

Step6. Add a function in java file for check Google play service is available or not.

Step7. Add a function for add Google play service if not available.

Step8. Initialize GoogleAccountCredential in onCreate() for account login and add a function for choose account.

Step9. Add ActivityResult function for handle result of actions.

Step10. Add async task function for call Youtube Subscribe api.

Find below link for tutorial - https://tutorialstack.in/implement-subscribe-youtube-channel-in-android/
