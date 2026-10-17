---
name: transkript-bereinigen
description: 'Bereinigt Markdown- und Texttranskripte von Pathfinder- oder anderen Pen-and-Paper-Sitzungen originalgetreu. Verwenden für transcript cleanup, clean transcript, Transkript bereinigen, Unsicherheiten markieren und Eigennamen anhand verfügbarer Kampagnenreferenzen prüfen.'
argument-hint: 'Transkript zur Bereinigung'
---

# Transkript bereinigen

## Zweck und Einsatz

Bereinige ein Markdown- oder Texttranskript einer Pathfinder- oder anderen Pen-and-Paper-Sitzung, ohne den Inhalt umzuschreiben oder zusammenzufassen. Bei langen Transkripten arbeite in logisch abgegrenzten Abschnitten und setze sie in der richtigen Reihenfolge in einer Markdown-Ausgabedatei zusammen.

Verlange eine Transkriptdatei, wenn noch keine Quelle vorliegt; sie kann als `.md` oder `.txt` bereitgestellt werden. In diesem Workspace bilden `Zusammenfassungen.md`, `Dramatis_personae.md` und `Quests.md` gemeinsam den Kampagnenkanon. Nutze diese Dateien zur Verifikation, sofern sie zugänglich sind. In anderen Arbeitsumgebungen nutze entsprechende vorhandene Kampagnenreferenzen aus hochgeladenen Dateien oder einem zugänglichen Repository. Frage nicht pauschal nach zusätzlichen Referenzen, wenn bereits welche vorliegen.

## Quellenregeln

- Das Transkript ist maßgeblich dafür, was in der Sitzung gesagt wurde.
- Kampagnenkanon dient ausschließlich dazu, Namen, Schreibweisen und Begriffe zu verifizieren. Ein Kanoneintrag belegt nicht, dass etwas in dieser Sitzung gesagt wurde.
- Wenn mehrere Schreibweisen oder Identitäten möglich sind und keine sicher belegt ist, frage gezielt nach. Rate nicht.
- Übernimm keine Spekulation als Tatsache und rekonstruiere keine fehlende Rede.

## Redaktionelle Regeln

1. Ändere nicht, was innerhalb der Spielsitzung gesagt wurde, und füge keine inhaltlichen Aussagen hinzu. Fasse nicht zusammen, dramatisiere nicht und formuliere nicht stilistisch neu. Klar vom Spiel unabhängige Vorbereitungs- und Nebengespräche gehören nicht in das bereinigte Sitzungstranskript.
2. Verbinde künstlich durch Zeilenumbrüche getrennte Teile desselben Satzes. Bewahre Sprecherwechsel, Absätze, Überschriften, Zeitmarken und Reihenfolge.
3. Korrigiere offensichtliche Transkriptionsartefakte, Interpunktion, Groß- und Kleinschreibung sowie klar erkennbare falsch transkribierte Namen. Bewahre Wortwahl, Umgangssprache und charakteristische Ausdrucksweise möglichst weitgehend.
4. Entferne nur eindeutige technische Duplikate oder Spracherkennungsartefakte. Lösche nicht pauschal echte Wiederholungen, Versprecher oder Füllwörter.
5. Bei einer relevanten Unklarheit, die eine inhaltliche Entscheidung oder einen unsicheren Eigennamen erfordert, halte an der Stelle an und stelle eine präzise Frage. Nimm bis zur Klärung keine unbelegte Korrektur vor. Belanglose Unsicherheiten behandelst du konservativ und originalnah.
6. Lasse keinen spielrelevanten Inhalt aus. Entferne klar spielunabhängige Passagen, insbesondere Begrüßungen, Warten, Mikrofon-/Stream-/Musikprobleme und sonstiges Vorgeplänkel vor dem Rückblick oder Spielbeginn. Schneide auch später eindeutig spielunabhängige Einschübe, aber keine In-Character-Dialoge, Spielentscheidungen oder relevanten Tischgespräche.

### Redaktionsstandard

