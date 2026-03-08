# Aktion Mesch - Dokumentacia dotaznikov

## Prehľad


| # | Skupina | PRED (pocet otazok) | PO (pocet otazok) |
|---|---------|--------------------|--------------------|
| 1 | Puberta (deti) | 24 | 23 |
| 2 | Sexualne a reprodukcne zdravie (deti) | 25 | 23 |
| 3 | Rodicia | 27 | 24 |
| 4 | Inovacne vzdelavanie (ucitelia/odbornici) | 35 | 37 |

Vsetky dotazniky su v Google Forms. Momentalne je **0 realnych odpovedi** vo vsetkych suboroch.

---
## OVERALL NOTES
1. Kedze sa jedna o rocniky kazdy dotaznik ku detom by sa mal pytat na rocnik ak chceme sledovat priebeh pocas rokov 
2. Meratelne otazky musia mat jasne definovane ocakavane odpovede hlavne volny text
3. Prvy dotaznik ma len 3 meratelne vedomostne otazky. Za mna ja by som sla hlbsie trochu ich preskusala, primerane veku a attention span ale predsa. Nieco viac ako len všeobecné deskriptory respondentov. 
    - taktiez meratelne otazky ako volny text je mierne problematicke okrem likert skal
---

## 1. PUBERTA - Dotaznik PRED workshopom

| # | Otazka | Typ odpovede | Mozne hodnoty / Rozsah | Poznamky k spracovaniu |
|---|--------|-------------|----------------------|----------------------|
| 0 | Casova peciatka | Automaticka | Datum + cas | Google Forms generuje automaticky. Format moze byt nekonzistentny pri rucnom exporte. |
| 1 | Uved svoj vek | Nespecifikovane | Predpoklad: volny text ALEBO rozsahy (10-14, 15-18, 19-25, 26-30) | **PROBLEM**: Ak je volny text, respondenti mozu zadat cokoľvek (cislo, text, rozsah). Ak su rozsahy, nie je mozne pocitat priemer/median. Treba overit ci je to dropdown alebo volny text v Google Forms. |
| 2 | Som | Single choice | Zena, Muz, Nechcem uviest | Kategoricka premenna. Chyba moznost "Ine". |
| 3 | Uved skolu a mesto | Volny text | - | **PROBLEM**: Skola a mesto su v jednom poli. Pri analyze sa bude musiet manualne parsovat/rozdelit. Ludia mozu pisat v roznom formate ("ZS Kukucinova, Kosice" vs "kosice zs kukucinova"). Takiez nie je jasne ci mesto skoly, alebo odkial pochadzaju. Odporucanie: rozdelit na 2 separatne polia (mesto bydliska?)+ pouzit dropdown pre skoly. |
| 4 | O com sa podla teba budeme na workshope bavit? | Volny text | - | Exploratory otazka. Vyzaduje kvalitativnu analyzu alebo text coding. |
| 5 | Co by si sa chcel/a na workshope dozvediet? | Volny text | - | Kvalitativna analyza. Pre kvantifikaciu by bolo lepsie pouzit kategorie + "ine". |
| 6 | Co uz o puberte vies? | Volny text | - | **PROBLEM**: Velmi siroka otazka. Respondenti si ju mozu rozne vylozit. Tazko kvantifikovatelna. |
| 7 | Je podla teba dolezite rozpravat sa o Puberte | Single choice | Ano, Neviem, Nie | Kategoricka premenna, 3 urovne. |
| 8 | Prosim, povedz preco | Volny text | - | Naviazane na Q7. Conditionalne - relevantne hlavne ak Q7 != Neviem. |
| 9 | Z akych zdrojov mas najcastejsie informacie o vztahoch, puberte a temach spojenych so sexualitou? | Multiple choice | ~10 moznosti | Respondent moze vybrat viacero. Pri exporte budu odpovede oddelene ciarkou v jednom poli - one hot encoding needed.|
| 10 | Ake zmeny pocas puberty prichadzaju a ako sa na ne mozeme pripravit? | Volny text | - | Vedomostna otazka - pouzitelna na meranie PRED/PO. |
| 11 | Ako mozeme pomoct ludom, ktori v puberte zazivaju tazkosti? | Volny text | - | Vedomostna otazka - pouzitelna na meranie PRED/PO. |
| 12 | Co by sme mali podla teba robit, aby sme pubertu zvladli v zdravi a pohode? | Volny text | - | Vedomostna otazka - pouzitelna na meranie PRED/PO. |
| 13-18 | Vyjadri ci a ako suhlasiš s vyrokom: [6 vyrokov] | Likert skala | Predpoklad: Suhlasim - Nesúhlasim (pocet urovni nespecifikovany) | **PROBLEM**: Nie je jasne ci je to 5-bodova, 7-bodova alebo 10-bodova skala. Treba overit v Google Forms. Vyroky: (1) 3 znaky puberty, (2) co je menstruacia, (3) preventivne prehliadky, (4) akne je prirodzeny jav, (5) co je polucia, (6) starostlivost o telo/hygiena. |
| 19 | Vies na koho sa obratit v skole ak by si mal/a problem? | Single choice | Predpoklad: Ano/Nie/Neviem | Kategoricka premenna. |
| 20 | Ak ano, kto by to bol | Volny text | - | Conditionalna otazka. |
| 21 | Chces s nami este nieco zdielat? | Volny text | - | Otvorena, volitelna. |

