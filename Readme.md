# setup
To install ionic cli
npm install -g @ionic/cli native-run cordova-res
npm install @capacitor/camera @capacitor/storage @capacitor/filesystem
npm install @ionic/pwa-elements

To create new project 
ionic start photo-gallery tabs --type=angular --capacitor
>ionic start firstapp --type=ionic-angular
>ionic start firstapp blank

>ionic serve

To check ionic version
>ionic info

To generate a page
>ionic generate page users 

ionic g service services/photo




The apk is generated in this folder C:\Users\pcUsername\firstapp\platforms\android\build\outputs\apk

npm uninstall -g ionic

// build process 
ionic build
ionic cap add ios
ionic cap add android

ionic cap copy
ionic cap sync

// android studio open
ionic cap open android

// run on wifi
ionic capacitor run android -l --external

Deploying app in android-
ionic Cordova platform add android
ionic cordova build android --prod --release // flags optional
or
ionic capacitor build android
ionic capacitor build android --prod --release

 ionic capacitor copy android 
 cd android 
 ./gradlew assembleDebug 
 cd ..


get git origin
git config --get remote.origin.url

for git origin
git remote -v
