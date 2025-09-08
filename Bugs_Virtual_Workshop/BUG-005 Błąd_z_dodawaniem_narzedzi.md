# BUG-005: Błąd z dodaniem narzędzi w ilości = 0.

**Priorytet:** Wysoki

**Data zgłoszenia:** 08.09.2025 

**Zgłaszający:** Paweł Garbaty  

---

## Opis błędu:
Możliwośc dodania narzędzia do listy w ilości 0 szt. 

---

## Warunki wstępne:
Użytkownik musi posiadać konto.

---

### Kroki odtworzenia:

1. Zaloguj się na swoje konto
2. Wejdź do zakładki "Narzędzia"
3. Dodaj narzędzie do listy, klikając "Dodaj narzędzie" 
4. Uzupełnij formularz, przy "Ilość sztuk" podaj 0.
5. Dodaj narzędzie.

##### Rezultat rzeczywisty:

Możliwe jest dodanie narzędzia do listy, gdy jego ilość wynosi 0.

##### Rezultat oczekiwany:
Brak możliwości dodania narzędzia przy zerowej ilości. Taka próba powinna być zablokowana odpowiednim komunikatem.
    

## Załączniki:

📎 [Niewłaściwa ilość](https://github.com/Pawel566/Virtual_Workshop_Testing_Manual/blob/main/Bugs_Virtual_Workshop/Screenshots/bug_005_dodawanie_narzedzia.png)  
📎 [Dodanie do listy](https://github.com/Pawel566/Virtual_Workshop_Testing_Manual/blob/main/Bugs_Virtual_Workshop/Screenshots/bug_005_lista_narzedzi.png)



---

## Uwagi:
- Wersja aplikacji: 0.1  
- Środowisko testowe: lokalne (`localhost:8000`)  
- Stworzono za pomocą dillinger.io  

---


