# Griffon Sublime Text 2 Package

The **Griffon Sublime Text 2 Package** provides code completion, syntax highlighting and other tools to work with [Griffon].


## Installation

There are two main ways to install the *Griffon Sublime Text 2 Package*:

1. Via the [Sublime Package Control]. 

2. Placing a Griffon directory containing this resource under Packages.

    Linux:

        git clone git://github.com/griffon/sublimetext-griffon.git ~/.config/sublime-text-2/Packages/Griffon

    OS X:

        git clone git://github.com/griffon/sublimetext-griffon.git ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/Griffon

    Windows:

        git clone git://github.com/griffon/sublimetext-griffon.git "%APPDATA%\Sublime Text 2\Packages\Griffon"


## Features

- Code completions for Griffon file types, with automatic file type detection (Models, Views, Controllers, and Services classes for now)

- Code completions for all methods from `griffon.core.MVCHandler`, `griffon.core.ThreadingHandler`, `griffon.core.ResourceHandler`, `griffon.core.i18n.MessageSource`, `griffon.core.resources.ResourceResolver` and `griffon.core.GriffonApplication`.

## TODO

- Run Griffon commands from the Sublime console (if possible)

- Navigation between classes and their tests (through context menu maybe)

- Improve code completions when multiple parameter lists are possible


## Participate!

Help us improve this plugin by reporting errors in the [issue tracker]. That's also the best way to ask questions or
give us suggestions. If you modify the plugin, we'd love to get a pull request so we can share the improvements with everyone.

## Credits

Andres Almiray - [@aalmiray](https://twitter.com/aalmiray)

Forked and modified from [sublimetext-grails] original by

* Arturo Herrero - [@ArturoHerrero](https://twitter.com/ArturoHerrero)
* Geli Crick - [@g_crick](https://twitter.com/g_crick)


[Griffon]: http://griffon-framework.org/
[Sublime Package Control]: http://wbond.net/sublime_packages/package_control
[issue tracker]: https://github.com/griffon/sublimetext-griffon/issues
[sublimetext-grails]: https://github.com/osoco/sublimetext-grails