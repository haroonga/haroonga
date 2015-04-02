Haroonga
===

[![Build Status](https://travis-ci.org/haroonga/haroonga.svg?branch=master)](https://travis-ci.org/haroonga/haroonga)

Low level Haskell binding for Groonga.

## dependencies

* Groonga 4.1.1+
* hsc2hs
* and some cabal packages (see: haroonga.cabal)

## export module(s)

* Bindings.Groonga
* Bindings.Groonga.Raw
* Bindings.Groonga.Raw.Plugin
* Bindings.Groonga.Raw.Tokenizer
* Bindings.Groonga.CommandAPI
* Bindings.Groonga.Types

## How to install

Install Groonga.
For example, if you use Ubuntu Linux, see: http://groonga.org/docs/install/ubuntu.html#lts-precise-pangolin

And then,

```bash
$ cabal install haroonga
```

## Support Platform

* Currently, Haroonga supports __platform which has pkg-config command only__.
    - Linux
    - Mac OSX

### Windows installation (for advanced users) *experimental*

* Install Groonga windows binary (e.g. C:\groonga)
* And type following command:

    > cabal install --extra-include-dirs='C:\groonga\include\groonga' --extra-lib-dirs='C:\groonga\lib'

## Haddock

* [Hackage](http://hackage.haskell.org/package/haroonga/docs/)
