# A 30 key layout that doesn't compromise on SFBs 
This layout is based on Apsu's APTv3 layout, which I fitted onto 30 keys. 

This layout is a result of boiling the layout down to 22 keys and then adding keys back in to allow for typing speeds above 100 wpm.


## Base layer
```
w g d f           l   u o y
r s t h   k    ex n   e a i
b c m p           ,   . ' / 
      num ✭     _ bsp
```

There is a key override for `,` and `.` in place to convert `<>` into an inroll.

## Combo layer
With so few keys, not all keys fit into the base layer. There are basically 2 different solutions. I tried a secondary alpha layer but found it limiting my typing speed.

Instead, I shifted the layout towards combos using 2 neighbouring keys. There are a lot of them.

Pressing both thumb keys together accesses the function layer.

```
  •ß•q•     • •ü•
•x•j•v•     • •ä• •
  •z• •     • •/ •
      •     •
```

## Magic key ✭
The key labeled ✭ in the base layer is a magic key. Its output changes based on the key that was pressed before. It's used to decrease the number of SFBs in the layout significantly, especially those that were introduced by the combo keys.

It covers bigrams like `dv`, `eu` or `br`. But also key repeats like `ll` or `rr`. It functions as some sort of "get out of jail free card", where every time pressing the next key seems uncomfortable, you can press the magic key instead.

With the magic key on a thumb this layout manages to signicantly keep the number of SFBs very low despite the heavy use of combos.

## Home Row Mods
Mods and layers are accessed via HRMs. To allow for fast natural typing while keeping accidental triggers to a minimum, the `tapping-term` is kept on the high side, but `hold-trigger-key-positions` are enabled, so that accessing the mods are usually pressed on the opposite side of the board from the key they are pressed with.

The mods stay constistent across the fun and nav layers as well.

```
   •   •   •      •   •   •   •
•  sym ctl alt    alt ctl sym •
   •   •   gui    gui •   •   •
           sft    nav
```

## The Num layer
The number layer uses a numpad layer, but the bottom row of the numpad is shifted onto the right hand. This way the muscle memory from using a calcuator can kick in while also reducing the number of SFBs when typing out number sequences. It also moves the most frequent number 1 onto the home row on a strong finger.

This layer also houses parentheses. These are positioned in such a way that they favor inrolls instead of the usual outrolls
```
    [ ]   7 8 9
0 3 2 1   4 5 6
    ( )   } {
```

## The sym layer
This layer is a hot pot of trying to put the most used symbols on the home row while trying to retain some sort of logic to it. It has everything that's left.

A thing to point out is that the keys for `-` and `=` produce `->` and `=>` on hold for convenience.

```
  @ | &      \ ~
# $ * !    - = : ;
  ^ %      _ + `
```

## The nav layer
...is kept basic. I am a Vim user so I don't have the need for extensive shortcut binds.

```
                     hom end del
 esc tab     ret     ←   ↓   ↑   →
                         pgd pgu
```

## The fun layer
```
   vol- vol+ mut   prs F11 F12
F1 F2   F3   F4    F7  F8  F9 F10
             F5    F6
```
