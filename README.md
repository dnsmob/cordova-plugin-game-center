## Game Center Plugin for Apache Cordova

### **WIP** NOT READY FOR USE

## Before you start

Adding Game Center support requires more than simple coding changes. To create a Game Center-aware game, you need to understand these basics before you begin writing code. The full outline of all the Game Center concepts and impacts can be viewed [here](https://developer.apple.com/library/ios/documentation/NetworkingInternet/Conceptual/GameKit_Guide/GameCenterOverview/GameCenterOverview.html).

## 1 step install

```
cordova plugin add https://github.com/leecrossley/cordova-plugin-game-center.git
```

## Usage

You **do not** need to reference any JavaScript, the Cordova plugin architecture will add a gamecenter object to your root automatically when you build. It will also automatically add the GameKit framework dependency.

### Auth

You should do this as soon as your deviceready event has been fired. The plug handles the various auth scenarios for you.

```
gamecenter.auth(successCallback, failureCallback);
```

### Send Score

**Coming soon**

### Show leaderboard

**Coming soon**

## Platforms

Only support for iOS, as the Game Center is Apple specific.

## License

[MIT License](http://ilee.mit-license.org)