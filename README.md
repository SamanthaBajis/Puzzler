# Puzzler
This repository contains a Unity 3D mobile application for iOS and Andriod devices called **_Puzzler_**. It has been built and tested using the Google Cardboard Viewer. **_Puzzler_** is an application created at the start of my Udacity VR Developer Nanodegree. The scene is a one level scene with the goal of the user to escape the dungeon by completing a specific rhythm based off the game "Simon Says". The code for the application was provided by, and used to better my understanding of C# scripting, Udacity and is implemented in the scene to make the user move forward, track their head position in order to follow the sequence, and back to restart the experience.
![img_1321](https://user-images.githubusercontent.com/35173600/36050316-10e7aa52-0db4-11e8-88fe-529319343fd0.PNG)
## Getting Started

### Prerequisites
The software you will need to download in order to build and run the game on a mobile device:
<br /> • The cross-platform engine [Unity 3D](https://unity3d.com/unity/qa/patch-releases/2017.1.0p4 "Unity 3D download") Patch Release 2017.1.0p4
<br />
- For iOS builds, the latest version of [Xcode](https://developer.apple.com/download/ "Xcode 9.3 Beta")
- NOTE! You will need to have an [Apple ID](https://appleid.apple.com/account#!&page=create "Developer Account") in order to download Xcode and build for iOS
- NOTE! Make sure to have the latest software version; 11 and up!
- For Android builds, you need [Android Studio](https://developer.android.com/studio/index.html "Android Studio download") and the [Java JDK 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html "JDK download")

### Installing
To build and run a copy of this application to your mobile device:
<br />
<br /> • On the **_Puzzler_** repository, go to the green "Clone or download" button and click "Download Zip"
<br />
<br /> • Once the zip file has loaded onto your desktop, double click the zip file to open. Navigate to the folder Assets > mainScene.unity and double click the scene to open it in Unity 3D
<br />
<br /> -NOTE! The scene may not be located at the top of the folder. If not, you will have to scroll through the folder to find it. It will be titled exactly mainScene.unity with the Unity logo-
<br />
<br /> After opening the scene in Unity 3D choose to build to either an iOS or Android mobile device
<br />
1. For iOS builds:
   - Go to File > Build Settings and switch the platform to iOS (this can take a while) then click the Player Settings button below that and with this open you can change the name of the application and bundle identifier, if you would like to change them, before pressing Build and Run to then be prompted to name the build and save it. (I usually save the build to my desktop so I can delete it later) 
     - The build will open in Xcode. Make sure to check your Apple ID is correct, the bundle identifier and the name of the application is what you would like it to be (again, you are more than welcome to use the default name) then press the play button in the upper left corner and the application will build and run directly to your iOS device.
2. For Android builds:
   - First, go to the top left corner and click Unity > Preferences. Then, select External Tools in the list and add the locations of Android Studio and Java JDK 8 in the correct section.
     - Afterwards, go to File > Build Settings and switch platform to Android (this can take a while to do) then click the Player Settings button below that and you can change the name of the application and bundle identifier, if you would like to change them, before pressing Build and Run to then be prompted to name the build and save it. The application will be built right to your Android device from Unity. 

### Deployment
When building the application to your phone a few important things to note:
<br />
<br /> • In Player Settings, you are able to not only change the name of the application and bundle identifier to whatever you would like you can also add a photo to be the icon for the application on your phone. It will be one of the first things you can do in Player Settings. Right under renaming the application.
<br /> • The Google VR SDK used in the game tracks your head movement. Meaning, where ever the phone is facing, the application will open and start your game from that position. If you would like to be facing a certain direction to play the game right after building to your phone I would suggest facing your device in that direction and hold it horizontally so you can start the experience in the most comfortable position for you.


## How to play
The instructions to play the application **_Puzzler_**:
![img_1320](https://user-images.githubusercontent.com/35173600/36050340-2ca04f88-0db4-11e8-97f8-22c4ff2fb8d6.PNG)
<br />
<br /> • Press the "Start" button on the panel
<br />
<br /> • The user will automatically move into the dungeon in front of a group of spheres that will play a rhythemic sequence they must solve in order to exit the dungeon
<br />
<br /> • User will be lead out of the dungeon once sequence is completed and will be presented with "Restart" panel in which case they will be moved back in restart the experience again
<br />

# Authors
• Samantha Cayla Bajis - _Initial work_ - SamBajis

# Acknowledgments
To make **_Puzzler_** possible:
<br /> 
<br /> • Udacity - Gathering of scene assets to use to make scene 
                 - Coding for player movement mechanic and sphere "simon says" mechanic
<br /> 
<br /> • Google VR SDK- head tracking, sound system and ability for the users interaction with the Google Cardboard Viewer
