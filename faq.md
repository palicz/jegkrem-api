# Gyakran ismételt kérdések

`1. "Mi az a JegkremAPI?"`
- A JegkremAPI a ***zenzty*** által módosított Steam API (steam_api.dll (32-bit) / steam_api64.dll (64-bit)), amely lehetővé teszi a felhasználók számára, hogy feloldják a DLC-ket a legálisan birtokolt Steam-játékokon.

`"Mi a JegkremAPI jelenlegi verziója?"`
- A jelenlegi verziót folyamatosan megtalálod [itt](https://github.com/palicz/jegkrem-api/blob/main/README.md).

`2. "Mi az oka annak, hogy egyes játékok nem használhatják a JegkremAPI-t?"`
- Túl sok egyéni ellenőrzés a játék indításakor.
- Csalás elleni védelem (EasyAntiCheat (EAC), BattlEye stb.).

`3. "„Egyéb” hibákat kapok, amikor a JegkremAPI-t EAC/BattlEye használatával próbálom ki egy játékon."`
- A JegkremAPI általában nem működik olyan játékokon, amelyek csalás elleni védelmet használnak.

`4. "Tudsz bypass-t biztosítani olyan játékok számára, amelyek általában nem működnek a JegkremAPI-val? Pl.: Dead by Daylight"`
- Nem

`5. "Ki tilthatnak a JegkremAPI használata miatt?"`
- Még senki nem jelentette, hogy kitiltották volna a JegkremAPI használata miatt. Ennek ellenére, folyamatosan fenn áll a veszélye, valóban alacsony rá az esély, de soha sem nulla.

`6. "Kipróbáltam egy Unreal Engine 4-es játékot JegkremAPI-val. És` [ezt](https://imgur.com/CXQsiAE) `a hibát kaptam."`
- Használd [ezt](https://imgur.com/a/DXAMvc3) referenciaként.

`7. "Minden Unreal Engine-t használó játéknak előre telepítve van a DLC-je?"`
- Nem feltétlenül. Egyes játékokban az összes DLC egy .pak fájlban található, és a hozzáféréshez logikai triggert kell aktiválni a JegkremAPI-val. De néhány játék tényleges fájlokat igényel a DLC-hez.

`8. "Van néhány DLC-m, amiket megosztanék. Milyen weboldalat tudnál ajánlani?"`
- Én személy szerint a Google Drive-ot részesítem előnyben, mivel a Mega 5 GB-os letöltési korláttal rendelkezik, és 5 órát kell várni, amíg visszaáll. A Google Drive-nak is van korlátja, ha a fájlt túl sokszor nézték meg vagy töltötték le. De könnyen [megkerülhető](https://www.youtube.com/watch?v=Qlt9QhXaWSM).

`9. "Meg kell várnom, amíg valaki beküld egy DLC letöltési linket egy adott játékhoz?"`
- Egyáltalán nem. Rengeteg [webhely](https://cs.rin.ru/forum/viewtopic.php?f=10&t=95461) van, amelyek segítségével megtalálhatod, amit keresel

`10. "Mit jelent, ha egy játék DLC-je „előre telepített”?"`
- Ez azt jelenti, hogy a játék összes DLC-je (vagy egy része) az eredeti telepítéssel érkezik (ezért is hatalmas néhány játék alapfájl mérete, ha sok DLC van, jó példa erre a [Payday 2.](https://steamdb.info/app/218620/depots/)) anélkül, hogy meg kellene vásárolnod bármi extrát. Ez azt is jelenti, hogy csak fel kell oldania a DLC-ket úgy, hogy csak hozzáadja indexeiket a jegkrem_api.ini fájlhoz. Egyes játékoknál a kísérleti „unlockall” funkciót „true” értékre kell állítani a DLC-k feloldásához, ha az indexek hozzáadása nem működik.

`11. "Amikor a JegkremAPI-t használom, a jogszerűen birtokolt DLC-k nincsenek feloldva. Miért?"`
- Továbbra is indexelni kell a Steamen keresztül jogszerűen birtokolt DLC-t. Ha nem, akkor nem lesz feloldva.

`12. "Amikor hozzáadom egy játék Season Pass-ját a DLC részhez. Semmi sincs feloldva."`
- Ha egy játék Season Pass-ja a Steamen keresztül működik, akkor a fejlesztő által a játékhoz kiadott új tartalom automatikusan az te tulajdonodba kerül. Csak a Season Pass hozzáadása nem old fel mindent a JegkremAPI-n keresztül. Manuálisan kell hozzáadni minden egyes feloldani kívánt DLC-t.

`13. "Mennyi DLC-t tudok feloldani egy játékhoz?"`
- Limit nélkül mindet.

`14. "Használhatom a JegkremAPI-t játékokhoz az Epic Games kliensen?"`
- Nem. Jelenleg is készülünk egy külön API-val ami kifejezetten az Epic Games-hez lesz konfigurálva.
