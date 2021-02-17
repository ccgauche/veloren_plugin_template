# Veloren Plugin Template
  This repo is meant to be cloned

  To build the plugin you need rust installed then:

  ```
  cargo build --release --target=wasm32-unknown-unknown
  ```

  Then create a TAR archive with the `veloren_plugin_template.wasm` file located in `target/wasm32-unknown-unknown/release` and the `plugin.toml` and place it into the  `assets/plugin` folder of your game, if the folder doesn't exist create it.
 