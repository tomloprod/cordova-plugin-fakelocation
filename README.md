# cordova-plugin-fakelocations

**FakeLocation** is a cordova plugin to check if "Allow mock locations" are enabled or disabled in android devices.


## Supported Platforms

- Android

## Installation

Cordova:

    cordova plugin add https://github.com/tomloprod/cordova-plugin-fakelocation.git

## Usage

This plugin exports an object with one method called "check" which returns true or false:

```javascript
window.plugins.fakeLocation.check(function(IsEnabledMockLocations){
	console.log(IsEnabledMockLocations);
});
```

