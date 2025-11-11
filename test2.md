## Test 2

### 1. Vysvětlete, co je komplexní síť, uveďte alespoň tři příklady takových sítí.

- rozsáhlý systém vzájemně propojených jednotek
- studuje struktury a vlastnosti sítí, interakce prvků, makrovzorce, projevy emergence atd
- příklady:

#### Sociální síť

- uzly: lidé
- hrany: sledující
- příklady: Facebook, Instagram

#### Internetová síť

- uzly: servery
- hrany: datová spojení

#### Dopravní síť

- uzly: zastávky
- hrany: trať

### 2. Vysvětlete alespoň tři důležité charakteristiky komplexních sítí.

- velikost - počet uzlů, nebo hran
- hustota - podíl počtu hran k maximálnímu možnému počtu hran
- topologické vlastnosti: 
- - stupeň uzlu - počet hran uzlu
- - shlukování - intenzita vzájemných spojů
- - nejkratší cesty - vzdálenost mezi uzly je nejmenší počet hran, které tvoří cesu

### 3. Popište, jak probíhal Milgramův experiment se zásilkami a jaké přinesl zjištění.

- Fenomém **malého světa** 
- měření vzdálenosti mezi lidmi
- vybral 2 adresáty
- požádal 160 náhodně vybraných osob z Kansasu a z Nebrasky, aby
  odeslali zásilky buď přímo adresátům (pokud je osobně znají), anebo
  někomu, kdo by adresáta pravděpodobně znát mohl
- 42 zásilek došlo přes 2 až 12 prostředníků (průměrně přes 5,5) => objevení fenoménu tzv. malého světa a 6 kroků 
odloučenosti
- experiment byl několikrát opakován na Facebooku i Twitteru

### 4. Vysvětlete pojmy malý svět, šest kroků separace, Erdősovo číslo.

> todo
#### Malý svět

- vazby mezi lidmi jsou tak rozsáhlé, že přes pár lidí lze znát všechny na světě

#### Šest kroků separace

- přes méně jak 6 vazeb lze najít kontakt na kohokoliv

#### Erdősovo číslo

- vyjadřuje vzdálenost spolupráce
- první člověk má číslo 0, další 1, k + 1

### 5. Vysvětlete, jaký význam má stupeň uzlu a rozdělení stupňů uzlů v komplexní síti.

#### Stupeň uzlu

- počet hran uzlu

#### Rozdělení stupňů uzlů

- pravděpodobnost, že náhodně vybraný uzel má stupeň _k_

### 6. Vysvětlete alespoň tři pojmy, související s hledáním nejkratších cest v síti.

> todo

### 7. Popište náhodný graf (Erdős-Rényiho model).

- Postup: je dáno **N** uzlů, náhodně vybíráme
  dvojice uzlů a s pravděpodobností **p** je propojíme (např. na základě
  výsledku hodu kostkou)
- Ze způsobu konstrukce grafu vyplývá,
  že všechny uzly mají přibližně stejný
  počet hran
- Náhodné grafy neodpovídají reálným
  komplexním sítím, ale z matematického
  hlediska jsou zajímavé
- např. se v nich projevuje **princip fázového přechodu**

### 8. Vysvětlete pojem obří komponenta v síti a popište proces (algoritmus) jejího utváření.

- komponenta, která obsahuje téměř všechny uzly sítě
- V každém kroku jsou dva náhodně vybrané uzly spojeny hranou
- Hrana mezi dvěma uzly existuje s pravděpodobností p
- Emergence: hrany spojující dvojice uzlů => řetězce => propojování komponent

### 9. Popište graf malého světa (Watts-Strogatzův model).

- 2 pravidla:
1. Pravidelné uspořádání – N vrcholů v kruhu, každý je spojen s K
   sousedy (K/2 na každé straně)
2. Proces náhodné změny hran – s pravděpodobností p každou
   hranu nahradíme jinou, náhodnou hranou

### 10. Popište bezškálovou síť (Barabási-Albertův model).

- Reprodukuje distribuci uzlů podle mocninného zákona
- 3 pravidla
1. Malý výchozí počet uzlů a hran
2. Přidávají se vrcholy, každý nově přidaný je spojen **k** hranami s
   již existujícími vrcholy
