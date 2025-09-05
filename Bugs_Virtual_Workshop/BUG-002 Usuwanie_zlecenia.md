# BUG-002: Po usunięciu zlecenia narzędzia "znikają" .

**Priorytet:** Najwyższy  
**Data zgłoszenia:** 1.09.2025  
**Zgłaszający:** Paweł Garbaty  

---

## Opis błędu:
Po usunięciu zlecenia, do którego były przypisane narzędzia, te nie wracają do warsztatu.
Zaznaczony jest checkbox "W pracy". 

---

## Warunki wstępne:
Użytkownik musi posiadać konto i przynajmniej jedno narzedzie w warsztacie.
Musi być utworzone przynajmniej jedno zlecenie i przypisane do niego narzędzie.
---

### Kroki odtworzenia:

1. Zaloguj się na swoje konto
2. Wejdź do zakładki "Zlecenia"
3. Usuń zlecenie, do którego przypisane jest narzędzie klikając "Usuń zlecenie" 
4. Przejdź do zakładki "Narzędzia"

##### Rezultat rzeczywisty:

Po usunięciu zlecenia z listy przypisane do niego narzędzie również jest usuwane (nie wraca do warsztatu).
Checkbox "W Pracy" jest zaznaczony.

##### Rezultat oczekiwany:
Po usunięciu zlecenia narzedzie do niego przypisane "wraca" do warsztatu.
Checkbox "W pracy" nie jest zaznaczony.
    

## Załączniki:

📎 [Narzędzie przypisane do zlecenia (lista narzędzi)  ](https://github.com/Pawel566/Virtual_workshop_testing/blob/main/screenshots/bug_001_user2.png)  
📎 [Narzędzie przypisane do zlecenia](https://github.com/Pawel566/Virtual_workshop_testing/blob/main/screenshots/bug_001_user3.png)
📎 [Po usunięciu zlecenia (lista narzędzi)](https://github.com/Pawel566/Virtual_workshop_testing/blob/main/screenshots/bug_001_user3.png)


---

## Uwagi:
- Wersja aplikacji: 0.1  
- Środowisko testowe: lokalne (`localhost:8000`)  
- Stworzono za pomocą dillinger.io  

---
