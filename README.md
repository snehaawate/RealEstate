# Real-Estate-App

This app was created as a challenge to show my skills as a mobile developer by creating a Real Estate App using Kotlin, MVVM, Coroutines, Hilt, Room, Retrofit, Google Maps and more.

## The Challenge

The challenge was to create an app that shows a list of houses and their details, learn how to use the repository
pattern, API calls, room, database, google maps and more.

## Requirements

Minimum SDK 24 (Android 7.0 Nougat).


## Screenshots

<p float="left">
  <img src="https://github.com/juanriqu/Real-Estate-App/blob/main/screenshots/Splash-Screen.png" width="24%"/>
  <img src="https://github.com/juanriqu/Real-Estate-App/blob/main/screenshots/List-Of-Houses.png" width="24%"/>
  <img src="https://github.com/juanriqu/Real-Estate-App/blob/main/screenshots/Detailed-House.png" width="24%"/>
  


</p>

## Usage

The app has the following screens:

* Splash Screen
* List of Houses (With searchbar, searching by Postal Code or City)
* Detailed House
* About

(See screenshots above)

## Installation & Guidelines

This app has been tested in a Pixel 3XL, to take in consideration the screen size and the density.

1. Clone this repository and open it in Android Studio.
    - To use the app with location services, you need to have a Google Maps API key. You can get yours [here](https://developers.google.com/maps/documentation/android-sdk/get-api-key).

2. Create the `gradle.properties` file in this path [RealEstate/](https://github.com/snehaawate/Real-Estate-App/tree/main/RealEstate/) and add the following lines like this example below:

    `android.useAndroidX=true`

    `android.enableJetifier=true`

    `GOOGLE_MAPS_API_KEY= "YOUR_API_KEY"`

    Note that the app will not work if you don't add the properties described above with a valid Maps API key.

3. To build and run the app.
    - To use it with location, accept the location permission.
    
    - This app can be used without location, but the distance shown will be "N/A".

## Code Usage & Instructions

If you want to know the different usage of code in the app, you can check the comments in the code.

## Architecture

App is based on MVVM architecture and a repository pattern.

The app has a single activity with multiple fragments.

The app uses the Navigation Component to handle navigation between fragments.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change or any
suggestions you have.



## Libraries

All the libraries used in this project are listed in the build.gradle file, indicating it usage in the app and the
version.

* [Kotlin](https://kotlinlang.org/)
* [Dagger Hilt](https://dagger.dev/hilt/)
* [Coroutines](https://kotlinlang.org/docs/reference/coroutines-overview.html)
* [Retrofit](https://square.github.io/retrofit/)
* [OkkHttp](https://square.github.io/okhttp/)
* [Room](https://developer.android.com/topic/libraries/architecture/room)
* [LiveData](https://developer.android.com/topic/libraries/architecture/livedata)
* [Data Binding](https://developer.android.com/topic/libraries/data-binding)
* [Navigation Component](https://developer.android.com/guide/navigation/navigation-getting-started)
* [Material Design](https://material.io/develop/android/docs/getting-started/)
* [Coil](https://github.com/coil-kt/coil)
* [Splash Screen](https://developer.android.com/guide/topics/ui/look-and-feel/splash-screen)
* [Google Maps](https://developers.google.com/maps/documentation/android-sdk/overview)
* [MapView](https://developers.google.com/maps/documentation/android-sdk/map-with-marker)
