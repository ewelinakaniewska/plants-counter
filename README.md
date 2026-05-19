# Licznik Podlanych Roślin

Prosta, funkcjonalna aplikacja webowa służąca do monitorowania i zapisywania liczby podlanych roślin. Projekt stanowi praktyczną realizację podstaw programowania interaktywnego z wykorzystaniem czystego języka **JavaScript (Vanilla JS)**, struktury **HTML5** oraz stylów **CSS3**.

https://harmonious-llama-5cec10.netlify.app/

---

## Funkcjonalności aplikacji

* **Zliczanie:** Przycisk `INCREMENT` dynamicznie zwiększa wartość głównego licznika o jeden przy każdym kliknięciu.
* **System zapisu historii (Logowanie danych):** Kliknięcie przycisku `SAVE` powoduje przechwycenie aktualnego stanu licznika, sformatowanie go i dopisanie do listy poprzednich wpisów ("Previous entries").
* **Automatyczne resetowanie stanu:** Po zapisaniu danych, główny licznik aplikacji automatycznie resetuje się do wartości `0`, przygotowując program do nowej serii zliczeń.

---

## Kluczowe koncepty JavaScript użyte w projekcie

* **Manipulacja drzewem DOM (Document Object Model):** Wykorzystanie metody `document.getElementById` do powiązania elementów interfejsu użytkownika z logiką aplikacji w pliku `index.js`.
* **Zarządzanie zmiennymi i typami:** Kontrola stanu aplikacji przy użyciu globalnej zmiennej liczbowej (`let count`) oraz dynamiczna zmiana jej typu na ciąg tekstowy podczas zapisu.
* **Właściwość `textContent`:** Zastosowanie bezpiecznej i wydajnej modyfikacji samej zawartości tekstowej węzłów HTML (zamiast wolniejszego i podatnego na ataki `innerHTML`).
* **Instrukcje przypisania z dodawaniem (`+=`):** Zastosowanie operatora złożonego do ciągłego rozbudowywania ciągu tekstowego historii bez nadpisywania wcześniejszych danych.

---

## Zastosowane technologie

* **JavaScript (ES6+)** – logika aplikacji, obsługa zdarzeń i manipulacja elementami DOM.
* **HTML5** – semantyczny szkielet aplikacji z przypisanymi zdarzeniami `onclick`.
* **CSS3** – estetyczne, wyśrodkowane ułożenie elementów (`margin: 0 auto`), zaokrąglenia bloków, efekty zmiany kursora myszy (`cursor: pointer`) oraz pełnowymiarowe tło florystyczne z dopasowaniem `background-size: cover`.

---


Projekt nie wymaga zaawansowanych bundlerów – działa bezpośrednio w przeglądarce:
1. Sklonuj to repozytorium na swój dysk.
2. Otwórz plik `index.html` bezpośrednio w dowolnej przeglądarce internetowej (lub użyj wtyczki Live Server w VS Code).