---

## 2. PUBERTA - Dotaznik PO workshope

| # | Otazka | Typ odpovede | Mozne hodnoty / Rozsah | Poznamky k spracovaniu |
|---|--------|-------------|----------------------|----------------------|
| 0 | Casova peciatka | Automaticka | Datum + cas | - |
| 1 | Uved svoj vek | Nespecifikovane | Rovnake ako PRED | Rovnaky problem ako PRED. |
| 2 | Som | Single choice | Zena, Muz, Nechcem uviest | - |
| 3 | Uved svoju skolu | Volny text | - | **ZMENA OPROTI PRED**: Tu sa pyta LEN skolu, v PRED sa pytalo skolu A mesto. |
| 4 | Na stupnici od 1 do 10, aky uzitocny bol pre teba workshop? | Numericka skala | 1 (Vobec) - 10 (Velmi) | Ciselna skala. |
| 5 | Co si na workshope naucil/a? | Volny text | - | - |
| 6 | Na workshope som sa citil/a bezpecne | Numericka skala | 1 (Nesuhlasim) - 10 (Suhlasim) | - |
| 7 | Ak si sa necitil/a bezpecne, prosim povedz preco | Volny text | - | Conditionalna. |
| 8 | Na stupnici od 1 do 10, ako by si odporucil/a workshop? | Numericka skala | 1-10 | - |
| 9 | Co by sme mali na workshope vylepsit? | Volny text | - | - |
| 10 | Co ti este chybalo na workshope? | Volny text | - | - |
| 11-13 | Vedomostne otazky (rovnake ako PRED Q10-12) | Volny text | - | Klucove pre meranie dopadu - porovnanie PRED vs PO. |
| 14-19 | Vyjadri ci a ako suhlasiš s vyrokom [6 vyrokov - rovnake ako PRED] | Likert skala | Rovnake ako PRED | Klucove pre meranie dopadu - porovnanie PRED vs PO. |
| 20 | Chces s nami este nieco zdielat? | Volny text | - | - |

### Poznamky k parovaniu PRED/PO (Puberta):
- 3 vedomostne otazky +1 nazorova priamo meratelne, inak deskriptory
- chyba rocnik

---

## 3. SEXUALNE A REPRODUKCNE ZDRAVIE - Dotaznik PRED

