# Flixster
Flixster is an Android app using Java that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Table of Contents
- [Description](#description)
- [Demo](#demo)
- [Installation](#installation)
- [Dependencies](#dependencies)
- [License](#license)

### Description
Some of the main features include:
- [x] User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API.
- [x] Views are responsive for both landscape/portrait mode.
  - [x] In portrait mode, the poster image, title, and movie overview is shown.
  - [x] In landscape mode, the rotated alternate layout should use the backdrop image instead and show the title and movie overview to the right of it.
- [x] Displays a nice default [placeholder graphic](https://guides.codepath.org/android/Displaying-Images-with-the-Glide-Library#advanced-usage) for each image during loading
- [x] Improved the user interface by experimenting with styling and coloring.
- [x] Shows details of movie (ratings using RatingBar, popularity, and synopsis) in a separate activity.
- [x] Allow video posts to be played in full-screen using the YouTubePlayerView.

### Demo
#### Current Progress Walkthrough

<img src="https://github.com/kabirdhillon7/Flixster/blob/master/Walkthrough%202.gif" width=250><br>

#### Progress 1 Walkthrough
<details>
  <img src="https://github.com/kabirdhillon7/Flixster/blob/master/Walkthrough.gif" width=250><br>
</details>

## Installation

To install and set up the app on your own device, follow these steps:

### Prerequisites
- Android Studio 4.0 or later
- Android SDK and Emulator or physical Android device for testing
- Java Development Kit (JDK) 8 or later installed and configured with Android Studio
- Gradle 4.0 or later for building the project

### Cloning the repository

- Download and install the latest version of Android Studio.
- Clone this repository to your local machine using the following command in your terminal:
```
git clone https://github.com/kabirdhillon7/Flixster.git
```
- Open Android Studio and click on "Open an existing Android Studio project".
- Navigate to the location where you cloned the repository, select the root folder of the project and click "OK".
- Wait for Android Studio to build the project and all its dependencies.
- Connect your Android device to your computer or use the Android emulator.
- In Android Studio, click on the "Run" button or press Shift+F10 to launch the app on your device.

## Dependencies

This app uses the following dependencies:

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## Contact

If you have any questions or feedback, you can reach me through the following channels:

- GitHub: [@kabirdhillon7](https://github.com/kabirdhillon7)
- LinkedIn: [Kabir Dhillon](https://www.linkedin.com/in/kabirdhillon/)

## License

    Copyright 2021 Kabir Dhillon

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
