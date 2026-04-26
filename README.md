Tabela veličina:

Analogni ulaz 2100 Nivo vode u rezervoaru, izražen u litrima.
STOP Digitalni izlaz 4400 Stanje STOP prekidača (uključen/isključen - eng. ON/OFF)
Ventil V1 Digitalni izlaz 4402 Stanje ventila (otvoren/zatvoren – eng. ON/OFF)
P1 Digitalni izlaz 4405 Stanje P1 prekidača (uključen/isključen – eng. ON/OFF)
P2 Digitalni izlaz 4406 Stanje P2 prekidača (uključen/isključen - eng. ON/OFF)
N1 Analogni izlaz 4300 Napajanje motora pumpe

U konfiguracionoj datoteci “RtuCfg” definisati sledeće:

RTU slave adresa je 44
Koristi se TCP transportni protokol i port 44376
Definisati digitalne izlaze (coils) prema tabeli veličina, sa podrazumevom vrednošću nula. Pri tome, neophodno je proširiti
konfuguracionu datoteku “RtuCfg.txt” sa sledećim parametrima primenjivim samo za digitalne veličine.

Zadatak:
Eliminacioni:
● Podesiti komunikacione parametre u dCom aplikaciji i u simulatoru tako da TCP veza može da se ostvari.
● Pravilno konfigurisati datoteku “RtuCfg.txt” u skladu sa zadatim veličinama u sistemu i njihovim
vrednostima.
Prema definisanoj konfiguraciji periodično očitavati sve digitalne izlaze (coils) i osvežavati vrednosti na

korisničkom interfejsu.

Prema definisanoj konfiguraciji periodično očitavati sve analogne izlaze (holding registers) i osvežavati vrednosti

na korisničkom interfejsu.

Omogućiti komandovanje kroz kontrolni prozor za sve definisane digitalne izlaze (coils) i nakon uspešnog upisa

osvežavati vrednosti na korisničkom interfejsu.

Omogućiti komandovanje kroz kontrolni prozor za sve definisane analogne izlaze (holding registers) i nakon uspešnog

upisa osvežavati vrednosti na korisničkom interfejsu.

Prema definisanoj konfiguraciji periodično očitavati sve digitalne izlaze/ulaze i osvežavati vrednosti na korisničkom

interfejsu svake 2 sekunde

Prema definisanoj konfiguraciji periodično očitavati sve analogne izlaze/ulaze i osvežavati vrednosti na korisničkom

interfejsu svake 4 sekunde
