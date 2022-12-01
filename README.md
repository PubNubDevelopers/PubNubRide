## Please note that this project is no longer actively maintained or accepting Pull Requests.  Please use the [Delivery Application](https://github.com/PubNubDevelopers/delivery-demo) instead.

----------------------

# PubNub Ride

## How to run

First, obtain your PubNub keys by signing up below. After creating a PubNub app, you will receive your subscribe and publish keys, which you will need to input in the `Constants.java` class. 

You will also need your Google Maps API keys. <a href="https://console.cloud.google.com/">Create a Google Cloud Platform account</a> to use google maps APIs, which will power a large portion of the app. Enable the Google Maps Android API, Directions API, and Places API from the API manager. You can obtain your keys from the credentials tab. Your key must go in the `Constants.java` file and the `AndroidManifest.xml` file. 


After including the relevant keys, build the project in Android Studio and run it through a connected device or an AVD. Note: the first build may take a while; [here is a barebones version](https://github.com/PubNubDevelopers/SelfDrivingApp) of this project. 

The current state supports passenger and driver geo-location tracking. To run this, first select `Home` from the passenger device and `Driver` from the driver device. 

**Sign up for PubNub click here:**

<a href="https://dashboard.pubnub.com/signup?devrel_gh=PubNubRide">
    <img alt="Sign up for PubNub" src="https://i.imgur.com/og5DDjf.png" width=260 height=97/>
</a>
