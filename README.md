## docksh ##
A simple way to spin up a fresh Docker container to use as your shell.

### Options ###
`docksh` options are specified (in true shell script fashion) through the
`DOCKSH_*` environment variables.

* `DOCKSH_SHELL` (default: `/bin/bash`) specifies the shell to `docker exec`
  into inside the container.
* `DOCKSH_USER` (default: `$HOME`) specifies the user to `sudo -u` into when
  running inside the container.
* `DOCKSH_IMAGE` (default: `$HOME/.docksh`) specifies the file which contains
  the name of the image to spin up the `docksh` container from.

### License ###
`docksh` is licensed under the MIT/X11 license:

```
docksh: use a (fresh) Docker container as your shell
Copyright (C) 2015 Cyphar <cyphar@cyphar.com>

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

1. The above copyright notice and this permission notice shall be included in
   all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
