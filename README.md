
# BetaGo

An open source virtual tourism app using augmented reality (currently Android only!)

# About

- Somewhat inspired by Pokemon Go by Niantic Inc

## Architecture

APIs utilized

- Google Maps Android API
- Google Maps Directions API
- android tutorials coming soon
  - intents
  - camera
  - activity


### Part 1: The App

App implementations are in `app/` - written by xeliot

#### Current Features

- Simple map from Google APIs
- Record
- Stop
- Snap
- Download
- Upload
- Sync activity with server

### Part 2: The server

Servers are located in `server/` in the repository.

Right now, there are 3 server implementations in place.

- A prototype Python base http server, using flat file storage (logic completed) inefficient - written by xeliot
- A Python server built with Flask, using SQLite as a backend - written by xeliot
- An ASP.NET Core server that uses LiteDB (MongoDB-like database) as a backend - written by 0xFireball

For now, we're still using the Python server, but plan to eventually
replace it with flask server and sqlite for convenience and simplicity
or use ASP.NET Core server for scalability and performance.

## Quick Start For Developers

BetaGo was developed using Android Studio

- <https://developer.android.com/studio/index.html?gclid=Cj0KEQjwztG8BRCJgseTvZLctr8BEiQAA_kBD8iqav_IkrM0sgLT7b1XJBAHE_Us2n-48onMabU9NDsaAsig8P8HAQ>

BetaGo was also built using Google Maps V2 Android

- <https://developers.google.com/maps/documentation/android-api/start>

## Tutorials

Check out my blog for some tutorials on Google Maps V2 Android

- <http://principal-programming-fundamentals.blogspot.com/>

## License and Copyrights

&copy; 2016 Xeliot. All Rights Reserved. - (Creator of Project)  
&copy; 2016 0xFireball. All Rights Reserved. - (Collaborator from IridiumIon Software)

Licensed under the AGPLv3.