| # | Otazka | Typ odpovede | Mozne hodnoty / Rozsah | Poznamky k spracovaniu |
|---|--------|-------------|----------------------|----------------------|
| 0 | Casova peciatka | Automaticka | - | - |
| 1 | Uved svoj vek | Nespecifikovane | - | Rovnaky problem ako Puberta. |
| 2 | Som | Single choice | Zena, Muz, Nechcem uviest | - |
| 3 | Uved skolu a mesto | Volny text | - | Rovnaky problem ako Puberta PRED - jedno pole pre dve info. |
| 4 | O com sa podla teba budeme na workshope bavit? | Volny text | - | - |
| 5 | Co by si sa chcel/a na workshope dozvediet? | Volny text | - | - |
| 6 | Co uz o sexualnom a reprodukcnom zdravi vies? | Volny text | - | Siroka otazka. |
| 7 | Uz si sa vo svojom okoli stretol/la s vyhladavanim zdravotnej starostlivosti v spojeni so sexualitou alebo reprodukciou? | Single choice | Ano, Neviem, Nie | - |
| 8 | Ak ano, prosim uved konkretny priklad | Volny text | - | Conditionalna. |
| 9 | Z akych zdrojov mas najcastejsie informacie...? | Multiple choice | ~10 moznosti | - |
| 10 | Co vsetko podla teba pod sexualne a reprodukcne zdravie spada? | Volny text | - | Vedomostna - pre PRED/PO porovnanie. |
| 11 | Ake su podla teba sexualne a reprodukcne prava? | Volny text | - | Vedomostna - pre PRED/PO porovnanie. |
| 12 | Ako a s kym sa podla teba bezny clovek potrebuje rozpravat o SRZ? | Volny text | - | Vedomostna - pre PRED/PO porovnanie. |
| 13-18 | Vyjadri ci suhlasiš s vyrokom [6 vyrokov] | Likert skala | Nespecifikovany rozsah | Vyroky: (1) poznam zakladne prava SRZ, (2) starostlivost o reprodukcne organy, (3) ochrana pred nechcenym otehotnenim/STI, (4) samovysetrenie prsnikov/semennikov, (5) preventivne prehliadky gynekologia/urologia, (6) pomenovanie pohlavnych organov. |
| 19 | Vies na koho sa obratit v skole ak by si mal/a problem? | Single choice | Predpoklad: Ano/Nie/Neviem | - |
| 20 | Ak ano, kto by to bol | Volny text | - | - |
| 21 | Myslis si ze tvoja skola ma postupy ako riesit ublizujuce spravanie? | Single choice | Predpoklad: Ano/Nie/Neviem | Otazka navyse oproti Puberte. |
| 22 | Chces s nami este nieco zdielat? | Volny text | - | - |

---

## 4. SEXUALNE A REPRODUKCNE ZDRAVIE - Dotaznik PO

| # | Otazka | Typ odpovede | Mozne hodnoty / Rozsah | Poznamky k spracovaniu |
|---|--------|-------------|----------------------|----------------------|
| 0 | Casova peciatka | Automaticka | - | - |
| 1 | Uved svoj vek | Nespecifikovane | - | - |
| 2 | Som | Single choice | - | - |
| 3 | Uved svoju skolu | Volny text | - | **ZMENA**: Opat len skola, bez mesta (PRED ma oboje). |
| 4 | Na stupnici 1-10 aky uzitocny bol workshop? | Numericka skala | 1-10 | - |
| 5 | Co si na workshope naucil/a? | Volny text | - | - |
| 6 | Na workshope som sa citil/a bezpecne | Numericka skala | 1-10 | - |
| 7 | Ak si sa necitil/a bezpecne, prosim povedz preco | Volny text | - | - |
| 8 | Na stupnici 1-10 odporucil/a by si workshop? | Numericka skala | 1-10 | - |
| 9 | Co by sme mali vylepsit? | Volny text | - | - |
| 10 | Co ti chybalo na workshope? | Volny text | - | - |
| 11-13 | Vedomostne otazky (rovnake ako PRED Q10-12) | Volny text | - | Pre PRED/PO porovnanie. |
| 14-19 | Vyjadri ci suhlasiš s vyrokom [6 vyrokov - rovnake ako PRED] | Likert skala | Nespecifikovany rozsah | Pre PRED/PO porovnanie. |
| 20 | Chces s nami este nieco zdielat? | Volny text | - | - |

### Poznamky k parovaniu PRED/PO (SRZ):
- Navyse: PRED obsahuje otazky Q21 (postupy skoly) ktore v PO chybaju. - mozno sa im zmenilaq def. ublizujuceho spravania?

---

## 5. RODICIA - Dotaznik PRED

