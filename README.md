# ZMK Layout for Corne

I have since changed my hardware, but the keyboard map described below is still valid. 

The ZMK layout I use with an [Aurora Corne](https://splitkb.com/collections/keyboard-kits/products/aurora-corne) and a standard Corne by [keebmaker](www.keebmaker.com). It is geared towards MacOS, and it allows typesetting of certain accented Italian letters.

This mapping is a customization of [Josean Martinez's](https://github.com/josean-dev/zmk-config/blob/master/config/corne.keymap) corne mapping. I am grateful to [Cem Aksoylar](https://github.com/caksoylar/zmk-config/tree/stock) from whom I have taken the combos macros.

The keyboard layouts are generated with [keymap-drawer](https://github.com/caksoylar/keymap-drawer) ([web application](https://keymap-drawer.streamlit.app)).

![corne image](https://github.com/danieleavitabile/zmk-config/blob/main/images/corne-small-2.png?raw=true) 
![keymap_image](https://github.com/danieleavitabile/zmk-config/blob/main/images/keymap-generator.svg?raw=true)

## Default layer
```
--------+-------+--------+--------+--------+--------+      +--------+--------+--------+--------+--------+--------+     
   tab      q       w        e        r         t              y        u        i        o        p        bksp
ctrl/esc    a       s        d        f         g              h        j        k        l       ; :       ' "
  shift     z       x        c        v         b              n        m       , <      . >      / ?     shift/sv
                            cmd     lay. ↓   opt/ent         space              hyper
                         +--------+--------+--------+      +--------+--------+--------+

ctrl/esc - mod tap: hold for ctrl, tap for esc
alt/ent  - mod tap: hold for option, tap for enter
hyper    - hyper key (ctrl+shift+opt+cmd), tap for space
opt/ent  - mod tap: hold for option, tap for enter
shft/sv  - tapdance: hold for shift, 2 taps for vim save (esc :w enter), 3 taps for vimtex save and compile (esc :w enter space l l),
```

## Lower layer
```
--------+-------+--------+--------+--------+--------+      +--------+--------+--------+--------+--------+--------+     
   \        !       @        #        $        %               ^         &         *         (         )         bksp
mscntrl     1       2        3        4        5               -         +         `         [         ]          |
 shift      6       7        8        9        0               _         =         ~         {         }        shift/sv
                            cmd              opt/ent         space              hyper
                         +--------+--------+--------+      +--------+--------+--------+

mscntrl - macos mission control to view windows; cmd+mscntrl shows the desktop. This button is just f3 key, brought on this layer
```

## Upper layer
```
--------+-------+--------+--------+--------+--------+      +--------+--------+--------+--------+--------+--------+     
         bright-  bright+    è        é                                 ù        ì         ò     vol up     delete
   f1       à       f2       f3       f4       f5               ←       ↓        ↑         →     vol dn     bt clear
          f6        f7       f8       f9       f10         play/pause  prev     next             vol mut    bt next 
                            cmd              opt/ent          space              hyper
                         +--------+--------+--------+      +--------+--------+--------+

delete                    - deletes character to the right (compare with backspace that deletes to the left)
à, è, é, ì, ò, ù          - selected italian accented letters, positioned where the corresponding vowels 
                            are in the default layer (except for the repeated e)
play/pause, prev, next    - music controls
vol up, vol down, vol mut - volume controls
bt clear, bt next         - bluetooth clear and next
```
