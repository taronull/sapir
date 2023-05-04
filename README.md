# Sapir - a sensible keyboard layout

```
z l h g q j f o u ` 
s r n t m y c a e i
v x b d k w p " : . /
```

Sapir is a keyboard layout for comfortable typing. It features

- Extremely low single-finger bigram percentage
- Ergonomics for fingers, especially for shorter pinkies

## Layout

Sapir is based on Whorf layout: 

```
f l h d m v w o u ,
s r n t k g y a e i
x j b z q p c ' ; .
```

> Edward Sapir and Benjamin Lee Whorf are known for _Sapir–Whorf hypothesis_. Although, they never co-authored any work or call it a hypothesis. The concept describes [linguistic relativity](https://en.wikipedia.org/wiki/Linguistic_relativity) where thoughts are shaped by the language used. 

Whorf is a purely algorithmic layout. It's optimised for shortest path travelled 2-dimensionally. The essence of Whorf is the vowels on the right-hand side. Sapir relocates consonants to add human factors. Least used keys are placed on the outer corners. This is especially comfortable for relatively shorter pinkies.

## Optional features

### Shifted punctuations and hidden comma

```
" : .
' ; ,  
```

Full/double punctuations can be more frequent than their semi/single counterparts. If this is your case, Sapir recommends shifted punctuations. Also, comma is layered on full stop. If you want to separate them, change backtick to comma.

### Layers 

If available, Sapir recommends using layers.

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

Caps-lock is moved down for more used keys. Backspace and tab are swapped. Arrow keys are matched by directions and deviates from the Vim default. 

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
| Whorf   | lowest       | low        | low             |
| Sapir   | lowest       | low        | low             |

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
