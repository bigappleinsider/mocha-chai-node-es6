### Testing out unit testing with mocha, chai, node, and es6

```
npm run test
```

- Installing required modules
```
npm i -D babel-core babel-preset-es2015 babel-preset-stage-2 chai mocha
```
- Babel presets
```json
{
  "presets": [
    "es2015",
    "stage-2"  
  ]
}
```
- By default mocha runs unit tests in a `test` folder
```
./node_modules/.bin/mocha --require babel-core/register
```
