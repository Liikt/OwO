OwO or (。O ω O。) is a Brainfuck derivative and thus the symbols can be directly mapped to Brainfuck.

## Mapping

| Brainfuck | (。O ω O。)|
|:-----------:|:-----:|
| <         | ôwo |
| >         | owô |
| +         | òwó |
| -         | ówò |
| .         | OwO |
| ,         | owo |
| [         | ÕwO |
| ]         | OwÕ |

## Behavior

(。O ω O。) differs not only in the syntax from Brainfuck

* `owo` reads in a whole string and writes it, starting from the cell the cell pointer is currently pointing at, onto the tape.
The cell pointer will point at the last char written onto the tape.
* The charset is the whole ascii range
* `OwO` will (like in C) print the entire tape from the current cell pointer until it hits a cell containing `0`.
This cell is where the cell pointer rests after the printing.
