PyDOC
=====

#### A Sublime Text plugin that supports Python documentation search from selections in the editor.

## About

PyDOC allows you to search Python 2 or Python 3 documentation on [http://docs.python.org](http://docs.python.org/) for selected built-in Python modules, classes, methods, and functions in the Sublime Text editor text.  A browser window is launched (in your default browser), using your selected text as the query term for the Python 2 or Python 3 documentation.

By default, the most recent Python 2 or Python 3 release documentation is used.

## Install PyDOC

PyDOC can be installed using [Sublime Package Control](https://sublime.wbond.net/).  Open the command palette with:

#### Mac OSX
```
Cmd + Shift + P
```

#### Linux & Windows
```
Ctrl + Shift + P
```

Type `install` and select the menu item, `Package Control: Install Package`.

Type `PyDOC` and select the PyDOC package that is displayed.  This will install the package in your editor.

## Use PyDOC

### Search with Right Click Menu

Select a built-in Python object in your editor text, then use the `Python 2 Doc Search` or `Python 3 Doc Search` menu item in the right click menu.

### Search with Keybinding

Select a built-in Python object in your editor text, then use one of the following keybindings to perform the search:

#### Python 2 Keybinding

```
Ctrl-2
```

#### Python 3 Keybinding

```
Ctrl-3
```

### Search with the Command Palette

Select a built-in Python object in your editor text then the command palette keybinding (see above) to open the command palette.  Type 'pydoc' and then select either `Python 2 Doc Search (PyDOC)` or `Python 3 Doc Search (PyDOC)`.

## License

[MIT License](https://github.com/chrissimpkins/PyDOC/blob/master/LICENSE)


