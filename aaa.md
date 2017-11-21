
# Cieľom projektu je :

 1.	Vytvorenie dokumentu Analýza rizík, ktorý bude obsahovať identifikované bezpečnostné riziká, ktoré sú závislé od aktív systému, ich zraniteľností, vplyvov prostredia (hrozby) a potenciálneho negatívneho dopadu (dopadov) na ministerstvo. Súčasťou dokumentu analýza rizík je:
	- Analýza rizík - podrobná správa, ktorá obsahuje identifikáciu:
		- aktíva a ich vlastníkov [^1] - zoznam aktív je špecifikovaný na úroveň jednotlivých technických komponentov[^2], údajových štruktúr[^3], miestností[^4] a pod., úložísk[^5],
		- osobných údajov – opis spracovateľských operácií[^6], účel spracovania[^7], oprávnený záujem na ich spracovaní (právny titul)[^8], kategória[^9], typ[^10], štruktúra[^11] atd., kategórie príjemcov[^12], ktorým sú alebo budú údaje prístupné[^13], lehoty pre výmaz jednotlivých kategórií údajov[^14], role[^15], povinnosti a oprávnenia pri spracovaní osobných údajov (riadenie prístupu)[^16],
		- prenosu /transferu osobných údajov v a medzi informačnými systémami[^17], 
		- prevádzkovateľov  a sprostredkovateľov osobných údajov[^18], 
		- rizík, ktoré majú dopad na aktíva - návrh sa riadenie rizík, pričom spôsob realizácie nemusí byť predikovateľný (t. j. nemusí byť určené, či správa rizika bude realizovaná organizačným alebo technickým opatrením, či prenos rizika bude znamenať poistenie alebo outsourcing a pod.),
		- hrozieb využívajúce zraniteľnosti aktív, ohodnotenie pravdepodobnosti naplnenia hrozieb, pričom stupnica hodnotenia je delená do minimálneho počtu úrovní tak, že stupne hodnotenia musia umožniť účelne rozlíšiť rozdiely v sile hrozby (pri hodnotení pravdepodobnosti naplnenia hrozby s použitou stupnicou by nemalo dôjsť k váhaniu pri výbere medzi viac ako 2 stupňami hodnotenia), návrhy penetračných testov
		- existujúcich opatrení,
		- zraniteľnosti zvyšujúcich bezpečnostné riziká - určenie zraniteľností aktív, pričom stupnica hodnotenie je delená do minimálneho počtu úrovní tak, že stupne hodnotenia musia umožniť účelne rozlíšiť rozdiely v úrovni zraniteľnosti (pri hodnotení zraniteľnosti by nemalo dôjsť k váhaniu pri výbere medzi viac ako 2 stupňami hodnotenia),
		- následkov dopadu jednotlivých hrozieb na aktívum – detailný popis možných dopadov na organizáciu  v dôsledku narušenia dôvernosti, integrity alebo dostupnosti údajov a komponentov systému,
	- návrh na ošetrenie rizík,
		- so zreteľom na povahu, rozsah a účel spracúvania osobných údajov ako aj na riziká, ktoré sú so spracúvaním spojené posúdenie, nutnosti a primeranosti spracovateľských operácií vo vzťahu k účelu, ako aj posúdenie rizika pre práva a slobody jednotlivcov, návrh na primerané technické a organizačné opatrenia pre každú formu spracúvania osobných údajov.
		- návrh stratégie riešenia havarijných stavov vrátane identifikácie kontaktného miesta pre dozorný orgán, mechanizmu nahlasovania incidentov a hrozieb, poskytovania poradenstva prevádzkovateľovi.
	- Katalóg aktív, identifikované aktíva rozdelené do skupín umožňujúce analyzovať jednotlivé subsystémy z rôznych pohľadov v závislosti na hodnotených skupinách aktív.
	- Manažérske zhrnutie výsledkov – hodnotenie, odporúčania a návrh opatrení.

