# cruise_control

Tinkering with karabiner elements. 

The thought is, instead of getting all-caps when you hit the Capslock key, it should either
- just be `CTRL` when pressed with other keys (heavy vim/spacemacs user on a laptop; so forgive me this); and
- activate Cruise Control mode when pressed and released by itself.

What, then, is Cruise Control mode? In concert with `ALT`, `CMD`, and `SHIFT`, the goal is to completely obsolesce the arrow keys and the mouse / trackpad. Having to move my right hand away from `HJKL` is such an inconvenience, and while vim/spacemacs as my editor and various vim plugins in various browsers go a long way, some websites don't play well with vimium, and sometimes I'm tinkering with some dialect of smalltalk and so I'm out of my vim and spacemacs, etc.

There are plenty of karabiner elements that remap capslock to `ESC` or `CTRL` or something else, but most of the ones I've found of those either a) don't do everything I want it to do, or b) require capslock to be held down for the duration of its effects. Modal editting is the bee's knees, and if I had to hold down `i` the entire time I was inserting text in vim, or hold down `ESC` the entire time I was in normal mode, I'd give up on it and just go back to using punchcards. 

Capslock is cruise control for cool ("look maw, no hands!"), but this could also be thought of as GUI-navigation mode.

This is where my JSON-in-progress for this karabiner element will live, where I'll make updates to it, track progress, and so on.

Currently, activating cruise control will allow one to move left, down, up, and right, with HJKL. It moves rather speedily, and so I will probably add some more keybinds to slow it down a bit, in case you're playing minesweeper or whatever. Also, left- and right-click need to be implemented as well; it's not exactly pneumonic, or even mnemonic, but I'm considering `U` and `I` for the two, mostly because if I had a mouse in my hand, it is those fingers making that motion which would do left- and right-clicks. Intensifying cyborgification means wiring up muscle memory to the machines, and if old patterns can be fed back into the loopings, even better. Finally, the scroll-wheel; not totally sure how to pull this off, so we'll see, we'll see.

Next, the arrow keys. They should be obviously mapped to HJKL, but I'd like to maintain the sort of behavior one can get by mixing shift, alt, and command into the mix. I'm a little sensitive about ever losing some command+{`HJKL`} functionality, but a) it's only in this one mode, so capslock would restore it; but b) maybe there's other ways to go about it as well. I'm thinking on it.
