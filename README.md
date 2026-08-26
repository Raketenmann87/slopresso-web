# slopresso — Weboberfläche

Täglicher Überblick über die Tech-Nachrichten. Maschinell gebaut, jede Zahl
gegen die eigenen Quellen geprüft.

Dieses Repository enthält **nur die Oberfläche und die veröffentlichten
Folgen**. Erzeugt wird alles aus einem separaten, privaten Repository; hier
landet ausschließlich das Ergebnis.

| Datei | Was |
|---|---|
| `index.html` | die komplette Oberfläche, Folgendaten eingebettet |
| `audio/*.mp3` | die Folgen |

Die Seite braucht keinen Server: `index.html` per Doppelklick öffnen
funktioniert genauso, solange `audio/` daneben liegt.

## Was die Oberfläche kann

- Player mit Springen per Ziehen, ±15 s, Tempo bis 2×, Tastatur
  (Leertaste, Pfeile). Die Hörposition wird je Folge gemerkt.
- Archiv über alle Folgen, jede mit Show Notes, Quellen und Volltranskript
- Hell und Dunkel, die Wahl wird gemerkt
- „Warum" erklärt Ablauf, Figuren und die Entscheidungen dahinter

## Der Schalter unten rechts

Diese Oberfläche ist absichtlich so gebaut, wie eine KI eine Seite baut.
Der **Slop-Meter** markiert jede Stelle und nennt die Regel, die sie bricht —
im Wortlaut. Das ist Teil des Konzepts, kein Versehen.
