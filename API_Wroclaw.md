# Dostępne API i źródła danych dla Wrocławia

## 1. Jakość powietrza
- **GIOŚ (Główny Inspektorat Ochrony Środowiska)**
  - Publiczne API: https://powietrze.gios.gov.pl/pjp/content/api
  - Dane: PM10, PM2.5, NO2, SO2, O3, CO, benzen, indeks jakości powietrza, prognozy, dane historyczne.
  - Przykład endpointu:
    - Lista stacji: `https://api.gios.gov.pl/pjp-api/rest/station/findAll`
    - Dane pomiarowe: `https://api.gios.gov.pl/pjp-api/rest/data/getData/{sensorId}`
    - Indeks jakości: `https://api.gios.gov.pl/pjp-api/rest/aqindex/getIndex/{stationId}`
- **World Air Quality Index (WAQI)**
  - API: https://aqicn.org/api/
  - Dane: globalny indeks jakości powietrza, dane historyczne, prognozy.

## 2. Pogoda
- **OpenWeatherMap**
  - API: https://openweathermap.org/api
  - Dane: aktualna pogoda, prognozy, alerty pogodowe.
  - Wymaga rejestracji (darmowy plan dostępny).

## 3. Komunikacja miejska (autobusy, tramwaje, opóźnienia)
- **MPK Wrocław**
  - Brak oficjalnego publicznego API, ale są nieoficjalne integracje oraz dane GTFS (rozkłady jazdy, trasy, przystanki).
  - Dane GTFS: https://www.wroclaw.pl/open-data/dataset/gtfs
  - Możliwe źródła opóźnień: aplikacje typu JakDojade, ale wymagają zgody/licencji.

## 4. Parkingi miejskie
- **Wrocław SmartCity**
  - API: https://www.wroclaw.pl/open-data/dataset/parkingi
  - Dane: lokalizacja parkingów, liczba miejsc, zajętość (jeśli dostępna).

## 5. Rower miejski
- **Nextbike (Wrocławski Rower Miejski)**
  - API: https://nextbike.net/maps/nextbike-live.xml?city=210
  - Dane: stacje, liczba rowerów, dostępność.

## 6. Wydarzenia miejskie
- **Wrocław Open Data**
  - API: https://www.wroclaw.pl/open-data/dataset/wydarzenia
  - Dane: wydarzenia kulturalne, sportowe, edukacyjne.

## 7. Ruch drogowy, korki
- **GDDKiA, Targeo, Google Maps API**
  - Google Maps API: https://developers.google.com/maps/documentation/traffic
  - Wymaga klucza i opłat przy większym ruchu.

## 8. Stacje ładowania pojazdów elektrycznych
- **OpenChargeMap**
  - API: https://openchargemap.org/site/develop/api
  - Dane: lokalizacja, dostępność ładowarek.

## 9. Czujniki hałasu, inne środowiskowe
- Brak oficjalnego API, ale czasem dane dostępne są przez SmartCity lub lokalne projekty.

## 10. Kalendarz wywozu śmieci
- Często dostępny przez strony urzędu miasta lub dzielnic, ale nie zawsze w formie API.

---

**Podsumowanie:**
Najłatwiej zacząć od jakości powietrza (GIOŚ), pogody (OpenWeatherMap), rowerów miejskich (Nextbike), parkingów (SmartCity), wydarzeń (Open Data Wrocław) i rozkładów jazdy (GTFS MPK). 