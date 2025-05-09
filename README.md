# What's Up City

Aplikacja webowa do monitorowania i prezentowania danych miejskich (Wrocław i inne miasta) z różnych publicznych API.

## Stack technologiczny

- **Frontend:** Next.js (React) + Tailwind CSS + obsługa wielu języków (i18next)
- **Backend:** Python + Django + Django REST Framework
- **Hosting:**
  - Frontend: Vercel/Netlify
  - Backend: LH.pl lub alternatywnie Railway/Render/Heroku

## Struktura projektu

- `/frontend` – aplikacja Next.js (React + Tailwind)
- `/backend` – aplikacja Django (REST API)

## Instrukcja uruchomienia

### Frontend (Next.js)

1. Przejdź do katalogu `frontend`:
   ```bash
   cd frontend
   ```
2. Zainstaluj zależności:
   ```bash
   npm install
   ```
3. Uruchom aplikację developerską:
   ```bash
   npm run dev
   ```
4. Aplikacja będzie dostępna pod adresem `http://localhost:3000`

### Backend (Django)

1. Przejdź do katalogu `backend`:
   ```bash
   cd backend
   ```
2. Utwórz i aktywuj wirtualne środowisko:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Windows: venv\Scripts\activate
   ```
3. Zainstaluj zależności:
   ```bash
   pip install -r requirements.txt
   ```
4. Wykonaj migracje:
   ```bash
   python manage.py migrate
   ```
5. Uruchom serwer developerski:
   ```bash
   python manage.py runserver
   ```
6. API będzie dostępne pod adresem `http://localhost:8000`

---

## Rozwój
- Kod źródłowy i dokumentacja API w katalogach `frontend` i `backend`.
- Szczegóły integracji z API miejskimi w pliku `API_Wroclaw.md`.

---

## Autor
Projekt rozwijany przez Mateusza i AI (asystent programistyczny).
