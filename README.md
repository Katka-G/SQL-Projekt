# Analýza dostupnosti potravin a její vliv na životní úroveň občanů
Projekt byl iniciován analytickým oddělením naší společnosti a jeho účelem je poskytnout komplexní data o cenách potravin a výši mezd v průběhu let. Cílem je poskytnout ucelenou a relevantní informaci ohledně vztahů mezi pohybem cen a mezd a následným vlivem na životní úroveň občanů.

Při tvorbě primární tabulky jsem spojila tabulku cen potravin a tabulku výše mezd. V zájmu lepší čitelnosti a srozumitelnosti byly kódy potravin a průmyslových odvětví z obou zdrojových tabulek nahrazeny jejich plnými názvy. Ceny potravin jsou v tabulce uváděny na denní bázi, naopak výše mezd je uváděna kvartálně. Bylo tedy nutné sjednotit data na roční bázi. Z tabulky cen potravin byl tedy extrahován pouze rok, který sloužil jako klíč pro propojení s tabulkou mezd. Pro primární tabulku jsem následně použila průměry cen i mezd vždy pro daný rok. Z tabulky mezd jsem pro analýzu vybrala pouze údaje o průměrné hrubé mzdě na zaměstnance, zatímco data o průměrném počtu zaměstnaných osob byla vynechána, jelikož to je pro naše potřeby irelevantní.

## Shrnutí
| Název projektu | Analýza dostupnosti potravin a její vliv na životní úroveň občanů |
| :--- | :--- |
| Cíl analýzy | Kvantifikovat vztah mezi dynamikou cen základních potravin a vývojem průměrných mezd v různých odvětvích a posoudit jeho dopad na kupní sílu občanů. |
| Analyzované období | 2006–2018 (dle dostupnosti dat) |

## Výzkumné otázky:
### **1. Rostou v průběhu let mzdy ve všech odvětvích, nebo v některých klesají?**

V některých letech a v některých odvětvích se několikrát od roku 2009 průměrná mzda snížila oproti předchozímu roku. Tento jev byl identifikován v různých odvětvích, přičemž nejvýraznější a plošný pokles nastal v roce 2013. V tomto roce klesla průměrná mzda ve více než polovině všech sledovaných odvětví. Nejsilněji byl zasažen obor Peněžnictví a pojišťovnictví, kde průměrná mzda zaznamenala pokles o 4 478,50 Kč. Tento plošný propad byl s největší pravděpodobností způsoben kombinací faktorů, jako jsou doznívající ekonomická krize a měnící se daňová legislativa ve vyplácení odměn.

Další roky, ve kterých byl zaznamenán pokles průměrné mzdy (příklady nejvíce zasažených odvětví v daném roce):
| Rok |	Odvětví s poklesem mzdy (příklady) |
| :--- | :--- |
| 2009 | Těžba a dobývání, Ubytování, stravování a pohostinství, Zemědělství |
| 2010 | Vzdělávání, Veřejná správa a obrana |
| 2011 | Veřejná správa a obrana, Kulturní, zábavní a rekreační činnosti |
| 2014 | Těžba a dobývání |
| 2015 | Výroba a rozvod elektřiny, plynu, tepla a klimatiz. vzduchu |
| 2016 | Těžba a dobývání |

### **2. Kolik je možné si koupit litrů mléka a kilogramů chleba za první a poslední srovnatelné období v dostupných datech cen a mezd?**

Porovnáváme kupní sílu v letech 2006 a 2018 a to skrze všechna sledovaná odvětví. Ve většině odvětví došlo k celkovému nárůstu kupní síly, také rozdíl mezi nejlépe a nejhůře placenými odvětvími se mírně snižuje. V případě chleba došlo však dokonce k poklesu kupní síly u nejbohatších odvětví.

**a. Mléko**

Kupní síla ve vztahu k mléku se celkově zvýšila. Průměrná mzda napříč celou ekonomikou (2006 vs. 2018) umožnila zakoupit o 204,33 litrů mléka více. Rozdíl mezi nejlépe a nejhůře placenými odvětvími se ve sledovaném období mírně snížil.

| Odvětví / Kategorie | Rok 2006 (litrů) | Rok 2018 (litrů) | Absolutní nárůst / pokles | Procentuální nárůst |
| :--- | :--- | :--- | :--- | :--- |  
| Průměr všech odvětví | 1 437,24 | 1 641,57 | + 204,33 | + 14,2 % | 
| Nejlépe placené (I. a K. činnosti) | 2 748,62 (Peněž.) | 2 830,54 | + 81,92 | + 3,0 % | 
| Nejhůře placené (Ubytování, stravování) | 788,78 | 947,02 | + 158,24 | + 20,1 % | 

Ačkoli nejhůře placené odvětví (Ubytování, stravování, pohostinství) zaznamenalo procentuálně velmi vysoký nárůst kupní síly (+20,1 %), v absolutních číslech si v roce 2018 stále mohlo za průměrnou mzdu koupit téměř třikrát méně mléka než nejlépe placené odvětví (Informační a komunikační činnosti).

