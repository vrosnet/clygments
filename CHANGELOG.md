# CHANGELOG

## 0.1.2 (upcoming)

* [breaking] main exceptions handler removed: versions 0.1.1 and before wrapped
  the main code in a `try/catch` that would print the catched exception’s
  message and the stacktrace. This is useless, exceptions should be catched by
  the caller.

## 0.1.1

* support for lexers & formatters options (#1)
* better handling of multi-lines code
* languages and outputs are case-insensitive (e.g. `:HTML` now works like
  `:html`)
* using Pygments [1.6][] instead of 1.5
* minor startup time improvement

[1.6]: https://bitbucket.org/birkenfeld/pygments-main/src/3e451a3806d9215bae592d9c28321076e5e046ef/CHANGES?at=default#cl-102

## 0.1.0

initial version.
