# nbdev-hello-world


<!-- WARNING: THIS FILE WAS AUTOGENERATED! DO NOT EDIT! -->

This file will become your README and also the index of your
documentation.

## Dev Env Setup

1.  Git clone the project
2.  pip install nbdev - this is for the global pip, not within the
    project virtualenv
3.  install quarto - if you try nbdev_install_quarto on Command Line, it
    will install Quarto or give you the link to download Quarto CLI
4.  Restart VSCode and try running nbdev_prepare - there should NOT be
    any errors
5.  Run nbdev_preview to start the documentation web server - this will
    open a preview of the docs generated from the notebooks
6.  Install VS Code extension nbdev
7.  Modify some notebook file and save - you should get a message about
    cleaned notebook - this is the extension running nbdev_clean to get
    rid of unwanted metadata. Check whether the docs preview is updated
    with your change.
8.  Each time you change the notebook, do a Run All - this will ensure
    that the corresponding code files are generated
9.  Run nbdev_prepare before each commit.
10. Check the diff in Git Diff view - you should see a meaningful diff -
    commit the changes and do a git push to test whether CI/CD workflow
    is working.
11. Open index notebook and do a Run All - you will get an error that
    the module nbdev-hello-world is NOT found
12. do `pip install -e ".[dev]"` from the project folder root - this
    should install the package in dev mode
13. Run All on index notebook to check whether the error is gone.

## Install

``` sh
pip install nbdev_hello_world
```

## How to use

Fill me in please! Don’t forget code examples:

``` python
1 + 1
```

    2

``` python
2 + 2
```

    4
