# Hloubkový výklad a aplikační mapa — Komentář k zákonu č. 416/2023 Sb., o dorovnávacích daních (ZDD)

<!-- LOCAL-HLOUBKOVY-VYKLAD-GENERATED -->

> Tento soubor je aditivní analytická vrstva komentáře. Zachovává všechny dosavadní kapitoly a citace a nic z nich nenahrazuje. Věcná zjištění níže vycházejí pouze z obsahu tohoto repozitáře (kapitoly 01–03); u zcela nového zákona bez dostupné judikatury dokument chybějící oporu označuje jako kontrolní prioritu, nikoli jako domnělý právní závěr.

## Jak mapu číst

Každá vrstva odděluje místní zjištění (podložené doslovnou citací), autorský test a otevřenou otázku:

- **Text:** závěr přímo vyplývající z místního znění předpisu.
- **Syntéza:** autorské propojení textu, systematiky napříč paragrafy.
- **Otevřená otázka:** místní korpus odpověď nedává nebo připouští více řešení; u tohoto zákona sem patří zejména otázky, které se teprve ustálí praxí správce daně a mezinárodním přezkumným mechanismem OECD.

Místní korpus tvoří tři kapitoly (01–03, § 1–152) bez judikaturní vrstvy.

## 1. Mechanika výpočtu efektivní daňové sazby (ETR)

**Zjištění z textu.** ETR se počítá jurisdikčně (souhrnně za stát), nikoli entitně ani globálně:

> „Efektivní daňová sazba skupiny pro dané výkazní období a stát činí podíl
>
>   - a) jurisdikčního úhrnu upravených výší zahrnutých daní této skupiny v daném výkazním období a státě a
>
>   - b) jurisdikčního kvalifikovaného zisku této skupiny v daném výkazním období a státě."

(§ 77 odst. 2)

Podmínkou vůbec provést výpočet je existence alespoň jedné členské entity ze státu a existence jurisdikčního kvalifikovaného zisku (nikoli ztráty) — viz § 77 odst. 1. Výsledek „se zaokrouhluje na 4 platná desetinná místa" (§ 77 odst. 3), což má přímý dopad na hraniční případy blízké 15 %.

Ze součtu jsou vyloučeny tři kategorie entit: „Pro účely výpočtu podle odstavců 1 a 2 se nezohlední upravená výše zahrnutých daní a kvalifikovaný zisk nebo ztráta členských entit skupiny, které jsou" investiční entitou, součástí podskupiny v menšinovém vlastnictví nebo členskou entitou v menšinovém vlastnictví (§ 77 odst. 4) — jejich ETR se počítá samostatně, aby menšinoví vlastníci nenesli důsledky daňového plánování zbytku skupiny.

Zvláštní fikce platí pro entitu bez státní příslušnosti: „Na členskou entitu, která není z žádného státu, se pro účely výpočtu efektivní daňové sazby hledí, jako by byla z jiného státu než všechny ostatní členské entity téže skupiny" (§ 78) — taková entita se do žádného reálného jurisdikčního blendingu nikdy nezapočítává.

**Hloubkový test.**
- Ověřte, zda byly ze součtu zahrnutých daní a kvalifikovaného zisku správně vyloučeny investiční entity a entity/podskupiny v menšinovém vlastnictví (§ 77 odst. 4) — opomenutí zkresluje ETR celého státu, nejen dotčené entity.
- U entit bez státní příslušnosti ověřte, že se neúčastní blendingu žádného reálného státu (§ 78), včetně státu mateřské entity.
- Přesnost zaokrouhlení (§ 77 odst. 3) prověřte až v posledním kroku výpočtu, nikoli u dílčích vstupů — u ETR těsně pod/nad 15 % rozhoduje.

**Místní opora.** § 77 (obecná konstrukce ETR); § 78 (entita bez státní příslušnosti); §§ 59–68 (upravená výše zahrnutých daní); §§ 41–56 (kvalifikovaný zisk nebo ztráta).

## 2. Výpočet dorovnávací daně — od jurisdikční sazby k dílčí dorovnávací dani

