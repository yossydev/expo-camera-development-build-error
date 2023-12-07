## Environment Setup

```bash
$ npm ci
$ npm run start
$ s // switch to development build
$ i // open iOS simulator
```

## error message

```bash
 ERROR  Error: Cannot find native module 'ExponentCamera', js engine: hermes
    at ContextNavigator (http://127.0.0.1:8081/node_modules/expo-router/entry.bundle//&platform=ios&dev=true&hot=false&lazy=true:152097:24)
    at ExpoRoot (http://127.0.0.1:8081/node_modules/expo-router/entry.bundle//&platform=ios&dev=true&hot=false&lazy=true:152068:30)
    at App
    at withDevTools(App) (http://127.0.0.1:8081/node_modules/expo-router/entry.bundle//&platform=ios&dev=true&hot=false&lazy=true:130460:27)
    at ErrorToastContainer (http://127.0.0.1:8081/node_modules/expo-router/entry.bundle//&platform=ios&dev=true&hot=false&lazy=true:130361:24)
    at ErrorOverlay
    at RCTView
    at View (http://127.0.0.1:8081/node_modules/expo-router/entry.bundle//&platform=ios&dev=true&hot=false&lazy=true:40336:43)
    at RCTView
    at View (http://127.0.0.1:8081/node_modules/expo-router/entry.bundle//&platform=ios&dev=true&hot=false&lazy=true:40336:43)
    at AppContainer (http://127.0.0.1:8081/node_modules/expo-router/entry.bundle//&platform=ios&dev=true&hot=false&lazy=true:40176:36)
    at main(RootComponent) (http://127.0.0.1:8081/node_modules/expo-router/entry.bundle//&platform=ios&dev=true&hot=false&lazy=true:120850:28)
```
