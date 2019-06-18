# Einführung

Elliptische Kurven gelten als eine der komplexestens Gebiete der Kryptografie, weshalb in den nächsten Kapiteln nur ein Grobüberblick über die Technologie geben wird.

Neben RSA und Verfahren auf dem diskreten Logarithmusproblem sind Elliptische Kurven die dritte asymmetrische Algorithmenverfahren welche derzeit in der Praxis eingesetzt werden.

Das Prinzip wurde Mitte der 1980er Jahre von [Victor S. Miller](https://de.wikipedia.org/wiki/Victor_S._Miller) und [Neal Koblitz](https://de.wikipedia.org/wiki/Neal_Koblitz) unabhängig voneinander vorgeschlagen und bietet die gleiche Sicherheit wie die anderen beiden Verfahren \(RSA, diskret Log mit 1024-3072Bit\) jedoch mit wesentlich kürzeren Schlüsseln \(160-256Bit\) und Operanden.

Unter Elliptic Curve Cryptography \(ECC\) oder zu Deutsch Elliptische-Kurven-Kryptografie versteht man [asymmetrische Kryptosysteme](https://de.wikipedia.org/wiki/Asymmetrisches_Kryptosystem), die das Problem des diskreten Logarithmus zu Nutzen machen, wobei die Berechnung aber viel schwieriger ist als zum Beispiel das Faktorisieren bei RSA oder die Berechnung beim diskreten Logarithmus Problems. 

Das Verfahren ist aber nur sicher, wenn [diskrete Logarithmen](https://de.wikipedia.org/wiki/Diskreter_Logarithmus) in der Gruppe der Punkte der elliptischen Kurve nicht effizient berechnet werden können. Es gibt Kurvenfunktionen welche dies erfüllen und solche die es nicht erfüllen.

Grundsätzlich 

 _"One way to think of public-key cryptography is: a way to enable public-key cryptography that uses very small keys and very obscure math."_

