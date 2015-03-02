Title: 		Listy  
Date: 		28-02-2015  
Source:     asp.katowice.pl => http://www.asp.katowice.pl/zobacz/markdown  
Reviewer:	Krystian Duma  

#Listy

W Markdown można tworzyć uporządkowane, a także nieuporządkowane listy. 

## Lista nieuporządkowana

Chcąc stworzyć nieuporządkowaną listę zastosujemy symbol gwiazdki „\*”, plusa „+” lub minusa „-”.

### Przykłady

```markdown
* Pierwszy element listy 
* Drugi element listy 
* Trzeci element listy
```
lub
```markdown
+ Pierwszy element listy 
+ Drugi element listy 
+ Trzeci element listy
```
lub
```markdown
- Pierwszy element listy 
- Drugi element listy 
- Trzeci element listy
```

Wynik:

* Pierwszy element listy 
* Drugi element listy 
* Trzeci element listy


## Lista uporządkowana

Aby otrzymać listę uporządkowaną, w Markdown można stosować kolejne cyfry: 1, 2, 3...
a także wpisać obojętnie jaką cyfrę, powielając ją na początku każdego nowego punktu np.: 2, 2, 2...
Ostatnim sposobem na otrzymanie listy uporządkowanej jest rozpoczęcie wiersza od losowo wybranej cyfry, przykładowo: 3, 6, 7...
Wówczas Markdown również zamieni cyfry w uporządkowaną listę. 
Nigdy nie wolno zapomnieć o znaku interpunkcyjnym kropki „.” umieszczonej tuż za każdą z cyfr.

### Przykłady

```markdown
1. Pierwszy element listy 
2. Drugi element listy 
3. Trzeci element listy
```
lub
```markdown
2. Pierwszy element listy 
2. Drugi element listy 
2. Trzeci element listy
```
lub
```markdown
3. Pierwszy element listy 
6. Drugi element listy 
7. Trzeci element listy
```

Wynik:

1. Pierwszy element listy 
2. Drugi element listy 
3. Trzeci element listy


## Wcięcie przed wypunktowaniem

Aby wypunktowanie było równe trzeba przed tekstem zastosować czterokrotnie spację albo jeden Tab. 

Zobacz różnicę w poniższych przykładach:

### Przykład 1

```markdown
*   Ten element listy składa się z dwóch paragrafów. To jest pierwszy paragraf…

    A to jest drugi paragraf. 
    
*   Drugi element listy
```

Wynik:

*   Ten element listy składa się z dwóch paragrafów. To jest pierwszy paragraf…

    A to jest drugi paragraf. 
    
*   Drugi element listy

### Przykład 2

```markdown
1.  Ten element listy składa się z dwóch paragrafów. To jest pierwszy paragraf…

    A to jest drugi paragraf.

2.  Drugi element listy
```

Wynik:

1.  Ten element listy składa się z dwóch paragrafów. To jest pierwszy paragraf…

    A to jest drugi paragraf.

2.  Drugi element listy


## Listy zagnieżdżone

Aby tworzyć zagnieżdżoną listę, wystarczy przed znakiem wypunktowania (tj. gwiazdki, plusa czy minusa) 
postawić odpowiednią ilość znaków spacji. Jeśli przykładowo postawimy jedną spację przed elementem listy, 
wówczas pojawi się drugi poziom wypunktowania.

### Przykład 1

```markdown
*   Pierwszy element listy
    *   Pierwszy element listy
    *   Drugi element listy
*   Drugi element listy
```

Wynik:

*   Pierwszy element listy
    *   Pierwszy element listy
    *   Drugi element listy
*   Drugi element listy














