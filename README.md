# Keyboard Maestro: MacOS Calculator Macros
## A set of Keyboard Maestro macros for the MacOS Calculator.

I prefer to use keyboard commands on MacOS as much as possible. I therefore use the Mac utility [Keyboard Maestro](https://www.keyboardmaestro.com/main/) to add my own key assignments to make up for those lacking within applications for my common tasks, increasing my productivity.

The MacOS calculator is a good example; I use it regularly, usually for simple calculations, but occasionally for more involved ones, too. For example, squaring a number has a button but no keyboard access, so I assign x² to ⇧ 2. Similarly, I assign 2<sup>x</sup> to ⌘ 2.

This set of macros provides a mostly complete set of such operations and also a few extras such as menu selections, especially where they conflict with commands I’d rather use for calculations, e.g. the Scientific view is assigned ⌘ ^ S rather than ⌘ 2.

My key assignments are in the following table, using the following symbols for key modifiers: ⇧ (shift), ⌘ (command), ^ (control), and ⌥ (option). Note that keys are indentified by capital letter (as they are on the keyboard), but are lower-case unless shifted.

<table>
<tr><th> Category </th>         <th> Symbol </th>   <th> Description </th>              <th> Key Assignment </th> <th> Built-In Key? </th></tr>

<tr><td rowspan=6> Numbers </td>
    <td> 0, 1, … 9 </td>  <td> Digits </td>                   <td> 0, 1, … 9 </td>  <td> Yes </td></tr>
<tr><td> <i>π</i> </td>   <td> 3.141… Pi </td>                <td> P         </td>  <td> Yes </td></tr>
<tr><td> <i>e</i> </td>   <td> 2.718… Euler’s Number </td>    <td> E         </td>  <td> No </td></tr>
<tr><td> <i>γ</i> </td>   <td> 0.577… Euler’s Constant </td>  <td> G         </td>  <td> No </td></tr>
<tr><td> <i>φ</i> </td>   <td> 1.618… Golden Ratio</td>       <td> F         </td>  <td> No </td></tr>
<tr><td> Rand     </td>   <td> 0 ≤ Random Number < 1</td>     <td> R         </td>  <td> No </td></tr>

<tr><td rowspan=7> Basic Operations </td>
    <td> <var>x</var> – <var>y</var> </td> <td> Subtraction </td>           <td> - </td>                                <td> Yes </td></tr>
<tr><td> <var>x</var> ÷ <var>y</var> </td> <td> Division </td>              <td> / </td>                                <td> Yes </td></tr>
<tr><td> <var>x</var> + <var>y</var> </td> <td> Addition </td>              <td> + &nbsp;<var>aka</var>&nbsp; ⇧ = </td> <td> Yes </td></tr>
<tr><td> <var>x</var> × <var>y</var> </td> <td> Multiplication </td>        <td> * &nbsp;<var>aka</var>&nbsp; ⇧ 8 </td> <td> Yes </td></tr>
<tr><td> <var>x</var> ÷ 100 </td>          <td> Percentage to Decimal </td> <td> % &nbsp;<var>aka</var>&nbsp; ⇧ 5 </td> <td> Yes </td></tr>
<tr><td rowspan=2> ±<var>x</var> </td>     <td rowspan=2> Negation </td>    <td> ⌥ - </td>                              <td> Yes </td></tr>
<tr>                                                                        <td> ⇧ - </td>                              <td> No </td></tr>

<tr><td rowspan=9> Algebraic Functions </td>
    <td> 1/<var>x</var> </td>                          <td> Inverse (Reciprocal) </td>  <td> ⇧ / </td>                             <td> No </td></tr>
<tr><td> <var>x</var>! </td>                           <td> Factorial </td>             <td> ! &nbsp;<var>aka</var>&nbsp; ⇧ 1 </td><td> Yes </td></tr>
<tr><td> <var>x</var> × 10<sup><var>y</var></sup> </td><td> Scientific Notation </td>   <td> ⇧ E </td>                             <td> Yes </td></tr>
<tr><td> <var>x</var><sup>2</sup> </td>                <td> Square </td>                <td> ⇧ 2 </td>                             <td> No </td></tr>
<tr><td> <var>x</var><sup>3</sup> </td>                <td> Cube </td>                  <td> ⇧ 3 </td>                             <td> No </td></tr>
<tr><td> <var>x</var><sup><var>y</var></sup> </td>     <td> Power (Exponentiation) </td><td> ^ &nbsp;<var>aka</var>&nbsp; ⇧ 6 </td><td> Yes </td></tr>
<tr><td> √<var>x</var> </td>                           <td> Square Root </td>           <td> ⇧ ⌥ 2 </td>                           <td> No </td></tr>
<tr><td> ∛<var>x</var> </td>                           <td> Cube Root </td>             <td> ⇧ ⌥ 3 </td>                           <td> No </td></tr>
<tr><td> <sup><var>y</var></sup>√<var>x</var> </td>    <td> yth Root </td>              <td> ⇧ ⌥ 6 </td>                           <td> No </td></tr>

<tr><td rowspan=8> Exponential & Logarithmic Functions </td>
    <td> 10<sup><var>x</var></sup> </td>       <td> Power of 10 </td>          <td> ⌘ 1 </td> <td> No </td></tr>
<tr><td> 2<sup><var>x</var></sup> </td>        <td> Power of 2 </td>           <td> ⌘ 2 </td> <td> No </td></tr>
<tr><td> y<sup><var>x</var></sup> </td>        <td> Power of y </td>           <td> ⌘ 6 </td> <td> No </td></tr>
<tr><td> <i>e</i><sup><var>x</var></sup> </td> <td> Exponential Function </td> <td> ⌘ E </td> <td> No </td></tr>
    <td> log₁₀ <var>x</var> </td>                  <td> Logarithm Base 10 </td> <td> ⌘ ⌥ 1 </td><td> No </td></tr>
<tr><td> log₂ <var>x</var> </td>                   <td> Logarithm Base 2 </td>  <td> ⌘ ⌥ 2 </td><td> No </td></tr>
<tr><td> log<sub><i>y</i></sub> <var>x</var> </td> <td> Logarithm Base y </td>  <td> ⌘ ⌥ 6 </td><td> No </td></tr>
<tr><td> ln <var>x</var> </td> <td> Natural Logarithm Base e </td> <td> ⌘ ⌥ E </td><td> No </td></tr>

<tr><td rowspan=6> Trignometric Functions </td>
    <td> sin <var>x</var> </td>    <td> Sine </td>             <td> ⇧ S </td>    <td> No </td></tr>
<tr><td> cos <var>x</var> </td>    <td> Cosine </td>           <td> ⇧ C </td>    <td> No </td></tr>
<tr><td> tan <var>x</var> </td>    <td> Tangent </td>          <td> ⇧ T </td>    <td> No </td></tr>
<tr><td> sin⁻¹ <var>x</var> </td>  <td> Inverse Sine </td>     <td> ⇧ ⌥ S </td>  <td> No </td></tr>
<tr><td> cos⁻¹ <var>x</var> </td>  <td> Inverse Cosine </td>   <td> ⇧ ⌥ C </td>  <td> No </td></tr>
<tr><td> tan⁻¹ <var>x</var> </td>  <td> Inverse Tangent </td>  <td> ⇧ ⌥ T </td>  <td> No </td></tr>

<tr><td rowspan=6> Hyperbolic Trignometric Functions </td>
    <td> sinh <var>x</var> </td>    <td> Hyperbolic Sine </td>             <td> ^ S </td>    <td> No </td></tr>
<tr><td> cosh <var>x</var> </td>    <td> Hyperbolic Cosine </td>           <td> ^ C </td>    <td> No </td></tr>
<tr><td> tanh <var>x</var> </td>    <td> Hyperbolic Tangent </td>          <td> ^ T </td>    <td> No </td></tr>
<tr><td> sinh⁻¹ <var>x</var> </td>  <td> Inverse Hyperbolic Sine </td>     <td> ^ ⌥ S </td>  <td> No </td></tr>
<tr><td> cosh⁻¹ <var>x</var> </td>  <td> Inverse Hyperbolic Cosine </td>   <td> ^ ⌥ C </td>  <td> No </td></tr>
<tr><td> tanh⁻¹ <var>x</var> </td>  <td> Inverse Hyperbolic Tangent </td>  <td> ^ ⌥ T </td>  <td> No </td></tr>
  
<tr><td rowspan=3> Numeration Bases </td>
    <td> 8 </td>   <td> Base 8 </td>    <td> ⌘ ^ 8 </td>  <td> No </td></tr>
<tr><td> 10 </td>  <td> Base 10 </td>   <td> ⌘ ^ 0 </td>  <td> No </td></tr>
<tr><td> 16 </td>  <td> Base 16  </td>  <td> ⌘ ^ 6 </td>  <td> No </td></tr>

<tr><td rowspan=9> Controls </td>
    <td> = </td>          <td> Equals (Evaluate) </td>         <td> = &nbsp;<var>or</var> &nbsp;return </td>      <td> Yes </td></tr>
<tr><td> C </td>          <td> Clear Entry </td>               <td> C &nbsp;<var>or</var> &nbsp; esc </td>        <td> Yes </td></tr>
<tr><td> C C </td>        <td> Clear Calculation </td>         <td> C C &nbsp;<var>or</var> &nbsp; esc esc </td>  <td> Yes </td></tr>
<tr><td> Rad ↺ Deg </td>  <td> Radians ↺ Degrees Toggle </td>  <td> D </td>                                       <td> No </td></tr>
<tr><td> mc </td>         <td> Memory Clear </td>              <td> X </td>                                       <td> No </td></tr>
<tr><td> m+ </td>         <td> Memory Addition </td>           <td> A </td>                                       <td> No </td></tr>
<tr><td> m- </td>         <td> Memory Subtraction </td>        <td> S </td>                                       <td> No </td></tr>
<tr><td> mc m+ </td>      <td> Memory New </td>                <td> N </td>                                       <td> No </td></tr>
<tr><td> mr </td>         <td> Memory Recall </td>             <td> M </td>                                       <td> No </td></tr>
  
<tr><td rowspan=3> Views </td>
    <td> Basic </td>       <td> Basic Operations only </td>              <td> ⌘ ^ B </td>  <td> No </td></tr>
<tr><td> Scientific </td>  <td> Full-Featured Decimal Calculator </td>   <td> ⌘ ^ S </td>  <td> No </td></tr>
<tr><td> Programmer </td>  <td> Useful Operations for Programming </td>  <td> ⌘ ^ P </td>  <td> No </td></tr>

</table>

### Philosophy of Key Choices

* Avoid system-wide key assignments, and leave all of the calculator’s existing key assignments in place if possible.
  * The major exception here is that Apple assigns unshifted E to the natural logarithm function, while I assign that to the constant <var>e</var>, and instead use ^ ⌥ E for natural logarithm (since I assign ^ E to the exponential function). This is more in keeping with the other assignments for operations.
  * The other exception is the assignments for views, which as noted above use command keys I’d rather use for calculations. My general pattern for views or windows within an application is also to use the modifiers ⌘ ^, so that shows up here, too, along with more memorable letter choices. I also use this pattern for numeration bases in the programmer view, i.e. octal, decimal, and hexadecimal.
* Otherwise follow existing patterns for key choices.
  * Numbers: Digits are both buttons and the obvious keys, but the button <i>π</i> is also assigned to P, so I also use unmodified keys for other values, both for existing buttons without keys like <i>e</i> and Rand, and for a couple more I provide.
  * Controls: Clear is assigned C and Equals is assigned =, so I also use unmodified keys for other controls such as the memory controls and the radians / degree toggle.
  * Basic Operations and Algebraic Functions: Many of these have buttons that also work with shifted keys, e.g. +, ^, and scientific notation, so I continue that pattern for buttons without assigned keys like inverse (⇧ /) and square (⇧ 2 — perfect symbol for “raising to the power of 2“). I also add other common functions in this family, notably negation (⇧ -), which already exists as ⌥ -, but the latter doesn’t follow the pattern and so is harder to remember (I do leave it in place, though).
  * Exponential & Logarithmic Functions: With both x² and 2<sup>x</sup> referencing 2, the latter and other more complicated functions require a different modifier, so I use the command key ⌘.
  * Trignometric Functions: I use ⇧ S, ⇧ C, and ⇧ T for sine, cosine, and tangent.
* Use other modifiers when necessary and in a consistent fashion:
  * Inverse Operations: I use the option key in general as an “inverse” key, so, for example square root is ⇧ ⌥ 2, and inverse sine is ⇧ ⌥ S .
  * Hyperbolic Trignometric Functions: For these less common functions, to be consistent with the circular trignometric functions and avoid collisions with the keys for Save, Copy, and Show Paper Tape, I use the same letters but instead use ^ : ^ S, ^ C, and ^ T.

One button that doesn’t seem to be addressable is y<sup>x</sup>, as it doesn’t appear to be named in a consistent way to other buttons. So it’s implemented based on a window-referenced click.

These macros work with MacOS 12 Monterey, and probably with later versions, too; earlier versions may be missing some functions.

It took a while to figure out what all of the button names are, and I can thank several people in [the Keyboard Maestro forums](https://forum.keyboardmaestro.com/t/km-macros-can-t-find-all-calculator-buttons/29859) for their assistance.
