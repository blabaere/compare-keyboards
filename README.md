# A-priori evaluation of some ergonomic keyboards.

I want to buy an ergonomic keyboard, and after some research I narrowed down the choice to 3 of them.
- [Keyboardio - Model 01](http://shop.keyboard.io/)
- [Esrille − NISSE](http://www.esrille.com/keyboard/)
- [ErgoDox EZ](https://www.indiegogo.com/projects/ergodox-ez-an-incredible-mechanical-keyboard#/)  

If everything else fail, fallback is [TypeMatrix 2030](http://www.typematrix.com/2030/features.php)

Here I list some selection criteria that came to my mind, and will use them to evaluate the three keyboards.

# Price
|      /      | Price | Comments                               |
|:------------|------:|:---------------------------------------|
| Model 01    | 330$  | Everything included !                  |
| NISSE (L)   | 420$  | Must find someone to get it from Japan |
| NISSE (M)   | 475$  | Must find someone to get it from Japan |
| Ergodox     | 300$  | Shipping & wrist rest included !       |

# Thumb keys placement
|      /      | Rank | Comments                               |
|:------------|:----:|:---------------------------------------|
| Model 01    | ***  | Perfect arc, outer most key require some stretch. Palm thing may get in the way ?  |
| NISSE       | ***  | Perfect arc, inner most key goes as deep as the ring finger, seems a bit strange.  |
| Ergodox     |  **  | Too far from home pos, several rows. Peope say only two keys per thumb are usable. |

Remarks: the model 01 thumbs are assigned by default to modifiers in addition to space and del, and since it has fewer keys it may be difficult to use the sides one instead.

# Other keys placement
|      /      | Rank | Comments                               |
|:------------|:----:|:---------------------------------------|
| Model 01    | ***  | Seems perfect, tears of joy: the pinkie keys are lower: it is shorter than the others!  |
| NISSE       | ***  | Seems very good, but the Enter and Tab keys are no bigger than the other, strange too.  |
| Ergodox     |  **  | Seems OK |

# Keys & key caps
|      /      | Count | Comments                               |
|:------------|:-----:|:---------------------------------------|
| Model 01    |  64   | Shape matches finger, texture looks very good                 |
| NISSE       |  76   | Shape seems curvy enough, texture looks good but hard to say  |
| Ergodox     |  76   | Depends on where you get it / customizable?                   |

# Misc.
The **model 01 has a built-in mouse** capability, using a modifier and left hand keys.
It is difficult to find out if the palm key of the mode 01 is usable just by looking at pictures.
The whole experience seems to depend on this.

The NISSE has a M size, which should make it require less stretch for a lot of combinations.

An ergodox can also be purchased from [falbatech.pl](http://falbatech.pl/prestashop/index.php), with full hand plate but NO TENTING.

**Several shortcuts listed below require several modifiers, maybe using a sequence would help in using a keyboard with fewer keys. For example, like in 'Run unit tests': Ctrl+T, R.**

The 'insert' key is mostly useless per se, but is useful for vim, mintty/zsh, and used in vital ReSharper shortcuts.

The NISSE can 'emulate' several common shortcuts with a FN+key shortcut (this idea can be reused with ergodox).
The NISSE needs some firmware modifications: replace "CAPS LOCK" by "Ctx Menu", "Ctx Menu" by "Del"

# Frequent keys shortcuts
TODO: record a day of work and write down frequency.

## Non-letter keys, used extremely frequently (several of them each line)
Period, semi-colon, enter, shift (for capital letter) left parenthesis, comma, left brace, double quote, left bracket.

## Non-letter keys, used frequently
Tab, Esc, math operators, $ ^ (for regex).

## Non-letter keys or symbols that we can get rid of
CAPS LOCK (if still there, remap it) £ µ § ¤ ²

##General (and used often)
These shortcuts are ubiquitous, so they should be easily accessible and mapping the command to another shortcut is not an option. Anything that appears in both Visual Studio and Notepad++ counts as ubiquitous.

| Command | Keyboard shortcut | Comment |
|---------|-------------------|---------|
| Copy                     | Ctrl+C | Ctrl+_Any letter_ is an obvious one.
| Paste                    | Ctrl+V | They are here as a reminder that Ctrl is used all the time.
| Cut                      | Ctrl+X |
| Undo                     | Ctrl+Z |
| Redo                     | Ctrl+Y |
| Find                     | Ctrl+F |
| Save                     | Ctrl+S |
| Find in Files            | Ctrl+Shift+F |
| Find Next                | F3 |
| Find Next Selected       | Ctrl+F3 |
| Goto Document Start      | Ctrl+Home |
| Goto Document End        | Ctrl+End |
| Delete word (left)       | Ctrl+Backspace |
| Delete word (right)      | Ctrl+Del |
| Extend world selection   | Ctrl+Shift+Arrow |
| Select to end of line    | Shift+End |
| Select to start of line  | Shift+Home |
| Select all               | Ctrl+A |
| Select rectangle         | Alt+Shift+Arrow |
| Show desktop             | Win+D |
| Run ...                  | Win+R |
| Lock session             | Win+L |
| Switch application       | Alt+Tab |
| Switch tab               | Ctrl+Tab |

##General (but used less often)
These shortcuts are  either , and should be easily accessible.

| Command | Keyboard shortcut | Comment |
|---------|-------------------|---------|
| Save All                 | Ctrl+Shift+S |
| Find Previous            | Shift+F3 |
| Find Previous Selected   | Ctrl+Shift+F3 |
| Notepad++                | Ctrl+Alt+N   | Not standard, can be changed
| Q-Dir                    | Ctrl+Alt+Q   | Not standard, can be changed
| Change windows password  | Ctrl+Alt+Del | Not used often, but must really work
| Copy                     | Ctrl+Ins (mintty, vim)  |
| Paste                    | Shift+Ins (mintty, vim) |

##Visual Studio, ReSharper : ULTRA-VIOLENCE !
| Command | Keyboard shortcut |
|---------|-------------------|
| Build Solution           | Ctrl+Shift+B |
| Symbol code completion   | Ctrl+Space |
| Smart code completion    | Ctrl+Shift+Space |
| Import symbol completion | Ctrl+Alt+Space |
| Quick-fixes              | Alt+Enter |
| Find usages              | Alt+F7 |
| Go to last edit location | Ctrl+Shift+Backspace |
| Go to everything         | Ctrl+N |
| Parameter info           | Ctrl+P |
| Cut line                 | Ctrl+L |
| Go to file member        | Ctrl+F12 | 
| Generate code            | Alt+Ins |

##Visual Studio, ReSharper : Hurt me plenty !
| Command | Keyboard shortcut |
|---------|-------------------|
| Delete line              | Ctrl+Shift+L |
| Comment Selection        | Ctrl+K, Ctrl+C |
| Uncomment Selection      | Ctrl+K, Ctrl+U |
| Incremental Search       | Ctrl+I |
| Complete statement       | Ctrl+Shift+Enter |
| Move stuff around        | Ctrl+Shift+Alt+Arrow |
| Go to previous usage     | Ctrl+Alt+Arrow Up | 
| Go to next usage         | Ctrl+Alt+Arrow Down |
| Go to declaration        | Ctrl+B |
| Go to type of symbol     | Ctrl+Shift+T |
| Go to implementation     | Ctrl+Shift+Alt+B |
| Go to derived symbols    | Ctrl+Alt+B |
| Go to usage              | Ctrl+Alt+F7 |
| Refactor this            | Ctrl+Shift+R |
| Rename F2 or             | Shift+R |
| Move type or member      | F6 |
| Introduce field          | Ctrl+Alt+D |
| Change signature         | Ctrl+F6 |
| Code Cleanup             | Ctrl+Alt+F |
| Properties               | Alt+Enter |
| **#TEST** ||
| Run unit tests           | Ctrl+T, R |
| Debug unit tests         | Ctrl+T, D |
| **#DEBUG** ||
| Start | F5 |
| Start Without Debugging  | Ctrl+F5 |
| Stop Debugging           | Shift+F5 |
| Set Breakpoint           | F9 |
| Enable Breakpoint        | Ctrl+F9 |
| Step Into                | F11 |
| Step Out                 | Shift+F11 |
| Step Over                | F10 |
| Locals                   | Ctrl+Alt+V, L |
| Autos                    | Ctrl+Alt+V, A |
| Quick Watch              | Shift+F9 |
| Breakpoints              | Ctrl+Alt+B |
| Call Stack               | Ctrl+Alt+C |

##Q-Dir
| Command | Keyboard shortcut |
|---------|-------------------|
| Applications             | Ctrl+S |
| Quick links              | Ctrl+Q |
| Focus address bar        | Alt+S |

##Conemu
| Command | Keyboard shortcut |
|---------|-------------------|
| Select tab               | Win+number |
| All the others           | Win+everything ... |
