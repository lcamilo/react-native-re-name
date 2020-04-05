# react-native-rename [![NPM version](https://img.shields.io/npm/v/react-native-rename.svg?style=flat)](https://www.npmjs.com/package/react-native-rename) [![NPM monthly downloads](https://img.shields.io/npm/dm/react-native-rename.svg?style=flat)](https://npm-stat.com/charts.html?package=react-native-rename) [![NPM total downloads](https://img.shields.io/npm/dt/react-native-rename.svg?style=flat)](https://npm-stat.com/charts.html?package=react-native-rename) [![Paypal Donate](https://img.shields.io/badge/paypal-donate-green.svg?style=flat)](https://www.paypal.me/junedomingo)

Rename react-native app with just one command

![react-native-rename](https://cloud.githubusercontent.com/assets/5106887/24444940/cbcb0a58-149a-11e7-9714-2c7bf5254b0d.gif)

> This package assumes that you created your react-native project using `react-native init`.



#### Installation
```
yarn global add react-native-rename
or
npm install react-native-rename -g
```

Switch to new branch first
>better to have back-up

```
git checkout -b rename-app
```

#### Usage
```
react-native-rename <newName>
```

> With custom Bundle Identifier (Android only. For iOS, please use Xcode)
```
react-native-rename <newName> -b <bundleIdentifier>
```

> With Display name 
```
react-native-rename <newName> -d <displayName>
```

#### Example
```
react-native-rename "Travel App"
```
> With custom Bundle Identifier
```
react-native-rename "Travel App" -b com.junedomingo.travelapp
```

<a href="https://www.buymeacoffee.com/leandro.camilo" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/lato-blue.png" alt="Buy Me A Coffee" style="height: 51px !important;width: 217px !important;" ></a>