1.	Nástroj na manažment rizík a evidenciu aktív
Obsahom nástroja na zvládanie rizík a evidenciu aktív budú spracovateľné dáta obsahujúce: 
	- Katalóg aktív z pohľadu jednotlivých :
		- i.	Aktív
		- ii.	Procesov  
		- iii.	Závislosti jednotlivých aktív navzájom,  identifikovaných v dokumente Analýza rizík podľa bodu 1.
	- Katalóg rizík a súbory pripravené na zaznamenávanie a vyhodnotenie zmien v rizikách 
	- Metriky a pripravené súbory na hodnotenie metrík
	- Šablóny na vytvorené reportov zo spracovaných informácii
	- Vytvorené reporty zo spracovaných informácii.

2.	Zaškolenie zamestnanca/ov Ministerstva financií Slovenskej republiky zodpovedných za informačnú bezpečnosť a ochranu osobných údajov na Ministerstve financií Slovenskej republiky do vyššie uvedených procesov a vykonávania analýzy rizík. Pomôcky a dokumenty použité pri procesoch riadenia rizík budú po zaškolení odovzdané manažérovi bezpečnosti ministerstva, čím sa vytvorí nástroj na systém manažmentu rizík. 


[^1]: 
    aktíva a ich vlastníci

     - Realizované
     - Doba vyniku akt=iva
     - 
     - Aktíva sú uvedené v tabuľke Katalóg aktív
     - K aktívam sú evidovaný používatelia. Jedno aktívum môžu používať viacerí používatelia.
     - Vlastníci sú v nej v stĺpci Názov aktíva, Stĺpec Skupina Aktíva zoskupuje aktíva do logických skupín typicky Moduly informačného systému. A každé aktívum môže mať iba jedného vlastníka
[^2]: 
    úroveň jednotlivých technických komponentov
    
    - Realizované
    - Aktíva sú realizované ako komponenty ktoré realizujú samostatnú logickú oblasť funkčnosti.
[^3]: 
    údajových štruktúr
    
    - Nerealizované - 
    - Možné realizovať dátami s bezpečnostných projektov
    	- otázka je či existujú aj v elektronickej podobe
[^4]: 
    miestností[^4] a pod.
    
    - Realizované
    - Úroveň je realizovaná v koncepte sledovania zón v ktorých sa fyzicky aktívum vyskytuje. Tieto zóny vstupujú do BCM ako jednotlivé ucelené celky pre obnovu funkčnosti.
[^5]: 
    úložísk
    
    - Zatiaľ nerealizované
    	- možné realizovať synteticky ako číselník úložísk v lokalite
[^6]: 
    opis spracovateľských operácií
[^7]: 
    účel spracovania

     - Realizované
     
```Gherkin
     ID	Index	Spôsob získania OÚ
     7	a	Súhlas osoby
     8	b	Nevyhnutné na plnenie zmluvy
     9	c	Nevyhnutné na splnenie zákonnej povinnosti prevádzkovateľa
     10	d	Ochrana životne dôležité záujmy dotknutej osoby alebo inej fyzickej osoby
     11	e	Vo verejnom záujme alebo pri výkone verejnej moci
     12	f	Na účely oprávnených záujmov, ktoré sleduje prevádzkovateľ alebo tretia strana
```


[^8]: 
    oprávnený záujem na ich spracovaní (právny titul)

     - Realizované
     - nutné rozhodnúť či to budeme riešiť podľa používateľov aktíva alebo vlastníkov
[^9]: 
    kategória OU

     - Realizované
     - Číselník *D-cis_OU_Typy*
     - nutné rozhodnúť či to budeme riešiť podľa používateľov aktíva alebo vlastníkov
[^10]: 
    typ OU

     - Realizované 
     - v číselníku D-cis_OU_Typy stĺpec Citlivosť je uvedený typ OU s koeficientom citlivosti
