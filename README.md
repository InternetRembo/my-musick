# React Native Music App

A mobile application built using React Native

<p align="center">
  <img src="https://github.com/m-inan/react-native-music-app/blob/master/images/screen.gif?raw=true" alt="animated" />
</p>

## Features

- Offline Playing
- Remote Control
- Customizable playlists
- Static sounds and artwork files
- Next, previous, shuffle, and replay

## Setup instructions
You have to put sounds and pictures in correct positions in the data. and you can edit the sample data on the file `data/index.js`.

#### Download
```console
git clone https://github.com/m-inan/react-native-music-app
cd react-native-music-app
```

#### Install dependencies
```console
yarn
```

#### Start metro bundler
```console
yarn start
```

#### IOS
> Install Pods
```console
cd ios; pod install; cd ..
```
> Run on ios simulator
```console
yarn ios
```

#### Android
```console
yarn android
```
### Dependencies
- [Svg](https://github.com/react-native-svg/react-native-svg)
- [Fast Image](https://github.com/DylanVann/react-native-fast-image)
- [Reanimated](https://github.com/software-mansion/react-native-reanimated)
- [Gesture Handler](https://github.com/software-mansion/react-native-gesture-handler)
- [Track Player](https://github.com/m-inan/react-native-track-player)
- [SafeArea Context](https://github.com/th3rdwave/react-native-safe-area-context)
