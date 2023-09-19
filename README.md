# bloc_practice_ex

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


Uses of project folder, according these terms:-

bloc: This holds all the bloc classes and state, events for each BLoC used in projects.

data: This directory will hold all the network, local DB, storage, etc., classes. Also, it holds all the model classes, 
which contain all the model classes for the API, DB, Storage, etc.
response, and for clean architecture creates inner directories for each API response model class.

repository: This directory will hold all the repository classes used in the project
for communicating with BLoC. For clean architecture, create an inner directory for each module of your project.

res: This directory will hold all the classes related to the colors, dimensions, strings, drawable, styling, etc files.

routes: This directory holds the application routes classes globally and will be used in the application.
If we define all routes globally, then it will be easy to manage & make changes if required in between development without going through the complex classes.

UI: this directory will hold all the view-related classes with subdirectory as per the module & widget as well for the project.