**b. Chléb** 

Zatímco v průměru se kupní síla mírně zvýšila, u nejlépe placeného odvětví došlo ke skutečnému poklesu reálné kupní síly.

| Odvětví / Kategorie | Rok 2006 (kg) | Rok 2018 (kg) | Absolutní nárůst / pokles | Procentuální nárůst | 
| :--- | :--- | :--- | :--- | :--- |  
| Průměr všech odvětví | 1 287,46 | 1 342,24 | + 54,78 | + 4,3 % | 
| Nejlépe placené (I. a K. činnosti) | 2 462,17 (Peněž.) | 2 314,41 | - 147,76 | - 6,0 % | 
| Nejhůře placené (Ubytování, stravování) | 706,58 | 774,33 | + 67,75 | + 9,6 % | 

Nejlépe placené odvětví (Informační a komunikační činnosti) tedy zaznamenalo pokles kupní síly o 6 %, což naznačuje, že průměrná cena chleba rostla rychleji než průměrná mzda v tomto odvětví v daném období. I přes tento pokles si však toto odvětví stále koupí více než trojnásobek chleba oproti nejhůře placenému odvětví.

### **3. Která kategorie potravin zdražuje nejpomaleji (je u ní nejnižší percentuální meziroční nárůst)?**

Z analýzy růstu cen potravin vyplynulo, že některé položky, jako třeba Cukr a Rajská jablka, šly dokonce proti inflaci a v průměru za rok zlevnily. Růst cen u těchto potravin byl tak nejpomalejší a nejstabilnější ze všech sledovaných kategorií.

* **Přehled kategorií s nejnižším nárůstem cen**

Nejpomalejší růst cen zaznamenaly položky, u kterých došlo k průměrnému poklesu cen napříč sledovanými lety:
| Hodnocení | Kategorie potravin | Průměrný roční nárůst ceny (%) | 
| :--- | :--- | :--- |
| 1. místo (Nejpomalejší růst) | Cukr krystalový | - 1,92 % | 
| 2. místo | Rajská jablka červená kulatá | - 0,74 % | 
| 3. místo | Banány žluté | 0,81 % | 
| 4. místo | Vepřová pečeně s kostí | 0,99 % | 
| 5. místo | Přírodní minerální voda uhličitá | 1,02 % | 

* **Extrémy a nejrychlejší zdražování**

Na opačném konci spektra se nachází kategorie, u kterých docházelo k nejrychlejšímu meziročnímu zdražování:
| Hodnocení | Kategorie potravin | Průměrný roční nárůst ceny (%) | 
| :--- | :--- | :--- |
| Nejrychlejší růst | Papriky | 7,29 % | 
| Předposlední | Máslo | 6,68 % | 
| Třetí od konce | Vejce slepičí čerstvá | 5,56 % | 

Kategoriemi potravin s nejpomalejším růstem ceny jsou tedy Cukr krystalový (-1,92 %) a Rajská jablka červená kulatá (-0,74 %). U těchto položek došlo v průměru za sledované období dokonce ke snížení průměrné ceny. Naopak, nejrychlejší cenový růst zaznamenaly Papriky s průměrným ročním nárůstem 7,29 %.

### **4. Existuje rok, ve kterém byl meziroční nárůst cen potravin výrazně vyšší než růst mezd (větší než 10 %)?**

Ne, analýza neidentifikovala žádný rok, ve kterém by průměrný meziroční nárůst cen potravin přesáhl nárůst mezd o více než 10 procentních bodů.
Největší rozdíl ve prospěch růstu cen potravin byl zaznamenán v roce 2013, kdy ceny rostly rychleji než mzdy o 6,66 procentního bodu.
| Rok | Růst Cen Potravin (%) | Růst Mezd (%) | Rozdíl (Ceny - Mzdy) | 
| :--- | :--- | :--- | :--- |
| 2013 | 5,10 | -1,56 | 6,66 p.b. | 
| 2012 | 6,73 | 3,03 | 3,70 p.b. | 
| 2017 | 9,63 | 6,28 | 3,35 p.b. | 

Přestože nebyla překročena hranice 10 p.b., rok 2013 je z hlediska reálné kupní síly nejdramatičtější:
* Růst cen potravin byl v tomto roce pozitivní (5,10 %).
* Průměrná mzda celkově klesla (-1,56 %).
* Tato kombinace (růst cen + pokles mezd) měla v roce 2013 největší negativní dopad na reálnou kupní sílu občanů ve sledovaném období.

### **5. Má výška HDP vliv na změny ve mzdách a cenách potravin? Neboli, pokud HDP vzroste výrazněji v jednom roce, projeví se to na cenách potravin či mzdách ve stejném nebo následujícím roce výraznějším růstem?**

Na základě analyzovaných dat za období 2007–2018 nelze říci, že by výška růstu HDP měla v daném roce vždy přímý a silný vliv na stejný růst mezd a cen. Vztahy jsou komplexní, často zpožděné (setrvačné) a ovlivněné vnějšími faktory (např. vládní regulace cen, globální trhy).

