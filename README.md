# Basis-C-Hello
##### Det første program med C

Det skal ikke være svært at lave første og traditionelle "Hello World" program i noget sprog. Meningen er at få det første hul igennem, og, fra programmet, udskrive det første "Hallo!", ("Hva' så ROSKILDEEEE?!").

Det ser sådan her ud:

```C
#include <stdio.h>

int main (void)
{
    printf("Hello World\n");
}
```
Gem filen, og giv den navnet `hello.c`.
I kommando-panelet skriver du `gcc hello.c` og tryk [enter].
Tjek hvad der er kommet ud af det med kommandoen `ls`. Der skulle gerne være en fil der hedder `a.out`. Den skal vi køre...

For at starte programmet skal man angive stien til den, selv om man står i samme dir som programmet ligger i. 

Skriv `./a.out` + [enter]

`./` betyder "den-nuværende-mappe".

*- Søren*