**Zjištění z textu.** Jurisdikční sazba dorovnávací daně je „mezerou" mezi minimální a efektivní sazbou:

> „Jurisdikční sazba dorovnávací daně skupiny pro jednotlivé výkazní období a stát činí kladný rozdíl
>
>   - a) minimální daňové sazby a
>
>   - b) efektivní daňové sazby skupiny v tomto výkazním období a státě."

(§ 79 odst. 3)

Tato sazba se aplikuje na jurisdikční nadměrný zisk — tj. zisk snížený o substance carve-out (§ 79 odst. 5, viz vrstva 3 níže) — a výsledek se dále upraví o dodatečnou dorovnávací daň a odečte se úhrn kvalifikovaných vnitrostátních dorovnávacích daní (§ 79 odst. 2, viz vrstva zásad ZASADY.md č. 3). Zaokrouhlení jurisdikční sazby probíhá rovněž na 4 platná desetinná místa (§ 79 odst. 4).

Zvláštní pozornost zaslouží ochrana odečtu QDMTT proti sporné dani: „Úhrn kvalifikovaných vnitrostátních dorovnávacích daní podle odstavce 2 písm. b) bodu 2 se sníží o částku, ... která je předmětem řízení vedeného v souvislosti s kvalifikovanou vnitrostátní dorovnávací daní ve státě, který ji zavedl, před soudem nebo jiným orgánem veřejné moci" (§ 79 odst. 6 písm. a)) — po vyřešení sporu a zaplacení platí, že „zahrne se tato částka zpět do úhrnu kvalifikovaných vnitrostátních dorovnávacích daní" (§ 79 odst. 7).

**Hloubkový test.**
- Prověřte, zda odpočet QDMTT nezahrnuje spornou částku (§ 79 odst. 6) — jinak hrozí neoprávněné snížení jurisdikční dorovnávací daně.
- U dílčí alokace na jednotlivé entity (§ 80 a násl., mimo přímý rozsah citovaných úseků) ověřte správné rozdělení jurisdikční daně mezi poplatníky podle jejich podílu na nadměrném zisku.

**Místní opora.** § 79 (jurisdikční dorovnávací daň skupiny); § 80 (dílčí dorovnávací daň); §§ 66–68 (přiřazení a úpravy zahrnutých daní).

## 3. Bezpečné přístavy (safe harbours)

**Zjištění z textu.** Zákon rozeznává katalog bezpečných přístavů v § 92 a násl., mimo jiné výjimku z důvodu malého rozsahu a trvalé bezpečné přístavy založené na QDMTT a na zjednodušených výpočtech.

**Výjimka z důvodu malého rozsahu (de minimis).** Fikce nulové dorovnávací daně nastupuje při splnění dvou kumulativních testů na tříletém průměru:

> „Učiní-li podávající členská entita rozhodnutí podle odstavce 1, platí, že jurisdikční dorovnávací daň skupiny ve výkazním období a státě, pro které je toto rozhodnutí učiněno, je nulová, pokud průměr
>
>     - a) kvalifikovaných výnosů všech členských entit z tohoto státu za toto výkazní období a 2 bezprostředně předcházející výkazní období nepřesahuje částku odpovídající 10 000 000 EUR a
>
>     - b) jurisdikčních kvalifikovaných zisků nebo ztrát skupiny v tomto státě za výkazní období a 2 bezprostředně předcházející výkazní období představuje ztrátu nebo je nižší než částka odpovídající 1 000 000 EUR."

(§ 91 odst. 2)

Rozhodnutí se však nepoužije na entitu, která není z žádného státu, ani na investiční entitu (§ 91 odst. 1 věta druhá).

**QDMTT bezpečný přístav (§ 92a).** Trvalé pravidlo lze uplatnit, pokud zahraniční QDMTT obstojí ve třech testech — účetního rámce, konzistence a přezkumu (§ 92a odst. 1). Podmínka konzistence není porušena, „pokud právní řád daného státu ... stanoví sazbu odpovídající minimální daňové sazbě vyšší než 15 %" (§ 92a odst. 5 písm. c)) — přísnější odchylka od modelových pravidel tedy nevadí, mírnější ano.

