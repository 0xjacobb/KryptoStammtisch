# DES \(Data Encryption Standard\)

DES ist eine symmetrische Block-Chiffre mit einem Algorithmus der Blöcke von 64 Bit mit einem 56 Bit Schlüssel chiffriert. Jeder Block wird in 16 Runden verschlüsselt. In jeder Runde wird ein neuer Sub-Schlüssel verwendet der vom Hauptschlüssel abgeleitet wird.

DES \(Data Encryption Standard\) war über 30 Jahre die bei Weitem verbreitetste Blockchiffre zwischen 1970-1990. 1977 wurde der [DES](https://de.wikipedia.org/wiki/Data_Encryption_Standard) Algorithmus als offizieller Standard aufgenommen. Entwickelt von [IBM](https://de.wikipedia.org/wiki/IBM) und der [National Security Agency](https://de.wikipedia.org/wiki/National_Security_Agency) \(NSA\), gab es diverse Zweifel daran ob es gewisse Hintertüren im Algorithmus gab um diesen zu brechen. Die Zweifel haben sich aber nie erhärtet und DES und die sicherere Varianten davon \(3DES = 3x DES hintereinander\) werden bis heute z. B. für Bankdienstleistungen eingesetzt. DES wurde schlussendlich 1999 durch den neuen Standard [AES](https://de.wikipedia.org/wiki/Advanced_Encryption_Standard) ersetzt.

Das Ver-/ und Entschlüsseln im DES ist praktisch die gleiche Funktion und wird dem Feistel Netzwerk bei DES verdankt. Feistel Netzwerke basieren auf der Grundlage der Lucifer Chiffre welche von Horst Feistel entwickelt wurde. Grundsätzlich werden bei der Lucifer Chiffre 48Bit Blöcke mit 128Bit Schlüssel verschlüsselt. Aus unbekannten Gründen hat aber die NSA IBM dazu gebracht den Schlüssel auf 56Bit zu reduzieren.

Es wurden diverse Spezialcomputer gebaut welche DES innert sieben tagen brechen konnten mit Hardwarekosten um 10'000$. Somit wurde der Beweis erbracht, dass DES nicht mehr sicher ist ausser für Anwendungen welche nur für kurze Momente verschlüsselt werden müssen. 3DES gilt aber weiterhin als sicher. DES ist viel performanter auf Hardware als in Software, wird aber heutzutage nur noch für bestehend Systeme genutzt und nicht mehr für neue. 3DES ist dreimal langsamer als DES und die relative kleine Blockgrösse von 64Bit weisst gewisse Nachteile auf.

  Aus diesem Grund wurde AES entwickelt.  


