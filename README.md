# cordova-plugin-fakelocations  [![License](https://img.shields.io/github/license/tomloprod/cordova-plugin-fakelocation.svg)](http://www.opensource.org/licenses/mit-license.php)

**FakeLocation** is a cordova plugin to check if "Allow mock locations" are enabled or disabled in android devices.


## Supported Platforms

- Android < 6.0 (*doesn't support Marshmallow yet*)

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

