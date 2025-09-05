# BUG-003: Nieprawidłowe dodawanie narzędzi do serwisu .

**Priorytet:** Wysoki  
**Data zgłoszenia:** 1.09.2025  
**Zgłaszający:** Paweł Garbaty  

---

## Opis błędu:
Możliwość dodania narzędzia do serwisu, jeśli jego ilość (na liście narzędzi) wynosi 0. 

---

## Warunki wstępne:
Użytkownik musi posiadać konto i przynajmniej jedno narzędzie w warsztacie w ilości 0 szt.

---

### Kroki odtworzenia:

1. Zaloguj się na swoje konto
2. Wejdź do zakładki "Serwis"
3. Dodaj narzędzie do serwisu, klikając "Wyślij narzędzie do serwisu" 
4. Uzupełnij formularz.

##### Rezultat rzeczywisty:

Możliwe jest dodanie narzędzia do serwisu, jeżeli jego ilość wynosi 0 sztuk.

##### Rezultat oczekiwany:
Brak możliwości dodania narzędzia, którego nie mamy w warsztacie. Stosowny komunikat, lub brak pozycji na liście.
    

## Załączniki:

📎 [Lista narzędzi ](https://github.com/Pawel566/Virtual_Workshop_Testing_Manual/blob/main/Bugs_Virtual_Workshop/Screenshots/Bug_003_Przed_dodaniem_do%20serwisu.png)  
📎 [Dodawanie do serwisu](https://github.com/Pawel566/Virtual_Workshop_Testing_Manual/blob/main/Bugs_Virtual_Workshop/Screenshots/Bug_003_Dodawanie%20do%20serwisu.png)
📎 [Dodane "brakujące" narzędzie](https://github.com/Pawel566/Virtual_Workshop_Testing_Manual/blob/main/Bugs_Virtual_Workshop/Screenshots/Bug_003_W%20serwisie.png)


---

## Uwagi:
- Wersja aplikacji: 0.1  
- Środowisko testowe: lokalne (`localhost:8000`)  
- Stworzono za pomocą dillinger.io  

---

