# Vim Commands

### Basics

* Three modes, normal, insert, visual.  Vim always starts in normal mode, insert mode is entered by one of the keys i,I,o,O,a for differing cursor positions. Insert mode is exited with Esc.
  * For most basic uses visual mode can be ignored.

### Navigation in normal mode
* h,j,k,l - Correspond to left, up, down, right respectively.  The arrow keys may be used to the same effect in both insert and normal mode.
* f - find the next occurance of the next letter you type and move the cursor there.  e.g. `f a` would land you at the a in land if pressed at its character position.  
* G - bottom of file
* gg - top of file
* :num - go to line $num
* /anything - find the next instance of anything and move the cursor there.  `n` goes to the next occurance

### Editing

* di{ - delete inside {.  This can be applied to all types of closures such as (,{,[,<,",'
* ci{ - Same as above but also invoke insert mode.  This is great for replacing text inside a closure.
* D - Delete to end of line
* C - Delete to end of line but enter insert mode
* dd - Delete whole line
* dt<char> - Delete up to a given character
* df<char> - Delete up to and including a given char

