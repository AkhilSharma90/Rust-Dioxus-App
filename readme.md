## Dioxus Todo App

<p>This application is a simple todo application built with Dioxus.
It explores the following features:</p>

- State management
- Components
- Events
- Hooks
- Styling
- Forms

## Instructions

- DO NOT RUN this with `cargo run`
- Install `cargo install dioxus-cli`
- run `dx serve`
- you will get an error about wasm-bindgen, that's alright, solve it with `cargo update -p wasm-bindgen --precise 0.2.91`
- now open `localhost:8080`
- if the program still doesn't work, check `cargo add dioxus dioxus-web wasm-bindgen im`