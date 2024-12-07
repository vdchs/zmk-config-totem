# A 22 key layout that doesn't compromise on SFBs 
This layout was originally based on Apsu's APTv3 layout. At one point I wanted to find out how far I could push it with eliminating keys and this is where I ended up. It turned out surprisingly comfy so I stuck with the low key count. After many many iterations I'm here - still iterating.

I also took some inspiration from Hands Down Promethium and moved `R` to a thumb key.

The keyboard I use it on is the Totem by Geist. Hence this firmware repo.

![grafik](https://github.com/user-attachments/assets/81a5aa6d-513b-49e9-b02b-96f011a3189e)

## Base layer
```
w g d f     l u o y
c s t h     n e a i
    m p     , .  
      r     _ 
```

- There is a key override for `,` and `.` in place to convert `<>` into an inroll.

## Combo layer
With so few keys, not all keys fit into the base layer. There are basically 2 different solutions. I tried a secondary alpha layer but found it limiting my typing speed.

Instead, I shifted the layout towards combos using 2 neighbouring keys. There are a lot of them.

Pressing both thumb keys together accesses the function layer.

```
•q•j•k•    •  •ü• •
•x•v•b•    •ex•'• •
    •k•    •ä •
      •    • 
```
- For German specific letters `ö` and `ß` I use diagonal 2 key combos. I don't type German very often, but I like to keep them under my fingertips just in case. 
- In addition to these 2 key combos, there are a number of 3 key combos to produce more very common bigrams, for example to type `qu` or `ck`.

## Adaptive keys
To alleviate some of the SFBs introduced by the high amount of combos, I use adaptive keys to favour alternate ways to type common same finger bigrams in favour of very uncommon ones. 

The timeout of these adaptive keys is chosen quite tightly, so that only rolls produce the alternate outcome, making the original bigram still easily achievable.

Full map of adaptive keys:
```
Input:     kc  gc  bc  dc  pc  mc  bg  tg
Output:    ks  gs  bv  dv  ph  mb  bj  tz
```

## Home Row Mods
Mods and layers are accessed via HRMs. To allow for fast natural typing while keeping accidental triggers to a minimum, the `tapping-term` is kept on the high side, but `hold-trigger-key-positions` are enabled, so that accessing the mods are usually pressed on the opposite side of the board from the key they are pressed with.

The mods stay constistent across the fun and nav layers as well.

```
•   •   •   •              •   •   •   •
num sym ctl alt    alt ctl sym num
        •   gui    gui • 
            sft    nav 
```

## The Num layer
The number layer uses a numpad layer, but the bottom row of the numpad is shifted onto the right hand. This way the muscle memory from using a calcuator can kick in while also reducing the number of SFBs when typing out number sequences. It also moves the most frequent number 1 onto the home row on a strong finger.

This layer also houses parentheses. These are positioned in such a way that they favor inrolls instead of the usual outrolls
```
• • [ ]    7 8 9 •
• 3 2 1    4 5 6 •
    ( )    } {
      0    •  
```

## The sym layer
This layer is a hot pot of trying to put the most used symbols on the home row while trying to retain some sort of logic to it. It has everything that's left.

A thing to point out is that the keys for `-` and `=` produce `->` and `=>` on hold for convenience.

```
% @ | &    ^ \ ` ~
# $ * !    - = : ;
    ? /    _ +
      R 
```

## The nav layer
...is kept basic. I am a Vim user so I don't have the need for extensive shortcut binds.

```
     tab             hom end del
 esc bsp     ret     ←   ↓   ↑   →
                     pgd pgu
```

## The fun layer
```
   vol- vol+ mut   prs F11 F12
F1 F2   F3   F4    F7  F8  F9 F10
             F5    F6
```
