# Project Configs
Like dotfiles but for projects.

Build status:

## Why?

Basic config files for majority of open source projects. From contributing.md to package.json and much more.

The focus of the project is on Javascript repos that are either private or can be ready to be published to NPM.

## Requirements

Since this project is JS-heavy, you're expected to have Node, NPM, and a few other dependencies.

All javascript projects require the following packages installed globally:

```bash
npm install -g eslint
```

For typescript projects install the following:

```bash
npm install -g typescript tslint typings
```

For front-end projects, make sure to install the following:

```bash
npm install -g bower
```

Other dependencies are driven by the editor used so look out for plugins for:

- eslint
- tslint and typescript
- editorconfig

## Installation and setup

Setup and installation is easy...there is none. Copy/paste from Github is just as acceptable as doing a manual `mv` or `cp` from the repository locally.

When starting a new project, the following is also acceptable:

```bash
git clone git@github.com:AntJanus/project-configs.git [name of new project]
cd [name of new project]

# and then delete files that aren't useful for the project with
rm uselessconfig.json .uselessdotfile
```

## Changelog

A summary changelog for smaller projects:

- **0.0.1** - project initialized