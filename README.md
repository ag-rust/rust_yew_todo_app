# Rust Yew Todo Application

# A simple Rust client side Todo App using the Yew Framework.  

#### Major Props to icode-live for updating this repository for the latest version of Yew. https://github.com/tensor-programming/rust_yew_todo_app/commit/a8b1aaafa5d3a71d6466686c6ce75703d66cf025

### Running it

Clone or download this repository.

You need to have cargo-web installed as well as a suitable target for the Rust compiler to generate web output. 
By default cargo-web uses asmjs-unknown-emscripten. 

#### Rust stable

Install cargo-web and the asmjs and wasm32 emscripten targets as follows:

```
$ cargo install cargo-web
$ rustup target add asmjs-unknown-emscripten
$ rustup target add wasm32-unknown-emscripten
```


To run an optimised build instead of a debug build use:

```
$ cargo web start --target=wasm32-unknown-emscripten --release
```

#### Rust nightly
If you are using rust nightly you can use the brand new `wasm32-unknown-unknown` target

```
$ cargo install cargo-web
$ rustup target add wasm32-unknown-unknown
$ cargo web start --target=wasm32-unknown-unknown
```

### Check out the Youtube Tutorial for this [Rust Tutorial](https://youtu.be/j8EnB7gkygw).  Here is our [Youtube Channel](https://www.youtube.com/channel/UCYqCZOwHbnPwyjawKfE21wg) Subscribe for more content.

### Check out our blog at [tensor-programming.com](http://tensor-programming.com/).

### Our [Twitter](https://twitter.com/TensorProgram), our [facebook](https://www.facebook.com/Tensor-Programming-1197847143611799/) and our [Steemit](https://steemit.com/@tensor).


