# Source Code

This project use google game sdk source code. Current dependency info:

- You can download from [github](https://android.googlesource.com/platform/frameworks/opt/gamesdk).
- **Branch**: android-games-sdk-release
- **CommitID**: 551ee6b30de541fabceb8424abfb3818b5037283

## How to use cloned code

- Copy 'GameActivity', 'GameController', 'GameTextInput' and 'src/extras' directories from cloned directories.

## How to Build

- Use gradle command. gradlew :lib-game-sdk::assembleRelease

## Where to copy classes.jar

- Copy classes.jar from build/intermediates/aar_main_jar/release
