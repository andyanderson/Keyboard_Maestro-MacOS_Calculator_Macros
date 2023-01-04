# Keyboard Maestro: MacOS Calculator Macros
## A set of Keyboard Maestro macros for the MacOS Calculator.

I prefer to use keyboard commands on MacOS as much as possible. I therefore use the Mac utility [Keyboard Maestro](https://www.keyboardmaestro.com/main/) to add my own key assignments to make up for those lacking within applications for my common tasks, increasing my productivity.

The MacOS calculator is a good example; I use it regularly, usually for simple calculations, but occasionally for more involved ones, too. For example, squaring a number has a button but no keyboard access, so I assign that to ⌘2.

This set of macros provides a mostly complete set of such operations and also a few extras such as menu selections, especially where they conflict with commands I’d rather use for calculations, e.g. the Scientific view is assigned ^⌘S rather than ⌘2. My assignments are as follows: 

<table>
<tr><th> Category </th><th>  Modifier  </th><th> Symbol </th><th> Description </th><th> Key Assignment </th><th> Built-In </th></tr>
<tr><td rowspan=6> Numbers </td><td rowspan=6> No Modifier </td><td> 0-9 </td><td> Digits </td><td> 0-9 </td><td> Yes </td></tr>
<tr><td> π </td><td> 3.141… Pi                  </td><td>       P        </td><td>   Yes    </td></tr>
<tr><td> e </td><td> 2.718… Euler’s Number      </td><td>       E        </td><td>   No     </td></tr>
<tr><td> γ </td><td> 0.577… Euler’s Constant    </td><td>       G        </td><td>   No     </td></tr>
<tr><td> φ </td><td> 1.618… Golden Ratio        </td><td>       F        </td><td>   No     </td></tr>
<tr><td> C </td><td> 0.915… Catalan’s Constant  </td><td>       C        </td><td>   No     </td></tr>
<tr><td rowspan=12> Standard Operations </td><td rowspan=3> No Modifier </td><td>   = </td><td> Equals (Evaluate)   </td><td>    =     </td><td>   Yes    </td></tr>
<tr><td> <var>x</var> – <var>y</var>              </td><td> Subtraction            </td><td>     -     </td><td>   Yes    </td></tr>
<tr><td> <var>x</var> ÷ <var>y</var>              </td><td> Division               </td><td>     /     </td><td>   Yes    </td></tr>
<tr><td rowspan=8> ⇧ (Shift) </td><td> <var>x</var> + <var>y</var> </td><td> Addition </td><td> + (⇧=) </td><td> Yes </td></tr>
<tr><td> <var>x</var> × <var>y</var>              </td><td> Multiplication         </td><td>    * (⇧8) </td><td>   Yes    </td></tr>
<tr><td> <var>x</var><sup><var>y</var></sup>      </td><td> Exponentiation (Power) </td><td>    ^ (⇧6) </td><td>   Yes    </td></tr>
<tr><td> <var>x</var>!                            </td><td> Factorial              </td><td>    ! (⇧1) </td><td>   Yes    </td></tr>
<tr><td> <var>x</var> × 100                       </td><td> Percentage             </td><td>    % (⇧5) </td><td>   Yes    </td></tr>
<tr><td> <var>x</var> × 10<sup><var>y</var></sup> </td><td> Scientific Notation    </td><td>    ⇧E     </td><td>   Yes    </td></tr>
<tr><td> 1/<var>x</var>                           </td><td> Inverse (Reciprocal)   </td><td>    ⇧/     </td><td>   No    </td></tr>
<tr><td> ±<var>x</var>                            </td><td> Negation               </td><td>    ⇧-     </td><td>   No    </td></tr>
<tr><td> ⌥ (Option) </td><td> ±<var>x</var>       </td><td> Negation               </td><td>    ⌥-     </td><td>   Yes    </td></tr>
<tr><td rowspan=5> Functions </td><td rowspan=5> ⌘ (Command) </td><td>  <var>x</var><sup>2</sup> </td><td> Square   </td><td>    ⌘2     </td><td>   No    </td></tr>
<tr><td> <var>x</var><sup>3</sup> </td><td> Cube   </td><td>    ⌘3     </td><td>   No    </td></tr>
<tr><td> cos <var>x</var> </td><td> Cosine   </td><td>    ⌘K     </td><td>   No    </td></tr>
<tr><td> sin <var>x</var> </td><td> Sine   </td><td>    ⌘N     </td><td>   No    </td></tr>
<tr><td> tan <var>x</var> </td><td> Tangent   </td><td>    ⌘G     </td><td>   No    </td></tr>
</table>

  
* Keys with the  modifier:
** Functions:
** Memory management:
* Keys with the ^⌘ modifiers: additional operations (hyperbolic); views (basic, scientific, programmers)
* Keys with the ⌥ modifier: inverse of the previous operations, including specific roots and logarithms.
** ± (the latter is ⌥- in the calculator rather than the default MacOS ⌥=±)

This leaves all of the calculator’s existing key assignments in place except for one — it assigns unshifted E to the natural logarithm function, while I assign that to the constant e, and use ⌘⌥E for natural logarithm (since I assign ⌘E to the exponential function).

These macros work with MacOS 12 Monterey, and probably with other versions, more or less.

It took a while to figure out what all of the button names are, and I can thank several people in [the Keyboard Maestro forums](https://forum.keyboardmaestro.com/t/km-macros-can-t-find-all-calculator-buttons/29859) for their assistance.