- Eine Bereinigung ist keine Abschrift mit vereinzelter Interpunktionskorrektur. Redigiere aktiv jeden Abschnitt, in dem die Rohfassung Satzfragmente, offensichtliche ASR-Fehler, fehlerhafte Namen oder unlesbare Artefakte enthält.
- Fasse aufeinanderfolgende Fragmente desselben Sprechers zu einem lesbaren Absatz zusammen, wenn sie erkennbar zum selben Redebeitrag gehören. Bewahre Reihenfolge und Sprecherwechsel; lege keine Beiträge verschiedener Sprecher zusammen.
- Korrigiere erkennbare ASR-Fehler anhand des unmittelbaren Satzkontexts und verfügbarer Kanonquellen. Verwende `[Unverständlich.]` nur für einen klar abgegrenzten Teil einer spielrelevanten Äußerung, dessen Wortlaut trotz Kontext nicht zuverlässig rekonstruierbar ist. Markiere nicht den gesamten Satz, wenn Teile verständlich sind. Isolierte Bruchstücke ohne erkennbaren Aussagewert, Geräusche und reine Erkennungsreste werden entfernt, nicht als "Unverständlich" ausgegeben.
- Achte in dieser Kampagne besonders auf Übersprechen: Das Headset von Lisa E (Fox) erfasst teils Jan (DM) im Hintergrund. Wenn eine Lisa-E-Zeile zeitlich und inhaltlich erkennbar Jans benachbarte Ansage wiederholt oder verstümmelt, behandle sie als Echo-/ASR-Artefakt und übernimm sie nicht zusätzlich. Entferne nicht pauschal echte, eigenständige Beiträge von Lisa E; bei einer klaren eigenen Reaktion oder Aussage bleibt ihr Beitrag erhalten.
- Entferne eindeutige Einblendungen, Untertitelreste und technische Erkennungsartefakte. Lass klar spielunabhängige Vorbereitungs- und Off-topic-Passagen weg; bewahre lockere Gespräche, sobald sie Teil des Spiels, der Figuren oder relevanter Tischentscheidungen sind.
- Verwende bei einem vorhandenen Datum den Titel `# Bereinigtes Transkript - TT.MM.JJJJ`. Bei langen Transkripten gliedere mit knappen, sachlichen Abschnittsüberschriften. Orientiere dich, sofern verfügbar, am Format von `transcripts/261007_edited_transcript.md`; nutze diese Datei nur als Stilreferenz, niemals als Quelle für Sitzungsinhalte.
- Unveränderte Formulierungen sind inhaltlich oft richtig, aber übernimm nicht automatisch die zeilenweise Rohstruktur. Wenn ein Rohabschnitt bereits vollständig klar, korrekt und lesbar ist, darf sein Wortlaut bestehen bleiben.
- Beginne das Ausgabetranskript beim Rückblick oder beim tatsächlichen Spielbeginn, nicht mit einem Abschnitt "Vor dem Spiel". Entferne eindeutig spielunabhängiges Vorgeplänkel, statt es zu redigieren oder mit `[Unverständlich.]` zu markieren.

## Ablauf und Ausgabemodi

