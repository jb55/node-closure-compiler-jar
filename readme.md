
# closure-compiler

  Allows you to add `closure-compiler` as dependency so that you can use it in
  your CI builds

## Installation

  Install with npm

    $ npm install --save-dev closure-compiler

## Example

```bash
# dev environment
export PATH=`npm bin`:$PATH
# ...
closure-compiler --some options < in > out
```
