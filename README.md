# my-first-tauri-test
Similar to repository my-first-electron-test, but with tauri for comparison


## Tauri + Vanilla

This template should help get you started developing with Tauri in vanilla HTML, CSS and Javascript.

### Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) + [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)


## References

 - [Tauri official Guide](https://tauri.app/v1/guides/)
 - [Creating Tiny Desktop Apps With Tauri And Vue.js](https://www.smashingmagazine.com/2020/07/tiny-desktop-apps-tauri-vuejs/)
 - [ref](https://www.rust-lang.org/tools/install)

## Tauri Installation Instructions (linux)

Tauri requires a number of tool dependencies:

```bash
$ sudo apt update && sudo apt install libwebkit2gtk-4.0-dev build-essential curl libssl-dev appmenu-gtk3-module
```
Install rust ([ref](https://www.rust-lang.org/tools/install))
```bash
$ curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

$ rustup update

$ rustc --version
```


## How to install a new Tauri project in GitHub from scratch

Start by creating the repository at GitHub

Clone the repository, e.g.:

```bash
$ git clone https://github.com/lauler1/my-first-tauri-test.git
```
This process will create a subdirectory with the project name, e.g. `my-first-tauri-test`. Do not enter this directory yet.

Create a complete Taurus project using automated templates. Use the same project name and chose to replace the content of the folder.

```bash
$ npm create tauri-app

✔ Project name · my-first-tauri-test
✔ my-first-tauri-test directory is not empty, do you want to overwrite? · yes
✔ Choose your package manager · npm
✔ Choose your UI template · vanilla

Please follow https://tauri.app/v1/guides/getting-started/prerequisites to install the needed prerequisites, if you haven´t already.

Done, Now run:
  cd my-first-tauri-test
  npm install
  npm run tauri dev
```

This process will create a complete vanila software.

Now you can enter the project directory:
```bash
$ cd my-first-tauri-test
```

Now compile and run:
```bash
$ npm install
$ npm run tauri dev
```
