*PlantUMLIt



Introduction
============

plantumlit (PlantUML Inline Text) is built atop the wang-hardeningly awesome [plantuml](http://plantuml.com).
It gives you a "live preview" of your UML diagrams when you save.

![Demo](https://github.com/rsinghgit/vim-plantumlit/raw/master/_assets/demo.gif)


Installation
============

First you need Java installed.

Then, install this plugin with your favourite vim plugin manager.

For [Vim Plug](https://github.com/junegunn/vim-plug), just stick this in your
vimrc and smoke it:

```
Plug 'rsinghgit/vim-plantumlit'
```

Then run `:PlugInstall`

I also recommend installing the
[plantuml-syntax](https://github.com/aklt/plantuml-syntax) plugin as plantumlit
uses this for its syntax file.

```
Plugin 'aklt/plantuml-syntax'
```

Usage
=====

Edit a `.uml` file and enter some plantuml code. When you save it, a preview
will be forcefully inserted/updated at the top of your file!

Note: I have only used this for sequence diagrams - the ASCII output of
plantuml seems to be less than stellar for other diagram types.
