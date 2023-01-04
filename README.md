# Keyboard Maestro: MacOS Calculator Macros
## A set of Keyboard Maestro macros for the MacOS Calculator.

I prefer to use keyboard commands on MacOS as much as possible. I therefore use the Mac utility application [Keyboard Maestro](https://www.keyboardmaestro.com/main/) to add my own key assignments to make up for those lacking within applications for my common tasks, increasing my productivity.

The MacOS calculator is good example; I use it regularly, usually for simple calculations, but occasionally for more involved ones, too. For example, squaring a number has a button but no keyboard access, and I can assign that to ⌘2.

This set of macros provides a mostly complete set of such operations and also a few extras such as menu selections, especially where they conflict with commands I’d rather use for calculations, e.g. the Scientific view is assigned ^⌘S rather than ⌘2. My assignment system is as follows: 

| Category               |  Subcategory        | Description                     | Key Assignment | Built-In |
| :--------------------- | :------------------ | :------------------------------ | :------------: | :------: |
| Keys with no modifiers | Numbers             | Digits                          |      0-9       |   Yes    |
|             ^          |    ^                | π = 3.141… (Pi)                 |       P        |   Yes    |
|             ^          |    ^                | e = 2.718… (Euler’s Number)     |       E        |   No     |
|             ^          |    ^                | γ = 0.577… (Euler’s Constant)   |       G        |   No     |
|             ^          |    ^                | φ = 1.618… (Golden Ratio)       |       F        |   No     |
|             ^          |    ^                | C = 0.915… (Catalan’s Constant) |       C        |   No     |
|             ^          | Standard Operations | = (Equals)                      |       =        |   Yes    |
|             ^          |    ^                | – (Subtraction)                 |       -        |   Yes    |
|             ^          |    ^                | / (Division)                    |       /        |   Yes    |
* Keys with the ⬆ modifier:
** Standard Operations:
*** x+y (⬆=)
*** x\*y (⬆8)
*** x^y (⬆6, power)
*** x\*100 (⬆5, % percent)
*** x\*10^y (⬆E, scientific notation)
* Keys with the ⌘ modifier:
** Functions:
*** x^2 (⌘2, square)
*** x^3 (⌘3, cube)
*** 1/x (⌘I, reciprocal)
*** trignometric
** Memory management:
* Keys with the ^⌘ modifiers: additional operations (hyperbolic); views (basic, scientific, programmers)
* Keys with the ⌥ modifier: inverse of the previous operations, including specific roots and logarithms.
** ± (the latter is ⌥- in the calculator rather than the default MacOS ⌥=±)

This leaves all of the calculator’s existing key assignments in place except for one — it assigns unshifted E to the natural logarithm function, while I assign that to the constant e, and use ⌘⌥E for natural logarithm (since I assign ⌘E to the exponential function).

These macros work with MacOS 12 Monterey, and probably with other versions, more or less.

It took a while to figure out what all of the button names are, and I can thank several people in [the Keyboard Maestro forums](https://forum.keyboardmaestro.com/t/km-macros-can-t-find-all-calculator-buttons/29859) for their assistance.
