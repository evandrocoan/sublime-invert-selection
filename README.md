Sublime invert selection
===============================

sublime 2 invert selection


## Installation

### By Package Control

1. Download & Install `Sublime Text 3` (https://www.sublimetext.com/3)
1. Go to the menu `Tools -> Install Package Control`, then,
   wait few seconds until the `Package Control` installation finishes
1. Go to the menu `Preferences -> Package Control`
1. Type `Package Control Add Channel` on the opened quick panel and press <kbd>Enter</kbd>
1. Then, input the following address and press <kbd>Enter</kbd>
   ```
   https://raw.githubusercontent.com/evandrocoan/StudioChannel/master/channel.json
   ```
1. Now, go again to the menu `Preferences -> Package Control`
1. This time type `Package Control Install Package` on the opened quick panel and press <kbd>Enter</kbd>
1. Then, search for `InvertSelection` and press <kbd>Enter</kbd>

See also:
1. [ITE - Integrated Toolset Environment](https://github.com/evandrocoan/ITE)
1. [Package control docs](https://packagecontrol.io/docs/usage) for details.


## Usage :

 - use `cmd+shift+P` then `Invert Selection`
 - or goto menubar `Selection` then `Invert Selection`
 - or bind some key in your user key binding:

  ```js
    {
	 "keys": ["ctrl+alt+shift+i"],
	 "command": "invert_selection"
	}
  ```

 [0]: http://wbond.net/sublime_packages/package_control
