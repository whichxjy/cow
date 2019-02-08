# cow

[cow.bf](https://github.com/whichxjy/cow/blob/master/cow.bf) is a program that generates an ASCII cow. It is written in [Brainfuck](https://en.wikipedia.org/wiki/Brainfuck).

```
^__^
(oo)\_______
(__)\       )\/\
    ||----w |
    ||     ||
```
(An ASCII cow from [cowsay](https://en.wikipedia.org/wiki/Cowsay))

## Cells

Cell | Dec | Char
-----|-----|-----
  0  | [Counter]
  1  |   10  | LF
  2  |   32  | space
  3  |   40  | (
  4  |   41  | )
  5  |   45  | -
  6  |   47  | /
  7  |   92  | \
  8  |   94  | ^
  9  |   95  | _
  10 |   111 | o
  11 |   119 | w
  12 |   124 | \|
