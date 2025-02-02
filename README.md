[![](https://img.shields.io/npm/v/@ajaysidhu/react-native-template.svg?style=flat)](https://www.npmjs.com/package/@ajaysidhu/react-native-template)
[![](https://img.shields.io/npm/dt/@ajaysidhu/react-native-template.svg)](https://www.npmjs.com/package/@ajaysidhu/react-native-template)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)


# react-native-template

A starter kit for initializing a new React-Native project with some commonly used preconfigured libraries and the folder structure.

<p align="center">
  <img height="400" alt="react-native-template installation" src="https://raw.githubusercontent.com/ajaykumar97/images-container/main/react-native-template/react-native-template-installation.gif">
</p>

## Key features:
- Pre-configured folder structure
- Navigation using [react-navigation](https://reactnavigation.org/) (v6)
- State management using [redux](https://redux.js.org/)
- Redux middleware [redux-saga](https://redux-saga.js.org/)
- Git hooks using [husky](https://typicode.github.io/husky/#/)
- Staging and Production environment configurations using [react-native-config](https://github.com/luggit/react-native-config)
- Image caching using [react-native-fast-image](https://github.com/DylanVann/react-native-fast-image)
- Splash screen using [react-native-bootsplash](https://github.com/zoontek/react-native-bootsplash)
- API request using [axios](https://axios-http.com/)
- Localization using [react-native-localization](https://github.com/stefalda/ReactNativeLocalization)
- Responsive UI using flexbox and [react-native-size-matters](https://github.com/nirsky/react-native-size-matters)

## Prerequisite
1. Make sure that you have followed the environment setup instructions properly from the official [React Native docs](https://reactnative.dev/docs/environment-setup).

2. The installation command will fail if you have the global legacy `react-native-cli` installed in your machine. Make sure you uninstall it first:

```shell
yarn global remove react-native-cli
```

or if using `npm`

```shell
npm uninstall -g react-native-cli
```

## Quick start

Generate a new React Native(**v0.66.3**) app using the **@ajaysidhu/react-native-template**:

```shell
npx react-native init MyApp --template @ajaysidhu/react-native-template --skip-install
```

You might also be prompted to confirm the installation for the packages `react-native` and `husky`. Simply hit `enter` to proceed.

The template will automatically install the `npm` dependencies and the `pods` (if you are on the MacOS).

## Digging Deeper

Check out the [documentation website](https://ajaykumar97.github.io/react-native-template/) to learn more about the template.
