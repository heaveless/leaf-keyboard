<p text-align="center">
	<h1>Leaf Keyboard</h1>
</p>

## About Leaf Keyboard

I'm absolutely thrilled to share with you my little application. I created it to customize the layout of my tablet, turning it into my personal computer. Along the way, I faced some challenges, especially with keyboards that had different mappings than what I was used to.

I tried several available apps, but none quite satisfied me. So, I decided to take matters into my own hands and build my very own solution. There's still so much to learn, but I'm genuinely excited about the endless possibilities ahead.

Currently, my app comes in the en_US version, but feel free to modify it as you please. After all, it's a simple template for you to adapt in any way that suits your needs.

I hope you enjoy the app as much as I enjoyed creating it! 😄🚀

## How to use

Simply locate this file `app/src/main/res/raw/keyboard_layout_en_us.kcm`, customize it as you wish, and you're all set. 😉

Naturally, you can also create many more layouts, as many as you like.

`keyboard_layout_en_us.kcm`

```
type OVERLAY

### ROW 1
key GRAVE {
    label:                              '\u001b'
    base:                               '\u001b'
    ralt:                                 '`'
    ralt+shift:                           '~'
}
key 1 {
    label:                              '1'
    base:                               '1'
    shift:                              '!'
}
key 2 {
    label:                              '2'
    base:                               '2'
    shift:                              '@'
}
key 3 {
    label:                              '3'
    base:                               '3'
    shift:                              '#'
}
key 4 {
    label:                              '4'
    base:                               '4'
    shift:                              '$'
}
key 5 {
    label:                              '5'
    base:                               '5'
    shift:                              '%'
}
key 6 {
    label:                              '6'
    base:                               '6'
    shift:                              '^'
}
key 7 {
    label:                              '7'
    base:                               '7'
    shift:                              '&'
}
key 8 {
    label:                              '8'
    base:                               '8'
    shift:                              '*'
}
key 9 {
    label:                              '9'
    base:                               '9'
    shift:                              '('
}
key 0 {
    label:                              '0'
    base:                               '0'
    shift:                              ')'
}
key MINUS {
    label:                              '-'
    base:                               '-'
    shift:                              '_'
}
key EQUALS {
    label:                              '='
    base:                               '='
    shift:                              '+'
}
### ROW 2
key Q {
    label:                              'Q'
    base:                               'q'
    shift, capslock:                    'Q'
    shift+capslock:                     'q'
}
key W {
    label:                              'W'
    base:                               'w'
    shift, capslock:                    'W'
    shift+capslock:                     'w'
    ralt:                               fallback PAGE_UP
}
key E {
    label:                              'E'
    base:                               'e'
    shift, capslock:                    'E'
    shift+capslock:                     'e'
}
key R {
    label:                              'R'
    base:                               'r'
    shift, capslock:                    'R'
    shift+capslock:                     'r'
}
key T {
    label:                              'T'
    base:                               't'
    shift, capslock:                    'T'
    shift+capslock:                     't'
}
key Y {
    label:                              'Y'
    base:                               'y'
    shift, capslock:                    'Y'
    shift+capslock:                     'y'
}
key U {
    label:                              'U'
    base:                               'u'
    shift, capslock:                    'U'
    shift+capslock:                     'u'
}
key I {
    label:                              'I'
    base:                               'i'
    shift, capslock:                    'I'
    shift+capslock:                     'i'
}
key O {
    label:                              'O'
    base:                               'o'
    shift, capslock:                    'O'
    shift+capslock:                     'o'
}
key P {
    label:                              'P'
    base:                               'p'
    shift, capslock:                    'P'
    shift+capslock:                     'p'
}
key LEFT_BRACKET {
    label:                              '['
    base:                               '['
    shift:                              '{'
}
key RIGHT_BRACKET {
    label:                              ']'
    base:                               ']'
    shift:                              '}'
}
key BACKSLASH {
    label:                              '\\'
    base:                               '\\'
    shift:                              '|'
}
### ROW 3
key A {
    label:                              'A'
    base:                               'a'
    shift, capslock:                    'A'
    shift+capslock:                     'a'
}
key S {
    label:                              'S'
    base:                               's'
    shift, capslock:                    'S'
    shift+capslock:                     's'
}
key D {
    label:                              'D'
    base:                               'd'
    shift, capslock:                    'D'
    shift+capslock:                     'd'
}
key F {
    label:                              'F'
    base:                               'f'
    shift, capslock:                    'F'
    shift+capslock:                     'f'
}
key G {
    label:                              'G'
    base:                               'g'
    shift, capslock:                    'G'
    shift+capslock:                     'g'
}
key H {
    label:                              'H'
    base:                               'h'
    shift, capslock:                    'H'
    shift+capslock:                     'h'
}
key J {
    label:                              'J'
    base:                               'j'
    shift, capslock:                    'J'
    shift+capslock:                     'j'
}
key K {
    label:                              'K'
    base:                               'k'
    shift, capslock:                    'K'
    shift+capslock:                     'k'
}
key L {
    label:                              'L'
    base:                               'l'
    shift, capslock:                    'L'
    shift+capslock:                     'l'
}
key SEMICOLON {
    label:                              ';'
    base:                               ';'
    shift:                              ':'
}
key APOSTROPHE {
    label:                              '\''
    base:                               '\''
    shift:                              '"'
}
### ROW 4
key Z {
    label:                              'Z'
    base:                               'z'
    shift, capslock:                    'Z'
    shift+capslock:                     'z'
}
key X {
    label:                              'X'
    base:                               'x'
    shift, capslock:                    'X'
    shift+capslock:                     'x'
}
key C {
    label:                              'C'
    base:                               'c'
    shift, capslock:                    'C'
    shift+capslock:                     'c'
}
key V {
    label:                              'V'
    base:                               'v'
    shift, capslock:                    'V'
    shift+capslock:                     'v'
}
key B {
    label:                              'B'
    base:                               'b'
    shift, capslock:                    'B'
    shift+capslock:                     'b'
}
key N {
    label:                              'N'
    base:                               'n'
    shift, capslock:                    'N'
    shift+capslock:                     'n'
}
key M {
    label:                              'M'
    base:                               'm'
    shift, capslock:                    'M'
    shift+capslock:                     'm'
}
key COMMA {
    label:                              ','
    base:                               ','
    shift:                              '<'
}
key PERIOD {
    label:                              '.'
    base:                               '.'
    shift:                              '>'
}
key SLASH {
    label:                              '/'
    base:                               '/'
    shift:                              '?'
}
```
## References

- [Key character map files](https://source.android.com/docs/core/interaction/input/key-character-map-files)
