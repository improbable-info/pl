## Automaty komórkowe

Automaty komórkowe pokazują, jak proste reguły mogą generować skomplikowane zachowanie.

Pokażemy kilka przykładów z „Gry w życie” (Game of Life).
Reguły są takie, że na dwuwymiarowej planszy komórki mogą mieć dwa stany – być martwe albo żywe.
Żywa komórka pozostaje w następnym kroku nadal żywa, jeżeli ma obok siebie 2 albo 3 żywe komórki;
przy innej liczbie sąsiadów umiera. Martwa komórka ożyje w następnym kroku,
jeżeli ma obok siebie dokładnie 3 żywych sąsiadów.
Na rysunkach jest żywa komórka zaznaczona czarnym kolorem i martwa komórka białym.

Przykład 1. Prosty przykład ewolucji zmierzającej do stanu, w którym już się stan komórek nie zmienia:

1a) Struktury żywych komórek stopniowo znikają aż pozostanie puste pole:
