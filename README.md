# Sapir

A sensible keyboard layout.

```
z l h g q j f o u ` 
s r n t m y c a e i
v x b d k w p " : . /
```

## Layout

Sapir is based on Whorf layout: 

```
f l h d m v w o u ,
s r n t k g y a e i
x j b z q p c ' ; .
```

> Edward Sapir and Benjamin Lee Whorf are known for _Sapir–Whorf hypothesis_. Although, they never co-authored any work or call it a hypothesis. The concept describes [linguistic relativity](https://en.wikipedia.org/wiki/Linguistic_relativity) where thoughts are shaped by the language used. 

Whorf is a purely algorithmic layout. It's optimised for shortest path travelled 2-dimensionally. The essence of Whorf is the vowels on the right-hand side. Sapir relocates consonants to add human factors.

To reproduce Sapir from Whorf:

1. Cycle `pcygdzfw`.
2. Cycle `vxj`.
3. Cycle `qmk`.
4. Shift and change punctuations.

### Finger strain map

```
5 2 2 3 4 4 3 2 2 5
1 1 1 1 3 3 1 1 1 1
3 3 3 2 4 4 2 3 3 3 

█ ░ ░ ▒ ▓ ▓ ▒ ░ ░ █ 
        ▒ ▒         
▒ ▒ ▒ ░ ▓ ▓ ░ ▒ ▒ ▒ 
```

1. Home key (least strain)
2. Finger moves 
3. Hand moves 
4. Wrist moves
5. Forearm moves (most strain)

Sapir places least used keys on the outer corners. This is especially comfortable for relatively shorter pinkies.

### Letter frequency

```
  e t a o i n s r h l d c u m g f p w y b , . 
v k ' " - x 0 j 1 q 2 z ) ( : ! ? 5 ; 3 4 9 / 
8 6 7 [ ] % $ | * = _ + > \ < & ^ # @ ` ~ { }
```

### Shifted punctuations

```
" : .
' ; ,  
```

Full/double punctuations are more frequent than their semi/single counterparts in prose and modern programming languages. Sapir presents shifted punctuations as an option.

## Layers and the rest

Sapir includes layers.

Delimiters and a numpad takes the lower layer. 

```
  { } <   - 7 8 9 /
| ( ) =   + 4 5 6 *
  [ ] >   0 1 2 3 . 
         _
```

Symbols are mapped on the upper layer.

```

$ % # ~     ^ @ & !
            ? ' ; , \
         - 
```

As you see, underscore and hyphen are associated with space. 

### AltGr & non-printables

```
⎋ Ω ¬ ˙ © œ ∆ ƒ ø ¨ ` ⇥ 
⌫ ß ® ˜ † µ ¥ ç å ´ ˆ ⏎ 
⇧ √ ≈ ∫ ∂ ˚ ∑ π Æ Ú ≥ ÷
^ ⇪ ⌥ ⌘ ▽  ␣  △ ↑ ↓ ← → 
```

Backspace and tab are swapped. Caps-lock is moved down for more used keys. Arrow keys are matched by directions and deviates from the Vim default. 

### ANSI mod

```
z l h g q j f o u ` 
 s r n t m y c a e i / 
  x b d k v w p ' ; , 
```

## Performance

| SFB%    | Common words | Rare words | Other languages |
| ------- | ------------ | ---------- | --------------- |
| Semimak | low          | lowest     | low             |
| Whorf   | lowest       | lower      | low             |
| Sapir   | lowest       | lower      | low             |

### Benchmark

```
monkeytype-10k
          alternate     roll redirect  onehand      sfb     dsfb
Qwerty ----- 18.61%   40.26%    9.89%    4.47%   11.68%    7.32%
Dvorak ----- 34.90%   39.70%    5.64%    2.00%    4.77%    5.34%
Workman ---- 24.25%   45.20%    7.80%    4.51%    4.64%    5.97%
Colemak ---- 24.03%   47.03%    8.07%    4.15%    2.20%    6.92%
ISRT ------- 25.98%   46.87%    8.03%    3.68%    1.91%    5.93%
APT -------- 30.65%   44.91%    5.82%    3.59%    1.84%    5.58%
Sapir ------ 31.75%   45.23%    5.81%    3.15%    1.22%    5.24%
Whorf ------ 31.71%   45.27%    6.71%    2.69%    1.18%    4.83%
Semimak ---- 31.24%   45.05%    6.80%    3.49%    1.07%    4.75%
```

## Reference

- [Keyboard Layouts](https://www.reddit.com/r/KeyboardLayouts/) - A subreddit for keyboard layouts
- [Alt Keyboard Layouts](https://discord.gg/xTVJzj7W) - A discord channel for keyboard layouts except Qwerty
- [Theory of Letter Frequency](https://mdickens.me/typing/theory-of-letter-frequency.html) - A study of letter frequency in different contexts.
- [Keyboard Layouts Doc](https://bit.ly/keyboard-layouts-doc) - A comprehensive guide for keyboard layouts
- [Layout Playground](https://o-x-e-y.github.io/layouts/playground/index.html) - An interactive layout analyzer
- [A200](https://github.com/ClemenPine/a200) - A spread-sheet-like layout analyzer