**Hloubkový test.**
- U de minimis výjimky ověřte, že jde skutečně o tříletý klouzavý průměr, nikoli o hodnotu za jediné období (§ 91 odst. 2), a že rozhodnutí je krátkodobé (nutno obnovovat).
- U QDMTT bezpečného přístavu prověřte, že fikce nulové daně nepůsobí na výpočet samotné české dorovnávací daně — viz § 92 odst. 3 (citováno ve výkladu k § 92a) — jde o omezení specifické pro tento typ přístavu.
- Ověřte, zda podskupina není z QDMTT bezpečného přístavu vyloučena podle § 92a odst. 7 nebo 8 (nezpůsobilost podle prováděcího rámce OECD, resp. probíhající spor o legalitu QDMTT).

**Místní opora.** § 91 (výjimka z důvodu malého rozsahu); § 92 (obecný rámec rozhodnutí o bezpečném přístavu); § 92a (QDMTT bezpečný přístav); §§ 92b–92m (další kategorie, včetně přechodných CbCR bezpečných přístavů).

## 4. Substance-based carve-out (věcné vyloučení na základě ekonomické podstaty)

**Zjištění z textu.** Vyloučení se počítá jako součet dvou paušálních 5% položek:

> „Vyňaté mzdové náklady členské entity činí 5 % jejích způsobilých mzdových nákladů na pracovníky členské entity, kteří vykonávají činnost pro nadnárodní skupinu nebo vnitrostátní skupinu, jejíž součástí je tato entita, ve státě, z něhož je tato entita"

(§ 82 odst. 4)

a obdobně pro hmotná aktiva (§ 82 odst. 5). Definice způsobilých mzdových nákladů a způsobilých hmotných aktiv stanoví § 81 — hmotná aktiva jsou vymezena taxativně (pozemky, budovy, zařízení, přírodní zdroje, právo k užívání na základě nájmu, veřejnoprávní povolení spojená s investicemi), nehmotná aktiva jsou vyloučena.

Poměrné krácení nastupuje, „Nevykoná-li pracovník alespoň 50 % ze své pracovní doby v daném výkazním období činnost pro skupinu ve státě" jeho zaměstnavatele (§ 82 odst. 6), obdobně u aktiv nepřítomných alespoň 50 % období (§ 82 odst. 7).

Přechodné období navíc zvyšuje koeficienty vyloučení nad standardních 5 % podle přílohy zákona (klesající řada od 10 %, resp. 8 % v roce 2023 k 5 % od roku 2033) — viz § 149 a příloha k zákonu citovaná u § 152.

**Hloubkový test.**
- Ověřte klasifikaci aktiv jako hmotných ve smyslu taxativní definice § 81 písm. b) — nehmotná aktiva (know-how, ochranné známky) se do carve-outu nezapočítávají.
- U mezinárodně vysílaných pracovníků a přemísťovaných aktiv aplikujte poměrné krácení podle § 82 odst. 6 a 7.
- Zkontrolujte, zda byl použit správný (přechodný, nikoli konečný 5%) koeficient podle výkazního období — viz příloha k zákonu.

**Místní opora.** § 81 (definice); § 82 (výpočet, přechodné koeficienty); § 149 (zvláštní přechodné zvýšení).

## 5. Správní tok — informační přehled a daňové přiznání

**Zjištění z textu.** Informační přehled (obdoba GloBE Information Return) je samostatnou informační povinností nezávislou na existenci daňové povinnosti:

> „Poplatník dorovnávací daně je povinen podat informační přehled k dorovnávací dani nejpozději do 15 měsíců po uplynutí zdaňovacího období, bez ohledu na to, zda je součástí velké vnitrostátní skupiny nebo velké nadnárodní skupiny nízce zdaněná členská entita nebo zda má taková členská entita nadměrný zisk. Je-li zdaňovací období vstupním obdobím skupiny, je poplatník povinen podat informační přehled nejpozději do 18 měsíců po uplynutí zdaňovacího období."

(§ 129 odst. 1)

Daňové přiznání má samostatnou, delší a rovněž neprodloužitelnou lhůtu:

