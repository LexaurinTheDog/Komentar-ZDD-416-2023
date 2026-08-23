# Výkladové otázky a odpovědi — Komentář k zákonu č. 416/2023 Sb., o dorovnávacích daních (ZDD)

<!-- LOCAL-VYKLADOVE-OTAZKY-GENERATED -->

> Tento dokument je pracovní kontrolní mapa sepisovatele komentáře. Vychází výhradně z místních kapitol, místního znění předpisu a souborů **ZASADY.md** a **PRAVNI-MODALITY.md**. Jde o zcela nový zákon bez dostupné judikatury k datu tvorby komentáře — dokument tuto skutečnost výslovně zohledňuje a nepřidává tezi převzatou z internetu ani nedoplňuje chybějící právo odhadem.

## Jak dokument používat

Každá otázka odděluje tři věci: co lze podle místního textu zákona říci, jak má sepisovatel otázku dále řešit a kde je místní podklad (odkaz na konkrétní paragraf a soubor). Není-li podklad v místním korpusu, dokument výslovně označí mezeru.

## 1. Koho se dorovnávací daň týká — jaké jsou finanční prahy?

**Odpověď.** Zákon dopadá jen na tzv. velké skupiny — nadnárodní i vnitrostátní — které dosáhly prahu konsolidovaných výnosů:

> „velkou skupinou skupina, jejíž konsolidované roční výnosy vykázané v konsolidované účetní závěrce nejvyšší mateřské entity nejméně ve 2 ze 4 výkazních obdobích bezprostředně předcházejících danému výkaznímu období, včetně výnosů vyloučených entit, činí alespoň částku odpovídající 750 000 000 EUR"

(§ 8 odst. 1 písm. b))

Test je retrospektivní (2 ze 4 bezprostředně předcházejících období, nikoli posuzované období samo) a při jiné délce výkazního období než 12 měsíců „upraví se prahová hodnota konsolidovaných výnosů poměrně pro každé z těchto výkazních období" (§ 8 odst. 1 písm. b) in fine). Zákon rozlišuje nadnárodní skupinu (alespoň jedna entita z jiného státu než nejvyšší mateřská entita) od vnitrostátní skupiny (všechny členské entity z jediného členského státu) — týž práh 750 mil. EUR platí pro obě kategorie (§ 8 odst. 1 písm. c) a d)).

**Jak ji řešit.** Sestavte přehled konsolidovaných výnosů za 4 bezprostředně předcházející výkazní období, přepočítejte je podle metodiky § 8 odst. 2 (nejde o mechanické převzetí účetních tržeb — zahrnuje mimořádné položky a čisté investiční zisky), a klasifikujte skupinu jako nadnárodní, nebo vnitrostátní.

**Místní opora.** § 8 (skupiny, prahová hodnota); § 106 (spojení a rozpad skupin); § 152 a příloha (koeficienty relevantní pro přechodné období, nikoli pro samotný práh).

## 2. Jak se počítá efektivní daňová sazba (ETR)?

**Odpověď.** ETR se počítá jurisdikčně, tj. souhrnně za všechny (nevyloučené) členské entity skupiny v témže státě:

> „Efektivní daňová sazba skupiny pro dané výkazní období a stát činí podíl
>
>   - a) jurisdikčního úhrnu upravených výší zahrnutých daní této skupiny v daném výkazním období a státě a
>
>   - b) jurisdikčního kvalifikovaného zisku této skupiny v daném výkazním období a státě."

(§ 77 odst. 2)

Výpočet se provede jen tehdy, existuje-li v daném státě alespoň jedna členská entita a vzniká-li jurisdikční kvalifikovaný zisk, nikoli ztráta (§ 77 odst. 1). Investiční entity, podskupiny a entity v menšinovém vlastnictví se ze součtu vylučují a jejich ETR se počítá odděleně (§ 77 odst. 4); entita bez státní příslušnosti tvoří vlastní samostatnou fiktivní jurisdikci (§ 78).

**Jak ji řešit.** Sečtěte upravenou výši zahrnutých daní a kvalifikovaný zisk za všechny nevyloučené entity v daném státě, vylučte investiční entity a entity v menšinovém vlastnictví, výsledek zaokrouhlete na 4 platná desetinná místa (§ 77 odst. 3) a porovnejte s minimální sazbou 15 % podle § 79.

**Místní opora.** § 77 (ETR skupiny); § 78 (entita bez státní příslušnosti); §§ 59–68 (upravená výše zahrnutých daní); §§ 41–56 (kvalifikovaný zisk nebo ztráta).

## 3. Co je bezpečný přístav a jak funguje výjimka z důvodu malého rozsahu?

**Odpověď.** Bezpečné přístavy jsou zjednodušující mechanismy, které při splnění podmínek nahrazují plný výpočet fikcí nulové dorovnávací daně, čímž snižují compliance zátěž. Výjimka z důvodu malého rozsahu (de minimis) je jedním z nich:

