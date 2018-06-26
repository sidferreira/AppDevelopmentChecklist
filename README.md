# AppDevelopmentChecklist

## Design

- [ ] App Icons
  - [ ] iOS 
  - [ ] Android
- [ ] App Slpash Screens
  - [ ] iOS
  - [ ] Android
- [ ] Notification Icon (Android)

## Development

### Before Start Development

- [ ] Setup Apple Store
  - [ ] Client has iTunes Connect and Developer Portal Accounts?
  - [ ] Do we have access?
  - [ ] Create and config `bundleId` in client's account first.
  - [ ] Create a `bundleId`.debug app in the development account
  - [ ] Request from client a list of `Development Testers` for testflight
  - [ ] Prepare the TestFlight app with a dummy deploy

- [ ] Setup Play Store
  - [ ] Client has iTunes Connect and Developer Portal Accounts?
  - [ ] Do we have access?
  - [ ] Request from client a list of `Development Testers` for testflight
  - [ ] Setup Internal Testing with a dummy deploy
  
- [ ] Setup App Versions
  - [ ] Setup [react-native-version](https://www.npmjs.com/package/react-native-version)
  - [ ] Setup [automatic version update for Android](https://medium.com/@manas/manage-your-android-app-s-versioncode-versionname-with-gradle-7f9c5dcf09bf)
  - [ ] Setup [command line deploy for Google Play](https://github.com/codepath/android_guides/wiki/Automating-Publishing-to-the-Play-Store)
  - [ ] Run `npm version 0.0.1` to setup versions properly
  - [ ] Build version is 2
  - [ ] Run `react-native run android` and check in `./android/app/build/intermediates/manifests/full/debug/AndroidManifest.xml` if it updated properly
  
  
### During Development

## Publishing

### Before Publishing

### After Publishing
