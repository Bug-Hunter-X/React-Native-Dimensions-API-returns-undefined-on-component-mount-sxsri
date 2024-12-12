# React Native Dimensions API returns undefined on component mount

This repository demonstrates a common issue when using the `Dimensions` API in React Native and provides a solution using the `useEffect` hook.

## Problem
The `Dimensions` API in React Native doesn't always provide dimensions immediately upon component mount. This leads to `undefined` values for `window.width` and `window.height`, causing unexpected behavior in the UI.

## Solution
The provided solution utilizes the `useEffect` hook to access the dimensions after the component mounts and the layout has been calculated.  This ensures accurate dimensions are available. 

## Usage
1. Clone this repository.
2. Navigate to the project directory: `cd react-native-dimensions-undefined`
3. Run `npm install` to install the necessary dependencies.
4. Run `npx react-native run-android` (or `npx react-native run-ios`) to run the app on an emulator or device.

## Credits
This example is for demonstrating the problem and solution of the `Dimensions` API in React Native, the issue is common and can affect many React Native applications. 