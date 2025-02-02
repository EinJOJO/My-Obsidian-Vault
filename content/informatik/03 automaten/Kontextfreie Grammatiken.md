---
title: Kontextfreie Grammatiken
tags:
  - kontextfrei
  - automaten
  - Grammatik
  - Sprache
---
Die Menge der Wörter, die sich mit einer [regulären Grammatik](Reguläre Grammatik) erzeugen lassen, sind kleiner als die der kontextfreien Grammatik.

### Regeln der kontextfreien Grammatik
1. Die linke Seite der Produktionsregel enthält jeweils genau ein Nicht-Terminal.
2. Auf der rechten Seite ist eine beliebige Kombination aus Terminalen und Nicht-Terminalen möglich

### Das unterscheidet die kontextfreie Grammatik von der Regulären

- Größere Menge an Wörtern
- Kann nicht mit einem DEA konstruiert werden
- Wörter können durch Ersetzungen in beide Richtungen wachsen (S-> aSb)


Eine formale Sprache ist eine , wenn es eine kontextfreie Grammatik gibt, die diese Sprache erzeugt , oder einen Kellerautomaten, der diese Sprache akzeptiert.