| # | Otazka | Typ odpovede | Mozne hodnoty / Rozsah | Poznamky k spracovaniu |
|---|--------|-------------|----------------------|----------------------|
| 0 | Casova peciatka | Automaticka | - | - |
| 1 | E-mailova adresa | Automaticka / Volny text | - | **VOLITELNE**: Dospeli si mozu zvolit ci uvedu email alebo zostavaju anonymni. Ak je uvedeny, umoznuje parovanie PRED/PO. |
| 2 | Vase pohlavie | Single choice | Zena, Muz, Intersex, Nechcem uviest | **ROZDIEL**: Toto je jediny dotaznik kde je moznost "Intersex". Ostatne dotazniky maju len Zena/Muz/Nechcem uviest. |
| 3 | Vas vek | Volny text | - | **ROZDIEL**: Tu je vek ako volny text (nie rozsahy). Moze obsahovat cisla ale aj text. |
| 4 | Vek vasho dietata | Volny text | - | **PROBLEM**: Ak ma rodic viacero deti, nevieme ktore ma na mysli. Moze zadat viacero hodnot, rozsah, atd. = vela cistenia|
| 5 | Co by ste sa chceli na workshope dozvediet? | Volny text | - | - |
| 6 | Riesili ste v minulosti temu menstruacie s detmi? | Single choice | Ano, Neviem, Nie | - |
| 7 | Ak ano, ako ste rozhovor uchopili? | Volny text | - | Conditionalna. |
| 8 | Chceli by ste sa o situaciu podelit? | Volny text | - | - |
| 9 | Mozeme uvedenu situaciu pouzit anonymne? | Boolean | Ano/Nie (T/F) | - |
| 10 | Ake su najdolezitejsie informacie o menstruacii pre deti? | Volny text | - | - |
| 11 | V akom veku je najlepsie zacat sa rozpravat o menstruacii? | Volny text | - | **PROBLEM**: Malo by byt numericke alebo rozsah. Volny text vedie k nekonzistentnym odpovediam ("od 8", "v 10 rokoch", "pred pubertou", atd.). |
| 12 | Ake menstruacne pomocky pouzivate? | Volny text | - | **PROBLEM**: Malo by byt multiple choice (vlozky, tampony, kalisok, menstruacne nohavicky, atd.) + "Ine (vypisete)". Volny text bude velmi tazko kvantifikovatelny. |
| 13 | Absolvovali ste niekedy vzdelavanie o pohlavnom zdravi? | Volny text | - | **PROBLEM**: Kombinuje Ano/Nie otazku s popisom v jednom poli. Malo by byt rozdelene na: (1) Ano/Nie, (2) Ak ano, popisete. |
| 14 | Ake zdroje by vam v teme menstruacie najviac pomohli? | Volny text | - | - |
| 15 | Je pre mna narocne hovorit o genitalich a ich funkciach | Likert skala | Predpoklad: 1-10 alebo Suhlasim-Nesuhlasim | **MERANIE DOPADU**: Tieto otazky (15-26) su klucove pre PRED/PO porovnanie postojov a vedomosti. |
| 16 | Je pre mna narocne vysvetlit menstruaciu | Likert skala | Predpoklad: 1-10 | - |
| 17 | Viem vysvetlit zakladne informacie o menstruacii | Likert skala | Predpoklad: 1-10 | - |
| 18 | Tema menstruacie je cisto pre dievcata/zeny | Likert skala | Predpoklad: 1-10 | Mytus/postoj - meranie stereotypov. |
| 19 | O menstruacii by sme sa nemali rozpravat (nahlas) | Likert skala | Predpoklad: 1-10 | Mytus/postoj - meranie stigmy. |
| 20 | Momentalne viem uprimne a otvorene komunikovat s mojim dietatom | Likert skala | Predpoklad: 1-10 | - |
| 21 | Pocas menstruacie nie je mozne otehotniet | Likert skala | Predpoklad: 1-10 | Mytus - obratene skorovanie |
| 22 | Pocas menstruacie sa nemoze cvicit ci plavat | Likert skala | Predpoklad: 1-10 | Mytus - obratene skorovanie. |
| 23 | Pocas jednej menstruacie clovek strati viac ako pol litra krvi | Likert skala | Predpoklad: 1-10 | Mytus - obratene skorovanie |
| 24 | Tampon alebo kalisok sa mozu vo vagine stratit | Likert skala | Predpoklad: 1-10 | Mytus - obratene skorovanie. |
| 25 | Za menstruaciu by sme sa mali hanbit | Likert skala | Predpoklad: 1-10 | Mytus - obratene skorovanie. |
| 26 | Predmenstruacny syndrom (PMS) je mytus | Likert skala | Predpoklad: 1-10 | Mytus - obratene skorovanie. |

---

