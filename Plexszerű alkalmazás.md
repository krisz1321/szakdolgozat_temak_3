# Plexszerű médiakezelő webalkalmazás

A szakdolgozat témáját úgy választottam ki, hogy abból induljak ki, én magam mit használnék szívesen a hétköznapokban, és mi nővelné számomra kényelmet.  
A mai világban szinte mindenki rengeteg médiatartalmat fogyaszt (videókat, filmeket, sorozatokat, zenéket vagy saját fényképeket).  
Emellett sokan szeretnek maguk tárolni ezeket a tartalmakat. Nem kiszolgáltatni a személyestartalmaikat külső cégeknek, felhőszolgáltatóknak.  

## A probléma

A probléma az, hogy hiába van sok tartalmunk, gyakran nehéz őket rendszerezni és kényelmesen elérni.  
Ha például valaki a telefonján vagy a tévéjén szeretné megnézni a számítógépén tárolt filmet, sokszor bonyolult a fájlok átmásolása, és nem mindig felhasználóbarát a lejátszás.  

## A megoldás

Egy **webes alkalmazás**, amely lehetővé teszi, hogy az otthon tárolt médiatartalmakat (filmek, sorozatok, zenék, képek) könnyedén elérhessük bárhol és bármilyen eszközön.  
A mai okostelefonok, tévék és táblagépek többsége már rendelkezik böngészővel, így logikusnak tűnik, hogy egy webalkalmazás szolgáljon kapuként a médiánkhoz.  

- Egyszerű bejelentkezés után mindenki elérhetné a saját médiatárát.  
- Nem kellene külső felhőszolgáltatásra bízni az adatokat, hanem **biztonságosan otthon maradnának**.  
- Kényelmesebbé, egyszerűbbé és élvezetesebbé tenné a médiatartalmak fogyasztását.  

Ez nemcsak **hasznos**, hanem szakdolgozati szinten is elég **komplex feladat**, mert szükség van backend–frontend kommunikációra, adatbázis kezelésre, streamingre és API integrációra is.

## Tervezett technológiák

- **Backend:** C# 
  - fájlkezelés  
  - videók streamelése  
  - kategorizálás  
  - feliratok kezelése  
  - adatok lekérése a filmekhez (AI-val vagy IMDB-ről lekérni)  

- **Frontend:** Angular  
  - reszponzív, modern webalkalmazás  
  - könnyű navigáció és felhasználói élmény  

- **Adatbázis:** MySQL  
  - felhasználói fiókok  
  - adatok (cím, év, műfaj, borítókép)  
  - feliratok és statisztikák  

## Funkcionalitás

- **Médiafájlok kezelése**  
  - Automatikus adat letöltés (pl. IMDb-ről)  
  - Feliratfájlok kezelése

- **Lejátszás**  
  - Beépített webes lejátszó  
  - Képnézegető (pl: családiképekhez)
 
- **Keresés és kategorizálás**  
  - Gyors keresés cím, műfaj vagy kulcsszó alapján  
  - Kategóriák és szűrők a könnyebb navigációhoz  

- **Felhasználói listák és statisztikák**  
  - „Már megnéztem”, „Még meg akarom nézni”, listák  
  - Nézési szokások követése (mennyi időt töltöttem filmekkel, mit néztem legutóbb)  

## Konkurencia

Természetesen léteznek már hasonló megoldások, mint például:
- A **Plex** nagyon népszerű, viszont sok funkciója csak fizetős előfizetés mellett érhető el, ami sok felhasználónak hátrány.  
- A **Jellyfin** egy nyílt forráskódú alternatíva, ami ingyenes, de sokszor bonyolult a beállítása és a kezelőfelülete sem mindig annyira felhasználóbarát.  

## Miért jó szakdolgozati téma?
Fontos szempont számomra, hogy ez a projekt nemcsak szakdolgozatként állná meg a helyét, hanem később **referencia munkának is nagyon jó lenne**.
A projekt jóval **összetettebb, mint egy egyszerű CRUD alkalmazás**, mert nemcsak adatokat tárol és listáz, hanem valós idejű lejátszást,elérést és kényelmes felhasználói élményt is biztosít.  
Szakmai szempontból szerintem elég komoly kihívást jelent, miközben a mindennapokban is hasznos és érdekes alkalmazás készülhet belőle.
Ezért a kész munka nemcsak az egyetemen, hanem álláskeresésnél vagy portfólióként is hasznos lehetne.
