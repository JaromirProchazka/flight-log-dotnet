# FlightLogNet

Jednoduchá aplikace pro evidenci letů na malém letišti.

## Run

Aplikaci lze spustit přez `dotnet build .\FlightLogNet\FlightLogNet.csproj`/`dotnet run .\FlightLogNet\FlightLogNet.csproj`, případně přez docker kontejner.

## Funkce

- evidence vzletů a přistání
- správa pilotů a letadel
- přehled historie letů
- export dat do CSV

## Důležité Soubory

- **FlightLogNet.Tests/** obsahuje unit a integrační testy
- **FlightLogNet/** obsahuje kód backendu
- **frontend/** obsahuje kód frontendu

- **API_doc.md** obsahuje dokumentaci REST API aplikace FlightLogNet
- **Dockerfile** a **docker-compose.yml** pro spuštění skrze docker