## 6. RODICIA - Dotaznik PO

| # | Otazka | Typ odpovede | Mozne hodnoty / Rozsah | Poznamky k spracovaniu |
|---|--------|-------------|----------------------|----------------------|
| 0 | Casova peciatka | Automaticka | - | - |
| 1 | E-mailova adresa | Automaticka | - | **VOLITELNE**: Ak uvedeny, umoznuje parovanie s PRED. |
| 2 | Workshop bol pre mna celkovo uzitocny | Numericka skala | 1 (Nesuhlasim) - 10 (Suhlasim) | - |
| 3 | Workshop by som odporucil/a znamym | Numericka skala | 1-10 | - |
| 4 | Na workshope som mohol/mohla otvorene zdielat svoje nazory | Numericka skala | 1-10 | - |
| 5 | V ramci vzdelavania ma najviac prekvapilo... | Volny text | - | - |
| 6 | Z workshopu si odnasam najma... | Volny text | - | - |
| 7-10 | Po absolvovani workshopu mozem o sebe prehlasit ze: [4 vyroky] | Likert skala | Predpoklad: 1-10 | Vyroky: (1) viesť diskusiu o puberte, (2) rozpravat o menstruacii, (3) tvorit bezpecie, (4) hovorit o genitalich. |
| 11 | Na workshope mi este chybalo... | Volny text | - | - |
| 12 | Co by sme mohli vylepsit? | Volny text | - | - |
| 13-18 | Facilitatorky workshopu podavali informacie: [6 aspektov] | Likert skala | Predpoklad: 1-10 | Hodnotenie lektoriek. |
| 19 | Pristup a praca facilitatoriek bola professionalna | Numericka skala | Predpoklad: 1-10 | - |
| 20 | Ako a co by mohli facilitatorky vylepsit? | Volny text | - | - |
| 21 | Kratke doporucenie na propagaciu workshopu | Volny text | - | Nie je analyticka premenna, marketingovy ucel. |
| 22 | Chcete s nami este nieco zdielat? | Volny text | - | - |

### Poznamky k parovaniu PRED/PO (Rodicia):
- V PO dotazniku **chybaju otazky Q15-26 z PRED** (postoje a myty o menstruacii). Tieto su klucove na meranie dopadu! Bez nich sa neda porovnat zmena vedomosti/postojov.
- **ODPORUCANIE**: Pridat otazky Q15-26 z PRED aj do PO dotaznika.

---

## 7. INOVACNE VZDELAVANIE (UCITELIA) - Dotaznik PRED

| # | Otazka | Typ odpovede | Mozne hodnoty / Rozsah | Poznamky k spracovaniu |
|---|--------|-------------|----------------------|----------------------|
| 0 | Casova peciatka | Automaticka | - | - |
| 1 | E-mailova adresa | Automaticka | - | **VOLITELNE**: Dospeli si mozu zvolit ci uvedu email alebo zostavaju anonymni. Ak uvedeny, umoznuje parovanie PRED/PO. |
| 2 | Som | Single choice | Zena/Muz/Ine | - |
| 3 | Vas vek | Volny text | - | Rovnaky problem s volnym textom. |
| 4 | Kraj v ktorom sa nachadzam | Single choice / Dropdown | 8 krajov SR | Dobre strukturovane. |
| 5 | Najvyssie dosiahnuté vzdelanie | Single choice | SŠ, VŠ Bc, VŠ Mgr/Ing, PhD | - |
| 6 | Vasa pracovna pozicia | Volny text / Single choice | - | - |
| 7 | O inovacnom vzdelavani som sa dozvedel/a z/od | Single choice / Multiple choice | - | - |
| 8 | Preco je pre vas dolezita vztahova a sexualna vychova? | Volny text | - | - |
| 9 | Mate skusenosti s pracou s detmi/mladezou v temach VSV? | Single choice | Ano/Nie | - |
| 10 | Ak ano, ake skusenosti + najvacsia vyzva? | Volny text | - | Conditionalna. Kombinuje 2 otazky v jednej - tazke na analyzu. |
| 11-15 | Pred absolvovanim vzdelavania mozem o sebe prehlasit ze: [5 vyrokov] | Likert skala | 1-10 | Vyroky: (1) viest diskusiu o vztahoch/sexualite, (2) hovorit o suhlase, (3) riesit krizove situacie, (4) vekovo adekvátne info, (5) tvorit bezpecne prostredie. **Klucove pre PRED/PO porovnanie.** |
| 16-24 | Vyjadrite uroven zrucnosti 1-10: [9 zrucnosti] | Numericka skala | 1 (najmenej sebaisto) - 10 (velmi sebaisto) | Zrucnosti: vysvetlovanie, recovy prejav, instrukcie, vedomosti, cas, spolupraca, vlastne postoje, reflexia predsudkov, praca so skupinou. **Klucove pre PRED/PO porovnanie.** |
| 25 | Najdolezitejsia pridana hodnota lektora? | Volny text | - | - |
| 26 | Kedy hodnotite WS ako uspesny? | Volny text | - | - |
| 27 | Monitorujete progres vasich zrucnosti? | Single choice | Predpoklad: Ano/Nie | - |
| 28 | Ak ano, podla coho viete ze sa posuvate? | Volny text | - | Conditionalna. |
| 29 | Co vas motivovalo k prihlaseniu? | Volny text | - | - |
| 30 | V akych oblastiach by ste chceli uplatnit zrucnosti? | Volny text | - | - |
| 31 | Zo vzdelavania by som si chcel/a odniest... | Volny text | - | - |
| 32 | Chcete s nami nieco zdielat? | Volny text | - | - |

