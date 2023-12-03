# 使用phaser.js制作的web小游戏

[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-908a85?logo=gitpod)](https://gitpod.io/#https://github.com/PhaserEditor2D/starter-template-basic-javascript)


## 特点

* It includes the latest Phaser v3 runtime (in the `lib/` folder).
* It is coded in JavaScript.
* It includes a VS Code project configuration (`jsconfig.json` file) and the type definitions (in the `types/` folder).

## nodejs 编辑

If you have NodeJS installed, you can run the editor using the `editor` NPM script, defined in the `package.json` file.

First you have to install & update the dependencies:

```bash
$ npm install
$ npm update
```

And then you can run the editor:

```bash
$ npm run editor
```

If you are in a remote environment (like the Gitpod.io IDE), then run the editor like this:

```bash
$ npm run editor-remote
```

## Script Nodes

Script nodes are logic objects. You can add a script node to the scene or a game object, for extending it with custom data and behavior.

This project includes the [basic script nodes](https://github.com/PhaserEditor2D/script-nodes-basic-js) in the `src/script-nodes-basic/` folder. You can add your own script nodes in the `src/script-nodes/` folder.