> „Poplatník dorovnávací daně je povinen podat daňové přiznání k této dani nejpozději do 22 měsíců po uplynutí zdaňovacího období."

(§ 132 odst. 1), s výslovným vyloučením prodloužení (§ 132 odst. 3).

Správcem daně je podle § 125 odst. 1 Specializovaný finanční úřad, byť „Vyhledávací činnost a kontrolní postupy při správě dorovnávací daně může provádět také jiný finanční úřad" (§ 125 odst. 2).

**Hloubkový test.**
- Rozlište důsledně lhůtu pro informační přehled (15, resp. 18 měsíců) od lhůty pro přiznání (22 měsíců) — jde o samostatná podání s odlišnými lhůtami i sankčními režimy.
- U vstupního období skupiny ověřte prodlouženou 18měsíční lhůtu pro informační přehled (§ 129 odst. 1 věta druhá).
- U společných podniků a přidružených osob (§ 110) prověřte ex lege prodloužení obou lhůt podle § 129 odst. 2 a § 132 odst. 2.
- Nepodá-li poplatník daňové přiznání, „považuje se daň za tvrzenou ve výši 0 Kč; pokuta za opožděné tvrzení daně se neuplatní" (§ 135 odst. 2, citováno ve výkladu k § 133) — odlište od standardního sankčního režimu daňového řádu.

**Místní opora.** § 125 (správce daně); § 128 (formulářové podání); § 129 (informační přehled); §§ 129a–129c (opravný, dodatečný přehled, výzva); § 132 (daňové přiznání); § 133 (výjimka z přiznání za část období).

## 6. Přechodná ustanovení

**Zjištění z textu.** Obecné intertemporální pravidlo testuje výhradně počátek výkazního období:

> „Pro výkazní období započaté přede dnem nabytí účinnosti tohoto zákona se tento zákon nepoužije."

(§ 147)

Účinnost zákona je stanovena na 31. prosince 2023 (§ 152). Zvláštní roční odklad platí pro UTPR:

> „Pro výkazní období započaté přede dnem 31. prosince 2024 se nepoužije část druhá hlava V díl 2."

(§ 148 odst. 1), s výjimkou pro skupiny řízené z členských států EU s nejvýše 12 nejvyššími mateřskými entitami, které samy odložily zavedení IIR i UTPR o šest let (§ 148 odst. 2 a 3) — u těch UTPR odklad nemá.

**Hloubkový test.**
- Test počátku výkazního období (§ 147) je binární — celé období buď spadá pod zákon, nebo vůbec, bez poměrné aplikace.
- U skupin s hospodářským rokem odlišným od kalendářního roku určete přesný den počátku prvního dotčeného výkazního období.
- Ověřte, zda stát sídla nejvyšší mateřské entity nespadá pod výjimku § 148 odst. 2 (nutnost sledovat zahraniční rozhodnutí o šestiletém odkladu).

**Místní opora.** § 147 (obecné přechodné ustanovení); § 148 (odklad UTPR); § 149 (přechodné zvýšení carve-outu); §§ 150–151b (další přechodná ustanovení); § 152 (účinnost a příloha s koeficienty).

## 7. Otevřené otázky (bez místní opory)

- Konkrétní výklad hraničních pojmů (např. přesná hranice povolení, se „kterými jsou spojeny významné investice do hmotných aktiv" u veřejnoprávních povolení podle § 81 písm. b) bodu 4) závisí na prováděcím rámci OECD, který je dynamicky doplňován (§ 2 odst. 4) — místní text zákona jej sám nekonkretizuje.
- Otázka ústavnosti dynamického odkazu na měnící se mezinárodní dokument (modelová pravidla a prováděcí rámec OECD, § 2 odst. 3 a 4) není v zákoně ani v komentovaných úsecích výslovně řešena a zůstává otevřená do budoucí ústavněprávní diskuse.
- Judikatura k výkladu jednotlivých ustanovení ZDD k datu tvorby komentáře neexistuje; otevřené výkladové otázky je nutné řešit primárně odkazem na modelová pravidla a prováděcí rámec OECD (§ 2).
