# Keyboard Maestro: MacOS Calculator Macros
## A set of Keyboard Maestro macros for the MacOS Calculator.

I prefer to use keyboard commands on MacOS as much as possible. I therefore use the Mac utility [Keyboard Maestro](https://www.keyboardmaestro.com/main/) to add my own key assignments to make up for those lacking within applications for my common tasks, increasing my productivity.

The MacOS calculator is a good example; I use it regularly, usually for simple calculations, but occasionally for more involved ones, too. For example, squaring a number has a button but no keyboard access, so I assign that to ⇧2, and powers of 2 are assigned to ⌘2.

This set of macros provides a mostly complete set of such operations and also a few extras such as menu selections, especially where they conflict with commands I’d rather use for calculations, e.g. the Scientific view is assigned ^⌘S rather than ⌘2. My assignments are as follows: 

<table>
<tr><th> Category </th><th> Symbol </th><th> Description </th><th> Key Assignment </th><th> Built-In </th></tr>

<tr><td rowspan=7> Numbers </td><td> 0, 1, … 9 </td><td> Digits </td><td> 0, 1, … 9 </td><td> Yes </td></tr>
<tr><td> <i>π</i> </td><td> 3.141… Pi                  </td><td>       P        </td><td>   Yes    </td></tr>
<tr><td> <i>e</i> </td><td> 2.718… Euler’s Number      </td><td>       E        </td><td>   No     </td></tr>
<tr><td> <i>γ</i> </td><td> 0.577… Euler’s Constant    </td><td>       G        </td><td>   No     </td></tr>
<tr><td> <i>φ</i> </td><td> 1.618… Golden Ratio        </td><td>       F        </td><td>   No     </td></tr>
<tr><td> <i>C</i> </td><td> 0.915… Catalan’s Constant  </td><td>       C        </td><td>   No     </td></tr>
<tr><td> Rand </td><td> 0 ≤ Random Number < 1  </td><td>       R        </td><td>   No     </td></tr>

<tr><td rowspan=3> Controls </td><td>   = </td><td> Equals (Evaluate)   </td><td>    = &nbsp;<var>or</var> &nbsp;return  </td><td>  Yes   </td></tr>
<tr><td> C </td><td> Clear Entry   </td><td>    esc     </td><td>   Yes    </td></tr>
<tr><td> C C </td><td> Clear Calculation   </td><td>    esc esc     </td><td>   Yes    </td></tr>

<tr><td rowspan=9> Basic Operations </td><td> <var>x</var> – <var>y</var> </td><td> Subtraction </td><td>   -  </td><td>   Yes    </td></tr>
<tr><td> <var>x</var> ÷ <var>y</var>              </td><td> Division               </td><td>     /     </td><td>   Yes    </td></tr>
<tr><td> <var>x</var> + <var>y</var> </td><td> Addition </td><td> + &nbsp;<var>aka</var>&nbsp; ⇧ = </td><td> Yes </td></tr>
<tr><td> <var>x</var> × <var>y</var>              </td><td> Multiplication         </td><td>    * &nbsp;<var>aka</var>&nbsp; ⇧ 8 </td><td>   Yes    </td></tr>
<tr><td> <var>x</var>!                            </td><td> Factorial              </td><td>    ! &nbsp;<var>aka</var>&nbsp; ⇧ 1 </td><td>   Yes    </td></tr>
<tr><td> <var>x</var> × 100                       </td><td> Percentage             </td><td>    % &nbsp;<var>aka</var>&nbsp; ⇧ 5 </td><td>   Yes    </td></tr>
<tr><td> <var>x</var> × 10<sup><var>y</var></sup> </td><td> Scientific Notation    </td><td>    ⇧ E     </td><td>   Yes    </td></tr>
<tr><td rowspan=2> ±<var>x</var>                  </td><td rowspan=2> Negation     </td><td>    ⇧ -     </td><td>   No    </td></tr>
<tr><td>    ⌥ -     </td><td>   Yes    </td></tr>

<tr><td rowspan=7> Algebraic Functions </td><td> 1/<var>x</var> </td><td> Inverse (Reciprocal) </td><td> ⇧ / </td><td> No </td></tr>
<tr><td>  <var>x</var><sup>2</sup> </td><td> Square   </td><td>    ⇧ 2     </td><td>   No    </td></tr>
<tr><td> <var>x</var><sup>3</sup>            </td><td> Cube   </td><td>    ⇧ 3     </td><td>   No    </td></tr>
<tr><td> <var>x</var><sup><var>y</var></sup>      </td><td> Power (Exponentiation) </td><td>    ^ &nbsp;<var>aka</var>&nbsp; ⇧ 6 </td><td>   Yes    </td></tr>
<tr><td>  √<var>x</var> </td><td> Square Root   </td><td>    ⇧ ⌥ 2     </td><td>   No    </td></tr>
<tr><td> ∛<var>x</var>            </td><td> Cube Root   </td><td>    ⇧ ⌥ 3     </td><td>   No    </td></tr>
<tr><td> <sup><var>y</var></sup>√<var>x</var>            </td><td> yth Root   </td><td>    ⇧ ⌥ 6     </td><td>   No    </td></tr>

<tr><td rowspan=3> Exponential Functions </td><td> 10<sup><var>x</var></sup> </td><td> Power of 10 </td><td>    ⌘ 1     </td><td>   No    </td></tr>
<tr><td> 2<sup><var>x</var></sup> </td><td> Power of 2 </td><td>    ⌘ 2     </td><td>   No    </td></tr>
<tr><td> <i>e</i><sup><var>x</var></sup> </td><td> Exponential Function </td><td>    ⌘ E     </td><td>   No    </td></tr>

<tr><td rowspan=4> Logarithmic Functions </td><td> log₁₀ <var>x</var> </td><td> Logarithm Base 10 </td><td>    ⌘ ⌥ 1     </td><td>   No    </td></tr>
<tr><td> log₂ <var>x</var> </td><td> Logarithm Base 2 </td><td>    ⌘ ⌥ 2     </td><td>   No    </td></tr>
<tr><td> log<sub><i>y</i></sub> <var>x</var> </td><td> Logarithm Base y </td><td>    ⌘ ⌥ 6     </td><td>   No    </td></tr>
<tr><td> log<sub><i>e</i></sub> <var>x</var> </td><td> Natural Logarithm </td><td>    ⌘ ⌥ E     </td><td>   No    </td></tr>

<tr><td rowspan=6> Trignometric Functions </td><td> cos <var>x</var> </td><td> Cosine   </td><td>    ⌘ K     </td><td>   No    </td></tr>
<tr><td> sin <var>x</var> </td><td> Sine     </td><td>    ⌘ N     </td><td>   No    </td></tr>
<tr><td> tan <var>x</var> </td><td> Tangent  </td><td>    ⌘ G     </td><td>   No    </td></tr>
<tr><td> cos⁻¹ <var>x</var> </td><td> Inverse Cosine   </td><td>    ⌘ ⌥ K     </td><td>   No    </td></tr>
<tr><td> sin⁻¹ <var>x</var> </td><td> Inverse Sine   </td><td>    ⌘ ⌥ N     </td><td>   No    </td></tr>
<tr><td> tan⁻¹ <var>x</var> </td><td> Inverse Tangent   </td><td>    ⌘ ⌥ G     </td><td>   No    </td></tr>

<tr><td rowspan=6> Hyperbolic Trignometric Functions </td><td> cosh <var>x</var> </td><td> Hyperbolic Cosine   </td><td>    ⌘ ^ K     </td><td>   No    </td></tr>
<tr><td> sinh <var>x</var> </td><td> Hyperbolic Sine   </td><td>    ⌘ ^ N     </td><td>   No    </td></tr>
<tr><td> tanh <var>x</var> </td><td> Hyperbolic Tangent   </td><td>    ⌘ ^ G     </td><td>   No    </td></tr>
<tr><td> cosh⁻¹ <var>x</var> </td><td> Inverse Hyperbolic Cosine   </td><td>    ⌘ ^ ⌥ K     </td><td>   No    </td></tr>
<tr><td> sinh⁻¹ <var>x</var> </td><td> Inverse Hyperbolic Sine   </td><td>    ⌘ ^ ⌥ N     </td><td>   No    </td></tr>
<tr><td> tanh⁻¹ <var>x</var> </td><td> Inverse Hyperbolic Tangent   </td><td>    ⌘ ^ ⌥ G     </td><td>   No    </td></tr>

<tr><td rowspan=1> Angular Unit </td><td> Rad/Deg </td><td> Radians/Degrees Toggle </td><td> ⌘ D </td><td>   No    </td></tr>
<tr><td rowspan=4> Memory </td><td> mc </td><td> Memory Clear </td><td> ⌘ esc </td><td>   No    </td></tr>
<tr><td> m+ </td><td> Memory Addition </td><td> ⌘ = </td><td>   No    </td></tr>
<tr><td> m- </td><td> Memory Subtraction </td><td> ⌘ - </td><td>   No    </td></tr>
<tr><td> mr </td><td> Memory Recall </td><td> ⌘ R </td><td>   No    </td></tr>
</table>


* Keys with the ^⌘ modifiers: views (basic, scientific, programmers)

This leaves all of the calculator’s existing key assignments in place except for one — it assigns unshifted E to the natural logarithm function, while I assign that to the constant e, and use ⌘⌥E for natural logarithm (since I assign ⌘E to the exponential function).

These macros work with MacOS 12 Monterey, and probably with other versions, more or less.

It took a while to figure out what all of the button names are, and I can thank several people in [the Keyboard Maestro forums](https://forum.keyboardmaestro.com/t/km-macros-can-t-find-all-calculator-buttons/29859) for their assistance.
