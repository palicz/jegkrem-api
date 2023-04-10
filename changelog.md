## Változási napló

- v4.5.0.0 hotfix:
  - Javítva az "unlockall" opció

- v4.5.0.0:
  - Támogatás hozzáadva a legújabb Steamworks SDK v1.50-hez (API verzió: 6.6.99.59)
  - Megváltoztattuk a feldolgozási módszert, hogy megkapjuk az helyes függvénymutatót
  - Javítva az interfész olvasó funkciója
  - Egyes játékok összeomlása javítva

- v4.4.0.0:
  - Teljes UTF-8 támogatás hozzáadva
  - A hiányzó SteamAPI exportok hozzáadása
  - Továbbfejlesztett naplóformátum
  - Eltávolítottuk a törött dolgokat a Monster Hunter Worldből (hamarosan érkezik egy speciális JegkremAPI verzió)

- v4.3.1.0:
  - Hozzáadott támogatás a "GetInstalledDepots" funkcióhoz (szükséges a Halo DLC feloldásához)
  - A teljes útvonalméret ellenőrzése hozzáadva
  - Kibővített "extraprotection" rendszer a Monster Hunter World számára

- v4.3.0.0:
  - Támogatás hozzáadva a legújabb Steamworks SDK v1.48-hoz (API verzió: 5.69.73.98)
  - Kijavítottuk azt a hibát, amikor a játék összeomolhatott vagy lefagyott, amikor megpróbálta meghívni a Steam játékszerver funkcióit (a Hearts of Iron IV ismét működik)
  - Kisebb kiegészítések az "extraprotection" rendszerhez
  - Kisebb kiegészítések a naplózási könyvtárban

- v4.2.1.0:
  - Kibővített "extraprotection" rendszer
  - Kisebb hibák javítása

- v4.2.0.0:
  - Támogatás hozzáadva a legújabb Steamworks SDK v1.47-hez (API verzió: 5.53.33.78)
  - Javítva az összeomlás az "unlockall" opció használatakor (a legújabb Steam felhasználói felület használata esetén számít)
  - Kezdeti kód előkészítése a Linux támogatáshoz (hamarosan)

- v4.1.1.0 hotfix:
  - Javítottuk a hibás SteamApps interfész mutatót a régebbi játékokhoz

- v4.1.1.0:
  - Javítva a "nyelv" opció
  - Javítottuk a hibás mutatókat a "SteamInternal_FindOrCreateUserInterface" függvényben
  - Egyéb kisebb hibajavítások

- v4.1.0.0:
  - Támogatás hozzáadva a legújabb Steamworks SDK v1.46-hoz (API verzió: 5.25.65.21)
  - Az "unlockall" opció most megfelelően lekéri a DLC-információkat a Steam szerverekről (ne feledd, hogy a "[dlc]" részt NEM szabad kitölteni, ha ezt az opciót használja)
  - Apró kódjavítások

- v4.0.0.0:
  - Az Unlocker kód teljesen megújult (Hello C++17)
  - A rakodó most teljesen más
  - Támogatás hozzáadva a legújabb Steamworks SDK v1.44-hez (API verzió: 4.95.20.30)
  - A logger könyvtárat egy kisebbre cserélték
  - Eltávolították a [steam_wrapper], [dlc_installdirs] és [steam_ugc] szakaszokat (igen, nincs több támogatás a wrapper funkcióhoz. Kérlek, ne kérdezd, miért)
  - Eltávolította a következő beállításokat: "installdir", "dlcasinstalldir", "disableutilsinterface", "disableregisterinterfacefuncs", "unlock parentalrestrictions", "steamid", "signaturebypass", "printbacktrace"

- v3.4.1.0:
  - Hozzáadott "disableregisterinterfacefuncs" opció (ha ezt az opciót "true"-ra állítod, az Injustice 2 újra működik)
  - Eltávolítva a "callbackstype" opciót
  - Javítva néhány belső visszahívási funkció és exportálás
  - Egyéb kisebb hibajavítások

- v3.4.0.0:
  - Hozzáadott "saveindirectory", "forcefullsavepath" és "callbackstype" opciók
  - Továbbfejlesztett belső naplóformátum
  - Javítva a probléma, amikor a belső visszahívási rendszer blokkolt néhány fő többjátékos funkciót, beleértve a ranglistákat (Tekken 7, Injustice 2, Borderlands 2 stb.)
  - Javítva az időnként előforduló memóriatúlcsordulási probléma
  - Javítva a "g_pSteamClientGameServer" és a "g_pSteamClientGameServer" mutatók
  - Javítva néhány belső fájltárolási funkció
  - Javítva néhány belső visszahívási funkció
  - Egyéb kisebb hibajavítások és fejlesztések

