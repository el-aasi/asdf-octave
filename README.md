# asdf-octave

[![Build Status](https://travis-ci.org/nverno/asdf-octave.svg?branch=master)](https://travis-ci.org/nverno/asdf-octave)

R plugin for [asdf](https://github.com/asdf-vm/asdf) version manager.

## Install

```
asdf plugin-add octave https://github.com/nverno/asdf-octave.git
```

## Use

Check [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to
install & manage versions of octave.

When installing octave using `asdf install`, you can pass custom configure options
with the following env vars:

* `OCTAVE_CONFIGURE_OPTIONS` - use only your configure options
* `OCTAVE_EXTRA_CONFIGURE_OPTIONS` - append these configure options along with ones
that this plugin already uses (`--prefix-path`)
* `OCTAVE_MAKE_FLAGS` - flags passed to `make`
