# Pong!

## How to run

To play the game on Windows and Linux, run:

```
cargo run --features "vulkan"
```

And on macOS run:

```
cargo run --features "metal"
```

For building without any graphics backend, you can use

```
cargo run --features "empty"
```

but be aware that as soon as you need any rendering you won't be able to run your game when using
the `empty` feature.
