---
description: 'Quellen: [2]'
---

# Einführung

Neben den symmetrischen wie auch asymmetrischen Protokollen gibt es eine weitere Gruppe von Kryptografischen Protokollen, die Hash Funktionen. Hash Funktionen haben viel mit symmetrischen Algorithmen gleich, weshalb diese oft auch in der symmetrischen Kategorie geführt werden.

Grundsätzlich berechnen Hash Funktionen aus einer gegebenen Nachricht eine Bitfolge mit fester Länge, die ein Repräsentant der Nachricht ist. Der Hashwert kann als Fingerabdruck der Nachricht betrachtet werden und im Gegensatz zu allen anderen Kryptoverfahren habe diese keinen Schlüssel \(unkeyd crypto functions\).

Hash Funktionen werden oftmals auch für digitale Signaturen von Klartext eingesetzt wobei bei den meisten Kryptoverfahren fixe Bitlängen vorgegeben sind und dadurch die Grösse der Nachricht begrenzt ist.

Hash Funktionen lösen nun das Problem, wie man effizient einzelne und kurze Signaturen für lange Nachrichten berechnen können.

Da jede Hash-Funktion eine feste Ausgangslänge hat, gibt es auch eine endliche Anzahl an mögliche Ausgangswerte. Da es aber unendliche viele Eingangswerte gibt, müssen zwangsläufig mehrere unterschiedliche Eingangswerte den gleichen Ausgangswert \(Hash-Wert\) produzieren können. Wichtig ist, dass dieses Kollisionsrisiko extrem klein ist, was mit einer Bitlänge von 128-512Bit gewährleistet ist.

Historisch betrachtet, begann man die Hash Funktionen ca. 1980 zu standardisieren. Folgend eine kleine Auflistung:

* MD4 \(1980\)
* MD5 \(1991\)
* SHA-1 \(1995
* SHA-2 \(2001\)
* SHA-3 \(2012 --&gt; Algorithmus "Keccak" wird SHA-3\)

Hash Funktionen werden in zwei Klassen unterteilt:

**Dezidierte Hash Funktion:** Algorithmen welche speziell für als Hash Funktion entwickelt wurde

**Hash Funktionen basierend auf Blockchiffren:** Hash Funktionen welche z.B aus AES konstruiert  