3. Dodržuje se preferenční připojování, tj. pravděpodobnost
   výběru vrcholu je přímo úměrná jeho aktuálnímu stupni (tím je
   dodržena mocninná distribuce stupňů uzlů)

### 11. Vysvětlete pojmy sociální fyzika a roli výpočetních modelů v této oblasti.

-  Člověk jako jednotka (atom, molekula, agent) v systému
- Přírodovědný pohled na sociální systémy a jevy
- - Pravděpodobnost a statistika
- - Zkoumání volebních preferencí, kriminality, nezaměstnanosti, sebevražednosti,…

> todo role výpočetních modelů

### 12. Vysvětlete, co je cílem modelů vývoje kooperace.

> todo

### 13. Vysvětlete, v čem spočívá opakované vězňovo dilema.
### 14. Jmenujte strategie, které lze použít při opakovaném vězňově dilematu.
### 15. Popište, jaké vysvětlující faktory podle E.Rogerse působí při šíření inovací (tj. co přispívá k rychlejšímu či
pomalejšímu šíření inovace).
### 16. Popište, jaké skupiny osvojitelů inovací definoval E.Rogers a jakou křivkou je popsáno rozložení skupin osvojitelů v
populaci.
### 17. V přednášce bylo popsáno několik modelů šíření inovací či nákazy, jeden z modelů jmenujte a popište jeho princip.
### 18. V přednášce bylo vysvětleno, jak lze modelovat sociální vliv na utváření a polarizaci názorů, jeden z modelů popište.
## Test 19–32

### 19. Vysvětlete pojem síla slabých vazeb ve vztahu ke komplexním sítím.

- Hypotéza slabých vazeb: pokud má osoba X vazbu s osobami Y, Z, tak je větší šance, že i mezi Y a Z existuje vazba
- Sociální síť je tvořena skupinami, intenzivně (silně) propojenými uvnitř a slabě spojenými navenek
- Rychlost a míra šíření v síti závisí na spojích mezi prvky sítě
- Slabé vazby mnohonásobně zvyšují počet propojení; s jejich počtem roste rychlost šíření
- Pokud skupina nemá dostatek slabých vazeb, nezíská informace ze vzdálenějších částí sociální sítě (tj. členové skupiny budou mít přístup jen k novinkám a názorům zevnitř vlastní skupiny)

### 20. Vysvětlete pojem bod zvratu ve vztahu k sociální dynamice, popište jeho zachycení v konkrétním modelu.

- Bod zvratu (prahová hodnota, threshold) – moment, kdy se jedinec přidá k davovému chování
- Prahová hodnota je individuální a souvisí s užitkem (ziskem) z toho, že se jedinec chová/nechová stejně jako okolí
- Příklad modelu: 5 agentů se rozhoduje, zda nosit výstřední módní doplněk (např. červenou čepičku)
  - a) Prahové hodnoty 1,1,1,2,2 (průměr 1,4) – žádný agent si čepičku nevezme
  - b) 0,1,2,2,2 (průměr 1,4) – první agent si čepičku vezme, to je důvod, aby si ji vzal druhý agent, což spustí reakci i u dalších tří
  - c) 0,1,2,3,4 (průměr 2,5) – kolektivní akce je pravděpodobnější, když prahové hodnoty jsou nižší a variabilnější

### 21. Vysvětlete rozdíl mezi šířením jednoduché nákazy a šířením komplexní nákazy (v síti).

- Jednoduchá nákaza – k přenosu stačí kontakt s jedním nakaženým (typicky infekce, informace)
- Komplexní nákaza – přenos vyžaduje více kontaktů nebo sociální podporu (typicky inovace, změna chování)
- Slabá pouta a sítě malého světa usnadňují šíření jednoduchých nákaz
- Komplexní nákazy jimi postupují pomaleji, protože vyžadují více potvrzení od sousedů

### 22. Vysvětlete pozici simulace mezi vědeckými metodami (např. tak, že uvedete rozdíl mezi indukcí, dedukcí a simulací).

