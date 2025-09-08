# BUG-001: Lista narzędzi, zleceń i serwisu jest taka sama dla różnych kont.

**Priorytet:** Najwyższy  
**Data zgłoszenia:** 1.09.2025  
**Zgłaszający:** Paweł Garbaty  

---

## Opis błędu:
System wyświetla te same dane (narzędzia, zlecenia, serwis) dla wszystkich kont, zamiast te przypisane do użytkownika. 

---

## Warunki wstępne:
Istnieją przynajmniej 2 różne konta w systemie.

___


## Kroki odtworzenia:

1. Zaloguj się na konto "user2".
2. Dodaj narzędzie i zlecenie.
3. Wyloguj się.
4. Zaloguj się na konto "user3"
5. Przejdź do zakładek "Narzędzia" i "Zlecenia".

---
## Rezultat rzeczywisty:
Użytkownik "user3" widzi narzędzia i zlecenia dodane przez "user2".

___
## Rezultat oczekiwany:
Żaden z użytkowników nie powinien widzieć narzędzi i zleceń dodanych przez innego. Każdy widzi wyłącznie dane dodane przez siebie.

## Załączniki:

📎 [Lista narzędzi user2 (zrzut ekranu)](https://github.com/Pawel566/Virtual_Workshop_Testing_Manual/blob/main/Bugs_Virtual_Workshop/Screenshots/bug_001_user2.png)  
📎 [Lista narzędzi user3 (zrzut ekranu)](https://github.com/Pawel566/Virtual_Workshop_Testing_Manual/blob/main/Bugs_Virtual_Workshop/Screenshots/bug_001_user3.png)


---

## Uwagi:
- Wersja aplikacji: 0.1  
- Środowisko testowe: lokalne (`localhost:8000`)  
- Stworzono za pomocą dillinger.io  

---




