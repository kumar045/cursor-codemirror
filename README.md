# Cursor-Codemirror

Hello! This is an old version of [Cursor](https://cursor.so/) based off of the [Codemirror](https://codemirror.net/) text editing component. If you're looking to build your own code editor, this may serve as a useful guide 🙂

## Getting Started

To get started:

```
git clone git@github.com:getcursor/cursor.git
cd cursor
npm i
```

Then, download some non-versioned dependencies (ripgrep binaries and language server js):

```
./setup.sh # Mac/Linux
./setup.ps1 # Windows
```

Finally, to run the client:

```
npm start
```

## Acknowledgements

Thank you to Marijn Haverbeke for his monumental work on Codemirror v6. Other open source dependencies that are critical to this editor include: Electron, React, [Pylsp](https://github.com/python-lsp/python-lsp-server), Replit's [many](https://github.com/replit/codemirror-vim) [CM](https://github.com/replit/codemirror-emacs) [packages](https://github.com/replit/Codemirror-CSS-color-picker), [Watcher](https://github.com/fabiospampinato/watcher). Thank you to everyone who filed bugs/suggestions on this version of the editor.

Finally, thank you the members of our community who contributed to Cursor's development, including: [Liam](https://github.com/terror), [Edoardo](https://github.com/elanzini), [Edwiin](https://github.com/boxizen), [Abby](https://github.com/abbychau), [Mileta](https://github.com/MiletaA), [孟健](https://github.com/mengjian-github), [Chen](https://github.com/yuchen9), and many others.
