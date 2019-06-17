# Diffie-Hellmann Schlüsselaustausch \(DHKE\)

Der Diffie-Hellman-Schlüsselaustausch oder Diffie-Hellman-Merkle-Schlüsselaustausch bzw. –Schlüsselvereinbarung \(auch kurz DHM-Schlüsselaustausch oder DHM-Protokoll oder Englisch DHKE für Key Exchange\) ist ein Protkoll zum Schlüsselaustausch und wurde 1976 veröffentlicht.

Es ermöglicht, dass zwei Kommunikationspartner über eine öffentliche, unsichere und abhörbare Leitung einen gemeinsamen und geheimen Schlüssel in Form einer Zahl vereinbaren können, den nur diese kennen und ein potenzieller Lauscher nicht berechnen kann. 

Der dadurch vereinbarte Schlüssel könnte auch anschliessend für ein symmetrisches Kryposystem verwendet werden was zu Hybriden System von symmetrisch wie auch asymmetrischen Algorithmen führt.

Der DHM- Schlüsselaustausch löst somit eines der wichtigsten Probleme der Kryptografie. Wie kann ich sicher und einfach einen gemeinsamen Schlüssel über eine unsichere Leitung austauschen.

Der DHM-Schlüsselaustausch alleine ist allerdings nicht sicher. Schaltet sich ein Angreifer zwischen die beiden Kommunikationspartner kann er die  Nachrichten verändern. Sprich der Empfänger weiss nicht, ob die Nachricht die er empfängt authentisch ist und wirklich vom Originalsender gekommen ist. Der Angreifer könnte auf eine Seite mit dem Absender kommunizieren und auf die andere Seite mit dem Empfänger und jeweils mit beiden Parteien separat einen Schlüsselaustausch durchführen

Diese Lücke schliessen andere Protokolle \(z.B Elliptische Kurven\), indem sie zusätzlich [digitale Signaturen](https://de.wikipedia.org/wiki/Digitale_Signatur) und [Message Authentication Codes](https://de.wikipedia.org/wiki/Message_Authentication_Code) verwenden, dazu aber später mehr.

