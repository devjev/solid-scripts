# Solid Scripts

Commandline Scripts used to power
[create-solid](https://github.com/ryansolid/create-solid)

## Fork

This is a fork with modified webpack config to include proper WebAssembly
loading and avoid some bugs with url-loader.

To include a Rust WebAssembly crate you would need to run with an additional
WebPack environment variable:

```
> npm run build --env.crateLocation="../my-wasm-crate"
```