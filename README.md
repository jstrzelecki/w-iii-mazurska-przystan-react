# ⚓ Projekt: Mazurska Przystań - System Rezerwacji


Witajcie w zespole deweloperskim! Waszym zadaniem jest stworzenie aplikacji typu "Kalkulator Rezerwacji" dla wypożyczalni sprzętu wodnego na Mazurach.

## 🛠️ Stack Techniczny
- **Framework:** React.js
- **Stylizacja:** CSS (Flexbox - wymóg konieczny!)
- **Workflow:** Git (GitHub) + Discord Webhooks

## 📋 Lista Issues dla Kanbanu (Vite & Template Edition)
Możecie skopiować te zadania bezpośrednio do swoich Issues na GitHubie:

`Issue #1`: Repository & Environment Setup ⚙️
Opis: Przygotowanie stanowiska pracy na bazie template.

Zadania:
- [ ] Stworzenie własnego repozytorium z Twojego template'u.
- [ ] Zaproszenie partnera i konfiguracja Discord Webhook.
- [ ] Odpalenie projektu komendą npm run dev.
- [ ] Sprawdzenie, czy documentation.md i README.md są gotowe do edycji.


`Issue #2`: UI: Form Structure & Flexbox 🎨
Opis: Budowa "szkieletu" formularza w App.jsx.

Zadania:
- [ ] Dodanie pól: Name (input), Boat (select), Hours (range), Extras (checkbox), Payment (radio).
- [ ] Stylowanie kontenera w App.css (lub index.css) przy użyciu Flexbox.
- [ ] Ustawienie responsywności (np. max-width dla formularza, żeby nie był na cały ekran).


`Issue #3`: Logic: State & Live Price 🧙‍♂️
Opis: Ożywienie formularza za pomocą React Hooks.

Zadania:
- [ ] Inicjalizacja useState dla wszystkich pól formularza.
- [ ] Podpięcie zdarzeń onChange (pamiętajcie o e.target.value i e.target.checked!).
- [ ] Implementacja funkcji liczącej cenę (Kajak 20/h, Rower 35/h, Omega 150/h).
- [ ] Wyświetlenie komunikatu o patencie przy wyborze "Omegi".


`Issue #4`: Logic: Validation & Final Polish ✅
Opis: Bezpieczeństwo i UX.

Zadania:
- [ ] Walidacja przycisku "Rezerwuję" (musi być disabled, gdy brak imienia lub regulaminu).
- [ ] Dodanie prostego "Alertu" lub podziękowania po kliknięciu w przycisk.
- [ ] Usunięcie niepotrzebnych plików/komentarzy z template'u.


`Issue #5`: Documentation & SDLC Wrap-up 📖
Opis: Podsumowanie prac w pliku documentation.md.

Zadania:
- [ ] Uzupełnienie tabeli stanów i opisanie algorytmu ceny.
- [ ] Krótka analiza w sekcji "Wnioski".
- [ ] Zamknięcie tablicy Kanban i sprawdzenie historii commitów.

## 🚀 Zasady pracy (SDLC)
- Nie wypychamy kodu bezpośrednio do gałęzi `main`.
- Tworzymy gałęzie dla każdego inżyniera.
- Każdy kod musi przejść przez **Pull Request**, który zatwierdza druga osoba z pary.
- Po każdym `git push` sprawdźcie, czy na Discordzie (kanał #feed-github) pojawiło się powiadomienie.
--------------



---
## :dart: Cel projektu:
Stworzenie responsywnego kalkulatora wynajmu w React.js, wykorzystując:
- formularze,
- `useState`
-  Flexbox.


##:warning: Wasze zadania na „Sprint 1” (dzisiaj):
- Praca: pracujecie w parach
- Repozytorium: Jedna osoba tworzy repo na GitHubie w oparciu o moje *repo template* i zaprasza partnera (Collaborator).
- Webhook: Skonfigurujcie połączenie z kanałem #github-feed, abyśmy widzieli każdy Wasz commit.
- Setup: Zapoznajcie się z plikiem README.md dostępnym w repo.

## :construction_site: Issues: Rozpiszcie zadania na GitHubie – podzielcie się na „UI Master” i „Logic Wizard”.

### Jak to połączyć w GitHubie?
- `Issues`: To opisy konkretnych zadań (np. „Stworzyć formularz we Flexboxie”).
- `Projects` (Kanban): To wizualna tablica z kolumnami (np. Todo, In Progress i Done).
- Przeciągacie swoje Issues między kolumnami.


### :performing_arts: Przykładowy podział ról w zespole (na Kanbanie)
Aby praca szła sprawnie, warto, żeby każdy uczeń wiedział, za co odpowiada na tablicy:

#### :art: UI Master (User Interface)
Jego zadania na Kanbanie:
- Przygotowanie struktury JSX (inputy, labele, selecty).
- Stylowanie we Flexboxie (wyśrodkowanie, responsywność).
- Obsługa wizualna stanów (np. zmiana koloru przycisku, gdy jest disabled).
- Cel: Aplikacja musi wyglądać profesjonalnie i nie rozjeżdżać się na telefonie.

#### :man_mage: Logic Wizard (Business Logic)
Jego zadania na Kanbanie:
- Obsługa hooków useState.
- Napisanie funkcji obliczającej cenę (np. calculateTotal).
- Walidacja pól (czy imię nie jest puste?).
- Cel: Aplikacja musi poprawnie liczyć pieniądze i reagować na działania użytkownika.


:warning: Zasada Zero Tolerancji:
- Brak pracy na main! Każda zmiana musi przejść przez Pull Request i zostać zatwierdzona przez partnera, czli pracujecie na oddzielnych gałęziach.
- Jak pracować w grupie na GitHubie? https://tie9-olsztyn-programmers.github.io/docs/Git%20i%20Github/GItHub%20w%20zespole

Good luck & happy coding! :computer::ocean:







