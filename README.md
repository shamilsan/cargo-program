# cargo-program

Utility to simplify Gear programs development.

:warning: **The project is currently under active development. Some features may be unstable.**

## Install

- [ ] *(not released yet)* Stable version from [crates.io](https://crates.io/crates/cargo-program):

```
cargo install cargo-program
```

- [x] Latest version from the repo:

```
git clone https://github.com/gear-tech/cargo-program.git
cargo install --path cargo-program
```

## Usage

###  Create a new Gear program

```
cargo program new my-program
```

###  Create a new async Gear program

```
cargo program new my-async-program --async
```

### Build the Gear program

```
cargo program build
```

### :construction: *(in progress)* Run the Gear program off-chain (default)

```
cargo program run
```

### :construction: *(in progress)* Run the Gear program on-chain using local node

```
cargo program run --node
# or
cargo program run --node 127.0.0.1:9933
```

### :construction: *(in progress)* Run tests

```
cargo program test
```

### :construction: *(in progress)* Login to the Gear backend

```
cargo program login
# or
cargo program login --host https://my-gear-backend.tld:8123
```

### :construction: *(in progress)* Publish the Gear program to the chain

```
cargo program publish
```

## License

**cargo-program** is licensed under [GPL v3.0 with a classpath linking exception](LICENSE).
