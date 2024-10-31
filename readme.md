# A 30 key layout based on APTv3
This is a 30-key keymap for the Totem keyboard by Geist.

I use it to code and write in English (70%) and German (30%).

The basic layout is apsu's [APTv3](https://github.com/Apsu/APT) that I adapted to fit onto 30 keys.

## Basic Typing
Base:
```
 ---------------------------------        ---------------------------------
|  W     G-[ß]-D-[Q]-F     B      |      |           L      U     O-[Ü]-Y  |
|  R-[X]-S-[V]-T-[J]-H     K      |      |           N      E-[Ä]-A     I  |
|        C     M-[Z]-P            |      |           ,      .     '        |
|                    sym   Φ/shft |      | _/nav     bspc                  |
 ---------------------------------        ---------------------------------
```

Letters missing from the base layer can be accessed via combos of neighbouring keys, indicated with `-[ ]-`.\
But there's more! A secondary alpha layer, accessed by a sticky layer key, contains the most common bigrams of these letters to allow for a smoother typing experience.

Alpha-2:
```
  @                 / ?
  sch !       qu ex ; :

```

But there's more. The key labeled as `Φ` in the layout is a magic key. Its output depends on the anteceding key and its main purpose is to provide an alternative way to type frequent SFBs that might occur in the layout, i.e. `rv`, `sc`, `tz`, `bj`. It defaults to a repeat key for other letters, i.e. `ll`, `nn`.\
You can think of it as a Get-Out-Of-Jail-Free-Card in a way. Whenever a key sequence doesn't feel right, I can press the magic key `Φ` instead.

For mods I use home row mods for (Ctl, Alt and GUI) and a thumb key for shift.

## Symbols and numbers
Most symbols and numbers are typed via a combines sym layer and is accessed by holding down one of the thumb keys.
```
$ # | & *   _ 7 8 9 =
0 3 2 1 [   ] 4 5 6 -
  ` ( )       } { +
```

The numbers layout is a basic numpad layout with the lower row shifted onto the left hand.\
This offers 2 advantages. Firstly the most commonly used numbers 1, 2 and 3 are in the home row. Secondly it reduces the number of SFB when typing out longer number sequences.

The rest of the symbols are spread on the remaining space with two things to mention.\
Brackets `{}` are deliberately placed so that they can be typed with an inroll instead of an outroll. I also use a mod morph behaviours to make `<>` an inroll.\
Some symbols can be held down to change the output, this is how I access convenient sequences like `??` or `=>`.
