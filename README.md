# Keyboard_Maestro-MacOS_Calculator_Macros
## A set of Keyboard Maestro macros for the MacOS Calculator.

I prefer to use keyboard commands as much as possible. I therefore use the Mac utility application [Keyboard Maestro](https://www.keyboardmaestro.com/main/) to add my own key assignments to make up for those lacking within applications for my common tasks, increasing my productivity.

The MacOS calculator is good example; I use it regularly, usually for simple calculations, but occasionally for more involved ones, too. For example, squaring a number has a button but no keyboard access, and I can assign that to ⌘2.

This set of macros provides a mostly complete set of such operations and also a few extras such as menu selections, especially where they conflict with commands I’d rather use for calculations, e.g. the Scientific view is assigned ^⌘S rather than ⌘2. My assignment system is as follows: 

* Keys with no modifiers: constants or other numbers, scientific notation, and standard operations (= + – * / ^ % ±)
* Keys with the ⌘ modifier: additional operations (specific exponentiation, reciprocal, trignometric), memory
* Keys with the ^⌘ modifiers: additional operations (hyperbolic); views (basic, scientific, programmers)
* Keys with the ⌥ modifier: inverse of the previous operations, including specific roots and logarithms.

This leaves all of the calculator’s key assignments in place except for one — it assigns unshifted E to the natural logarithm function, while I assign that to the constant e = 2.71828…, and use ⌘⌥E for natural logarithm (since I assign ⌘E to the exponential function).

These macros work with MacOS 12 Monterey, and probably with other versions, more or less.

It took a while to figure out what all of the button names are, and I can thank several people in [the Keyboard Maestro forums](https://forum.keyboardmaestro.com/t/km-macros-can-t-find-all-calculator-buttons/29859) for their assistance.
