🐱‍🐉 This is a work in progress...
# A sample app demonstrating the usage of app center features with xamarin forms.

Be aware, this app uses the following packages:

* Xamarin.Forms 4.0.0.62955-pre2
* Microsoft.AppCenter.Push 1.13.0 (and dependencies)

***

### App Center Push (https://docs.microsoft.com/en-us/appcenter/push/)

To use App Center Push on your app, you just need to add the Microsoft.AppCenter.Push package, https://docs.microsoft.com/en-us/appcenter/sdk/push/xamarin-ios#prerequisite---enable-apple-push-notifications-service-apns-for-your-app

* [Added App Center Package](https://github.com/willbuildapps/app-center-with-xamarin/commit/08da7f308f19db0e121ecff6725f5e1003833fac)

#### Android implementation

First of all, to be able to receive a push notification on Android, you had to follow these steps https://docs.microsoft.com/en-us/appcenter/sdk/push/xamarin-android#prerequisites 

Then, it's not a big deal, you can check thise commits and see that is a piece of cake. 

* [Android Push Setup](https://github.com/willbuildapps/app-center-with-xamarin/commit/3686ca323fe325db5b7408af0933cf32f600af28)


#### iOS implementation

The challenge here is to set up the keys and certificates, luckily we can follow this doc's and get things going 

* [iOS Push Setup](https://github.com/willbuildapps/app-center-with-xamarin/commit/1da6795418cd2d14aa0e4e02f7161aedb1f935e3)

***

### App Center Diagnostics
WIP

***

### App Center Analytics
WIP


