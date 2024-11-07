# A 22 key layout that doesn't compromise on SFBs 
This layout is based on Apsu's APTv3 layout. At one point I wanted to find out how far I could push it with eliminating keys and this is where I ended up.

It may be a bit out there but after getting used to it it's supprisingly comfy - and insanely fun to type on.

The keyboard I use it on is the Totem by Geist. Hence this firmware repo. 

## Base layer
```
  g d f   l u o
r s t h   n e a i
  c m p   , . k
      ✭   _
```

There is a key override for `,` and `.` in place to convert `<>` into an inroll.

## Combo layer
With only 22 keys, not all keys fit into the base layer. There are basically 2 different solutions. I tried a secondary alpha layer but found it limiting my typing speed.

Instead, I shifted the layout towards combos using 2 neighbouring keys. There are a lot of them.

Pressing both thumb keys together accesses the function layer.

```
  •j•q•     •  •ü•
•x•w•b•     •ex•ä•y•
  •z•v•     •/ •'•
      • fun •


```

In addition to these 2 key combos, there are a number of 3 key combos that simulate rolls, for example to type `you` or `sch`.

## Magic key ✭
The key labeled ✭ in the base layer is a magic key. Its output changes based on the key that was pressed before. It's used to decrease the number of SFBs in the layout significantly, especially those that were introduced by the combo keys.

It covers bigrams like `mb`, `eu` or `dv`. But also key repeats like `ll` or `rr`. It functions as some sort of "get out of jail free card", where every time pressing the next key seems uncomfortable, you can press the magic key instead.

With the magic key being a thumb key, this layout manages to signicantly decrease the number of SFBs despite the high number of combos used.

## Home Row Mods
Mods and layers are accessed via HRMs. To allow for fast natural typing while keeping accidental triggers to a minimum, the `tapping-term` as kept on the high side, but `hold-trigger-key-positions` are enabled, so that accessing the mods usually are usually pressed on the opposite side of the board from the key they are pressed with. The exception to that is the shift key on the thumb which favors the hold action aggressively.

The mods stay constistent across the fun and nav layers as well.

```
    •   •   •      •   •   •
num sym ctl alt    alt ctl sym num
    •   •   gui    gui •   •
            sft    nav
```

## The Num layer
The number layer uses a numpad layer, but the bottom row of the numpad is shifted onto the right hand. This way the muscle memory from using a calcuator can kick in while also reducing the number of SFBs when typing out number sequences. It also moves the most frequent number 1 onto the home row on a strong finger.

This layer also houses parentheses. These are positioned in such a way that they favor inrolls instead of the usual outrolls
```
    [ ]   7 8 9
  3 2 1   4 5 6
    ( )   } {
      0
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
     del           hom end
 esc bsp tab ret   ←   ↓   ↑   →
                       pgd pgu
```

## The fun layer
```
   vol- vol+ mut   prs F11 F12
F1 F2   F3   F4    F7  F8  F9 F10
             F5    F6
```
