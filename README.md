[![Build Status](https://travis-ci.org/rocky/remake.svg?branch=remake-4-3)](https://travis-ci.org/rocky/remake) [![Packaging status](https://repology.org/badge/tiny-repos/remake.svg)](https://repology.org/project/remake/versions)

[![Download remake](https://a.fsdn.com/con/app/sf-download-button)](https://sourceforge.net/projects/bashdb/files/remake/4.3%2Bdbg-1.5/)

Here we have patched GNU Make 4.3 sources to add improved error reporting, tracing, target listing, graph visualization, profiling, and more. It also
contains a [debugger](https://remake.readthedocs.io/en/latest/debugger.html). Branches [`remake-4-2`](https://github.com/rocky/remake/tree/remake-4-2), [`remake-4-1`](https://github.com/rocky/remake/tree/remake-4-1), [`remake-3-82`](https://github.com/rocky/remake/tree/remake-3-82), and [`remake-3-81`](https://github.com/rocky/remake/tree/remake-3-81) for patched GNU Make 4.2, 4.1, 3.82, and 3.81 respectively.

See the [readthedocs guide](https://remake.readthedocs.io/en/latest/index.html) for information, including `remake` [features](https://remake.readthedocs.io/en/latest/features.html), and [installation](https://remake.readthedocs.io/en/latest/install.html).

The [wiki](https://github.com/rocky/remake/wiki) also has information, including links to videos, and information for developers.

Example showing `--tasks` feature:

![--tasks](screenshots/remake-session0.gif)
https://kcachegrind.github.io/html/Home.html
Example showing `--trace` (short option `-x`) feature:

![--trace](screenshots/remake-trace.gif)


Example showing `--show-parent` (short option `-c`) feature:

![--show-parent](screenshots/remake-search-parent.gif)

Example showing `--profiling` output (displayed via [KCachegrind](https://kcachegrind.github.io/html/Home.html)):

![--profile](screenshots/remake-profiled2.png)
