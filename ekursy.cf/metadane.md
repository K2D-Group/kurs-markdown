Title: 		Metadane dokumentu  
Date: 		28-02-2015  
Author:     Krystian Duma  
Reviewer:	Krystian Duma  
Private:	True  

# Metadane dokumentu
Każdy dokument MarkDown trafiający na ekursy.cf powinien zawierać Metadane[^1].

Metadane muszą zacząć się na początku dokumentu, a bezpośrednio po nich musi się znajdować przynajmniej jedna pusta linia.

Metadane są zbiorem wartości typu `klucz: wartość`. Każdy klucz może mieć kilka wartości poprzez umieczczenie ich 
w następnych liniach używając wcięć.

Są wymagane przynajmniej 2 klucze:
- `Title` - Tytuł dokumentu
- `Date` - Data utworzenia, i daty aktualizacji

Aby utrzymać kompatybilność z programami które nie obsługują metadanych poleca się postawienie 2 spacji na końcu każdej lini metadanych.

## Przykład

```
Title: 		Sample Document  
Date: 		13-01-2015  
            30-02-2015  
Author:     Jan Kowalski
            Ewa Nowak

# Tu jest reszta dokumentu
```

# Standardowe klucze

| Klucz      | Wymagany  | Opis                                              			|
|:---------- |:---------:|:------------------------------------------------------------ |
| `Title`    | **Tak**   | Tytuł dokumentu                                   			|
| `Date`     | **Tak**   | Data utworzenia, i daty aktualizacji              			|
| `Author`   | Nie       | Autorzy tekstu                                    			|
| `Reviewer` | Nie       | Recenzenci tekstu                                			|
| `Source`   | Nie       | źródła którymi posłużono się do napisania tekstu  			|
| `Private`  | Nie       | Czy wymagane jest logowanie. (True/False) domyślnie false 	|










[^1]: Zbiór informacji o dokumencie i jego autorach.