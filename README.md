# WebView Browser App

A Flutter-based WebView application that allows users to open and browse any website directly within the app. Users can enter a URL and access web content without leaving the application.

## Features

* Open any website using a custom URL
* Embedded WebView browser
* Internet connectivity detection
* Fast and lightweight interface
* Android and iOS support
* Simple navigation and routing
* User-friendly design

## Project Structure

```text
lib/
├── Routes/
│   └── routing.dart
├── View/
│   ├── potoedit.dart
│   └── webView.dart
├── controller/
│   └── networkController.dart
└── main.dart

android/
ios/
images/
```

## Technology Stack

* Flutter 3.19
* Dart
* WebView Flutter
* GetX Navigation
* Network Connectivity

## Run Project

```bash
flutter --version
flutter pub get
flutter run
```

## How It Works

1. Enter or configure any website URL.
2. Launch the application.
3. The website opens inside the built-in WebView.
4. Users can browse the website without opening an external browser.

## Supported Platforms

* Android
* iOS

## Purpose

This application provides a simple solution for converting any website into a mobile app experience using Flutter WebView.


<p align="center">
  <img src="https://github.com/user-attachments/assets/dbb25cb3-e5ff-41a9-88af-a989867a0a3a" width="30%">
  <img src="https://github.com/user-attachments/assets/f9c132bb-839a-4730-94af-03d193d9b4cb" width="30%">
  <img src="https://github.com/user-attachments/assets/21c82907-4688-44eb-ab55-25fb6143642d" width="30%">
</p>




       
          


<table>
  <tr>
    <td>
      <img src="https://github.com/rehmanflutter/WebView-App-Net-Check-/assets/144882089/f568f8f9-ea99-4a4c-8cab-a4a0d967e2e6" alt="Image 1">
    </td>
    <td>
      <img src="https://github.com/rehmanflutter/WebView-App-Net-Check-/assets/144882089/879d7daa-d5b0-43ce-8f5f-a21c77cc7aaa" alt="Image 2">
    </td>
  </tr>
</table>





# practice
remove time to page  
    SystemChrome.setEnabledSystemUIMode(SystemUiMode.edgeToEdge);
    
////////////////////////////////////////////////////////////////

# Add Top Of app  main

extension View on num {

  Widget get height => SizedBox(height: toDouble()); 
  
  Widget get width => SizedBox(width: toDouble());  
}
and use          100.height

//////////////////////////////////////////////////////////////

# Add To croller bottomSheet End textfiled move to keyboard and show top

Padding(

      padding: MediaQuery.of(context).viewInsets,
          
          child  widget
          
          )
//////////////////////////////////////////////////////////////
# Find SH kye         
    ./gradlew signingReport


# Ios SetUp

Error: Error running pod install

pod cache clean --all

pod cache

pod deintegrate

sudo gem install cocoapods-deintegrate cocoapods-clean

sudo arch -x86_64 gem install ffi

arch -x86_64 pod repo update

arch -x86_64 pod install



# flutter build macos
This command creates a .app file in the build/macos/Build/Products/Release directory. create apk file for mac desktop 







# flutter build ios --release

# pod Issus
pod cache clean --all

rm Podfile.lock

pod repo update


pod install



#   Error IOS 

rm -rf ~/.cocoapods/repos/trunk

pod repo remove trunk

pod setup

cd ios

pod install


# RazorPay
https://github.com/HEMANT-HEY/RazorPay-integration



   

 
