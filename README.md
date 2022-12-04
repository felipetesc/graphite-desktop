# Graphite Desktop

I've only setup Graphite and Tauri

## All the work was done by the people of https://github.com/GraphiteEditor/Graphite

# If you have a request, ask them 

## Requisites to build your own version
- Shell client
- Git
- Rust
- Node
- NPM
- Tauri

## What I did to build my own version
- I installed git
- Installed Rust from https://rustup.rs/ and followed its instructions
- I had setup Tauri as explained at: https://tauri.app/v1/guides/getting-started/setup/ (I've used cargo to install tauri and tauri-cli)
- I've cloned Graphite with `git clone https://github.com/GraphiteEditor/Graphite.git`
- Build Graphite using the instructions at  https://graphite.rs/contribute/.
- Created a new tauri project from the terminal `cargo create-tauri-app graphite-desktop`
- Removed all files from the src directory EXCEPT `main.js`
- I copied the contents from Graphite/frontend/dist and pasted inside src
- I executed `cargo tauri build`

## How to build

- Install Rust (https://rustup.rs/)
- Navigate to src-tauri and run `cargo tauri build`

![Printscreen](https://github.com/felipetesc/graphite-desktop/blob/master/assets/print.jpg)