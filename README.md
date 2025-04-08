# Flight Search App #

Ovo je aplikacija koja se sastoji od dva dijela:
- Backend: ASP.NET Core Web API (`FlightSearchV1`)
- Frontend: React aplikacija (`FlightSearchApp`)

Kako pokrenuti aplikaciju?

### 1. Priprema

1. Unzip-ujte oba projekta:
   - `FlightSearchV1` (backend)
   - `FlightSearchApp` (frontend)

2. Otvorite projekte:
   - `FlightSearchV1` otvorite u **Visual Studio**
   - `FlightSearchApp` otvorite u **VS Code**



### 2. Backend konfiguracija (`FlightSearchV1`)

1. Registrujte se na [Amadeus Developer Portal](https://developers.amadeus.com/), napravite aplikaciju i dobit cete:
   - Client ID
   - Client Secret

2. U Visual Studio-u, otvorite fajl `appsettings.json` unutar `FlightSearchV1` projekta i unesite dobijene vrijednosti na odgovarajuća mjesta.

3. Idite na: Tools > NuGet Package Manager > Package Manager Console

4. U konzolu upišite: dotnet ef database update

5. Pokrenite projekat.



### 3. Frontend konfiguracija (`FlightSearchApp`)

1. Otvorite terminal u VS Code: Terminal > New Terminal

2. Instalirajte potrebne pakete: npm install

3. Pokrenite frontend aplikaciju: npm run start



### 4. Ako naiđete na probleme, provjerite:
- Da li su Client ID i Client Secret ispravno uneseni
- Da li je backend uspješno pokrenut i baza migrirana
- Da li je frontend instalirao sve pakete bez grešaka


