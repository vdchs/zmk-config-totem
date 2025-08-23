# A (failed) push to making even fewer keys work
## The general idea behind this layout
This layout makes heavy use of combos for everything that is not on the alpha layer.

In my head I tend to distinguish between 2 kinds of combos: two-finger-combos and thumb-combos. The former are a concept that worked really well in my 22 key version, the latter are new to this layout and the cornerstone of getting the number of keys down even further than before.

This amount of combos comes with a lot of tradeoffs and just leaving it at that would result in a layout that is - frankly - bad. In order to compensate and elevate the layout to a usable one, I made use of adaptive keys (and some other neat tricks). The resulting layout comes with a substantial learning curve and is my smallest layout so far.

Update: After a few weeks of experimentation with this I am not happy with how this turned out. Initially I was pretty confident that this was an improvement over the 22 key version. The typing speeds were quite alright, breaking 100 wpm seemed totally doable, but in the end things never fell quite into place. I ended up dissatisfied with either M or W being on a combo and not finding a solution. For now I've abandoned this layout and went back to the main one. I left this branch up because is was a fun learning experience and maybe interesting for some.

Oh yeah, and this layout does feel a bit like playing DDR. 

## Layers
### alpha
#### alpha base
```
m    g    d    p        l    u    o    y
c    s    t    h        n    e    a    i
               r        _
```

#### alpha held
```
gui  •    •    •        •    •    •    gui
num  sym  ctl  alt      alt  ctl  sym  num
               Rroll    nav
```

#### alpha two-finger-combos
```
• q  • ß  • z  •        • ex • ü  •    •
•os⇧ • f  • b  •        • .  • '  •os⇧ •
               •   rr   •
```

#### alpha other combos
```
•    •    •    •        •    •    •    •
1|3  1    1    1|3      2|4  2    2    2|4
               •        •
```
1, 2 caps word\
3, 4 func

#### alpha two-finger-combo held
```
• qq •    • zz •        •    •    •    •
• ⇧  • ff • bb •        •... •    • ⇧  •
               •        •
```

#### alpha thumb-combos
```
•    j    •    •        •    •    •    • 
x    v    w    k        ,_   ,    •    •
               ★        ★
```
All these combos only work with the same side thumb, so keys on the left half are paired with the left thumb key and vice versa.

#### alpha Rroll layer
```
•    rj   •    •        •    •    •    •
rx   rv   rm   rk       •    •    •    •
               •        •
```
This is basically there to avoid awkward bigrams where the right thumb `r` is followed by a thumb-combo-letter. It enables me to just roll the keys instead.

Entering this layer is done with a `&sk` macro instead of an actual `&mo` key. This way the layer is always only triggered for one keypress, allowing for rolling "out" of this layer, too.

#### alpha thumb-combo held
```
•    jr   •    •        •    •    •    •
xr   vr   mr   kr       •    •    •    •
               •        •
```
This is basically the `Rroll` layer in reverse. Some of these bigrams are used infrequently and the function could be used more effectively. But I intentionally decided to keep this straight forward - the layout is complex enough as it is.

### num
#### num base
```
•    .    (    )        7    8    9    •
•    3    2    1        4    5    6    •
               0        _
```
#### num two-finger-combos
```
•    •    • [  •        • ]  •    •    •
•    • <  • {  •        • }  • >  •    •
               •        •
```

#### num thumb-combos
```
•    ,    •    •        •    •    •    •
•    •    •    •        •    •    •    •
               •        •
```

### sym
#### sym base
```
%    @    |    &        _    +    `    ^
#    $    ?    !        -    =    :    ;
               /        •
```
#### sym held
```
•    •    •    •        •    •    ~    •  
•    •    •    •        ->   =>   •    end;
               \        •
```
#### sym two-finger-combos
```
•    •    •    •        •    •    •    •
•    • *  •    •        •    •    •    •
               •        •
```

### nav
```
gui  tab  pgdn pgup     home end  del  •
esc  bsp  ctl  alt      ←    ↓    ↑    →
               ⇧        •
```

### func
```
•    vold volu mute     pscr f11  f12  •
f1   f2   f3   f4       f7   f8   f9   f10
               f5       f6
```

...
tbc
