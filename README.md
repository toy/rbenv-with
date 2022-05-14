This [rbenv](http://rbenv.org/) plugin allows easily changing Ruby version to run one command without having to keep patchlevels in mind.

## Usage examples

Switch current shell to latest stable JRuby:

```shell
rbenv with jruby ruby -v
```

Switch to whatever would be default (global or local):

```shell
rbenv with default ruby -v
```

Use 2.0 development version:

```shell
rbenv with 2.0 ruby -v
```

## Installation

Run these commands:

```shell
mkdir -p "$(rbenv root)"/plugins
git clone https://github.com/toy/rbenv-whatis.git "$(rbenv root)"/plugins/whatis
git clone https://github.com/toy/rbenv-with.git "$(rbenv root)"/plugins/with
```

Skip the first `git clone` if you already installed [rbenv-whatis](https://github.com/toy/rbenv-whatis).
