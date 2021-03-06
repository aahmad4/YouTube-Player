<h1 align="center">YouTube Player</h1> 

<p align="center">
An Android App which uses Google's YouTube Data API to view and watch videos / playlists. It allows users to select different videos or playlists and watch them directly in the app. 
</p>

<p align="center">
A link to the API I used in this app can be found here: <a href="https://developers.google.com/youtube/android/player" target="_blank">developers.google.com/youtube/android/player</a>
</p>

## Setup

#### Clone
```
git clone https://github.com/aahmad4/YouTube-Player
```

#### Implementation

In [YoutubeActivity.java](https://github.com/aahmad4/YouTube-Player/blob/master/app/src/main/java/aliahmad/netlify/com/YoutubeActivity.java) change these lines of code to match your API key found on Google's site, the YouTube Video ID, and the YouTube Playlist ID. 

```java
static final String GOOGLE_API_KEY = "API_Here";
static final String YOUTUBE_VIDEO_ID = "TBWX97e1E9g";
static final String YOUTUBE_PLAYLIST = "PLE7E8B7F4856C9B19";
```

#### Usage
```
cd YouTube-Player
```

Initiate a debug APK build:
```
gradlew assembleDebug
```
Build APK and immediately install on running emulator or connected device:
```
gradlew installDebug
```
Mac or Linux Prefix:
```
./gradlew task-name
```
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
