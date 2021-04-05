# Tyr Releases
Latest releases of Timm Felden's Tyr compiler.

## Status

As of today, the compiler is incomplete.
Expect bugs!

**NO WARANTY OR LIABILITY OF ANY KIND!**

However, a lot of very cool features work very well.
The release notes will mention the supported language level and the overall tyr.lang + conformance.test test status.

## Requirements

Currently, I do only compile to Ubuntu 20.04.
Furthermore, you need
 - java 11
 - llvm 10 (opt+lli)

## On Licensing

Tyr has a very cool feature that allows you to use templates from other libraries without knowing the other library's source code.
From my perspective, this makes a compiled library (.tl file) something that is neither source nor binary.
In order to solve this issue, all options are split into two categories *public free* and *commercial*.
Both categories allow you to use the resulting executables without any non-obvious restrictions.

### Public Free

In order to be considered public free you have to
 - publish your sources under a permissive license that allows derivatives and commercial uses (e.g. Apache v2, MIT, BSD)
 - publish all sources and configuration required to build your library in a *public* repository

The latest version of the compiler published in this repository may be used to compile public free Tyr projects.

### Commercial

Any project that is not public free is considered commercial.
This includes any copy-left licenses such as GPL or LGPL.

Using this compiler to compile a commercial project requires that the user owns a valid commercial license.
