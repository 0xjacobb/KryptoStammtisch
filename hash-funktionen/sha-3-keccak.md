---
description: 'Quellen: [2], [3], [17], [18]'
---

# SHA-3 \(Keccak\)

Das Herzstück vieler Hash-Algorithmen ist die Kompressionsfunktion.

SHA steht für Secure-Hashing-Algorithm. Es gibt verschiedene SHA Typen \(SHA-0, SHA-1. SHA-2, SHA-3\) mit unterschiedlichen Bitlängen 128Bit, 256Bit etc und unterschiedlichen Kompressionsverfahren.

SHA-1 und SHA-2 verwenden eine Merkle-Damgard Konstruktion und basieren auf der MD4. sind also Teil der MD4-Familie.

SHA-3 hingegen ist eine ganz andere Art nach der Sponge-Konstruktion und ist nicht Teil der MD4-Familie. SHA-3 ist die neuste und modernste Hash Funktion welche in der Praxis genutzt wird und seit 2015 vom NIST \([https://www.nist.gov/](https://www.nist.gov/)\) standardisiert wurde.

Heutzutage gelten SHA-2 wie auch SHA-3 als sicher. Da beide Hash-Funktionen unterschiedliche Algorithmen zu Grunde liegen, hat man zwei Alternativen für den Einsatz in heutigen Systemen.

SHA-2 ist sehr gut für Softwareimplementierungen hingegen SHA-3 besser für die Hardwareimplementierung.

SHA-3 oder auch Keccak genannt \(ist ein erfundener Name\) basiert auf einer sogenannten "sponge construction", in der der Eingang wie ein Schwamm eingelsen aufgesogen wird \(Absorbtionsphase\) und danach Ausgabebits erzeugt werden \(Outputphase\). Wählt man 256 Bit Outputlänge, kommen aus der Absorbtionsphase 1088 Bits raus. Man nimmt dann die höherwertigen 256-Bits von den total 1088 Bits. Das heisst, man erzeugt immer mehr Bits als man am Schluss wirklich nutzt.

In jedem f-Funktions-Durchlauf werden sechs Schritte mit den Namen theta, rho,pi, chi,iota ausgeführt. Jeder dieser Schritte hat eine spezielle Aufgabe um Bits zu manipulieren, verrechnen oder zu verschieben. Hier wird auf die genaue Beschreibung verzichtet

SHA3- / Keccak wird bei den Kryptowährungen wie Bitcoin und Ethereum eingesetzt

