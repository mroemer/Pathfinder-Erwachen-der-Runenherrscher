---
description: "Use when revising campaign transcripts, cleaning AI transcription artifacts, fixing names or spellings from repository context, and preserving transcript structure in transcript files."
applyTo: "transcripts/**/*.txt"
---
# Transkript-Regeln

- Diese Regeln gelten für KI-generierte Kampagnen-Transkripte im Ordner transcripts/.
- Erhalte die bestehende Sprecherstruktur und Reihenfolge der Aussagen; direkt aufeinanderfolgende Aussagen derselben Person duerfen zu einer Zeile zusammengezogen werden.
- Entferne nur klare Transkriptionsartefakte wie kaputte Zeichen, reine Rauschfragmente und offensichtlichen Wortsalat ohne erkennbaren Inhalt.
- Korrigiere bestätigte Namen, Orte, Fraktionen und Begriffe anhand des Repository-Kontexts.
- Behalte verständliche, aber holprige Aussagen im Kern bei; schreibe sie nicht frei um.
- Normalisiere Zeichensetzung sowie Groß- und Kleinschreibung vorsichtig, wenn der Inhalt klar ist.
- Behalte verständliches Off-topic-Tischgespräch bei und bereinige darin nur grobe Rauschstellen.
- Wenn etwas nicht sicher auflösbar ist, bleibe konservativ und erfinde nichts.
- Keine Zusammenfassung, keine Neuordnung des Dialogs und kein Zusammenziehen von Aussagen verschiedener Sprecher.