a. Vliv růstu HDP na Změny ve Mzdách

Vztah mezi růstem HDP a růstem mezd je silný, ale typicky s ročním zpožděním.
| Rok silného růstu HDP	% | Změna HDP	% | Změna Mzdy v následujícím roce | Pozorování | 
| :--- | :--- | :--- | :--- |
| 2007 | 5.57 % | 7.87 % (v roce 2008) | Vysoký růst HDP v roce 2007 vedl k vysokému růstu mezd v roce 2008, i když HDP již zpomalilo. | 
| 2017 | 5.17 % | 7.62 % (v roce 2018)| Podobně, silný růst HDP v roce 2017 vedl k akceleraci růstu mezd v roce 2018, i když HDP již zpomalovalo. | 

Pokud HDP vzroste výrazněji v jednom roce (např. > 5 % v letech 2007, 2015, 2017), projeví se to na mzdách spíše v následujícím roce. V daném roce je mzdový růst často spíše pokračováním trendu z předchozího období (viz rok 2008). Během poklesu HDP v roce 2009 (-4.66 %) se mzdy držely a stále rostly (3.16 %), což naznačuje, že mzdy reagují na krize pomaleji než HDP.

b. Vliv růstu HDP na Změny v Cenách Potravin

Vztah mezi růstem HDP a růstem cen potravin je méně přímý a je významně narušen vnějšími vlivy a cenovými šoky.
* V letech silného ekonomického růstu (např. 2007, kde HDP rostlo o 5.57 % a ceny o 6.76 %; a 2017, kde HDP rostlo o 5.17 % a ceny o 9.63 %), se zdá, že silná poptávka tažená HDP dokáže výrazně zvednout i ceny.
* 2009: HDP prudce kleslo, ceny reagovaly poklesem (-6.42 %)
* 2012–2013: HDP stagnovalo/klesalo (-0.79 % a -0.05 %), přesto ceny rostly velmi rychle (6.73 % a 5.10 %). Tento vztah je silně narušen, pravděpodobně vládními zásahy (např. zvýšení DPH).
* 2015–2016: HDP rostlo velmi silně (až 5.39 %), ale ceny potravin klesaly (-0.55 % a -1.19 %), což bylo patrně dáno vnějšími vlivy

Má tedy výška HDP vliv na změny ve mzdách? Spíše ne přímo v daném roce. Výrazný růst HDP se spolehlivě projeví výrazným růstem mezd, ale obvykle až v následujícím roce. V daném roce jsou mzdy setrvačné.

Má výška HDP vliv na změny v cenách potravin? Má, ale jen za ideálních podmínek. Vliv je silný v obdobích růstu (2007, 2017), ale často je potlačen nebo překonán vnějšími vlivy (DPH, levné/drahé komodity).

## Závěr a Doporučení

* Analýza potvrzuje, že dynamika růstu mezd a cen potravin má přímý a složitý dopad na reálnou kupní sílu obyvatel České republiky.
* Přestože celkový trend je růst mezd, sledované období bylo narušeno krizovými lety. Rok 2013 představoval největší šok pro kupní sílu, kdy průměrná mzda poklesla ve více než polovině odvětví, zatímco ceny potravin rostly (rozdíl 6,66 procentního bodu ve prospěch cen).
* Analýza ukázala pozitivní trend, kdy se rozdíl v kupní síle (měřený v litrech mléka a kilogramech chleba) mezi nejlépe a nejhůře placenými odvětvími mírně snížil v letech 2006 až 2018. To naznačuje, že mzdy v nízkopříjmových odvětvích rostly relativně rychleji ve vztahu k cenám těchto základních komodit.
* U nejlépe placeného odvětví (Informační a komunikační činnosti) byl zaznamenán pokles reálné kupní síly chleba o 6 %, což upozorňuje na skutečnost, že rychlý růst cen specifických komodit může zasáhnout i vysokopříjmové skupiny.
* Největší cenovou stabilitu, vedoucí v průměru k deflaci, vykazovaly komodity jako Cukr krystalový (-1,92 %) a Rajská jablka červená kulatá (-0,74 %). Tyto položky působily jako stabilizátory spotřebního koše.
* Naopak, největší cenovou volatilitu a riziko pro rozpočty domácností představují položky jako Papriky (+7,29 %) a Máslo (+6,68 %), jejichž průměrný roční nárůst byl násobně vyšší než celková inflace.

Výsledky analýzy jasně indikují, že životní úroveň občanů je silně ovlivněna ekonomickými vlivy (např. v roce 2013) a cenovou dynamikou v segmentu základních potravin. Pro budoucí politická a ekonomická rozhodování je klíčové monitorovat zejména vývoj mezd v odvětvích s tradičně nízkou kupní silou (např. Ubytování, stravování a pohostinství), protože jakékoli výrazné inflační vlny v cenách potravin zasahují tyto skupiny nejtvrději.
