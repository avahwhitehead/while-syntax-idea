# while-syntax-idea

Intellij IDEA syntax highlighting for the WHILE language used in "Limits Of Computation" at [The University of Sussex](https://susex.ac.uk).

See [alexj136/HWhile](https://github.com/alexj136/HWhile/) for more information on the language.

# Installing

1. Zip the `filetypes/` folder
   (or grab the latest [release zip](https://github.com/sonrad10/while-syntax-idea/releases))
   so that it looks like this:

    ```
    while-idea.zip
    ├── filetypes
    │   └── ...
    ```

1. Import to IDEA with:

   *File* -> *Manage IDE Settings* -> *Import Settings*

   And choose the zip file

1. Done!

# Uninstalling

1. Go to:

    *File* -> *Settings* -> *Editor* -> *File Types*

1. Press the `-` button to delete the file type association

# Contributing/Issues

There's probably not much to add here, but if you notice anything you can either open an [issue](https://github.com/sonrad10/while-syntax-idea/issues), or you can add the proposed changes to a new branch, and open a [pull request](https://github.com/sonrad10/while-syntax-idea/pulls) into [master](https://github.com/sonrad10/while-syntax-idea/tree/master).

This was made by adding the language's keywords into IDEA's "New File Type" window (see [uninstalling](#uninstalling)), then exporting them using *File* -> *Manage IDE Settings* -> *Export Settings*.
It's probably easiest to make any changes that was, but you could also edit the XML file(s) directly without much issue.