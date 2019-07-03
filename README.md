# flutter_web_app

Modified flutter setup application to support web build.

## Prerequisite

### Flutter SDK
Install the flutter SDK on your machine from [here](https://flutter.dev/docs/get-started/install).

### Flutter Web Build Tools
Install the webdev tools by running:
````
flutter pub global activate webdev
````

## Setup
Clone the repository and install local dependencies.
````
git clone https://github.com:florisdh/flutter-web.git AWESOME-PROJECT
cd AWESOME-PROJECT
flutter pub upgrade
````

## Run
The flutter web tools contain a debugger which can be used using:
````
flutter pub global run webdev serve --auto restart
````
This will compile your project and start a webserver. You can now check the result in your browser at ``http://localhost:8080``.

## About
Flutter just released version 1.5 and has a technical preview for web exports. I made this project for testing out the flutter web export capabilities, build sizes and performance.

## Continue Reading
- [Official flutter web repo](https://github.com/flutter/flutter_web)
- [Flutter for web](https://flutter.dev/web)