[^11]: 
    štruktúra OU
    
    - Nerealizované - 
    - Možné realizovať dátami s bezpečnostných projektov
    	- otázka je či existujú aj v elektronickej podobe
[^12]: 
    kategórie príjemcov

    - Zatiaľ nerealizované
    - g) príjemcom každý, komu sú osobné údaje poskytnuté alebo sprístupnené, pričom príjemcom môže byť aj tretia strana; prevádzkovateľ, ktorý spracúva osobné údaje na základe § 3 ods. 1 písm. g), a úrad, ktorý plní úlohy ustanovené týmto zákonom, sa nepovažujú za príjemcu.
    - "§ 4 ods. 2 písm. g) zákona č. 122/2013 Z. z. - znenie predpisu od 01.06.2017":[http://www.epi.sk/zz/2013-122/znenie-20170601#p4-2-g]
[^13]: 
    ktorým sú alebo budú údaje prístupné

    - Používatelia IS
[^14]: 
    lehoty pre výmaz jednotlivých kategórií údajov
    
    - Zatiaľ nerealizované
[^15]: 
    role

    - OUT off Scope
[^16]: 
    povinnosti a oprávnenia pri spracovaní osobných údajov (riadenie prístupu)

     - Zatiaľ nerealizované
[^17]: 
    prenosu /transferu osobných údajov v a medzi informačnými systémami

     - Realizované
     - v tabuľke [Katalóg aktív - Rozhrania]

[^18]: 
    prevádzkovateľov  a sprostredkovateľov osobných údajov

    - Realizované
    - Pridaná tabuľka Katalog Aktiv - Detail1
```SQL
SELECT [Katalog Aktiv - Detail1].prevádzkovateľ, Count([Katalog Aktiv - Detail1].[Názov aktíva]) AS [CountOfNázov aktíva]
FROM [Katalog Aktiv - Detail1]
GROUP BY [Katalog Aktiv - Detail1].prevádzkovateľ;

```

```
     prevádzkovateľ	CountOfNázov aktíva
     NULL	9
     ARDAL	1
     Daňové riaditeľstvo SR	1
     DataCentrum	2
     ENISA	1
     Európska komisia	8
     Google	1
     IANA	1
     IBFD	1
     IP Viedeň	1
     MF SR	134
     Ministerstvo spravodlivosti SR	1
     NAR marketing s.r.o.	1
     Národná agentúra pre sieťové a elektronické služby	1
     NBÚ	1
     OECD, MMF, EIB, EBOR, RBRE, MIB, MBHS a Svetová banka	1
     Profesia, spol. s r.o.	1
     Rada Európy	1
     S-EPI, s. r. o. 	1
     Squire Patton Boggs	1
     Štátna pokladnica	2
     Úrad pre finančný mechanizmus, Brusel	1
     Úrad pre verejné obstarávanie	1
     Úrad vlády SR	3
     VUJE, a.s.	1
     Wolters Kluwer s. r.o.	1
```
    - prevádzkovateľom 
    	- "§ 4 ods. 2 písm. g) zákona č. 122/2013 Z. z. - znenie predpisu od 01.06.2017":[http://www.epi.sk/zz/2013-122/znenie-20170601#p4-2-g]
    - sprostredkovateľ
    	- "§ 4 ods. 2 písm. g) zákona č. 122/2013 Z. z. - znenie predpisu od 01.06.2017":[http://www.epi.sk/zz/2013-122/znenie-20170601#p4-2-g]

# _s-01 - Potvrdenie vlastnictva
```sql
SELECT [Katalóg aktív].Vlastník, [Katalóg aktív].[Skupina Aktíva], [Katalóg aktív].[Názov aktíva], False AS [Som vlastnik] 
INTO [_s-01 - Potvrdenie vlastnictva]
FROM import_OrgChart INNER JOIN [Katalóg aktív] ON import_OrgChart.[Organizačný útvar] = [Katalóg aktív].Vlastník
ORDER BY [Katalóg aktív].Vlastník, [Katalóg aktív].[Skupina Aktíva], [Katalóg aktív].[Názov aktíva];
```

# _s-01-a - Potvrdenie vlastnictva Externy vlastnici
```sql
SELECT [Katalóg aktív].Vlastník, [Katalóg aktív].[Skupina Aktíva], [Katalóg aktív].[Názov aktíva], False AS [Som vlastnik] 
INTO [_s-01-a - Potvrdenie vlastnictva Externy vlastnici]
FROM import_OrgChart
RIGHT JOIN [Katalóg aktív] ON import_OrgChart.[Organizačný útvar] = [Katalóg aktív].Vlastník
WHERE (((import_OrgChart.[Organizačný útvar]) IS NULL))
ORDER BY [Katalóg aktív].Vlastník, [Katalóg aktív].[Skupina Aktíva], [Katalóg aktív].[Názov aktíva];
```
# _s-02 - Používatelia aktíva
```sql
SELECT [Katalóg aktív].Vlastník, [Katalóg aktív].[Skupina Aktíva], [Katalóg aktív].[Názov aktíva], [Aktíva - používatelia].Používateľ, "Áno" AS [Je používateľom] 
INTO [_s-02 - Používatelia aktíva]
FROM [Katalóg aktív] INNER JOIN [Aktíva - používatelia] ON [Katalóg aktív].[Názov aktíva] = [Aktíva - používatelia].[Názov aktíva]
ORDER BY [Katalóg aktív].Vlastník, [Katalóg aktív].[Skupina Aktíva], [Katalóg aktív].[Názov aktíva], [Aktíva - používatelia].Používateľ;
```
# _s-03-Spracovávané OU v aktívach
```sql
SELECT [Katalóg aktív].Vlastník, [Katalóg aktív].[Skupina Aktíva], [Katalóg aktív].[Názov aktíva], [D-cis_OU_Typy].[Druh OD], "NIE" AS [Aktivum spracovava OÚ] 
INTO [_s-03-Spracovávané OU v aktívach]
FROM [D-cis_OU_Typy], import_OrgChart INNER JOIN [Katalóg aktív] ON import_OrgChart.[Organizačný útvar] = [Katalóg aktív].Vlastník
ORDER BY [Katalóg aktív].Vlastník, [Katalóg aktív].[Skupina Aktíva], [Katalóg aktív].[Názov aktíva];
```
# _s-04-OU účely spracovania

```sql
SELECT [Katalóg aktív].Vlastník, [Katalóg aktív].[Skupina Aktíva], [Katalóg aktív].[Názov aktíva], [D-cis_OU_Ucely].[Spôsob získania OÚ], "NIE" AS [Spracováva na základe] 
INTO [_s-04-OU účely spracovania]
FROM [D-cis_OU_Ucely], import_OrgChart INNER JOIN [Katalóg aktív] ON import_OrgChart.[Organizačný útvar] = [Katalóg aktív].Vlastník
ORDER BY [Katalóg aktív].Vlastník, [Katalóg aktív].[Skupina Aktíva], [Katalóg aktív].[Názov aktíva];
```

```sql
SELECT [Katalóg aktív].Vlastník, [Katalóg aktív].[Skupina Aktíva], [Katalóg aktív].[Názov aktíva], [Aktíva - používatelia].Používateľ, "Áno" AS [Je používateľom] 
INTO [_s-02 - Používatelia aktíva]
FROM [Katalóg aktív] INNER JOIN [Aktíva - používatelia] ON [Katalóg aktív].[Názov aktíva] = [Aktíva - používatelia].[Názov aktíva]
ORDER BY [Katalóg aktív].Vlastník, [Katalóg aktív].[Skupina Aktíva], [Katalóg aktív].[Názov aktíva], [Aktíva - používatelia].Používateľ;
```
