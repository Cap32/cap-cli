# cap-cli

> 🎩 cap is short for "Copy-And-Paste"

Sync clipboard over LAN

## Installations

Make sure installed [Node.js](http://nodejs.org/) (>= v4.2) and [npm](http://npmjs.org/), and then run:

```bash
$ npm install -g cap-cli
```


## Usage

1. Open terminal or cmd on your device
2. Run `cap start`, it will show you a PIN code
3. Open terminal or cmd on another device in the same LAN
4. Run `cap start --pin=XXXXX` (use the PIN code above instead of XXXXX)
5. Enjoy this awesome

For more usage, please run:

```bash
$ cap -h
```


## Caveats

- Clipboard data is NOT encrypted
- Sync text only


## TODO

- Auto start


## License

MIT
