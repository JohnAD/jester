# 🃏 Jester (with plugins) 🃏

The sinatra-like web framework for Nim. Jester provides a DSL for quickly
creating web applications in Nim.

This particular version is a fork of the main-line `jester` for the testing of
the "plugin" functions. It will eventually
be merged back into `jester`. If you are not using the plugins, I recommend
using the main `jester` library. See https://nimble.directory/pkg/jester

## Install

It is best to install using the nimble tool:

```bash
$ nimble install jesterwithplugins
```

## Example Of Use

```nim
# example.nim
import jesterwithplugins

routes:
  get "/":
    resp "<html><body><h1>Hello World!</h1></body></html>"
```

Compile and run with:

```bash
$ nim c -r example.nim
```

View with a browser at: [localhost:5000](http://localhost:5000)

## [WIP] Plugins

For using plugins, see [plugins](../blob/master/docs/plugin.md).

To develop a plugin, see [plugin development](../blob/master/docs/plugin-develop.md).

## Further documentation

TBD
