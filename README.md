# JegkremAPI - DLC Unlocker (v4.5.0.0)

## Jellemzők:

- Lehetőség az ***összes DLC feloldására*** legális megvásárolt/meglévő játék esetében
- Az összes ismert **SteamApps-verzió** támogatása (2-8)
- Az összes ismert **SteamUser verzió** támogatása (9-től 20-ig)
- A **steamclient(64).dll**-t használó játékok támogatása

### Telepítés (x86):

 - Töltsd le és csomagold ki a kívánt DLC-t
 - Nevezd át az eredeti ***steam_api.dll*** fájlt ***steam_api_o.dll***-re
 - Másoljd a ***steam_api.dll*** és ***jegkrem_api.ini*** fájlokat a játék mappájába *
 - Konfiguráld a ***jegkrem_api.ini*** fájlt (*lásd lent a „Konfigurációs megjegyzések” című részt*)


### Telepítés (x64):

 - Töltsd le és csomagold ki a kívánt DLC-t
 - Nevezd át az eredeti ***steam_api64.dll*** fájlt ***steam_api64_o.dll***-re
 - Másold a ***steam_api64.dll*** és ***jegkrem_api.ini*** fájlt a játék mappájába *
 - Konfiguráld a ***jegkrem_api.ini*** fájlt (*lásd lent a „Konfigurációs megjegyzések” című részt*)

> Választhat a naplózó JegkremAPI verzió között (a telepített DLC-k naplózásának lehetőségével), amely a log_build mappában található, és a nem naplózó verzió között, amely a nonlog_build mappában található.

### Konfigurációs megjegyzések:

- Egyes játékoknak van egy speciális ellenőrzése a ***steam_api.dll/steam_api64.dll*** fájlhoz, így ha módosítják, a játék már nem indul el (*pl. Magicka*) (egyes játékok azt is ellenőrzik, hogy van-e *.ini fájl a könyvtárban).
  - Ahhoz, hogy ilyen játékokat tudj játszani unlockerrel, az "***extraprotection***" opciót "***true***"-ra kell állítania.
   - Ne feledd, hogy egyes játékok továbbra sem működnek (*pl. Serious Sam HD: TFE/TSE*), ha a vártnál több egyéni ellenőrzést végeznek.
- Egyes játékok támogatják az automatikus DLC-feloldást, így beírhatod: ***unlockall = true***, és minden DLC fel lesz oldva.


## [Itt találod a Változtatásokat [changelog]](https://github.com/palicz/jegkrem-api/blob/main/changelog.md)
## [Itt találod a Gyakori kérdéseket [faq]](https://github.com/palicz/jegkrem-api/blob/main/faq.md)

### ***Jelszó: zenzty***
