# AVA-App
An Android native wrapper for voebb.ava.watch using [Apache Cordova](https://cordova.apache.org/)


## Setup for Ubuntu 18.10 and Cordova 9.00
### Install Java 8 (exactly this version is required)

`sudo apt-get install openjdk-8-jdk`

### Install Android SDK

`sudo apt install android-sdk`

### Install npm

`sudo apt install npm`

### Install Cordova via npm

`sudo npm install -g cordova`

### Create Cordova project

`cordova create [project_name]`
### Add platform browser and Android for cordova project

`cd [project_name]`

`cordova platform add browser`

`cordova platform add android`

## Run project in the browser
`cordova run browser`
