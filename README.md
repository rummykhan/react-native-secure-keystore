
# react-native-secure-keystore

## Getting started

`$ npm install react-native-secure-keystore --save`

### Mostly automatic installation

`$ react-native link react-native-secure-keystore`

### Manual installation


#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.shellmonger.reactnative.RNSecureKeystorePackage;` to the imports at the top of the file
  - Add `new RNSecureKeystorePackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-secure-keystore'
  	project(':react-native-secure-keystore').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-secure-keystore/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-secure-keystore')
  	```


## Usage
```javascript
import RNSecureKeystore from 'react-native-secure-keystore';

// TODO: What to do with the module?
RNSecureKeystore;
```
  