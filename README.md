# DISCLAIMER

This [fork](https://github.com/ethanneff/react-native-web-typescript) aims to enable working with React Native libraries that need to be compiled
by Babel. It is mainly based in the next [comment](https://github.com/necolas/react-native-web/issues/1192#issuecomment-459867802). Feel free to use it and improve it if you feel is necessary.

# React Native Web with TypeScript

![image](https://i.imgur.com/sa5z3DR.gif)

## install

```sh
gem install cocoapods
npm i -g yarn
git clone git@github.com:ethanneff/react-native-web-typescript.git
cd react-native-web-typescript
yarn install
cd ios
pod install
cd ..
```

### run

```sh
yarn ios
```

```sh
yarn android
```

```sh
yarn web
```

### lint

```sh
yarn lint
```

### test

```sh
yarn test
```

### deploy

```sh
yarn build
```