---

## 8. INOVACNE VZDELAVANIE (UCITELIA) - Dotaznik PO

| # | Otazka | Typ odpovede | Mozne hodnoty / Rozsah | Poznamky k spracovaniu |
|---|--------|-------------|----------------------|----------------------|
| 0 | Casova peciatka | Automaticka | - | - |
| 1 | E-mailova adresa | Automaticka | - | **VOLITELNE**: Ak uvedeny, umoznuje parovanie s PRED. |
| 2 | Inovacne vzdelavanie bolo pre mna celkovo uzitocne | Numericka skala | 1-10 | - |
| 3 | Vzdelavanie by som odporucil/a kolegom | Numericka skala | 1-10 | - |
| 4 | Moje ocakavania boli naplnene | Numericka skala | 1-10 | - |
| 5 | Najviac ma prekvapilo... | Volny text | - | - |
| 6 | Zo vzdelavania si odnasam... | Volny text | - | - |
| 7-10 | Po absolvovani vzdelavania mozem o sebe prehlasit ze: [4 vyroky] | Likert skala | Predpoklad: 1-10 | **PROBLEM**: PRED ma 5 vyrokov (Q11-15), PO ma len 4 (Q7-10). Vyrok o "bezpecnom prostredi" z PRED chyba v PO. Neda sa plne porovnat. |
| 11-16 | V tychto oblastiach sa chcem zlepsovat: [6 oblasti] | Checkbox / Multiple choice | Predpoklad: zakmitnutie = ano | Oblasti: vysvetlovanie, recovy prejav, faktografia, cas, spolupraca, vlastne postoje. **PROBLEM**: V PRED je 9 zrucnosti na skale 1-10, v PO je 6 oblasti ako checkboxy. Uplne iny format - neda sa priamo porovnat! |
| 17-19 | Organizacna stranka vzdelavania: [3 aspekty] | Likert skala | Predpoklad: 1-10 | Evaluacne, nie pre PRED/PO porovnanie. |
| 20 | Na vzdelavani sa mi pacilo | Volny text | - | - |
| 21 | Na vzdelavani sa mi nepacilo | Volny text | - | - |
| 22 | Co by sme mohli vylepsit? | Volny text | - | - |
| 23 | Pristup a praca facilitatoriek bola professionalna | Numericka skala | Predpoklad: 1-10 | - |
| 24-28 | Facilitatorky podavali informacie: [5 aspektov] | Likert skala | Predpoklad: 1-10 | - |
| 29 | Co by mohli facilitatorky vylepsit? | Volny text | - | - |
| 30 | Mam chut spolupracovat s InTYMYtou | Numericka skala / Single choice | Predpoklad: 1-10 alebo Ano/Nie | - |
| 31 | Mam konkretny napad na spolupracu | Volny text | - | - |
| 32 | V buducnosti by som sa chcel/a venovat cielovej skupine | Multiple choice | Viacero moznosti | - |
| 33 | Datum a miesto narodenia (certifikat) | Volny text | - | Administrativny ucel. |
| 34 | Chcete s nami nieco zdielat? | Volny text | - | - |

