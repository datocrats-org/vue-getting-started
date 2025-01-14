# Vue Getting Started

This project is seen in demos including the Pluralsight course "Vue: Getting Started" to help represent a fundamental app written with Vue. The heroes and villains theme is used throughout the app.

by [John Papa](http://twitter.com/john_papa)

## Projects

This repository contains several projects. Each project represents a step in the learning experience. Two proejects of note are:

- `02-getting-started/end/vue-heroes` - This is the starting point for the app
- `xx-final/vue-heroes` - This is the ending point for the app


## Quick Start

1. Clone this repository

   ```bash
   git clone https://github.com/johnpapa/vue-getting-started.git
   cd vue-getting-started
   ```

1. Change to the folder you wish to use

   ```bash
   cd 02-getting-started/end/vue-heroes
   ```

1. Install the npm packages

   ```bash
   npm install
   ```

1. Run the app!

   ```bash
   npm run serve
   ```

## Quick Start - `npm install` for each module

### Git bash commands to install npm modules at the beginning of each example

```bash
export PARENT_DIR
PARENT_DIR=C:/code/training/vue-getting-started # edit this to match your local git directory

cd $PARENT_DIR/03-data-and-events/begin/vue-heroes | npm install
cd $PARENT_DIR/04-lists-and-conditionals/begin/vue-heroes | npm install
cd $PARENT_DIR/05-interacting-within-a-component/begin/vue-heroes | npm install
cd $PARENT_DIR/06-component-communication/begin/vue-heroes | npm install
cd $PARENT_DIR/07-accessing-data/begin/vue-heroes | npm install
cd $PARENT_DIR/08-routing/begin/vue-heroes | npm install
cd $PARENT_DIR/09-managing-state/begin/vue-heroes | npm install
```

### Git bash commands to install npm modules at the end of each example

```bash
cd $PARENT_DIR/02-getting-started/end/vue-heroes | npm install
# copy begin commands and replace `begin` with `end` here 
cd $PARENT_DIR/xx-final/vue-heroes | npm install
```

## Problems or Suggestions

[Open an issue here](/issues)

## Resources

- [VS Code](https://code.visualstudio.com?wt.mc_id=vuegettingstarted-github-jopapa)
- [VS Code Extension Marketplace](https://marketplace.visualstudio.com/vscode?wt.mc_id=vuegettingstarted-github-jopapa)
- [VS Code - macOS keys](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf?WT.mc_id=vuegettingstarted-github-jopapa)
- [VS Code - Windows keys](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf?WT.mc_id=vuegettingstarted-github-jopapa)
- [Debugging Vue in VS Code](https://code.visualstudio.com/docs/nodejs/vuejs-tutorial?wt.mc_id=vuegettingstarted-github-jopapa)
