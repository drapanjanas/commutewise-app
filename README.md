![logo](https://commutewise.com/assets/admin/layout/img/logo-commutewise-inverted.png)

---

This project is a mobile app for https://commutewise.com. 

The app is built using ReactNative + ClojureScript using 
* [Reagent](https://github.com/reagent-project/reagent)
* [re-frame](https://github.com/Day8/re-frame)
* [Re-Natal](https://github.com/drapanjanas/re-natal)

## Development
Make sure you have all [dependencies](https://github.com/drapanjanas/re-natal#dependencies) installed.
 
After cloning this repo please install NPM dependencies, and enable dev mode:
```
$ npm i
$ re-natal use-figwheel
```

Start nREPL session from your IDE and start Figwheel
```clojure
> (start-figwheel "ios")
```

Then start the application
```
$ react-native run-ios
```