- v3.3.0.0:
  - Hozzáadott új lakásexport
  - "Achievementscount" opció hozzáadva
  - Fokozott ainterfész elemző rendszer
  - Néhány kódrész átdolgozása jobb optimalizálást eredményezett
  - Javítva a Civilization VI és a LEGO Marver Super Heroes 2 összeomlása
  - Javítva a probléma, amikor a belső visszahívási rendszer blokkolt néhány létfontosságú többjátékos funkciót
  - Módosult a "vásárlási időbélyeg" opció alapértelmezett értéke
  - Egyéb kisebb hibajavítások és fejlesztések

- v3.2.0.0:
  - Hozzáadott UGC (műhely) támogatás a burkoló módhoz
  - A [steam_ugc] szekció hozzáadva az előfizetett műhelytárgyak kezeléséhez
  - Hozzáadott "wrapperugc" és "printbacktrace" opciók
  - Javítva az "installdir" beállítás elírása a jegkrem_api.ini fájlban (.\" - "..\")
  - Az interfészkereső rendszer teljesen megújult (most kétszer gyorsabb)
  - Javítva a Sid Meier's Civilization V összeomlást
  - Kijavítottuk az összeomlást néhány játéknál a burkoló mód használatakor
  - Kisebb javítások a naplózási rendszerben (beleértve a formázást is)
  - Egyéb kisebb hibajavítások

- v3.1.1.0:
  - Az "extraprotection" teljesen megújult, és most még több játékot támogat (pl. Injustice 2)
  - Hozzáadott "vásárlási időbélyeg" és "visszahívások letiltása" opciók
  - A "forceuserdatafolder" opció eltávolítva
  - Javítottunk néhány rossz mutatót a lapos függvényekre
  - Javítottuk a váratlan összeomlást néhány játéknál (Tekken 7, Mighty No. 9, Life is Strange, Naruto sorozat)
  - Kijavítottuk azt a problémát, hogy a DLC nem oldódott fel a NARUTO SHIPPUDEN Ultimate Ninja STORM 4-en
  - Frissített naplózási könyvtár
  - Kisebb javítások a visszahívási rendszeren

- v3.1.0.0 hotfix:
  - Javítva a "nyelv" opció
  - Kijavítottuk a SteamAPI_RegisterCallResult váratlan viselkedése miatti összeomlást néhány játéknál

- v3.1.0.0:
  - Frissített felületek a legújabb API-verzióra (4.4.91.85)
  - ISteamParentalSettings interfész támogatás hozzáadva
  - "SteamGameServerInternal_CreateInterface", "SteamInternal_GlobalContextGameServerPtr", "g_pSteamClientGameServer_Latest" exportok hozzáadva
  - Hozzáadott "dlcasinstalldir", "unlockparentalrestrictions", "steamid", "signaturebypass" opciók
  - Hozzáadott [dlc_installdirs] szakasz a DLC telepítési könyvtárainak kezeléséhez
  - Néhány opció most a [steam_misc] részben található
  - A naplózó rendszer most már támogatja a többszálú feldolgozást
  - Javítottunk néhány lehetséges memóriaszivárgást
  - Javítva a hibaüzenetek kezelője
  - Javítottunk néhány mutatót
  - Kisebb kódtisztítások
  - Kisebb hibajavítások
  - Továbbfejlesztett/bővített visszahívás-kezelő
  - A legtöbb belső tároló funkciót STL/modern fájlrendszer könyvtár használatával újrakódoltuk

- v3.0.0.3 hotfix:
  - Javítva a SteamInternal_CreateInterface mutató

- v3.0.0.3:
  - Hozzáadott Steam lapos export
  - Két új lehetőség hozzáadva: "forceuserdatafolder", "lowviolence"
  - Frissített SteamClient017 felület
  - Több játék összeomlásának javítása (Killing Floor, Warhammer Vermintide)
  - Javított általános indulási sebesség
  - Kisebb hibajavítások

- v3.0.0.2:
  - Hozzáadott "disableuserinterface" és "disableutilsinterface" opciók
  - Kisebb hibajavítások

- v3.0.0.1 hotfix:
  - Javítva a "nyelv" opció
  - Javítva a dlcById funkciómutató a SteamApps v7-ben, amely problémát okozott egyes DLC-k feloldásakor
  - Kicsit megváltoztattuk a naplózó formátumát

- v3.0.0.1:
  - A "forceoffline" opció hozzáadva
  - A "storestatscallback" opció hozzáadva
  - Kijavítottuk a visszahívásokkal kapcsolatos problémát egyes játékokban

- v3.0.0.0:
  - Az Unlocker kód teljesen megújult
  - Teljesen megváltozott a DLC kezelés (most így néz ki: dlc_id = dlc_description)
  - Az interfészek észlelési módszere most sokkal gyorsabb
  - Mostantól a DLC megfelelően feloldható a következő játékokban: Shadow Warrior 1+2 (esetleg be kell kapcsolni a Steam offline módot), Dead Rising 4, Naruto sorozat
  - Hozzáadtuk a belső visszahívási rendszert a wrapper módhoz (kreditek: Painter és Tihiy)
  - Hozzáadtuk a belső tároló/statisztikai rendszert a wrapper módhoz (kreditek: Painter)
  - Lecseréltük a naplózó könyvtárat (újra, most már teljesen threading-safe)
  - Eltávolították az "extraprotectionlevel" opciót, most az Unlocker önmagában határozza meg
  - Eltávolították az "emudll", "loademu", "wrapperutils", "wrappercallbacks" kulcsokat

- v2.0.0.7:
  - A [dlc_timestamp] szakasz hozzáadva a DLC vásárlási dátumának időbélyegének kezeléséhez (unix formátum)
  - Kibővített "extravédelem" a jövőbeni célokra
  - Kicserélték a logger könyvtárat
  - Hozzáadott naplózó és nem naplózott JegkremAPI buildek
  - Hozzáadott támogatás a 3.62.82.82 SteamAPI verzióhoz
  - Kisebb hibajavítások

- v2.0.0.6 hotfix:
  - Javítva a naplózó könyvtár okozta összeomlás
  - A "newappid" és az "emudll" opciók most a "steam_wrapper" részben találhatók
  - "Nyelv" opció hozzáadva (opcionális)
  - Hozzáadott "loademu", "wrapperremotestorage", "wrapperuserstats", "wrapperutils" és "wrappercallback" opciók
  - Hozzáadott támogatás a 3.45.58.40 SteamAPI verzióhoz

- v2.0.0.6:
  - Kód optimalizálás
  - Hozzáadtuk a könnyű csomagoló módot
  - Hozzáadott "extraprotectionlevel" opció
  - Javítottunk néhány hibás mutatót
  - Javítottuk a logger könyvtárat
  - Különféle hibajavítások

- v2.0.0.5:
  - A kódot alapoztuk át, hogy megfelelő interfészverziót kapjon
  - Javítva az új SteamAPI verzió támogatása
  - Kisebb hibajavítások

- v2.0.0.4:
  - Hozzáadott támogatás a SteamApps v8 interfészhez
  - Új SteamAPI exports
  - Eltávolítottuk a haszontalan struct/flat exportokat
  - Továbbfejlesztett "extravédelem" (most a Serious Sam 3 és a The Talos Principle is működik)

- v2.0.0.3 hotfix:
  - Javítva a hiba, amikor az "extraprotection" nem működött egyes játékoknál
  - Javítottuk a konfigurációs fájl betöltését

- v2.0.0.3:
  - Hozzáadott támogatás azokhoz a játékokhoz, amelyek a steam_api.dll/steam_api64.dll módosítás(oka)t ellenőrzik ("extravédelem" opció)
  - jegkrem_api.ini elrejtés hozzáadva ("extraprotection" opció)
  - Kisebb hibák javítása

- v2.0.0.2 hotfix:
  - Javítva a probléma, amikor a naplózó létrejött, még akkor is, ha az érték "false" volt.
  - Megváltoztattuk a naplózó működését
  - A konfigurációs fájl jobb betöltése
  - Az "appid" opció ellenőrzése hozzáadva
  - Hozzáadott "orgapi" és "orgapi64" opciók

- v2.0.0.2:
  - Hozzáadott "appid" opció
  - Hozzáadott [dlc_subscription] szakasz
  - "napló" opció hozzáadva a [steam] részhez
  - A "subscribed" opció eltávolítva
  - Különféle hibajavítások

- v2.0.0.1:
  - Eltávolítottuk a SteamApps kulcsot a jegkrem_api.ini fájlból (a SteamApps verziót a rendszer most automatikusan elemzi az eredeti fájlból)
  - Eltávolítottuk a Language kulcsot a jegkrem_api.ini webhelyről (a nyelvet most közvetlenül a Steam alkalmazás beállításaiból értelmezi)
  - A steamclient.dll fájlt használó játékok támogatása
  - Különféle hibajavítások

- v1.0.0.1 hotfix:
  - Javítottunk egy hibát a nyelvi opcióval