- Indukce
  - Pracujeme přímo se zkoumaným systémem, který může být i rozsáhlý
  - Odhalování nových vztahů z empirických dat (např. dotazníky, měření)
  - Závěry jsou popisné, vyplývají z pozorování
- Dedukce
  - Pracujeme se zjednodušeným modelem světa
  - Odvozování nových tvrzení z daných předpokladů a axiomů
  - Příklady: hledání rovnovážného bodu ve hře, model racionální volby
  - Exaktní důkazy možné jen u jednoduchých modelů
- Simulace
  - Využívá modely jako dedukce, ale místo dokazování generuje data
  - Výsledky zkoumáme empiricky podobně jako při indukci
  - Umožňuje zkoumat složité systémy, kde analytické řešení není možné

### 23. Vysvětlete pojem model, uveďte hlavní kategorie modelů.

- Model = výsledek procesu modelování; zjednodušená reprezentace objektů nebo jevů reálného světa
- Typy modelů:
  - Mentální – základ lidského vnímání světa a myšlení
  - Fyzické – reálné objekty v měřítku (zvětšeniny, zmenšeniny)
  - Matematické – vyjádřené pomocí rovnic
    - Popisné modely – vystihují vztahy proměnných v daném okamžiku (např. regresní modely)
    - Dynamické (analytické) modely – popisují změny proměnných v čase (např. diferenciální rovnice, nabídka–poptávka)
  - Výpočetní modely – zkoumány simulací (spuštění programu nebo řešení rovnic); nutný výpočetní výkon

### 24. Jmenujte základní kroky tvorby agentových simulačních modelů.

- Iterativní proces s návraty k předchozím krokům:
  - Návrh modelu
  - Implementace modelu
  - Verifikace a validace
  - Simulace a analýza
  - Sumarizace a sdílení výsledků
  - Reprodukce simulace

### 25. Vysvětlete, z čeho se skládá a k čemu se používá protokol ODD.

- Standardní protokol pro formulování a popis agentových modelů
- Používá se k jednoznačnému a srozumitelnému popisu modelu
- Umožňuje reprodukovatelnost a porovnatelnost mezi výzkumy
- ODD = Overview, Design concepts, Details
  - Overview – přehled: cíle modelu, entity, procesy, měřítko
  - Design concepts – hlavní principy: adaptace, interakce, heterogenita, emergentní chování
  - Details – detaily implementace: inicializace, vstupy, výstupy
- Vizualizace schémat a diagramů se používá pro popis struktury modelu

### 26. Vysvětlete, proč je třeba agentové modely kalibrovat a jak se to provádí.

- Agentové modely popisují chování jednotlivců pomocí mnoha parametrů
- Tyto parametry nejsou univerzální, musí odpovídat reálnému chování lidí v daném prostředí
- Kalibrace = nastavení parametrů podle reality (např. podle historických dat, měření, dotazníků)
- Provádí se statistickým přizpůsobením výsledků modelu empirickým datům
- Cílem je, aby model realisticky reprodukoval chování skutečného systému

### 27. Vysvětlete rozdíl mezi validací a verifikací agentového simulačního modelu.

- Validace – ověření, zda model odpovídá chování reálného systému
- Verifikace – ověření, zda model funguje podle návrhu (tj. dělá to, co má dělat)

### 28. Popište, z jakých hledisek je model zkoumán při prověřování validity.

- Strukturální validita – zda vztahy v modelu odpovídají vztahům v reálném systému
- Prediktivní validita – zda chování modelu odpovídá chování reálného systému
  - Základní validita – model s výchozími parametry odpovídá pozorovanému systému
  - Retrodikce – při použití historických dat model správně reprodukuje minulost
  - Rovnováha – model produkuje rovnovážný stav, pokud je znám analyticky
  - Mezní hodnoty – model se chová přijatelně i při krajních (nereálných) hodnotách parametrů

### 29. Jmenujte aplikační oblasti, v nichž se uplatňují modely pohybu chodců (davu).

