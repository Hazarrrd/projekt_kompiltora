# Projekt kompiltora
Kompilator
autor : Jan Sieradzki

dostarczone pliki :
kompilator.l
kompilator.y

Kompilator wykonany za pomocą flexa,bison, c  c++. Wymagane g++.

Sposób użycia :
Należy najpierw skompilować programy za pomocą polecenia 'make'
Aby użyć kompilatora neleży wpisać w konsolę :

./kompilator <plik z wejściem> <plik z wyjściem>

np :
./kompilator input.txt code.txt

Kompilator na wejściu przyjmuje kod w języku opisanym w poleceniu, a zwraca kod maszynowy (opisany również w poleceniu).
