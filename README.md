[![Build Status](https://travis-ci.org/extr0py/vim-electrify-typescript-completion.svg?branch=enable-travis-ci)](https://travis-ci.org/extr0py/vim-electrify-typescript-completion)
[![Stories in Ready](https://badge.waffle.io/extr0py/vim-electrify-typescript-completion.png?label=ready&title=Ready)](https://waffle.io/extr0py/vim-electrify-typescript-completion)
# vim-electrify-typescript-completion
##### Supercharge VIM into a TypeScript powerhouse

- [Intro](#intro)
- [Installation](#installation)
    - [Windows](#windows)
- [Usage](#usage)
- [Commands](#commands)
- [Notes](#notes)
- [License](#license)
- [Contact](#contact)

Intro
------

A js plugin implementation of JS omnicompletion, using the TypeScript language service.

This was built to give a premier TypeScript experience on  Windows, through Vim.

![vim-electrify-typescript-completion demo](http://imgur.com/0Y3dvWB.gif)

The demo shows the following aspects:
- Quick info through the status line
- Autocompletion
- Error flagging and highlighting
- Goto definition

Installation
------------

### Windows

#### Prerequisites:
- Vim 7.4
- Node / npm (recommended version 6+ and 3+)
- [vim-electrify](https://github.com/extr0py/vim-electrify)

Recommended:
- [typescript-vim](https://github.com/leafgarland/typescript-vim)

#### Installation:
- Clone into your plugins folder:

    `git clone https://github.com/extr0py/vim-electrify-typescript-completion.git`

- Install dependencies

    `npm install`

Usage
-----

Once the plugin is installed, it will automatically be activated for JavaScript and TypeScript files.

Commands
--------

#### Goto definition

    :TSDefinition

Navigates to the definition of an object, if possible.

Notes
-----
- Make sure to have a valid tsconfig.json or jsconfig.json for best results
- Not yet tested for compatibility with AutoComplPop, YouCompleteMe, or Syntastic.
    - Recommend disabling these plugins for typescript files.

License
-------

MIT License

Contact
-------

extropy@extropygames.com
