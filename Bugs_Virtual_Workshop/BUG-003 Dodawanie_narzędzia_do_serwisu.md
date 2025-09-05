# BUG-003: Nieprawidlowe dodawanie narzędzi do serwisu .

**Priorytet:** Wysoki  
**Data zgłoszenia:** 1.09.2025  
**Zgłaszający:** Paweł Garbaty  

---

## Opis błędu:
Możliwość dodania narzędzia do serwisu, jeśli jego ilość (na liście narzędzi) wynosi 0. 

---

## Warunki wstępne:
Użytkownik musi posiadać konto i przynajmniej jedno narzedzie w warsztacie w ilości 0 szt.

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

📎 [Lista narzędzi ](https://github.com/Pawel566/Virtual_workshop_testing/blob/main/screenshots/bug_001_user2.png)  
📎 [Dodawanie do serwisu](https://github.com/Pawel566/Virtual_workshop_testing/blob/main/screenshots/bug_001_user3.png)
📎 [Dodane "brakujące" narzędzie](https://github.com/Pawel566/Virtual_workshop_testing/blob/main/screenshots/bug_001_user3.png)


---

## Uwagi:
- Wersja aplikacji: 0.1  
- Środowisko testowe: lokalne (`localhost:8000`)  
- Stworzono za pomocą dillinger.io  

---
