# Einführung

RSA basiert auf der Schwierigkeit der Primfaktorzerlegung des Modulo n, sprich der Schwierigkeit, grosse Zahlen zu faktorisieren. Es handelt sich somit um die Einwegfunktion des **Faktorisierungsproblems**.

RSA ist ein [asymmetrisches kryptographisches Verfahren](https://de.wikipedia.org/wiki/Asymmetrisches_Kryptosystem), das sowohl zum Verschlüsseln als auch zum digitalen Signieren verwendet werden kann. Es verwendet ein Schlüsselpaar, bestehend aus einem privaten Schlüssel, der zum Entschlüsseln oder Signieren von Daten verwendet wird, und einem öffentlichen Schlüssel, mit dem man verschlüsselt oder Signaturen prüft.

Nachdem [Whitfield Diffie](https://de.wikipedia.org/wiki/Whitfield_Diffie) und [Martin Hellman](https://de.wikipedia.org/wiki/Martin_Hellman) im Jahr 1976 eine Theorie zur Public-Key-Kryptografie veröffentlicht hatten, versuchten die drei Mathematiker [Rivest](https://de.wikipedia.org/wiki/Ronald_L._Rivest), [Shamir](https://de.wikipedia.org/wiki/Adi_Shamir) und [Adleman](https://de.wikipedia.org/wiki/Leonard_Adleman) am MIT, die Annahmen von Diffie und Hellman zu widerlegen. Nachdem sie den Beweis bei verschiedenen Verfahren durchführen konnten, stiessen sie schließlich auf eines, bei dem sie keinerlei Angriffspunkte fanden. Hieraus entstand 1977 RSA, das erste veröffentlichte asymmetrische Verschlüsselungsverfahren. 

Der Name RSA steht für die Anfangsbuchstaben ihrer Familiennamen. Folgende eine Grobübersicht:

* RSA war in den USA bis 2000 patentiert
* wird hauptsächlich für die Verschlüsselung von kleinen Datenmengen und vor allem den Schlüsseltransport für symmetrische Algorithmen verwendet
* auch eingesetzt bei digitalen Signaturen und für Zertifikate im Internet
* Wird bei neueren Anwendungen nicht mehr so oft benutzt, sondern eher Elliptische Kurven
* Auf Grund von Attackvektoren sollte man Schlüssellängen von mindestens 2048 Bit einsetzen.

