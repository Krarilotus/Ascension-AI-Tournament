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

Für die Einreichung wird auch zwingend eine sortierte Präferenzliste der im Plugin verfügbaren Karten erwartet. Jeder Map-Pick wird im Turnierverlauf einmalig berücksichtigt und danach aus der Liste gelöscht. Für Entscheidungsspiele wird eine zufällige Auswahl getroffen.  
***Achtung:** Die Maps sind noch nicht im finalen Zustand, die Liste kann noch erweitert werden.*

---

## III. Turnierablauf

Spiele enden immer spätestens nach 50 Jahren, was in einem Unentschieden resultiert!

### Spielplan
__Einleitungsphase:__ Es wird eine Einführungsrunde geben, in der alle KIs in einer Kurzvorstellung gezeigt werden, bevor das eigentliche Turnier stattfindet.

__Phase 1:__ Das Turnier findet anfänglich im klassischen **[Schweizer System](https://de.wikipedia.org/wiki/Schweizer_System)** statt. Es wird mindestens **zwei Runden im Schweizer System** zur grundlegenden Einordnung der KIs geben. Die genaue Anzahl steigt mit der Anzahl der teilnehmenden KIs.  

__Phase 2:__ Es schließt sich eine Runde **[Jeder gegen Jeden (FFA)](https://en.wikipedia.org/wiki/Deathmatch)** an und anschließend **zwei Runden 2 vs. 2**. Dabei werden für jede der Runden die Teams anhand der aktuellen Punkte aus der Tabelle gematcht: Der Erste mit dem Letzten, der Zweite mit dem Vorletzten usw.

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
  `(Truppen des Gegners gestorben) - (eigene getötete Truppen)`
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
Hier geht es nochmal um alles! Jedes der Kriterien wird nach Abschluss aller KI-Kämpfe gewertet.
- **Ascended:** am meisten Ascension-Punkte (siehe unten) nach Turnierende übrig
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
**Ascension-Punkte** (APs) können im Laufe des Turniers eingesetzt werden, um zwischen den Runden Veränderungen an den eingesendeten KIs vorzunehmen. Die Optionen können der unten angegebenen Tabelle entnommen werden. Änderungen werden auf der **[Stronghold Modschmiede](https://discord.com/invite/sKtrj9S626)** im Forumskanal dieser KI diskutiert und **müssen** für das Inkrafttreten vom KI-Ersteller akzeptiert werden.

Es werden jede Runde (10 x Anzahl der teilnehmenden KIs) APs ausgeschüttet. Die Ausschüttung funktioniert wie folgt:
- Nachdem ein Video 'live' geht, wird genau **7 Tage** später die Watchtime `WT` **für dieses Video** abgelesen.
- Die gesamte Watchtime **aller Videos** der Runde wird zu `GWT` akkumuliert.
- Die für die im Video **gezeigten KIs** ausgeschütteten **APs** entsprechen dann dem Verhältnis `WT / GWT`.
- Beispiel: Die Watchtime für ein Video ist `WT = 100h` und die gesamte Watchtime aller Videos der Runde entspricht `GWT = 1000h`. Bei 20 teilnehmenden KIs bekommen die beiden KIs aus dem Video für diese Runde jeweils (100 / 1000) x (10 x 20) = 20 AP.

- **[0] Hotfixes (kostenlos):** **Hotfixes** sind frei, z. B. bei **Pathfinding-Problemen**, schlecht gesetzten **AIC-Parametern** oder zum **Hinzufügen von Häusern**.
- **[1] Einheitenanzahl anpassen (10 AP):** **Anzahl** eines bestehenden **Einheitenslots** um bis zu 10 verändern (bei Belagerungsgeräten nur 1).
- **[2] Neuen Einheitenslot hinzufügen (15 AP):** Einen **neuen Einheitenslot** mit bestehender Einheit hinzufügen (bis zu 10 Einheiten).
- **[3] Neuen Einheitentyp einführen (20 AP):** Einen **neuen Einheitentyp** einführen, den die KI bisher nicht verwendet hat.
- **[4] AIC-Wirtschaftsgebäude anpassen (4 AP):** Anzahl von **AIC-Wirtschaftsgebäuden** um 1 verändern.
- **[5] AIC-Parameter anpassen (8 AP):** Einen anderen **AIC-Parameter** anpassen.
- **[6] AIV-Gebäude anpassen (5 AP):** Ein bestehendes **AIV-Wirtschaftsgebäude** oder 2 **Angstfaktorgebäude** erneut hinzufügen oder entfernen.
- **[7] AIV-Burgteile anpassen (10 AP):** Ein bestehendes **AIV-Burggebäude** (Rekrutierung, Tore, Türme) erneut hinzufügen oder entfernen **oder** bis zu 10 Teile Wall/Wassergraben/Mördergrube/Pech.
- **[8] Neuen Gebäudetyp freischalten (15 AP):** Einen neuen **Gebäudetyp** in der AIV einführen (freischalten).
- **[9] Build-Order anpassen (40 AP):** **Build-Order** anpassen.
- **[10] Lordstärke erhöhen (50 AP):** **Lordstärke auf 2 erhöhen**.
- **[11] Starttruppen anpassen (75 AP):** **Starttruppen** anpassen, bis zu einem Maximum von 15.


__Fallbeispiele:__  
Um z. B. bei einer KI ohne Kathedrale die Melee-Sortie-Einheiten (bisher 10 Speerkämpfer) durch 10 Mönche zu ersetzen, sind folgende Optionen nötig:  
[1] Speerkämpfer auf 0 reduzieren (10 AP)  
[3] Mönche ins Repertoire hinzufügen (20 AP)  
[2] Neuen Slot (Melee-Sorties war ja jetzt 0) hinzufügen: 10 Mönche zu Melee-Sorties (15 AP)  
[8] Kathedrale freischalten (15 AP)  
[7] Kathedrale der AIV hinzufügen (10 AP)  
Insgesamt kostet dies also **70 AP**.

Um einer KI eine vernünftige Brot-Eco zu geben, die sie vorher nicht hatte:  
[4] MaxFarms um 3 erhöhen (3 x 4 AP)  
[5] Farmslot 1 und 2 auf Getreidefarmen ändern (2 x 8 AP)  
[6] 2 weitere AIV Holzfäller hinzufügen (2 x 5 AP)  
[8] Mühle und Bäckerei freischalten (2 x 15 AP)  
[6] Eine Mühle und 8 Bäckereien platzieren (9 x 5 AP)  
Insgesamt würde dies **113 AP** kosten.

Um einer KI einen zweiten Burg-Vorhof hinzuzufügen:  
[7] Ein weiteres großes Torhaus mit Zugbrücke hinzufügen (2 x 10 AP)  
[7] 78 Wall- bzw. Zinnwall-Felder platzieren (8 x 10 AP)
[7] 22 Felder Wassergraben hinzufügen (3 x 10 AP)
Dies würde sich insgesamt auf **130 AP** belaufen.

## V. Mitmachangebot

[Stronghold Modschmiede](https://discord.com/invite/sKtrj9S626)

Wollt ihr auch mitorganisieren, Karten bauen, casten oder einfach nur bei Statistik-Auswertungen mithelfen? Oder wollt ihr Preise sponsorn? Bewerbt euch jetzt als Caster oder meldet euch einfach bei **Krarilotus** oder **Xander10alpha**. Ihr findet uns auf dem **Discord!**