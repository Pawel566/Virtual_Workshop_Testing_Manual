# BUG-004: Błąd_z_datą_w_serwisie.

**Priorytet:** Średni 
**Data zgłoszenia:** 1.09.2025  
**Zgłaszający:** Paweł Garbaty  

---

## Opis błędu:
Przy dodawaniu narzędzia do serwisu można zaznaczyć datę z przeszłości, np. tydzień temu. 

---

## Warunki wstępne:
Użytkownik musi posiadać konto i przynajmniej jedno narzędzie w warsztacie.

---

### Kroki odtworzenia:

1. Zaloguj się na swoje konto
2. Wejdź do zakładki "Serwis"
3. Dodaj narzędzie do serwisu, klikając "Wyślij narzędzie do serwisu" 
4. Uzupełnij formularz, wybierz datę sprzed kilku dni/tygodni.

##### Rezultat rzeczywisty:

Możliwe jest dodanie narzędzia do serwisu, po podaniu wcześniejszej daty

##### Rezultat oczekiwany:
Brak możliwości dodania narzędzia do serwisu podając wcześniejszą datę (np. wczorajszą).  Wyświetlanie stosownego komunikatu.
    

## Załączniki:

📎 [Niewłaściwa data](https://github.com/Pawel566/Virtual_workshop_testing/blob/main/screenshots/bug_001_user2.png)  
📎 [Dodanie do serwisu](https://github.com/Pawel566/Virtual_workshop_testing/blob/main/screenshots/bug_001_user3.png)



---

## Uwagi:
- Wersja aplikacji: 0.1  
- Środowisko testowe: lokalne (`localhost:8000`)  
- Stworzono za pomocą dillinger.io  

---
