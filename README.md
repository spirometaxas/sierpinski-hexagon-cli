# sierpinski-hexagon-cli
Print the Sierpinski Hexagon to the console!

## Usage
### Via `npx`:
```
$ npx sierpinski-hexagon-cli <n>
$ npx sierpinski-hexagon-cli <n> <size>
```

### Via Global Install
```
$ npm install --global sierpinski-hexagon-cli
$ sierpinski-hexagon-cli <n>
$ sierpinski-hexagon-cli <n> <size>
```

### Via Import
```
$ npm install sierpinski-hexagon-cli
```
then:
```
const sierpinski = require('sierpinski-hexagon-cli');
console.log(sierpinski.create(<n>, <size>));
```