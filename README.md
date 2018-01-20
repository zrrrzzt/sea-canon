[![Build Status](https://travis-ci.org/zrrrzzt/sea-canon.svg?branch=master)](https://travis-ci.org/zrrrzzt/sea-canon)
[![Greenkeeper badge](https://badges.greenkeeper.io/zrrrzzt/gun-next-example.svg)](https://greenkeeper.io/)

# sea-canon

A temporary fix for [GUN/SEA](https://github.com/amark/gun) and browserify/webpack

Very experimental and just created to get some demoes up and running with Next.js.

## Usage

In your package.json add this to your dependencies

```JavaScript
"sea-canon": "git+https://github.com/zrrrzzt/sea-canon.git"
```

In your file add this

```JavaScript
import Gun from 'gun/gun'
import SEA from 'sea-canon'
Gun.SEA = SEA
const gun = new Gun('https://url-to-your-peer')
const user = gun.user && gun.user()
```

And from here you should be able to follow the SEA examples

## Disclaimer

This is only for demonstrational purposes. For your production code please wait for the official support. 

## Acknowledegements

This is based on the awesome work of [Mark Nadal](https://github.com/amark) and [Mika](https://github.com/mhelander)

## License
[MIT](LICENSE)

