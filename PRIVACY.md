# Weather or Not: privacy policy

_Last updated: October 6, 2026_

Weather or Not ("WorNot") is a weather app for Android, made for personal use by a family. It has no
accounts, no ads, no analytics and no tracking, and its developer runs no servers that receive your
data.

## Location

With your permission, the app uses your phone's **approximate** location (not precise GPS) to show
the weather where you are, to check for weather alerts, and to keep current-location widgets up to
date. If you choose "Allow all the time", it also does this in the background, so alerts and widgets
follow you while the app is closed. Your location stays on your phone; the app keeps only the last
position it saw, to use when a fresh one isn't available.

To get the weather, the app sends a location (coordinates, or a ZIP code) directly from your phone
to these public weather services, the same way a web browser would:

- U.S. National Weather Service (api.weather.gov): forecasts, conditions and alerts
- Google Air Quality and Pollen APIs: air quality and pollen
- U.S. EPA and AirNow: UV index and air quality
- Iowa Environmental Mesonet and Esri: radar and map pictures for the area shown
- Open-Meteo (open-meteo.com): days 8 to 16 of the forecast everywhere, all the weather for places
  outside the US (including where you are, when you're abroad), and past weather for a trip's
  "typical" weather
- Google (through Android's geocoder): place search, ZIP codes, and town names abroad

To put the forecasters' notes into plain English, the app sends the National Weather Service's
public forecast discussion for the area to Google's Gemini API. For a trip, it sends Gemini the
saved place's name, the trip dates and its weather numbers, to write a short note on what to
expect. These requests contain nothing about you, and never your current location.

Each service handles requests under its own privacy policy. The app sends nothing else about you.

## Places and photos

Saved places, settings, cached weather, and any background photos you choose from your gallery are
stored only on your phone. Gallery photos are never uploaded. Uninstalling the app deletes all of it.

The app downloads its built-in background photos from a public GitHub repository; that request
contains no information about you.

## Notifications

Weather alerts and the morning forecast are created on your phone. You can turn them off in the app
or in Android's settings.

## Children

The app isn't directed at children and doesn't knowingly collect information from anyone.

## Contact

Questions about this policy: brnaccts@gmail.com
