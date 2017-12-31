
# react-native-short-video-camera

## Getting started

`$ npm install react-native-short-video-camera --save`

### Mostly automatic installation

`$ react-native link react-native-short-video-camera`

### Manual installation

 

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNShortVideoCameraPackage;` to the imports at the top of the file
  - Add `new RNShortVideoCameraPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-short-video-camera'
  	project(':react-native-short-video-camera').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-short-video-camera/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-short-video-camera')
  	```
 

## Usage
```javascript
import RNShortVideoCamera from 'react-native-short-video-camera';

// TODO: What to do with the module?
RNShortVideoCamera;
```
  