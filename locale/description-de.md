# Stronghold Crusader KI‑Turnier 2025 – Offizielle Regeln & Setup

Dieses Turnier fordert Modder heraus, überzeugende KI-Charaktere zu erschaffen, die in verschiedenen Szenarien gegeneinander antreten. Teilnehmende reichen **eine funktionierende KI** für die gegebenen Randbedingungen ein:
- Die **Ascension AI Balance** ist eine bestimmende Rahmenbedingung für das gesamte Turnier.
- Die **Ascension-typischen**, harschen Startbedingungen (z.B. 0 Startgold) sind leicht für KI-Standards angepasst.

![Description](https://raw.githubusercontent.com/Krarilotus/Ascension-AI-Tournament/refs/heads/main/bootstrap_finaltrans.png)

---

## I. Setup & Startressourcen

Wenn ihr es hierher geschafft habt, seid ihr schon fast fertig: Denn zum Testen, KI-Erstellen und Einsenden ist lediglich das **Ascension-AI-Tournament**-Plugin notwendig. Damit sind alle Einstellungen gegeben, die Startbedingungen könnt ihr dann im Spiel mit euren KIs testen. Aber keine Bange, fast alle KIs, die in *Vanilla* gut funktionieren, funktionieren auch in **Ascension**.  

Für die wichtigsten Änderungen könnt ihr euch die Zusammenfassung des **Ascension-AI-Balance**-Plugins durchlesen. Wenn ihr es ganz genau wissen wollt, dann guckt doch gerne in die Tabelle mit den Werten:
- **[Ascension-AI-Balancesheet](https://docs.google.com/spreadsheets/d/1CyEB7tdixSODzZCHn2xPRCGAScqicDi4k6oUCilch4A/edit?gid=0#gid=0)**
- **[Vanilla Balance zum Vergleich](https://docs.google.com/spreadsheets/d/1PdMwVbIfu8c2ebszkSiqlALeZ0YWL_1nHp9TEU10r48/edit?gid=0#gid=0)**

---

## II. Einreichungen – Das richtige Format wählen!

Um am Turnier teilzunehmen, ist es erforderlich, eine UCP3-kompatible KI einzusenden. Dafür erstellt ihr euch einen Account auf **[GitHub](https://www.github.com)** und ein eurer KI gleichnamiges Repositorium mit einem funktionierenden Plugin, das eure KI im **resources/ai**-Ordner enthält.
Den Link zu eurem GitHub-Repositorium eurer KI sendet ihr dann z.B. per Discord an **Xander10alpha** oder per E-Mail an **shc.aicontest@gmail.com**.

Wie ihr eine solche KI erstellen könnt, könnt ihr **[hier im Wiki](https://unofficialcrusaderpatch.com/#wiki/Stronghold-Crusader-Wiki%2FAI-Lords%2FAI-Editing-Tutorial)** nachlesen. Unsere persönliche Empfehlung ist es aber, einfach mal auf der **[Stronghold Modschmiede](https://discord.com/invite/sKtrj9S626)** nachzufragen, wenn ihr Hilfe braucht, und euch an einer bestehenden KI aus dem Plugin (unter **resources/ai**) zu orientieren. Viel Spaß beim Bauen ;)

Unser Wunsch ist es, dass die KIs nicht nur **sehr gut funktionieren** und mit den Startbedingungen auskommen. Es wäre besonders wünschenswert, wenn die **KIs auch einen eigenen Charakter verkörpern**, z.B. durch eine Hintergrundgeschichte (Beschreibung) und ein eigenes KI-Portrait sowie animierte Videos & Audio-Dateien.

Außerdem gelten folgende Einschränkungen:  
- Maximal 12 Starttruppen (von bereits in der AIC vorhandenen Truppentypen)
- Maximale Lordstärke 1.5
- Keine unnötigen Exploits!

Für die Einreichung wird auch zwingend eine sortierte Präferenzliste der im Plugin verfügbaren Karten erwartet. Jeder Map-Pick wird im Turnierverlauf einmalig berücksichtigt und danach aus der Liste gelöscht. Für Entscheidungsspiele wird eine zufällige Auswahl getroffen, aus den Karten die von beteiligten KIs zusammengenommen bisher am wenigsten gespielt wurden.  
**Anmerkungen:** 
- Für 2 vs 2 Karten wird außerdem eine präferierte Position erwartet.  
- Es sind mindestens 5 Karten für das 1 vs 1, zwei Karten für das 2 vs 2 und eine Karte für das Alle gegen Alle zu wählen  
- Die finale Kartenliste kann im Appendix (siehe VI.) eingesehen werden.  

---

## III. Turnierablauf

Spiele enden immer spätestens nach 50 Jahren, was in einem Unentschieden resultiert! Dieses Limit beträgt für Karten mit Dummy AIs 60 Jahre und für 2 vs 2 Matches 75 Jahre.

### Spielplan
__Einleitungsphase:__ Es wird eine Einführungsrunde geben, in der alle KIs in einer Kurzvorstellung gezeigt werden, bevor das eigentliche Turnier stattfindet.

__Phase 1:__ Das Turnier findet anfänglich im klassischen **[Schweizer System](https://de.wikipedia.org/wiki/Schweizer_System)** statt. Es wird mindestens **zwei Runden im Schweizer System** zur grundlegenden Einordnung der KIs geben. Die genaue Anzahl steigt mit der Anzahl der teilnehmenden KIs.  

__Phase 2:__ Es schließt sich eine Runde **[Jeder gegen Jeden (4 Spieler FFA)](https://en.wikipedia.org/wiki/Deathmatch)** an und anschließend **zwei Runden 2 vs. 2**. Dabei werden für jede der Runden die Teams anhand der aktuellen Punkte aus der Tabelle gematcht: Der Erste mit dem Letzten, der Zweite mit dem Vorletzten usw. Dabei fällt die Kartenwahl an den Punkteschwächeren und die Positionswahl an den Punktestärkeren im Team. In Jeder gegen Jeden Spielen wird das Angriffsziel aller KIs festgesetzt auf **Gold**.

__Abschlussphase:__ Zum Abschluss kommt eine finale Runde **1 vs. 1** nach **[Schweizer System](https://de.wikipedia.org/wiki/Schweizer_System)**-Verteilung.

### Punkteverteilung
**Siegpunkte:** Für **1 vs. 1**- und **2 vs. 2**-Spiele werden pro KI nach Spielausgang folgende **Siegpunkte (SP)** ausgeschüttet:
- **Gewinn:** 2 SP
- **Unentschieden:** 1 SP
- **Verloren:** 0 SP

Im Free for all (FFA) werden für die Platzierung die folgenden SP ausgeschüttet:
- **Platz 1:** 3 SP
- **Platz 2:** 2 SP
- **Platz 3:** 1 SP
- **Platz 4:** 0 SP
- **Unentschieden** (für alle übrigen KIs): 2 SP


**Bonuspunkte:** Weiterhin gibt es für die einzelnen Phasen die folgenden Bonus-Challenges, für die es **Bonuspunkte (BP)** gibt. Diese sind äquivalent zu Siegpunkten, beeinflussen aber nicht das Matchmaking:

__Phase 1:__ Für jede dieser Challenges gibt es für die **besten N KIs** der Phase in jeder der Kategorien je einen Punkt, wobei **N die Anzahl der Runden** dieser Phase ist.
- **Chefkoch:** die meiste Nahrung in einem einzigen Spiel produziert
- **First Blood:** in den wenigsten Monaten nach Spielstart den Gegner umgebracht
- **Spammer:** in einem Spiel das größte Verhältnis (Anzahl rekrutierte Truppen / erwirtschaftetes Gold) erlangt
- **Raidmaster:** in einem Spiel die meisten Gebäude zerstört
- **MVP:** die meisten Truppen in einem Spiel getötet
- **Ökofreak:** am wenigsten Holzbretter in einem Spiel produziert
- **Hinterlistig:** in einem Spiel die größte Differenz aus  
  `(Truppen des Gegners gestorben) - (eigene getötete Truppen)`, wobei Karten mit Dummy-Ratten ausgenommen sind!
- **Opferlamm:** die meisten Gebäude akkumuliert über die gesamte Phase verloren
- **Showmaster:** die Ingame-Spieldauer eines Spieles liegt am nächsten am Durchschnitt aller Spiele dieser Phase

__Phase 2:__ Für jede dieser Challenges gibt es für die **besten N KIs bzw. Teams** in jeder der Kategorien je einen Punkt, wobei **N die Anzahl der Runden** ist, die diese Kategorie betrifft. Außerdem gilt für Einzelspielziele aus **Phase 1**, dass diese bei **Rekordüberbietung einmalig** erneut vergeben werden! 
- **Märtyrer:** (2 vs. 2) in einem gewonnenen Spiel als erste KI am frühesten gestorben
- **Einsiedler:** (2 vs. 2) kleinste gemeinsame Bevölkerung aller gewinnenden Teams und aller verlierenden Teams (Achtung: Es wird jeweils nur ein BP pro KI pro Team in der Phase vergeben).
- **Teamwork:** (2 vs. 2) das Verhältnis (produzierte Truppen KI 1 / produzierte Truppen KI 2) beider KIs in einem Spiel am nächsten an 1
- **Gebäudeinstandhaltung:** (2 vs. 2) höchstes positives Ergebnis im Spiel für die Differenz aus:  
  `gesamte zerstörte Gebäude - gesamte verlorene Gebäude`
- **Punching Bag:** (FFA) am längsten von allen Spielen durchhalten, aber im eigenen Spiel zuerst sterben
- **Abstauber:** (FFA) am wenigsten Truppen gebaut und trotzdem gewonnen
- **King of Dust:** (FFA) die höchste Differenz aus  
  `Kronen - Kills`  
  (Wird bei Gleichstand mehrfach vergeben!)
- **Minimalist:** beste (minimale) Bilanz (produzierte harte Ressourcen (Stein, Eisen, Pech) / Spielzeit) über die gesamte Phase
- **Suicide:** frühester Tod des Lords abseits des Bergfrieds
- **Headhunter:** insgesamt in der Phase die meisten Kills gesammelt. Bei Gleichstand zählt die akkumulierte Ingamezeit für alle Kills.

__Abschlussphase:__
Hier geht es nochmal um alles! Jedes der Kriterien wird nach Abschluss aller KI-Kämpfe gewertet und an die besten drei KIs je ein BP vergeben.
- **Ascended:** über den Verlauf des gesamten Turniers die meisten Ascension-Punkte verdient
- **Kingslayer:** ein einzelnes Spiel mit dem größten Punkterückstand gewonnen
(Wird bei Gleichstand mehrfach vergeben!)
- **Superstar:** aus ausgewählten Highlights vom Publikum gewählt (YouTube-Poll). Dies ehrt das krasseste Highlight des Turniers.
- **Ekstase:** Es gibt einen BP für die drei KIs, deren Vorstellungsvideo die meisten Likes bekommen hat.
- **Rekordbrecher V2:** bestehende Rekorde der 7 Einzelkriterien aus **Phase 1** dürfen erneut für einen BP gebrochen werden
- **Krösus:** meistes über alle Phasen hinweg akkumuliertes Gesamtgold
- **Game of Thrones:** meiste über alle Phasen akkumulierte Kronen
- **The Joker:** größter Sprung der Gesamtplatzierung zwischen Ende von Phase 1 und Abschlussphase; wird nach allem anderen vergeben
- **Topf der Gier:** bestes (maximales) Verhältnis aus (Bonuspunkte / Siegpunkte)

Die KI mit den Meisten SP + BP am Ende des Turniers hat gewonnen!

## IV. Sonderregeln: Ascension-Punkte
**Ascension-Punkte** (APs) können im Laufe des Turniers eingesetzt werden, um zwischen den Runden Veränderungen an den eingesendeten KIs vorzunehmen. Die Optionen können der unten angegebenen Liste entnommen werden. Änderungen werden auf der **[Stronghold Modschmiede](https://discord.com/invite/sKtrj9S626)** im Forumskanal dieser KI diskutiert und **müssen** für das Inkrafttreten vom KI-Ersteller akzeptiert werden.

Es werden jede Runde (10 x Anzahl der teilnehmenden KIs) APs ausgeschüttet. Die Ausschüttung funktioniert wie folgt:
- Nachdem ein Video 'live' geht, wird genau **7 Tage** später die Watchtime `WT` **für dieses Video** abgelesen.
- Die gesamte Watchtime **aller Videos** der Runde wird zu `GWT` akkumuliert.
- Die für die im Video **gezeigten KIs** ausgeschütteten **APs** entsprechen dann dem Verhältnis `WT / GWT`.
- Beispiel: Die Watchtime für ein Video ist `WT = 100h` und die gesamte Watchtime aller Videos der Runde entspricht `GWT = 1000h`. Bei 20 teilnehmenden KIs bekommen die beiden KIs aus dem Video für diese Runde jeweils (100 / 1000) x (10 x 20) = 20 AP.

Die genauen Optionen für Änderungen sind:  
- **Hotfixes (kostenlos):** Hotfixes sind frei, z.B. bei **Wegfindungsproblemen**, schlecht gesetzten **AIC-Parametern** oder zum **Hinzufügen von Häusern**.

### AIV-Änderungsoptionen
- **[VBC] Dorf-Basisänderung (5 AP):** Ein AIV Nicht-Burggebäude hinzufügen/entfernen/neu positionieren ODER bis zu zwei Angstfaktor-Gebäude hinzufügen/entfernen/neu positionieren ODER einen AIV-Truppen-Sammelpunkt hinzufügen/entfernen/neu positionieren.
- **[CBC] Burg-Basisänderung (10 AP):** Ein AIV-Burggebäude hinzufügen/entfernen/neu positionieren ODER bis zu zwanzig Wall/Graben/Pech/Mördergruben-Felder hinzufügen/entfernen/neu positionieren ODER bis zu fünf Angstfaktor-Gebäude hinzufügen/entfernen/neu positionieren ODER bis zu drei AIV-Truppen-Sammelpunkte hinzufügen/entfernen/neu positionieren.
- **[UBT] Gebäudetyp freischalten (15 AP):** Einen neuen Gebäudetyp einführen (freischalten) (Hinweis: Holzfäller, Jäger, Ochsenjoch-Hersteller und Geisterschritte (Index 2) sind immer freigeschaltet!).
- **[ABO] Bau-Reihenfolge anpassen (40 AP):** Die Bau-Reihenfolge anpassen, keine Neu-Positionierung von Gebäuden!

### AIC-Änderungsoptionen
- **[BBC] Verhaltens-Basisänderung (5 AP):** Einen AIC-Wert anpassen, der nicht mit einem Einheiten-Slot zusammenhängt.
- **[UCC] Einheitenanzahl ändern (5 AP):** Die Anzahl der Einheiten in einem bestehenden Einheiten-Slot um bis zu 5 ändern ODER die Anzahl der Belagerungsgeräte um eines ändern ODER ein Belagerungsgerät und die nötigen Ingenieure hinzufügen/entfernen/ersetzen.
- **[AUS] Einheitenslot hinzufügen (10 AP):** Einen neuen Einheiten-Slot mit einem bestehenden Einheitentyp mit bis zu 5 Einheiten hinzufügen.
- **[UUT] Einheitentyp freischalten (20 AP):** Einen neuen Einheitentyp einführen, der von dieser KI bisher nicht verwendet wurde.

### AP-Paketangebote
- **[ORN] Ochsen- & Lauf-Neuling (10 AP):** Beliebig alle neu eingeführten Werte im Zusammenhang mit Ochsenjoch-Logik und lauffähigen Einheiten hinzufügen/entfernen/anpassen.
- **[WBS] Arbeiter-Großausverkauf (10 AP):** Beliebig alle Einstellungen zum Ressourcen-Verkauf und Werkstatt-Präferenzen anpassen.
- **[FFT] Furchtsamer Steuereintreiber (10 AP):** Beliebig alle Werte zu Steuern und Beliebtheit sowie den Schwellenwert für doppelte Rationen anpassen.
- **[CRL] Ernte-Umsiedlung (10 AP):** Beliebig alle Farm-Slot-Werte und den Wert für Bevölkerung pro Farm anpassen.
- **[SPH] Vorratslager-Hamstern (15 AP):** Beliebig alle minimalen und maximalen Ressourcenwerte, die Ressourcen-Varianz und die Handelsmengen anpassen.
- **[SEX] Strategische Expertise (15 AP):** Beliebig alle Anzahlen für Mauer- und Außenpatrouillen, deren Sammelzeiten und Bewegung, sowie die Verzögerung für das Ändern von Angriffszielen, Unterstützungsschwellenwerte, Sammelprozentsätze, Angriffsverzögerungen, Befehlsverzögerungen und das Kuhwurf-Intervall anpassen.
- **[FBG] Frische Schlachtfelder (20 AP):** Beliebig die verbleibende Kartenauswahl anpassen (Hinweis: Die Kartenauswahl muss einzigartig bleiben und bereits gespielte Karten können nicht erneut gewählt werden!).
- **[DEA] Wirtschafts-Anpassung (20 AP):** Beliebig alle Werte für Bevölkerung pro Gebäudetyp, maximale Anzahl pro Gebäudetyp und die Verzögerung für den Wiederaufbau von Ressourcen-Gebäuden anpassen.
- **[ACP] Armee-Einberufungen (25 AP):** Beliebig alle Rekrutierungswahrscheinlichkeiten, den Gold-Schwellenwert für Rekrutierung und Belagerungsgeräte, die Rekrutierungsintervalle und die rekrutierenden Gebäude im AIV-Bauplan anpassen.
- **[SQS] Heimlicher Schnelltausch (10 + x AP):** Zwei einzelne Einheiten-Slots tauschen, nach Einheitentyp und Einheitenanzahl, wobei A + B die kombinierte Anzahl der Einheiten beider Slots ist und x = abs(A + B - 10) / 2.
- **[ILS] Lordstärke erhöhen (50 AP):** Die Lordstärke auf 2 erhöhen.
- **[AST] Starttruppen anpassen (75 AP):** Die Starttruppen im Rahmen der freigeschalteten Truppentypen anpassen, bis zu einem Maximum von 15.
- **[GPT] Großer Philanthrop (x AP):** Einer anderen KI x Ascension-Punkte geben.
- **[BBB] Die große schöne Rechnung (bis zu 25% Rabatt):** Kaufe 4 Ascension-Änderungsoptionen und erhalte die günstigste davon gratis. (Hinweis: Dies kann auf mehrere Käufe für mehrere KIs aufgeteilt werden).

Für eine detaillierte Übersicht aller Optionen, schaut bitte in die offizielle **[Ascension-Änderungsoptionen-Tabelle](https://docs.google.com/spreadsheets/d/1l8Ec1E-8jLa6KuQa6udAQWffidRXIl2_H3PBQ8jS_Ew/edit?usp=sharing)**.

Alle Anpassungen müssen spätestens einen Tag vor dem ersten Spieltag der Runde abgeschlossen sein.

__Fallbeispiele:__

**Beispiel 1: Ausfalltruppen austauschen**
Um bei einer KI ohne Söldnerposten die Nahkampf-Ausfalleinheiten (angenommen, es waren 10 Speerkämpfer) durch 10 Assassinen zu ersetzen, sind folgende Optionen erforderlich:
- **[UUT] Einheitentyp freischalten (20 AP):** Assassinen zum Repertoire der KI hinzufügen.
- **[UBT] Gebäudetyp freischalten (15 AP):** Den Söldnerposten freischalten, um Assassinen zu rekrutieren.
- **[CBC] Burg-Basisänderung (10 AP):** Einen Söldnerposten zum AIV-Burgplan hinzufügen.
- **[UCC] Einheitenanzahl ändern x2 (10 AP):** Den ursprünglichen Speerkämpfer-Slot um 10 reduzieren, um ihn zu leeren.
- **[AUS] Einheitenslot hinzufügen (10 AP):** Einen neuen Einheitenslot für Assassinen hinzufügen, der mit bis zu 5 Einheiten startet.
- **[UCC] Einheitenanzahl ändern (5 AP):** Den neuen Assassinen-Slot um weitere 5 Einheiten erhöhen, um das Ziel von 10 zu erreichen.

Insgesamt kostet dies also **70 AP**.

---

**Beispiel 2: Eine Brotwirtschaft hinzufügen**
Um einer KI eine richtige Brotwirtschaft zu geben, die sie vorher nicht hatte, angenommen sie benötigt 3 weitere Farmen, die Fähigkeit Weizen anzubauen, 2 weitere Holzfäller, Mühlen und Bäckereien:
- **[BBC] Verhaltens-Basisänderung x3 (15 AP):** MaxFarms um 3 erhöhen und zwei Farm-Slots auf Weizen umstellen.
- **[VBC] Dorf-Basisänderung x2 (10 AP):** 2 weitere AIV-Holzfällerhütten hinzufügen.
- **[UBT] Gebäudetyp freischalten x2 (30 AP):** Die Mühle und die Bäckerei freischalten.
- **[VBC] Dorf-Basisänderung x9 (45 AP):** Eine Mühle und 8 Bäckereien in der AIV platzieren.

Insgesamt würde dies **100 AP** kosten.

---

**Beispiel 3: Einen zweiten Burghof bauen**
Um dem Schloss einer KI einen zweiten äußeren Burghof hinzuzufügen, bestehend aus einem Torhaus, einer Zugbrücke, 78 Mauerabschnitten und 22 Grabenabschnitten:
- **[CBC] Burg-Basisänderung x2 (20 AP):** Ein großes Torhaus und eine Zugbrücke hinzufügen.
- **[CBC] Burg-Basisänderung x4 (40 AP):** 78 Mauerabschnitte platzieren (4 Käufe von je bis zu 20 Feldern).
- **[CBC] Burg-Basisänderung x2 (20 AP):** 22 Grabenabschnitte platzieren (2 Käufe von je bis zu 20 Feldern).

Dies würde sich auf Gesamtkosten von **80 AP** belaufen.

---

**Beispiel 4: Angriffstrupps tauschen und verstärken**
Um den `AttUnitVanguard`-Slot (10 europäische Bogenschützen) mit dem `SortieUnitRanged`-Slot (20 Armbrustschützen) zu tauschen und anschließend 20 weitere Einheiten zum neuen Vanguard-Slot hinzuzufügen.
- **[SQS] Heimlicher Schnelltausch (20 AP):** Die beiden Slots tauschen. Die Kosten berechnen sich als `10 + abs(A + B - 10) / 2`, was `10 + abs(10 + 20 - 10) / 2 = 20 AP` ergibt.
    - *Ergebnis nach dem Tausch: `AttUnitVanguard` enthält nun 20 Armbrustschützen und `SortieUnitRanged` enthält 10 europäische Bogenschützen.*
- **[UCC] Einheitenanzahl ändern x4 (20 AP):** Den `AttUnitVanguard`-Slot um 20 Einheiten erhöhen (4 Käufe von je +5 Einheiten).
    - *Ergebnis nach der Verstärkung: `AttUnitVanguard` enthält nun 40 Armbrustschützen.*

Diese gesamte Operation würde insgesamt **40 AP** kosten. 

## V. Mitmachangebot

[Stronghold Modschmiede](https://discord.com/invite/sKtrj9S626)

Wollt ihr auch mitorganisieren, Karten bauen, casten oder einfach nur bei Statistik-Auswertungen mithelfen? Oder wollt ihr Preise sponsorn? Bewerbt euch jetzt als Caster oder meldet euch einfach bei **Krarilotus** oder **Xander10alpha**. Ihr findet uns auf dem **Discord!**

## VI. Appendix - Mapliste & Ersteller
### 1vs1 - 15 Stück
Ancient Terraces - von Crusader Pilaw  
Beaten Heart - von Krarilotus  
Berg Alawia - von Nevikov  
Conquest Deadly Ascent - von Monsterfish_  
Conquest Dune - von Monsterfish_  
Crimson Rivers - von Nevikov  
Dusty River - von Lord Hühnerfutter  
Fissure - von Krarilotus  
Guilty Modder - von Krarilotus  
Insel Kyklos - von Hacksülze  
Oasis Power - von Krarilotus  
Rumble - von Nevikov  
Silence - von Nevikov  
Trommelhügel - von Nevikov  
Watcher's Eye - von Krarilotus  

### 2vs2 - 9 Stück
Fading Riches - von Lord Hühnerfutter  
Green Trench - von Nevikov  
Hammer and Anvil - von Tobbi  
Heimatland - Der Archipel - von Crusader Pilaw  
Heimatland - Der Graben - von Crusader Pilaw  
Heimatland - Die Klamm - von Crusader Pilaw  
Mesopotamien - von Hacksülze  
Rocky Crenels - von Crusader Pilaw  
Two Mountains - von Xander10alpha  

### FFA - 3 Stück
Desert Throne - von Nevikov  
Green Haven Retraced - von Krarilotus  
Mayham - von Crusader Pilaw  
