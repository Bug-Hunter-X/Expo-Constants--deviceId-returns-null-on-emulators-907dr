# Expo Constants: deviceId returns null on emulators

This repository demonstrates a bug and its solution related to the Expo Constants API's `deviceId` property returning null on emulators.  The bug causes crashes if the app relies on a unique device identifier. The solution shows how to handle this gracefully.

## Bug Description
The `Constants.deviceId` property, when accessed on an emulator or simulator, may return null, leading to unexpected behavior or crashes in applications that use this ID for essential functions.

## Solution
The solution involves adding checks to handle the potential null value of `deviceId`.

## Usage
1. Clone this repository.
2. Navigate to the repository directory.
3. Run `expo start` to start the Expo development server.
4. Observe the behavior on a physical device and an emulator/simulator.