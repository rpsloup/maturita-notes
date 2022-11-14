Číselná soustava je systém, kterým můžeme vyjádřit hodnotu pomocí čísel a znaků. Nejvíce používanou soustavou je soustava decimální (desítková), která disponuje číslicemi od 0 - 9. Každá cifra (s výjimkou soustavy jedničkové) představuje násobek mocniny o základu dané soustavy.

Pokud chceme vyjádřit, v jaké soustavě je číslo vyjádřeno, používáme dolní index -

75<sub>10</sub> (desítková)
75<sub>8</sub> (osmičková)
75<sub>16</sub> (šestnáctková)

## Decimální

* také desítková soustava
* číslice od 0-9
* jedná se o nejvíce užívanou soustavu v občanském životě, technice a vědě
* tato soustava je pravděpodobně odvozena od počítání do 10 na prstech ruky

Na ukázku, hodnota čísla 420 -

| 10^2 | 10^1 | 10^0 |
|------|------|------|
| 4    | 2    | 0    |

Celková hodnota je tedy 4 \* 10<sup>2</sup> + 2 \* 10<sup>1</sup> + 0 \* 10<sup>0</sup>.

## Binární

* také dvojková soustava
* číslice nula a jedna
* je zvykem psát tato čísla po osmicích nebo čtveřicích
* lze ji snadno převést do soustavy hexadecimální
* používají ji všechny moderní počítače
* její číslice odpovídají hodnotám zapnuto (1) a vypnuto (0)
* dále odpovídají i dvojici pravda (1) a nepravda (0)

Na ukázku hodnota čísla 1011 0101 -

| 2^7 | 2^6 | 2^5 | 2^4 | 2^3 | 2^2 | 2^1 | 2^0 |
|-----|-----|-----|-----|-----|-----|-----|-----|
| 1   | 0   | 1   | 1   | 0   | 1   | 0   | 1   |

Sečtění hodnot by vypadalo takto - 1 \* 2<sup>7</sup> + 0 \* 2<sup>6</sup> + 1 \* 2<sup>5</sup> + 1 \* 2<sup>4</sup> + 0 \* 2<sup>3</sup> + 1 \* 2<sup>2</sup> + 0 \* 2<sup>1</sup> + 1 \* 2<sup>0</sup> -> 181 (DEC).

Pokud chceme binární číslo převést do hexidecimální soustavy, musíme ho nejdříve rozložit na čtveřice. Následně každou čtveřici převedeme na číslo z hexadecimální soustavy. 4 bity (jedničky a nuly) mohou mít maximální hodnotu 15, proto je převod tímto způsobem možný.

1011 0101 - 1011 a 0101
1011 - 11 -> B
0101 - 5

Naše výsledné číslo je tedy B5.

## Hexadecimální

* také šestnáctková soustava
* číslice 0-9 a písmena A-F (pro hodnoty 10-15)
* lze ji snadno přivést do soustavy binární
* praktická při práci s programováním počítačů, protože velká čísla se v binární soustavě stanou lehce nepřehledná
* každá cifra představuje právě jednu binární čtveřici (jeden nibble)
* používaná pro zápis adres paměti u počítačů

Na ukázku hodnota čísla CF3 -

| 16^2 | 16^1 | 16^0 |
|------|------|------|
| 12   | 15   | 3    |

F koresponduje číslu 15 a C číslu 12. Výsledná hodnota je tedy - 12 \* 16<sup>2</sup> + 15 \* 16<sup>1</sup> + 3 \* 16<sup>0</sup> -> 12 \* 256 + 15 \* 16 + 3 \* 0 -> 3315 (DEC).

Pro převod do soustavy binární převedeme každou cifru na binární čtveřici.

## Oktální

* také osmičková soustava
* číslice 0-7
* využívaná v informatice
* každá cifra představuje právě jednu binární trojici

Na ukázku hodnota čísla 712 -

| 8^2 | 8^1 | 8^0 |
|-----|-----|-----|
| 7   | 1   | 2   |

Nyní převod do decimální soustavy - 7 \* 8<sup>2</sup> + 1 \* 8<sup>1</sup> + 2 \* 8<sup>0</sup> -> 7 \* 64 + 1 \* 8 + 2 \* 1 -> 458.

Pro převod do soustavy binární převedeme každou cifru na binární trojici.