### Poznamky k parovaniu PRED/PO (Ucitelia):
- Sebahodnotenie zrucnosti v PRED (9 poloziek, skala 1-10) a v PO (6 poloziek, checkboxy) su v **uplne ineom formate**. Neda sa priamo porovnat zmena.
- **ODPORUCANIE**: V PO dotazniku pouzit rovnake otazky Q11-15 a Q16-24 z PRED (so skalou 1-10).

---

## SUHRN SYSTEMOVYCH PROBLEMOV

### 1. Nekonzistentnost veku napriec dotaznikmi
| Dotaznik | Format veku |
|----------|------------|
| Puberta PRED/PO | Nespecifikovane (mozno rozsahy 10-14, 15-18...) |
| Rodicia PRED | Volny text |
| Ucitelia PRED | Volny text |
| SRZ PRED/PO | Nespecifikovane |

**Dopad**: Neda sa jednotne analyzovat vekova distribucia. Rozsahy neumoznuju priemer/median.
**Riesenie v Google Forms**: Pouzit "Short answer" s response validation (Number, between X and Y).

### 2. Nekonzistentne otazky medzi PRED a PO
| Skupina | Problem |
|---------|---------|
| Puberta | PRED pyta "skolu a mesto", PO len "skolu" |
| SRZ | PRED pyta "skolu a mesto", PO len "skolu"; PRED ma otazky o skole (Q19-21) ktore PO nema |
| Rodicia | PO **nema** otazky o mytoch/postojoch (Q15-26 z PRED) - neda sa merat dopad |
| Ucitelia | PRED ma 5 sebahodnotiacich vyrokov + 9 zrucnosti na skale, PO ma 4 vyroky + 6 checkboxov - **iny format** |

**Dopad**: Priame PRED/PO porovnanie je nemozne alebo obmedzene pri vsetkych skupinach.
**Riesenie**: Zjednotit otazky - vedomostne a postojove otazky z PRED musia byt identicke v PO.

### 3. Nadmerny podiel volneho textu
| Skupina | Pocet otazok | Volny text | % volneho textu |
|---------|-------------|-----------|----------------|
| Puberta PRED | 24 | ~10 | ~42% |
| SRZ PRED | 25 | ~10 | ~40% |
| Rodicia PRED | 27 | ~11 | ~41% |
| Ucitelia PRED | 35 | ~14 | ~40% |

**Dopad**: Volny text vyzaduje manualne kodovanie alebo NLP pre kvantitativnu analyzu. S malym poctom respondentov (3 skoly) to moze byt zvladnutelne, ale so skalovanim projektu (3 roky) sa stane nepraktickym.
**Riesenie v Google Forms**: Nahradit volny text kde sa da za:
- Multiple choice (jedna odpoved)
- Checkboxes (viacero odpovedi)
- Multiple choice grid (matice)
- Ponechat "Ine (vypisete)" ako poslednu moznost

### 4. Skola a mesto v jednom poli
**Dopad**: Manualne parsovanie, nekonzistentne formaty, mozne preklepy.
**Riesenie v Google Forms**: Rozdelit na 2 otazky. Pre skoly pouzit Dropdown (ak je zoznam skol znamy) alebo Short answer s instrukciami.
---

## ODPORUCANIA PRE GOOGLE FORMS UPRAVU

1. **Zjednotit format veku** - pouzit "Number" validation (Short answer, must be number between 6 and 99)
4. **Rozdelit "skola a mesto"** na 2 separatne otazky, idealne s dropdown
5. **Zjednotit otazky medzi PRED a PO** - vedomostne a postojove otazky by mali byt identicke
6. **Pridat mytus/postoj otazky do Rodicia PO** (Q15-26 z PRED)
7. **Zjednotit format sebahodnotenia v Ucitelia PO** na skalu 1-10 (rovnako ako v PRED)
8. **Nahradit volny text za structured odpovede** kde je to mozne (menstruacne pomocky, zdroje info, vek kedy zacat rozpravat)
9. **Standardizovat Likert skaly** na rovnaky rozsah napriec vsetkymi dotaznikmi
10. **Pridat pohlavie a vek do Rodicia PO** (momentalne chybaju)
