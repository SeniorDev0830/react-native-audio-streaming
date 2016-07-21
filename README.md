
# react-native-react-native-android-streaming

## Getting started

`$ npm install react-native-react-native-android-streaming --save`

### Mostly automatic installation

`$ react-native link react-native-react-native-android-streaming`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-react-native-android-streaming` and add `RNReactNativeAndroidStreaming.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNReactNativeAndroidStreaming.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNReactNativeAndroidStreamingPackage;` to the imports at the top of the file
  - Add `new RNReactNativeAndroidStreamingPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-react-native-android-streaming'
  	project(':react-native-react-native-android-streaming').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-react-native-android-streaming/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-react-native-android-streaming')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNReactNativeAndroidStreaming.sln` in `node_modules/react-native-react-native-android-streaming/windows/RNReactNativeAndroidStreaming.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Cl.Json.RNReactNativeAndroidStreaming;` to the usings at the top of the file
  - Add `new RNReactNativeAndroidStreamingPackage()` to the `List<IReactPackage>` returned by the `Packages` method
      

## Usage
```javascript
import RNReactNativeAndroidStreaming from 'react-native-react-native-android-streaming';

// TODO: What do with the module?
RNReactNativeAndroidStreaming;
```
  