> „Učiní-li podávající členská entita rozhodnutí podle odstavce 1, platí, že jurisdikční dorovnávací daň skupiny ve výkazním období a státě, pro které je toto rozhodnutí učiněno, je nulová, pokud průměr
>
>     - a) kvalifikovaných výnosů všech členských entit z tohoto státu za toto výkazní období a 2 bezprostředně předcházející výkazní období nepřesahuje částku odpovídající 10 000 000 EUR a
>
>     - b) jurisdikčních kvalifikovaných zisků nebo ztrát skupiny v tomto státě za výkazní období a 2 bezprostředně předcházející výkazní období představuje ztrátu nebo je nižší než částka odpovídající 1 000 000 EUR."

(§ 91 odst. 2)

Jde o krátkodobé rozhodnutí (nutno obnovovat pro každé období) a nepoužije se na entitu bez státní příslušnosti ani na investiční entitu (§ 91 odst. 1). Trvalé bezpečné přístavy (§ 92a a násl.) jsou vázány na zahraniční kvalifikovanou vnitrostátní dorovnávací daň nebo na zjednodušené výpočty a testují se podle § 92a odst. 1 třemi podmínkami (účetní rámec, konzistence, přezkum).

**Jak ji řešit.** Ověřte tříletý klouzavý průměr výnosů a zisku podle § 91 odst. 2 a 3, vylučte investiční entity a entity bez státní příslušnosti z testovaných průměrů, a u trvalých přístavů prověřte, že fikce nulové daně nepůsobí na výpočet samotné české dorovnávací daně (§ 92 odst. 3, citováno ve výkladu k § 92a).

**Místní opora.** § 91 (výjimka z důvodu malého rozsahu); § 92 (obecný rámec); § 92a (QDMTT bezpečný přístav); §§ 92b–92m (další kategorie).

## 4. Jaké jsou lhůty pro podání informačního přehledu a daňového přiznání?

**Odpověď.** Zákon rozlišuje dvě samostatná podání s odlišnými lhůtami. Informační přehled (obdoba GloBE Information Return):

> „Poplatník dorovnávací daně je povinen podat informační přehled k dorovnávací dani nejpozději do 15 měsíců po uplynutí zdaňovacího období, bez ohledu na to, zda je součástí velké vnitrostátní skupiny nebo velké nadnárodní skupiny nízce zdaněná členská entita nebo zda má taková členská entita nadměrný zisk. Je-li zdaňovací období vstupním obdobím skupiny, je poplatník povinen podat informační přehled nejpozději do 18 měsíců po uplynutí zdaňovacího období."

(§ 129 odst. 1)

Daňové přiznání:

> „Poplatník dorovnávací daně je povinen podat daňové přiznání k této dani nejpozději do 22 měsíců po uplynutí zdaňovacího období."

(§ 132 odst. 1)

Obě lhůty jsou kogentní — „Lhůtu pro podání informačního přehledu k dorovnávací dani nelze prodloužit ani navrátit v předešlý stav" (§ 129 odst. 4) a „Lhůtu pro podání daňového přiznání nelze prodloužit" (§ 132 odst. 3). U společných podniků a přidružených osob (§ 110) se obě lhůty ex lege prodlužují, aby neskončily dříve než odpovídající lhůta skupiny vykazující výsledky společného podniku ekvivalenční metodou (§ 129 odst. 2, § 132 odst. 2).

**Jak ji řešit.** Určete zdaňovací období (= výkazní období skupiny, § 115), rozlište, zda jde o vstupní období skupiny (18 měsíců pro přehled), a naplánujte podání s dostatečným předstihem — obě lhůty jsou neprodloužitelné.

**Místní opora.** § 115 (zdaňovací období); § 128 (formulářové podání); § 129 (informační přehled); § 132 (daňové přiznání); § 133 (výjimka z přiznání za část období).

## 5. Jaký je vztah dorovnávací daně k dani z příjmů právnických osob?

**Odpověď.** Dorovnávací daň je samostatnou daní vedle daně z příjmů právnických osob, s vlastním poplatníkem, předmětem a zdaňovacím obdobím. Zdaňovacím obdobím přiřazované dorovnávací daně je výkazní období skupiny, nikoli individuální zdaňovací období poplatníka pro účely daně z příjmů:

> „Zdaňovacím obdobím přiřazované dorovnávací daně je výkazní období."

(§ 115)

Vztah k tuzemskému režimu zdanění ovládaných zahraničních společností (CFC) upravuje § 34: zahraniční kvalifikovaná vnitrostátní dorovnávací daň (QDMTT) se „pro účely snížení daně z příjmů právnických osob, která vznikla ovládající společnosti na základě právního předpisu upravujícího zdanění ovládané zahraniční společnosti, považuje za daň obdobnou dani z příjmů právnických osob" (§ 34 odst. 1), avšak zápočet je limitován poměrnou částí odpovídající podílu příjmů zachycených CFC pravidly na kvalifikovaném zisku dané entity (§ 34 odst. 2). Kvalifikovaná vnitrostátní dorovnávací daň (česká i zahraniční) se dále odečítá od jurisdikční dorovnávací daně skupiny podle § 79 odst. 2 písm. b) bodu 2, aby nedocházelo k dvojímu výběru téže daně různými státy.

