## Webassembly with Rust

1. Install Rust
 - $ curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
2. Create wasm_project
 - $ cargo init --name wasm_project --lib
3. Install Rust package
 - $ cargo install wasm-pack
4. install webpack dependencies
 - $ npm init
5. Install dependencies
 - $ npm install
6. create simple webpack.config file
 - $ touch webpack.config.js
7. Run wasm-pack
 - $ wasm-pack build
8. check for webpack build in dist folder
 - $ node_modules/.bin/webpack
9. copy index.html to dist folder
 - $ cp index.html ./dist
10. To serve correct content-type use wasm-server
 - $ node_modules/.bin/wasm-server

 http://localhost:3000


