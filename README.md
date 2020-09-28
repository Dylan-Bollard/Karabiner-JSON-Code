# Karabiner-Elements-JSON-Code
Personal key mappings for use with the Karabiner-Elements mapping software for macOS. Specifically useful for using a WindowsOS associated keyboard with macOS systems.

[Karabiner Elements](https://karabiner-elements.pqrs.org) is a utility to help macOS users change keybinds. There are a few other utilities that can do this. Mainly [Automator](https://support.apple.com/guide/automator/welcome/mac) will allow you to map actions to specific key sequences. This can be done in Karabiner using [Complex Modifications](https://ke-complex-modifications.pqrs.org) or simple modifications. 

Complex modifications differ from simple modifications in a few ways. First, a complex modification is capable of mapping a sequence of keystrokes to one button whereas a simple modification is not. For example, the traditional "Print Screen" button on WindowsOS keyboards does not naturally take a screenshot of your macOS desktop. However, it's possible to map several keystrokes (shift + command + 3) to one button. [See "Print Screen Complex Modifications" from master branch]. Second, complex modifications require creating or downloading code to specifically map a sequence of keystrokes. Simple modifications do not. Lastly, it's possible to add timing for keystrokes with complex modifications. For example, it's possible to configure the previously mentioned "Print Screen" button to act as "shift + command + 4" (user defined area for screenshot on macOS) if held down for more than two seconds. 

Complex modifications are very useful and follow a simple syntax. This file aims to explore the basic syntax.

# Simple Modifications Instructions

https://karabiner-elements.pqrs.org/docs/manual/configuration/configure-simple-modifications/

# Pre-Built Complex Modifications

https://ke-complex-modifications.pqrs.org

# Writing You Own Code

[Complex Modification Operators](https://karabiner-elements.pqrs.org/docs/json/complex-modifications-manipulator-definition/) are the basic syntax for Karabiner Elements. 
