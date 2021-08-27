### Tauri
* github: https://github.com/tauri-apps/tauri
* doc: https://tauri.studio/en/docs/getting-started/intro

```bash
# dev
npm run tauri dev
# build
npm run tauri build
```

在mac上编译win64应用（理论应该可以，测试未通过。。。）
```bash
brew install mingw-w64
rustup target add x86_64-pc-windows-gnu
tauri build --target x86_64-pc-windows-gnu
```