**Jak ji řešit.** Veďte odděleně sledování zdaňovacího období pro daň z příjmů právnických osob a pro dorovnávací daň (mohou se lišit, je-li hospodářský rok skupiny odlišný od kalendářního roku poplatníka). U CFC struktur ověřte poměrný zápočet QDMTT podle § 34 odst. 2, nikoli plný zápočet.

**Místní opora.** § 34 (snížení daně ovládající společnosti o QDMTT); § 115 (zdaňovací období); § 3 odst. 4 (definice kvalifikované vnitrostátní dorovnávací daně); § 79 odst. 2 (odpočet QDMTT od jurisdikční dorovnávací daně).

## 6. Kdo je poplatníkem přiřazované a kdo české dorovnávací daně?

**Odpověď.** Zákon rozlišuje dvě daně se strukturně zrcadlovým okruhem poplatníků. Poplatníkem přiřazované dorovnávací daně je „česká členská entita, která ... není stálou provozovnou a ... je součástí velké vnitrostátní skupiny nebo velké nadnárodní skupiny" nebo hlavní entita odpovědná za českou stálou provozovnu (§ 112 písm. a) a b)). Předmětem přiřazované dorovnávací daně je „nadměrný zisk nízce zdaněných členských entit v rámci velké vnitrostátní skupiny nebo velké nadnárodní skupiny, bez ohledu na to, ve kterém státě a kterou členskou entitou byl dosažen" (§ 113 odst. 1) — tedy globální pohled bez ohledu na to, kde k nízkému zdanění došlo.

Poplatníkem české dorovnávací daně je obdobně vymezená česká členská entita (§ 117 odst. 1), avšak předmětem je jen „nadměrný zisk nízce zdaněných českých členských entit a nízce zdaněných entit, které nejsou z žádného státu a jsou poplatníky české dorovnávací daně" (§ 118 odst. 1) — tedy jen nízké zdanění vzniklé v ČR.

**Jak ji řešit.** U každé české entity nejprve určete, zda je či není stálou provozovnou (§ 112 a § 117 rozlišují tyto dvě kategorie poplatníků), následně prověřte, zda skupina uplatňuje IIR, UTPR, nebo obojí, a odděleně posuďte expozici vůči přiřazované dorovnávací dani (globální předmět) a vůči české dorovnávací dani (tuzemský předmět).

**Místní opora.** § 112 (poplatník přiřazované dorovnávací daně); § 113 (předmět přiřazované dorovnávací daně); § 114 (výše daně — součet IIR a UTPR složky); § 117 (poplatník české dorovnávací daně); § 118 (předmět české dorovnávací daně).

## 7. Jaký je vztah IIR a UTPR — kdy nastupuje který mechanismus?

**Odpověď.** IIR je primárním („top-down") mechanismem — mateřská entita „vypočítá a hradí svůj podíl na přiřazované dorovnávací dani ve vztahu k nízce zdaněným členským entitám této skupiny" (§ 4 odst. 1). UTPR je subsidiárním záchytným mechanismem: členské entitě vzniká dodatečná daň „ve výši odpovídající podílu této entity na přiřazované dorovnávací dani, která nebyla stanovena podle pravidla pro zahrnutí zisku" (§ 5 odst. 1) — nastupuje tedy jen v rozsahu, v jakém IIR daň nepokrylo.

**Jak ji řešit.** Zmapujte hierarchii skupiny a určete, které mateřské entity mají ve svém státě kvalifikované IIR (§ 4 odst. 2); teprve u zbytkové (nepokryté) částky prověřte expozici vůči UTPR podle alokačního vzorce zaměstnanců a hmotných aktiv (§ 102, mimo přímý rozsah citovaných úseků tohoto dokumentu).

**Místní opora.** § 4 (IIR); § 5 (UTPR); § 99 (okruh entit podléhajících UTPR); § 148 (přechodný roční odklad UTPR).

## 8. Jak přechodná ustanovení ovlivňují první roky účinnosti zákona?

**Odpověď.** Zákon se nepoužije na výkazní období započatá přede dnem jeho účinnosti (31. 12. 2023):

> „Pro výkazní období započaté přede dnem nabytí účinnosti tohoto zákona se tento zákon nepoužije."

(§ 147)

UTPR má navíc samostatný roční odklad: „Pro výkazní období započaté přede dnem 31. prosince 2024 se nepoužije část druhá hlava V díl 2" (§ 148 odst. 1), s výjimkou pro skupiny řízené z malých členských států EU, které samy odložily zavedení obou pravidel o šest let (§ 148 odst. 2 a 3). Substance carve-out navíc v přechodném období používá vyšší koeficienty než konečných 5 % (§ 149 a příloha k zákonu).

**Jak ji řešit.** Určete přesný den počátku prvního dotčeného výkazního období skupiny (rozhodný je den počátku, nikoli konce období — test je binární), ověřte, zda se uplatní roční odklad UTPR, a použijte správný přechodný koeficient carve-outu podle roku.

**Místní opora.** § 147 (obecné přechodné ustanovení); § 148 (odklad UTPR); § 149 (přechodné zvýšení carve-outu); § 152 (den účinnosti a příloha s koeficienty).
