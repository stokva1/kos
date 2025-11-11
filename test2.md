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

Vysvětlete, v čem spočívá opakované vězňovo dilema.
Jmenujte strategie, které lze použít při opakovaném vězňově dilematu.
Popište, jaké vysvětlující faktory podle E.Rogerse působí při šíření inovací (tj. co přispívá k rychlejšímu či
pomalejšímu šíření inovace).
Popište, jaké skupiny osvojitelů inovací definoval E.Rogers a jakou křivkou je popsáno rozložení skupin osvojitelů v
populaci.
V přednášce bylo popsáno několik modelů šíření inovací či nákazy, jeden z modelů jmenujte a popište jeho princip.
V přednášce bylo vysvětleno, jak lze modelovat sociální vliv na utváření a polarizaci názorů, jeden z modelů popište.
Vysvětlete pojem síla slabých vazeb ve vztahu ke komplexním sítím.
Vysvětlete pojem bod zvratu ve vztahu k sociální dynamice, popište jeho zachycení v konkrétním modelu.
Vysvětlete rozdíl mezi šířením jednoduché nákazy a šířením komplexní nákazy (v síti).
Vysvětlete pozici simulace mezi vědeckými metodami (např. tak, že uvedete rozdíl mezi indukcí, dedukcí a simulací).
### 23. Vysvětlete pojem model, uveďte hlavní kategorie modelů.
### 24. Jmenujte základní kroky tvorby agentových simulačních modelů.


### 25. Vysvětlete, z čeho se skládá a k čemu se používá protokol ODD.
Standardní protokol pro formulování a popis agentových modelů
<img width="1123" height="622" alt="image" src="https://github.com/user-attachments/assets/1dd03dc6-a9b9-48a4-8583-57ea79128a94" />
<img width="1182" height="763" alt="image" src="https://github.com/user-attachments/assets/35211397-e209-4e36-8f5f-b456219b0e76" />


### 26. Vysvětlete, proč je třeba agentové modely kalibrovat a jak se to provádí.
Agentové modely popisují individuální chování agentů pomocí mnoha parametrů
Tyto parametry nejsou univerzální a musí odpovídat reálnému chování lidí v daném prostředí.
Je tedy třeba kalibrovat (= doplnit kvantitativní informace, nastavit parametry podle reality nebo historických dat, dat z dotazníků, statisticky zpracovaných měření,…)

### 27. Vysvětlete rozdíl mezi validací a verifikací agentového simulačního modelu.
Validace = ověření, zda model odpovídá chování reálného systému
Verifikace = ověření, zda model dělá, co si myslíme, že by dělat měl

### 28. Popište, z jakých hledisek je model zkoumán při prověřování validity.
• Strukturální validita = zda vztahy v modelu odpovídají vztahům v reálném systému
• Prediktivní validita = zda chování modelu odpovídá chování reálného systému
	– Základní validita = chování modelu se základními parametry odpovídá systému
	– Retrodikce = použijeme-li historická data, model dává odpovídající výsledky pro daný časový interval
	– Rovnováha = pokud lze analyticky stanovit rovnovážný stav při určitých podmínkách, model jej musí produkovat
	– Mezní hodnoty parametrů = zda se model chová přijatelně při krajích (i když nereálných) hodnotách

### 29. Jmenujte aplikační oblasti, v nichž se uplatňují modely pohybu chodců (davu).
• Dopravní plánování a architektura – efektivnost dopravy, evakuační postupy pro různá prostředí
• Psychologie – ověřování hypotéz o chování lidí za různých situací
• Marketing – porozumění chování lidí – muzea, letiště, nákupní centra
• Vizuální efekty – věrohodné modely pro filmy, počítačové hry
• Informatika – umělá inteligence, algoritmy pro předchozí aplikace

### 30. Vysvětlete principy modelování pohybu chodců (davu).
• Agent reprezentuje typického chodce, který se řídí jednoduchými pravidly
• Chůzi chápeme jako aktivitu částečně
	– cílenou (chodec obvykle má cíl)
	– náhodnou (vyhýbání se, drobné změny směru a rychlosti)
• Prostor je dvourozměrný
• Podstatné je měřítko
	– Prostorové (rozměr chodce ve vztahu k rozměru mapy)
	– Časové (rychlost chodce ve vztahu k běhu simulace)

### 31. Jmenujte (nakreslete) typické struktury, které mohou být generovány pohybem chodců.
>TODO

### 32. Vysvětlete pojem základní diagram (ve vztahu k modelování pohybu chodců).
• Empirická zjišťování vztahu mezi hustotou davu a rychlostí, liší se pro různé prostory (chodník, náměstí, schodiště,…)
• Analogie: pohyb tekutin
• Možnost validace modelu!

### 33. Uveďte, podle jakých hledisek lze klasifikovat modelovací přístupy, použitelné v simulacích pohybu chodců.
• Mikroskopický model – zachycení jednotlivcůs individuálními charakteristikami a trasami
• Makroskopický model – agregovaný pohled (hustoty a rychlosti)
• Tři proměnné (prostor, čas, rychlost) mohou být diskrétní nebo souvislé 
• Deterministický model – následující stav je jednoznačně určen předchozím stavem a akcemi
• Stochastický model – použitím pravděpodobností překleneme chybějící poznatky o procesech
• Pravidlový model (rule-based) – agent má systém pravidel pro různé situace
• Model sil (force-based) – agentem manipulují síly z okolí (fyzikální mechanistický pohled)
• Vysoce věrné modely (high-fidelity) – snaha namodelovat chování chodce co nejvěrněji i za cenu velké složitosti modelu
• Málo věrné modely (low-fidelity) – chodec jako částice v prostoru, bez inteligence; relativně menší počet parametrů modelu

### 34. Popište modelování pohybu chodců za využití buněčného automatu.
• Diskrétní prostor (2D mřížka)
• V jedné buňce nejvýš 1 chodec (překážka/prázdná buňka
• Diskrétní čas – paralelní přesuny + řešení konfliktů
• Směr pohybu závisí na interpretaci stavu sousedních buněk (směřovat k cíli, vyhýbání se kolizím)
• Reprezentace např. maticí pravděpodobností přechodu do sousedních buněk:
• Varianty modelu: různé rychlosti, různé typy chodců, různá definice okolí buňky (4, 6, 8 sousedů), více
chodců v buňce...

### 35. Popište modelování pohybu chodců za využití modelu sociálních sil.
(repulsive) síly, kterými působí cíl, výchozí bod, ostatní
chodci a překážky, světelné a zvukové signály, míra
stresu, sklon terénu. Výsledné chování agenta řídí souhrn působících sil +
další faktory (zorné pole, snaha šetřit energií,
držet se ve skupině,…) 
Výhody:realistické trajektorie a interakce, přirozeně vznikají jevy jako lanes, oscilace u zúžení atd.
Nevýhody:náročnější výpočetně, nutnost kalibrace parametrů (síly, čas reakce).
