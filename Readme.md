# cheerio-no-node-native

[cheerio](https://github.com/cheeriojs/cheerio) build that excludes node native modules so that you can use it in platforms like React Native.

cheerio version: `0.20.2`

```
npm i cheerio-no-node-native@0.20.2
```

* use [htmlparser2-without-node-native](https://github.com/oyyd/htmlparser2-without-node-native) instead of [htmlparser2](https://github.com/fb55/htmlparser2).
* exclude node Buffer

## Test

```
npm run test
```
