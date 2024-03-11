Datensatzdokumentation  
# ESI-CorA: SARS-CoV-2-Abwassersurveillance  


[Robert Koch-Institut](https://rki.de) | RKI  
Nordufer 20   
13353 Berlin   

**Fachgebiet 32 | Surveillance und elektronisches Melde- und Informationssystem (DEMIS) | ÖGD-Kontaktstelle** 
<br>

**Zitieren**   
Robert Koch-Institut, Fachgebiet 32 (2024): "ESI-CorA: SARS-CoV-2-Abwassersurveillance". [Dataset] Zenodo. DOI:[10.5281/zenodo.10781653](https://doi.org/10.5281/zenodo.10781653).

---

## Informationen zum Datensatz und Entstehungskontext

Das Vorhaben „Emergency Support Instrument - Nachweis von SARS-CoV-2 im Abwasser“ (ESI-CorA) lief von November 2021 bis März 2023. Zwanzig Kläranlagenstandorte wurden in Deutschland ausgewählt, die im Februar 2022 gestaffelt mit der Überwachung von SARS-CoV-2 im Abwasser begonnen haben. Das zentrale Ziel in ESI-CorA war die Vorbereitung und Durchführung der bundesweiten Pilotphase zur Überwachung von SARS-CoV-2 und seiner Varianten im Abwasser. Unter anderem wurde das Verfahren zur Normalisierung der Rohdaten, der angewandten PCR-Analytik und der Berechnung der Trenddynamiken untersucht. 
Abwassersurveillance ist die systematische Überwachung von Erregern im Abwasser mit dem Ziel Gesundheitsschutzmaßnahmen zu steuern. Abwasserdaten erlauben keine genaue Einschätzung von Krankheitsschwere oder Belastung des Gesundheitssystems. Bei der epidemiologischen Bewertung sollten die Daten stets mit anderen Indikatoren, z.B. aus der syndromischen Surveillance, gemeinsam bewertet werden. Weitere Informationen sind im [ESI-CorA Projektblatt](https://www.ptka.kit.edu/img/Projektblatt_ESI-CorA.pdf) des Karlsruher Instituts für Technologie (KIT) zu finden.

![Standorte ESI-CorA](https://github.com/robert-koch-institut/ESI-CorA_SARS-CoV-2-Abwassersurveillance/blob/main/.github/pictures/standorte.png?raw=true "Standorte ESI-CorA")

Im hier veröffentlichten Datensatz "ESI-CorA: SARS-CoV-2-Abwassersurveillance" wird die normalisierte SARS-CoV-2-Viruslast von den 20 EU-geförderten Pilotstandorten im ESI-CorA-Projekt für den oben beschriebenen Zeitraum bereitgestellt.

### Administrative und organisatorische Angaben
Die Europäische Kommission hat das Pilotprojekt gefördert und gemeinsam mit dem Bundesministerium für Gesundheit (BMG), dem Bundesministerium für Umwelt, Naturschutz, nukleare Sicherheit und Verbraucherschutz (BMUV) sowie vom Bundesministerium für Bildung und Forschung (BMBF) verfolgt. Koordiniert wurde das Projekt vom Karlsruher Institut für Technologie (KIT), Projektträger Karlsruhe (PTKA). Konsortialpartner waren das Umweltbundesamt (UBA), das RKI und die Technische Universität Darmstadt (TUDa). 
Das ESI-CorA-Projekt erfolgte in enger Zusammenarbeit der vier Konsortialpartner. Weitere Informationen zum Projekt und Aufgaben der Konsortialpartner können Sie dem [Kurzbericht](https://www.rki.de/DE/Content/Institut/OrgEinheiten/Abt3/FG32/Abwassersurveillance/Bericht-ESI-CorA.pdf) entnehmen. 
Die Veröffentlichung der Daten, die Datenkuration sowie das Qualitätsmanagement der (Meta-) Daten erfolgt durch das Fachgebiet [MF 4 | Fach- und Forschungsdatenmanagement](https://www.rki.de/DE/Content/Institut/OrgEinheiten/MF/MF4/mf4_node.html). Fragen zum Datenmanagement können an das Open Data Team des Fachgebiets MF4 gerichtet werden [OpenData@rki.de](mailto:OpenData@rki.de).  
ESI-CorA wurde von der Europäischen Kommission im Rahmen des Soforthilfeinstruments (Emergency Support Instrument – ESI) gefördert (No 060701/2021/864650/SUB/ENV.C2).

### Datenerhebung

Im Rahmen des Projekts wurden detaillierte Handreichungen zur Probennahme und Laboranalytik erstellt und den Kläranlagen bzw. Laborbetreibern zur Verfügung gestellt. Die Handreichungen sind auf der Seite des PTKA unter [Downloads](https://www.ptka.kit.edu/AbschlussPilotbetrieb.html) zu finden. 
An jeder der 20 EU-geförderten Kläranlagen wurden in aller Regel zwei Mal pro Woche Rohabwasserproben entnommen und zusammen mit den entsprechenden Begleitparametern (z.B. Wetterdaten, Volumenstrom, pH-Wert, Temperatur), die notwendig für die Charakterisierung der Abwassersituation während der Probenahme waren, erhoben. Rohabwasserproben sollten nach dem Sandfang der Kläranlage entnommen werden. Das Probenahmevolumen sollte einen Liter betragen und in luftdichte, verschließbare Polyethylenflaschen abgefüllt werden. Eine 24-Stunden-Mischprobe wurde bevorzugt, die mit einem automatisierten Probennehmer durchgeführt wurde. Die Beprobung sollte möglichst von Montag auf Dienstag und von Mittwoch auf Donnerstag durchgeführt werden. 
Die Rohabwasserproben wurden an entsprechende Labore versandt, wo die Aufkonzentrierung, Extraktion der viralen Nukleinsäure und Quantifizierung der viralen Gensequenzen durch dPCR oder qRT-PCR erfolgte. Mindestens zwei repräsentative SARS-CoV-2-Genfragmente (N1, N2, N3, E, ORF oder RdRp) sollten bestimmt werden. 

![Datenfluss ESI-CorA](https://github.com/robert-koch-institut/ESI-CorA_SARS-CoV-2-Abwassersurveillance/blob/main/.github/pictures/pipeline.png?raw=true "Datenfluss ESI-CorA")
 
Für das Datenmanagement wurde eine digitale Dateninfrastruktur genutzt, die auf ArcGIS Online von ESRI basiert. Die Daten wurden zunächst mit der ArcGIS Survey123 App, welche als mobile App oder am Computer im Browser zu bedienen ist, in die Dateninfrastruktur eingepflegt. Die Kläranlage, die die Probe entnommen hat, hat den Datensatz angelegt und die Angaben zur Probennahme entsprechend eingetragen. Die Labornachweise konnten im nächsten Schritt erfasst werden dem Probendatensatz über eine eindeutige Proben-ID zugeordnet werden. 

### Weiterverarbeitung der Daten

Zunächst wurde in ArcGIS für jede Probe ein Mittelwert der Viruslast (Genkopien/L) aller gemessenen Zielgene (mindestens zwei) berechnet. 

#### Normalisierungsverfahren

Eine Verdünnung des Abwassers, zum Beispiel aufgrund von Regenereignissen oder unregelmäßigen industriellen Einflüssen, kann zu geringeren oder höheren Konzentrationen von SARS-CoV-2 führen. Um diese externen Einflüsse zu berücksichtigen, kann die gemessene Viruslast durch den Durchfluss oder andere Humanmarker wie z. B. CrAssphage oder PMMoV normalisiert werden.

Im ESI-CorA-Projekt wurde nach dem Abwasserdurchfluss normalisiert. Folgende Formel wurde hierbei verwendet: 
$$ Gene_{Mittelwert\_normalisiert} = Gene_{Mittelwert} \cdot Volumenstrom \cdot 86400000 $$

### Datenauswertung

Die Ergebnisse des Projekts ESI-CorA wurden in Form eines deutschsprachigen [Kurzberichts](https://www.rki.de/DE/Content/Institut/OrgEinheiten/Abt3/FG32/Abwassersurveillance/Bericht-ESI-CorA.pdf) publiziert. 
### Hinweise zur Datenauswertung
Bei der Datenbewertung sind einige Besonderheiten zu beachten:

* Es wurden an den unterschiedlichen Standorten verschiedene Zielgene gemessen. 
* An zwei Kläranlagen (Hof und Rollsdorf) kam es während des Projekts zu einem Laborwechsel. Die Zeitreihen sind zwischen 31.07.2022 und 23.08.2022 unterbrochen, bis das neue Labor vollständig übernommen hat.
* Der Standort Bonn ist im Datensatz drei Mal vertreten: “Bonn Süd”, “Bonn Nord” und “Bonn Gesamt”. Bonn Nord und Süd sind zwei Zuläufe der gleichen Kläranlage und wurden separat beprobt. Während des Projekts musste der Zulauf Bonn Nord aufgrund von Wartungsarbeiten geschlossen werden. Das Abwasser wurde umgeleitet nach Bonn Süd. Für diesen Zeitraum sind die Daten als “Bonn Gesamt” zusammengefasst.
* Der Standort Hamburg ist mit zwei Zuläufen vertreten: “Hamburg Nord” und “Hamburg Süd”.
* Lag die Viruslast unter der Bestimmungsgrenze (BG), so wurde 0,5 * BG als Wert eingetragen. 

### Inhalt und Aufbau des Datensatzes

Der als Open Data veröffentliche Datensatz enthält:
* SARS-CoV-2-Viruslast im Abwasser der meldenden Standorte
* Datensatzdokumentation in deutscher Sprache
* Lizenz-Datei mit der Nutzungslizenz des Datensatzes in Deutsch und Englisch
* Metadaten zur automatisierten Weiterverarbeitung

Die Daten zur SARS-CoV-2-Viruslast im Abwasser der ESI-CorA-Standorte sind nach den folgenden Merkmalen differenziert:
1. Standort der Messtellen  
2. Datum der Probennahme  
3. Die normalisierte Viruslast (Genkopien/L)

> [ESI-CorA_Abwassersurveillance.tsv](https://github.com/robert-koch-institut/ESI-CorA_SARS-CoV-2-Abwassersurveillance/blob/main/ESI-CorA_Abwassersurveillance.tsv)

#### Variablen und Variablenausprägungen  

Die Abwasserdaten enthalten die in der folgenden Tabelle abgebildeten Variablen und deren Ausprägungen:

| Variable |Typ | Ausprägung | Beschreibung| 
| --- | ---| --- | ---|
| Bundesland| String | ```Baden-Württemberg``` <br /> ```Bayern``` <br /> ```Berlin``` <br /> ... <br /> ```Thüringen```| Bundesland in der sich die Kläranlage befindet |
| Standort | String | | Name der Kläranlage bzw. des Orts |
| Datum | Datum | `jjjj-mm-tt` | Startdatum der Probenahme an der Kläranlage.  |
| Genkopien_normalisiert | Ganze Zahl | `≥0` | SARS-CoV-2-Viruslast nach Abwasserdurchfluss normalisiert. (Genkopien/Liter) |

### Formatierung 

Die Daten sind im Datensatz als tabseparierte .tsv-Datei enthalten. Der verwendete Zeichensatz der .tsv-Datei ist UTF-8. Trennzeichen der einzelnen Werte ist ein Tab "\t".
- Zeichensatz: UTF-8  
- .tsv-Trennzeichen: Tab "\t"  

### Metadaten

Zur Erhöhung der Auffindbarkeit sind die bereitgestellten Daten mit Metadaten beschrieben. Über GitHub Actions werden Metadaten an die entsprechenden Plattformen verteilt. Für jede Plattform existiert eine spezifische Metadatendatei, diese sind im Metadatenordner hinterlegt:

> [Metadaten/](https://github.com/robert-koch-institut/ESI-CorA_SARS-CoV-2-Abwassersurveillance/tree/main/Metadaten/)  

Versionierung und DOI-Vergabe erfolgt über [Zenodo.org](https://zenodo.org). Die für den Import in Zenodo bereitgestellten Metadaten sind in der [zenodo.json](/Metadaten/zenodo.json) hinterlegt. Die Dokumentation der einzelnen Metadatenvariablen ist unter https://developers.zenodo.org/representation nachlesbar.   

> [Metadaten/zenodo.json](https://github.com/robert-koch-institut/ESI-CorA_SARS-CoV-2-Abwassersurveillance/blob/main/Metadaten/zenodo.json)  

## Hinweise zur Nachnutzung der Daten

Offene Forschungsdaten des RKI werden auf [GitHub.com](http://GitHub.com/), [Zenodo.org](http://Zenodo.org/) und [Edoc.rki.de](http://Edoc.rki.de/) bereitgestellt:
- https://github.com/robert-koch-institut
- https://zenodo.org/communities/robertkochinstitut
- https://edoc.rki.de/

### Lizenz

Der Datensatz "ESI-CorA: SARS-CoV-2-Abwassersurveillance" ist lizenziert unter der [Creative Commons Namensnennung 4.0 International Public License | CC-BY 4.0 International](https://creativecommons.org/licenses/by/4.0/deed.de).
Die im Datensatz bereitgestellten Daten sind unter Bedingung der Namensnennung des Robert Koch-Instituts als Quelle frei verfügbar. Das bedeutet, jede Person hat das Recht, die Daten zu verarbeiten und zu verändern, Derivate des Datensatzes zu erstellen und sie für kommerzielle und nicht kommerzielle Zwecke zu nutzen. Weitere Informationen zur Lizenz finden sich in der [LICENSE](https://github.com/robert-koch-institut/ESI-CorA_SARS-CoV-2-Abwassersurveillance/blob/main/LICENSE) bzw. [LIZENZ](https://github.com/robert-koch-institut/ESI-CorA_SARS-CoV-2-Abwassersurveillance/blob/main/LIZENZ)-Datei des Datensatzes.
