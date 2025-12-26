<p align="center">
  <img src="src-tauri/icons/icon.png" width="150" alt="Tauri Template">
</p>

# Tauri Template

[![build](https://github.com/remarkablemark/tauri-template/actions/workflows/build.yml/badge.svg)](https://github.com/remarkablemark/tauri-template/actions/workflows/build.yml)

🔗 Template to develop with [Tauri](https://tauri.app/) in vanilla HTML, CSS and TypeScript.

## Prerequisites

Install [Rust](https://rust-lang.org/):

```sh
brew install rust
```

Install [Node.js](https://nodejs.org/):

```sh
brew install node
```

## Install

Clone the repository:

```sh
git clone https://github.com/remarkablemark/tauri-template.git
cd tauri-template
```

Install the dependencies:

```sh
npm install
```

Rename the project:

```sh
git grep -l tauri-template | xargs sed -i '' -e 's/tauri-template/my-app/g'
git grep -l 'Tauri Template' | xargs sed -i '' -e 's/Tauri Template/My App/g'
```

Set the version:

```sh
git grep -l '"1.0.0"' | xargs sed -i '' -e 's/"1.0.0"/"1.2.3"/g'
```

Update the files:

- [ ] `src-tauri/Cargo.toml`
- [ ] `src-tauri/icons/`
- [ ] `src-tauri/tauri.conf.json`

## Available Scripts

In the project directory, you can run:

### `npm run dev`

Runs the app for development.

### `npm run build`

Builds the app for production.

## IDE

Recommended IDE setup:

- [VS Code](https://code.visualstudio.com/)
- [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode)
- [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)

## License

[MIT](LICENSE)
