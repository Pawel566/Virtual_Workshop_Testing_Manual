# BUG-001: Lista narzędzi, zleceń i serwisu jest taka sama dla różnych kont.

**Priorytet:** Najwyższy  
**Data zgłoszenia:** 1.09.2025  
**Zgłaszający:** Paweł Garbaty  

---

## Opis błędu:
System wyświetla te same dane (narzędzia, zlecenia, serwis) dla wszystkich kont, zamiast te przypisane do użytkownika. 

---

## Warunki wstępne:


## Kroki odtworzenia:

| #  | Akcja                                                | Dane wejściowe                          | Rzeczywisty wynik                                     | Oczekiwany wynik                                      |
|----|-------------------------------------------------------|------------------------------------------|--------------------------------------------------------|--------------------------------------------------------|
| 1  | Zaloguj się na konto user2                            | `login: user2`                           | -                                                      | Użytkownik jest zalogowany                            |
| 2  | Dodaj narzędzie i utwórz zlecenie                     |                 | Narzędzie i zlecenie dodane                            | Pozycje zostały dodane                                                   |
| 3  | Wyloguj się i zaloguj na konto user3                  | `login: user3`                           | -                                                      | Użytkownik jest zalogowany                            |
| 4  | Przejdź do listy narzędzi i zleceń                    |             | user3 widzi narzędzia i zlecenia dodane przez user2    | user3 powinien widzieć tylko swoje narzędzia i zlecenia|

---
## Załączniki:

📎 [Lista narzędzi user2 (zrzut ekranu)](https://github.com/Pawel566/Virtual_Workshop_Testing_Manual/blob/main/Bugs_Virtual_Workshop/Screenshots/bug_001_user2.png)  
📎 [Lista narzędzi user3 (zrzut ekranu)](https://github.com/Pawel566/Virtual_Workshop_Testing_Manual/blob/main/Bugs_Virtual_Workshop/Screenshots/bug_001_user3.png)


---

## Uwagi:
- Wersja aplikacji: 0.1  
- Środowisko testowe: lokalne (`localhost:8000`)  
- Stworzono za pomocą dillinger.io  

---


