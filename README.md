# Visualization Application based on electron-vite-vue

[![GitHub Build](https://github.com/bishop9910/visualization-app/actions/workflows/build.yml/badge.svg)](https://github.com/bishop9910/visualization-app/actions/workflows/build.yml)

## Quick Setup

```sh
# clone the project
git clone https://github.com/bishop9910/visualization-app.git

# enter the project directory
cd electron-vite-vue

# install dependency
npm install

# develop
npm run dev
```

## Debug

![electron-vite-react-debug.gif](https://github.com/electron-vite/electron-vite-react/blob/main/electron-vite-react-debug.gif?raw=true)

## Directory

```diff
  ├─┬ electron
  │ ├─┬ main
  │ │ └── index.ts    entry of Electron-Main
  │ └─┬ preload
  │   └── index.ts    entry of Preload-Scripts
  ├─┬ src
  │ └── main.ts       entry of Electron-Renderer
  ├── index.html      entry of Vue and Vite
  ├── package.json
  └── vite.config.ts
```

## FAQ

- [C/C++ addons, Node.js modules - Pre-Bundling](https://github.com/electron-vite/vite-plugin-electron-renderer#dependency-pre-bundling)
- [dependencies vs devDependencies](https://github.com/electron-vite/vite-plugin-electron-renderer#dependencies-vs-devdependencies)
