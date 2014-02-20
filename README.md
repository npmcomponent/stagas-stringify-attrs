*This repository is a mirror of the [component](http://component.io) module [stagas/stringify-attrs](http://github.com/stagas/stringify-attrs). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/stagas-stringify-attrs`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# stringify-attrs

serialize an object into an html attributes string

## example

```js
var stringify = require('stringify-attrs');

var res = stringify({ foo: 'bar', baz: 'zo"o', flag: '' });

console.log(res); // foo="bar" baz="zo&quot;o" flag
```

## License

MIT
