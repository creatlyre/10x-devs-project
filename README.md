TripCrafti - Twój Inteligentny Asystent Podróży
🌟 Wizja Projektu

TripCrafti to inteligentny asystent podróży, którego misją jest zrewolucjonizowanie sposobu, w jaki planujemy i przeżywamy wyjazdy. Naszym celem jest zredukowanie stresu związanego z organizacją do minimum, pozwalając podróżnikom czerpać czystą radość z odkrywania świata.

Aplikacja kompleksowo wspiera użytkownika na każdym etapie: od inspiracji i automatycznego planowania, przez precyzyjne zarządzanie budżetem i rezerwacjami, aż po inteligentne spakowanie walizki z pomocą AI.
✨ Główne Funkcjonalności

TripCrafti to nie tylko planer, to zintegrowany ekosystem, który dba o każdy detal Twojej podróży.

    ✈️ Centralne Zarządzanie Podróżą (CRUD): Stanowi serce aplikacji. Twórz, przeglądaj, edytuj i usuwaj swoje wyjazdy. Zarządzaj rezerwacjami, kluczowymi dokumentami i notatkami w jednym miejscu.

    💰 Precyzyjne Śledzenie Budżetu: Ustaw ogólny budżet dla podróży i na bieżąco dodawaj wydatki. TripCrafti automatycznie podsumuje koszty i pokaże, jak Twoje wydatki mają się do założonego planu.

    🗺️ Inteligentny Kreator Planu Podróży (AI): Opisz swoje zainteresowania, styl podróży i budżet, a Google Gemini stworzy dla Ciebie spersonalizowany, edytowalny plan zwiedzania na każdy dzień.

    🧳 Asystent Pakowania (AI): Na podstawie celu, długości wyjazdu i zaplanowanych aktywności, AI wygeneruje idealną listę rzeczy do spakowania, abyś nigdy więcej o niczym nie zapomniał(a).

    🔒 Bezpieczne Uwierzytelnianie: Pełne bezpieczeństwo i izolacja danych dzięki systemowi rejestracji i logowania. Każda podróż i jej dane należą tylko do Ciebie.

    📱 Pełna Responsywność: Korzystaj z aplikacji wygodnie na komputerze, tablecie i smartfonie.

🛠️ Stos Technologiczny

Aplikacja zbudowana jest w oparciu o nowoczesny i skalowalny stos technologiczny, zapewniający wydajność i bezpieczeństwo.

Kategoria
	

Technologia

Frontend
	

React z TypeScriptem dla interaktywnego i bezpiecznego UI.

Styling
	

Tailwind CSS dla szybkiego budowania nowoczesnych i responsywnych interfejsów.

Backend
	

Node.js z frameworkiem NestJS, zapewniającym modułową i uporządkowaną architekturę.

Baza Danych
	

PostgreSQL – potężna, relacyjna baza danych, idealna do przechowywania złożonych, powiązanych ze sobą danych.

AI
	

Google Gemini API do napędzania inteligentnych funkcji planowania i pakowania.

CI/CD
	

GitHub Actions do automatyzacji procesów testowania, budowania i wdrażania aplikacji.
🏗️ Architektura Aplikacji

TripCrafti wykorzystuje architekturę zorientowaną na usługi. Aplikacja kliencka (frontend) komunikuje się z serwerem (backend) poprzez bezpieczne API REST. Backend zarządza całą logiką biznesową, danymi oraz integracją z usługami zewnętrznymi, takimi jak Google Gemini.

[Frontend: React] <--- (API REST) ---> [Backend: NestJS] <--- (Integracja) ---> [Baza Danych: PostgreSQL]
                                              ^
                                              |
                                              v
                                      [Google Gemini API]

🚀 Plan Rozwoju (Roadmap)

Projekt rozwijany jest iteracyjnie. Poniżej znajdują się kluczowe etapy wdrożenia:

    [x] Etap 1: MVP - Rdzeń Planera Podróży

        [x] System uwierzytelniania użytkowników.

        [x] Pełny CRUD dla podróży (Trips).

        [x] Zarządzanie elementami podróży (TripItems) - wydatki, rezerwacje.

        [x] Podstawowe podsumowanie budżetu.

        [x] Konfiguracja infrastruktury (DB, CI/CD).

    [x] Etap 2: Integracja z Inteligentnym Planerem Podróży AI

        [x] Formularz preferencji użytkownika (zainteresowania, styl podróży).

        [x] Implementacja zaawansowanych promptów dla Gemini.

        [ ] Wizualizacja planu podróży (np. w formie osi czasu).

        [x] Możliwość ręcznej edycji planu (np. metodą "przeciągnij i upuść").
	[ ] Etap 3: Integracja z Asystentem Pakowania AI

        [ ] Interfejs do generowania listy rzeczy do spakowania.

        [ ] Integracja backendu z Gemini API.

        [ ] Wyświetlanie i zarządzanie wygenerowaną listą (CRUD).

    [ ] Etap 4: Udoskonalenia i Funkcje Społecznościowe

        [ ] Udostępnianie planów podróży za pomocą linku.

        [ ] Powiadomienia (np. o nadchodzącym locie).

        [ ] Możliwość dodawania zdjęć i notatek do podróży.

        [ ] Tryb offline.