1. Ermittle Struktur, Sprecher und natürliche Abschnittsgrenzen. Bei großen Dateien lies und bearbeite das Transkript nicht in einem einzigen Aufruf, sondern sequenziell in handhabbaren Quellbereichen. Verwende als Richtwert höchstens 100-200 Zeilen pro Bereich und verkleinere den Bereich, falls Lesen, Redigieren oder Prüfen sonst unzuverlässig wird.
2. Übernimm die ursprüngliche Gliederung, soweit vorhanden. Bearbeite alle Abschnitte in einem Durchlauf, wenn die Aufgabe ausdrücklich autonom abgeschlossen werden soll. Bei interaktiver Bearbeitung redigiere zunächst nur den ersten Abschnitt.
3. Erstelle eine Markdown-Ausgabedatei mit einem eindeutigen Namen. Prüfe, dass die Datei tatsächlich erstellt wurde, bevor du ihren Link ausgibst.
4. Bei interaktiver Bearbeitung nenne kurz den bearbeiteten Abschnitt und wo der nächste beginnt. Bitte ausdrücklich um Freigabe und bearbeite keinen weiteren Abschnitt, bevor der Nutzer eindeutig zugestimmt hat. "Okay" ist eine Freigabe; ebenso zählen klare Zustimmungen wie "Weiter" oder "Passt". Bei mehrdeutigen Antworten frage nach.
5. Nach jeder eindeutigen Freigabe bearbeite genau den nächsten möglichst langen, logisch abgegrenzten Abschnitt und ergänze ihn an dieselbe fortlaufende Ausgabedatei. Ersetze keine früheren Abschnitte und hänge sie nicht doppelt an. Gib den aktualisierten Dateilink aus und warte erneut auf die Freigabe.
6. Bewahre bei einer interaktiven Fortsetzung die Quelle, die letzte bearbeitete Position und die Ausgabedatei. Sind sie nicht mehr verfügbar, bitte um erneuten Upload, statt einen Fortsetzungsstand zu erfinden. Bei autonomer Bearbeitung setze alle Abschnitte in derselben Ausgabedatei zusammen, ohne Zwischenfreigaben abzuwarten.
7. Tritt eine relevante Unklarheit auf, frage zuerst nach. Nimm keine unbelegte Korrektur vor und gib keine scheinbar fertige Fassung mit einer geratenen Stelle aus.
8. Nach dem letzten Abschnitt vergleiche die vollständige Ausgabedatei mit dem Original auf Vollständigkeit und Reihenfolge, insbesondere an den Übergängen. Gib den Link zur vollständigen Datei aus und kennzeichne den Abschluss.

### Große Dateien inkrementell bearbeiten

- Verarbeite Quellbereiche strikt in Reihenfolge. Halte die Quellzeilen des nächsten noch unbearbeiteten Bereichs fest.
- Redigiere jeweils nur den aktuellen Bereich, prüfe ihn gegen die entsprechende Quelle und schreibe ihn sofort an das Ende derselben Ausgabedatei. Halte nicht das gesamte bearbeitete Transkript bis zum Schluss im Kontext und gib es nicht als eine große Antwort aus.
- Lies bei Bedarf wenige Zeilen des vorherigen Bereichs als Übergangskontext erneut, aber füge überlappende Kontextzeilen nicht ein zweites Mal in die Ausgabe ein.
- Fahre erst mit dem nächsten Quellbereich fort, wenn der aktuelle vollständig in die Ausgabedatei geschrieben und geprüft wurde. Wiederhole, bis alle Quellzeilen lückenlos verarbeitet sind.
- Prüfe auch den abschließenden Vergleich bereichsweise: Vergleiche nacheinander jeden Quellbereich mit dem entsprechenden Abschnitt der Ausgabedatei, statt beide vollständigen Dateien erneut auf einmal zu laden.
- Melde den Auftrag erst als abgeschlossen, wenn der letzte Quellbereich bearbeitet und alle Bereiche auf Reihenfolge, fehlende oder doppelte Passagen und Übergänge geprüft wurden.

## Qualitätssicherung

Prüfe jeden bearbeiteten Abschnitt gegen die entsprechende Originalpassage:

- Keine Auslassungen, hinzugefügten Aussagen oder Bedeutungsverschiebungen.
- Keine doppelten oder fehlenden Sätze an Abschnittsübergängen.
- Eigennamen nur korrigiert, wenn die Schreibweise tatsächlich belegt ist.
- Gliederung, Sprecher, Zeitmarken und Reihenfolge bewahrt.
- ASR-Fragmente zu lesbaren Absätzen verbunden und nicht rekonstruierbare Passagen eindeutig markiert.
- Kein klar spielunabhängiges Vorgeplänkel oder bestätigtes Echo als zusätzlicher Sprecherbeitrag übernommen; `[Unverständlich.]` nur sparsam und lokal eingesetzt.
- Ausgabedatei vor Bereitstellung des Links erzeugt und geprüft.
