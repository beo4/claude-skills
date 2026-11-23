# claude-skills

Skills für Claude.

## german-plain-business-writing

Schreibt und überarbeitet deutsche Geschäftstexte in klarem, konkretem Deutsch
ohne Floskeln und ohne KI-Muster: Strategie-Dokumente, Business-Modelle,
BMC/VPC, Entscheidungsvorlagen, Website- und Sales-Texte, E-Mails.

Die Regeln stützen sich auf die deutsche Stilkunde (Wolf Schneider), das
Hamburger Verständlichkeitsmodell, den Hohenheimer Verständlichkeitsindex, die
Normen für Einfache Sprache (DIN ISO 24495-1, DIN 8581-1) und öffentliche
Regelsammlungen gegen KI-Stil.
Quellen und Lizenzen: [`QUELLEN.md`](skills/german-plain-business-writing/QUELLEN.md).

## german-tech-article-writing

Schreibt und überarbeitet deutsche Fachartikel und Erfahrungsberichte für
Fachmagazine (heise Developer, iX, c't): Überschrift, Vorspann, szenischer
Einstieg, These, Zwischentitel, Belege, Grenzen, Schluss. Baut auf
german-plain-business-writing auf, das die Sprachregeln und KI-Muster liefert.
Quellen: [`QUELLEN.md`](skills/german-tech-article-writing/QUELLEN.md).

## Installation

Als Plugin-Marketplace in Claude Code:

```
/plugin marketplace add beo4/claude-skills
/plugin install german-business-writing@beo4-skills
```

Ohne Marketplace: die Ordner unter `skills/` als Skills in Claude hochladen oder nach `~/.claude/skills/` kopieren.
