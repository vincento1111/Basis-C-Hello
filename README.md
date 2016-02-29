# Basis-C-Hello
##### Det første program med C

(Tjek lige vejledningen i brug af git også https://github.com/STU-IT/Basis-GitIntro/blob/master/git.md)

Det skal ikke være svært at lave første og traditionelle "Hello World" program i noget sprog. Meningen er at få det første hul igennem, og, fra programmet, udskrive det første "Hallo!", ("Hva' så ROSKILDEEEE?!").

Det ser sådan her ud:

```C
#include <stdio.h>

int main (void)
{
    printf("Hello World\n");
}
```
- Gem filen, og giv den navnet `hello.c`.
- I kommando-panelet skriver du `gcc hello.c` og tryk [enter].
- Tjek hvad der er kommet ud af det med kommandoen `ls`. Der skulle gerne være en fil der hedder `a.out`. Den skal vi køre...

For at starte programmet skal man angive stien til den, selv om man står i samme dir som programmet ligger i. 

- Skriv `./a.out` + [enter]

`./` betyder "den-nuværende-mappe".

## hello-2.c

Men hvad nu hvis vi gerne vil kunne lave en mere personlig hilsen? Og derud over vil introducere brug af en varibel, sam indlæsning af data fra tastaturet, og bibliotektet CS50.h?

Ja, så ser koden således ud:
```C
#include <cs50.h>
#include <stdio.h>

int main(void)
{
    printf("State your name: ");
    string name = GetString();
    printf("hello, %s\n", name);
}
```
Men nu er det ikke nok at bruge `gcc`. Nu skal vi nemlig også linke den binære object-fil der hører til CS50.h. Derfor bruger vi `make hello-2` uden `.c`. I denne sammenhæng betyder linke at copiere object-fiulen med i den eksekverbare fil.

*- Søren*



