# Android App for Current Location
Android App for getting current Location using Google Fused Api. And if no previous data for location is available, it gets the current location.<br>
Here you can see the [Demo Video](https://youtu.be/dpYbxyUgIro).<br>
For step by step tutorial visit [Android Tech Point](http://androidtechpoint.blogspot.com/2017/01/android-tutorial-to-get-last-known.html).

Follow the setps to successfully buid this app: <br>

1. Download Google Play Services from `SDK Manager`.
2. In Build.gradle add dependency for google:
  ```
  compile 'com.google.android.gms:play-services:10.0.1'
  ```
3. Add premissions in androidmanifest.xml:<br>
    ```
    <uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION" />
    ```
    <br>
    ```
    <uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />
    ```
4. Paste the code in you activity.
<br> <br>All Done. :+1:
