# Installation of Node Modules
1) Run command in project root directory :

```
yarn // if using yarn
npm install // if using node

```

# For Android
1) Open android folder of your project in Android Studio.
2) Build gradle.
3) And click on run button.
4) Run command in Projects root directory:
```
adb reverse tcp:8081 tcp:8081
yarn strat //if using yarn
npx react-native start // if using node
```


or

## Command for run project using terminal
```
npx react-native run-android

```
# For ios
1) In project root directory run command
```
cd ios
pod install
```
2) open prjectName.xcworkspace file from ios folder of your project in xcode.
3) Click on Run Button.

# File Structure Overview

├── App.tsx
├── Gemfile
├── Gemfile.lock
├── README.md
├── __tests__
│   └── App-test.tsx
├── android
│   ├── app
│   │   ├── build.gradle
│   │   ├── debug.keystore
│   │   ├── proguard-rules.pro
│   │   └── src
│   │       └── main
│   │           ├── AndroidManifest.xml
│   │           ├── java
│   │           │   └── com
│   │           │       └── socialapp
│   │           │           ├── MainActivity.java
│   │           │           └── MainApplication.java
│   │           └── res
│   │               ├── drawable
│   │               │   └── rn_edit_text_material.xml
│   │               ├── mipmap-hdpi
│   │               │   ├── ic_launcher.png
│   │               │   └── ic_launcher_round.png
│   │               ├── mipmap-mdpi
│   │               │   ├── ic_launcher.png
│   │               │   └── ic_launcher_round.png
│   │               ├── mipmap-xhdpi
│   │               │   ├── ic_launcher.png
│   │               │   └── ic_launcher_round.png
│   │               ├── mipmap-xxhdpi
│   │               │   ├── ic_launcher.png
│   │               │   └── ic_launcher_round.png
│   │               ├── mipmap-xxxhdpi
│   │               │   ├── ic_launcher.png
│   │               │   └── ic_launcher_round.png
│   │               └── values
│   │                   ├── strings.xml
│   │                   └── styles.xml
│   ├── build.gradle
│   ├── gradle
│   │   └── wrapper
│   │       ├── gradle-wrapper.jar
│   │       └── gradle-wrapper.properties
│   ├── gradle.properties
│   ├── gradlew
│   ├── gradlew.bat
│   ├── local.properties
│   └── settings.gradle
├── app.json
├── babel.config.js
├── index.js
├── ios
│   ├── Podfile
│   ├── SocialApp
│   │   ├── AppDelegate.h
│   │   ├── AppDelegate.mm
│   │   ├── Images.xcassets
│   │   │   ├── AppIcon.appiconset
│   │   │   │   └── Contents.json
│   │   │   └── Contents.json
│   │   ├── Info.plist
│   │   ├── LaunchScreen.storyboard
│   │   └── main.m
│   ├── SocialApp.xcodeproj
│   │   ├── project.pbxproj
│   │   ├── project.xcworkspace
│   │   │   └── xcshareddata
│   │   │       └── swiftpm
│   │   │           └── configuration
│   │   └── xcshareddata
│   │       └── xcschemes
│   │           └── SocialApp.xcscheme
│   ├── SocialApp.xcworkspace
│   │   ├── contents.xcworkspacedata
│   │   ├── xcshareddata
│   │   │   ├── IDEWorkspaceChecks.plist
│   │   │   └── swiftpm
│   │   │       └── configuration
│   │   └── xcuserdata
│   │       └── imran.xcuserdatad
│   │           └── UserInterfaceState.xcuserstate
│   └── SocialAppTests
│       ├── Info.plist
│       └── SocialAppTests.m
├── metro.config.js
├── package-lock.json
├── package.json
├── src 
│   ├── Icons
│   │   ├── Home.png
│   │   ├── Icons.ts
│   │   └── insta.png
│   ├── components
│   │   ├── BottomTab.tsx
│   │   ├── Button.tsx
│   │   ├── Header.tsx
│   │   └── PostDetailComp.tsx
│   ├── data.tsx
│   └── screens
│       └── Profile.tsx
├── tsconfig.json
└── yarn.lock