- Dopravní plánování a architektura – efektivnost dopravy, návrh evakuací
- Psychologie – ověřování hypotéz o chování lidí v různých situacích
- Marketing – analýza chování návštěvníků (letiště, nákupní centra, muzea)
- Vizuální efekty – realistické davové scény ve filmech a hrách
- Informatika – algoritmy pro umělou inteligenci a simulace

### 30. Vysvětlete principy modelování pohybu chodců (davu).

- Agent reprezentuje typického chodce, který se řídí jednoduchými pravidly
- Chůze je aktivita částečně:
  - cílená (chodec má cíl)
  - náhodná (vyhýbání se, drobné odchylky)
- Prostor je dvourozměrný
- Důležité je měřítko:
  - prostorové – rozměr chodce vůči mapě
  - časové – rychlost chodce vůči časovému kroku simulace

### 31. Jmenujte (nakreslete) typické struktury, které mohou být generovány pohybem chodců.

- Typické samoorganizované vzory:
  - proudy (lanes) v protisměru
  - oscilace u zúžení
  - shluky u překážek
  - kruhové pohyby kolem cílů nebo bariér

### 32. Vysvětlete pojem základní diagram (ve vztahu k modelování pohybu chodců).

- Empiricky zjišťovaný vztah mezi hustotou davu a průměrnou rychlostí pohybu
- Liší se podle prostředí (chodník, náměstí, schodiště apod.)
- Slouží jako analogie k pohybu tekutin
- Umožňuje validaci modelů – simulované chování lze porovnat s naměřenými daty


### 33. Uveďte, podle jakých hledisek lze klasifikovat modelovací přístupy, použitelné v simulacích pohybu chodců.

- Mikroskopický model – zachycuje jednotlivé chodce s individuálními charakteristikami a trasami
- Makroskopický model – agregovaný pohled, popisuje proudění davu pomocí veličin jako hustota a rychlost
- Rozlišení proměnných – prostor, čas a rychlost mohou být diskrétní nebo spojité
- Deterministický model – další stav systému je jednoznačně určen předchozím stavem a akcemi
- Stochastický model – využívá pravděpodobnosti k překlenutí neznalosti detailních procesů
- Pravidlový model (rule-based) – agent se řídí souborem pravidel pro různé situace
- Model sil (force-based) – chování agenta je výsledkem působení sil z okolí (cíle, ostatní chodci, překážky)
- Vysoce věrné modely (high-fidelity) – snaha o realistické zobrazení chování i za cenu složitosti
- Málo věrné modely (low-fidelity) – chodec reprezentován zjednodušeně (např. částice), menší počet parametrů

### 34. Popište modelování pohybu chodců za využití buněčného automatu.

- Prostor – reprezentován jako diskrétní 2D mřížka
- Buňka – může obsahovat nejvýše jednoho chodce, překážku nebo být prázdná
- Čas – diskrétní kroky; všichni agenti se pohybují paralelně
- Konflikty – při snaze více chodců vstoupit do stejné buňky se rozhoduje podle pravidel nebo pravděpodobností
- Směr pohybu – určen podle stavu okolních buněk (blízkost cíle, vyhýbání se kolizím)
- Reprezentace – matice pravděpodobností přechodu do sousedních buněk
- Varianty modelu:
  - různé rychlosti a typy chodců
  - různé definice okolí buňky (4, 6, 8 sousedů)
  - možnost více chodců v jedné buňce (rozšířené verze)

### 35. Popište modelování pohybu chodců za využití modelu sociálních sil.

- Každý chodec je modelován jako částice, na kterou působí síly:
  - přitažlivá síla směrem k cíli
  - odpudivé síly od ostatních chodců a překážek
  - vlivy prostředí – světelné, zvukové signály, stres, sklon terénu
- Výsledné chování je dáno součtem všech působících sil
- Do výpočtu mohou vstupovat i další faktory:
  - omezené zorné pole
  - snaha šetřit energií
  - držení se ve skupině
- Výhody:
  - realistické trajektorie a interakce
  - spontánně vznikají jevy jako lanes nebo oscilace u zúžení
- Nevýhody:
  - výpočetně náročný
  - nutnost kalibrace parametrů (intenzity sil, doba reakce)
