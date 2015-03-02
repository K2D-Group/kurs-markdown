Title: 		Linki  
Date: 		28-02-2015  
Source:     asp.katowice.pl => http://www.asp.katowice.pl/zobacz/markdown  

# Linki

## Tworzenie odnośnika

Aby utworzyć link należy użyć dwóch nawiasów: pierwszy - kwadratowy, 
w którym wpisuje się treść linku oraz tuż za nim otwiera się nawias okrągły, 
w którym wpisuje się adres URL, a za nim opcjonalnie w cudzysłowie tytuł linku. 
Spójrz na poniższy przykład:

### Przykład 1
```
[Tekst linku](http://example.pl/ "Opis linku")
```
wynik:

[Tekst linku](http://example.pl/ "Opis linku")

### Przykład 2
```
[Tekst linku](http://example.pl/)
```
wynik:

[Tekst linku](http://example.pl/)


## Tworzenie odnośnika

Kolejny sposób (bardziej czytelny) zapisu linku polega na zapisie w dwóch nawiasach kwadratowych danych o linku, 
tzn. w pierwszym nawiasie kwadratowym zapisuje się opis linku, a w drugim nawiasie wpisujemy krótką nazwę, 
która jest tylko punktem odniesienia do legendy. Legenda skonstruowana jest z nawiasu kwadratowego, 
w nim powtarza się krótka nazwa (taka sama jak w drugim nawiasie kwadratowym), za nim znak dwukropka, 
a za nim adres strony. 

### Przykład
```
[Tekst linku][test] 

[test]: http://example.pl/
```
wynik:

[Tekst linku][test] 

[test]: http://example.pl/

## Automatyczne odnośniki

Markdown pozwala na dodawanie automatycznych linków z adresami URL 
oraz linki do adresów e-mail za pomocą nawiasów ostrych. 

### Przykład 1
```
<info@example.pl>
```
wynik:

<info@example.pl>

### Przykład 2
```
<info@example.pl>
```
wynik:

<http://example.pl/>