⚙️ Instalacja i Uruchomienie

Projekt składa się z dwóch głównych części: aplikacji backendowej i frontendowej.
Wymagania

    Node.js (wersja 20.x lub wyższa)

    NPM lub Yarn

    Działająca instancja PostgreSQL

    Klucz API do Google Gemini

Backend (NestJS)

    Sklonuj repozytorium:

    git clone [https://github.com/twoja-nazwa-uzytkownika/TripCrafti.git](https://github.com/twoja-nazwa-uzytkownika/TripCrafti.git)
    cd TripCrafti/backend

    Zainstaluj zależności:

    npm install

    Skonfiguruj zmienne środowiskowe:

        Stwórz plik .env na podstawie .env.example.

        Uzupełnij dane dostępowe do bazy danych (DATABASE_URL) oraz klucz API (GEMINI_API_KEY).

    Uruchom migracje bazy danych (jeśli używasz ORM np. Prisma/TypeORM):

    npm run migrate:dev
    
    Uruchom serwer deweloperski:

    npm run start:dev

Frontend (React)

    Przejdź do katalogu frontend:

    cd ../frontend

    Zainstaluj zależności:

    npm install

    Skonfiguruj zmienne środowiskowe:

        Stwórz plik .env.local na podstawie .env.example.

        Wskaż adres URL działającego backendu (VITE_API_BASE_URL).

    Uruchom aplikację kliencką:

    npm run dev

🤝 Współtworzenie

Jesteś pasjonatem podróży i kodowania? Chcesz pomóc w rozwoju TripCrafti? Twoja pomoc jest mile widziana!

    Sforkuj repozytorium.

    Utwórz nową gałąź (git checkout -b feature/twoja-funkcja).

    Wprowadź swoje zmiany.

    Zacommituj zmiany (git commit -m 'feat: Dodaj nową, wspaniałą funkcję').

    Wypchnij zmiany do swojej gałęzi (git push origin feature/twoja-funkcja).

    Otwórz Pull Request, opisując wprowadzone zmiany.

Stworzone z ❤️ dla wszystkich podróżników.
## BudgetCraft Phase 3 Additions

The project now includes foreign exchange (FX) conversion, post-trip budget reports, and CSV export.

### Environment Variable

Set a public FX API base (no key required for exchangerate.host):

```
PUBLIC_FX_API_BASE=https://api.exchangerate.host
```

If unset, the utility defaults to `https://api.exchangerate.host`.

### FX Conversion

When creating or updating an expense where `expense.currency !== trip.currency`, the API:

1. Fetches the live rate (cached 6h) via `/latest?base={from}&symbols={to}`.
2. Converts `amount` into `amount_in_home_currency` stored with the expense.
3. Falls back to rate=1 with a warning if the fetch fails (avoids blocking the user).

> NOTE: To persist exact historical FX, add migration: `ALTER TABLE expenses ADD COLUMN fx_rate NUMERIC;`

### New Endpoints

| Endpoint | Method | Purpose |
|----------|--------|---------|
| `/api/trips/:tripId/expenses` | POST | Create expense with FX conversion |
| `/api/trips/:tripId/expenses/:expenseId` | PUT | Update expense with recalculated FX |
| `/api/trips/:tripId/budget/report` | GET | Planned vs actual per category & totals |
| `/api/trips/:tripId/expenses/export.csv` | GET | CSV export of expenses |

### Report Structure (`BudgetReport`)

```
{
  trip_id: string,
  currency: string | null,
  plannedTotal: number,
  totalSpent: number,
  totalPrepaid: number,
  totalOnTrip: number,
  deltaTotal: number,
  categories: [{ category_id, name, planned, spent, delta, utilization }],
  generated_at: string
}
```

### UI Enhancements

* Budget dashboard: CSV export button.
* Post-trip (`end_date` passed) displays a consolidated report card.
* Summary widget already surfaces daily safe-to-spend.

### Testing

`tests/unit/fx.service.test.ts` covers:

* Identity rate
* Live fetch & subsequent cache hit
* Fallback on provider error
* Conversion calculation

Run tests:

```
npm test
```

### Future Extensions

* Persist `fx_rate` per expense.
* Historical date-based rate lookup.
* Reconciliation & revaluation tool.
* Multi-currency reporting (group by source currency).

=======
