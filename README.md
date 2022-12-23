# Demo

A demo application to test and showcase FIDO2 authentication using the
[Wax library](https://github.com/tanguilp/wax).

## How to run the demo

Run the following commands

```bash
mix deps.get
cd assets && npm install && node node_modules/webpack/bin/webpack.js --mode development && cd ..
iex -S mix phx.server
```

and then browse [http://localhost:4000](http://localhost:4000)