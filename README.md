# Express environments

Mit environment variables können wir das Verhalten unserer Anwendung konfigurieren.

## Konstante Werte
* Schreibe einen Endpunkt `GET /multiply/:number`. 
* Benutze eine Env Variable `MULTIPLIKATOR`.  
* Der Endpunkt soll das Ergebnis von `number * MULTIPLIKATOR` zurückliefern.

## Logging Middleware
* Schreibe eine widdleware, die die aktuelle Route auf dem Terminal augibt.
* Das logging soll nur eingeschaltet sein, wenn eine Env Variable `DEBUG` auf true steht.

## Teil 2 - Dotenv
### installiere dotenv
Benutze npm um das dotenv Paket zu installieren.  
Paket & Anleitung: https://www.npmjs.com/package/dotenv

### Variablen in die .env Datei
schreibe die Werte für die Env variablen (MULTIPLIKATOR, DEBUG) in die .env-Datei.