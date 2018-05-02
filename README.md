
mod-datasets
============

Copyright (C) 2018 The Open Library Foundation.  This software is distributed
under the terms of the Apache License, Version 2.0.  See the file
[LICENSE](https://github.com/folio-org/mod-datasets/blob/master/LICENSE) for
more information.


Overview
--------

The mod-datasets package runs a [Glint](https://github.com/indexdata/glint)
server as an [Okapi](https://github.com/folio-org/okapi) module.


System requirements
-------------------

These are requirements and dependencies for running mod-datasets:

* [Glint](https://github.com/indexdata/glint) v0.1.4 or later
* [Okapi](https://github.com/folio-org/okapi) v2.9.2 or later
* [Go](https://golang.org) 1.10 or later

Go is needed in order to compile mod-datasets from source code.  On macOS
running [Homebrew](https://brew.sh/), Go can be installed with `brew install
go`.


Installing mod-datasets
-----------------------

First ensure that the `GOPATH` environment variable specifies a path that can
serve as your Go workspace directory, the place where mod-datasets and other Go
packages will be installed.  For example, to set it to `$HOME/go`:

```shell
$ export GOPATH=$HOME/go
```

Then to download and compile mod-datasets:

```shell
$ go get -u github.com/folio-org/mod-datasets/...
```

