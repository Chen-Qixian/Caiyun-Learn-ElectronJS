# Electron.js 学习

为了开发小译桌面应用，本仓库为练习electron.js的基本使用而创建。



## 学习资料

- Electron: https://electronjs.org/
- Electron is a framework for creating native applications with web technologies like JavaScript, HTML, and CSS.
- Reference: [Electron IN ACTION](



## 第一个electron项目

- `mkdir <project_name>`
- `cd <project_name>`
- `mkdir app`
- `touch app/main.js app/renderer.js app/style.css app/index.html`
- `npm init` Note: If you want to skip the process, add `--yes`
- `npm install electron --save` Note: 'save' will add the installed package to the list of dependencies in the package.json.
- `vim package.json` and Add `"start": "electron ."` in `"scripts"`,
- `npm start`



## 如何debug

- Render procee: Open View and chocie Toggle Developer Tool, or press `Command-Option-I`(Mac)
- Main process: add `--debug` flag