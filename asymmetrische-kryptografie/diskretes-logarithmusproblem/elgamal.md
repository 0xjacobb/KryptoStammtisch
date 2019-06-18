# Elgamal

Das Verfahren wurde 1985 von Taher Elgamal vorgeschlagen und kann als Erweiterung zur Diffie-Hellman-Schlüsselaustausch gesehen werden. Es ist ein probabilistisches Verschlüsselungsverfahren bei der der Sitzungsschlüssel als multiplikative Maske zur Nachrichtenverschlüsselung verwendet wird

Es besteht aus zwei Phasen:

**Phase 1:** Möchten Alice und Bob eine verschlüsselte Nachricht austauschen müssen beide Parteien zunächst einen Diffie-Hellman-Schlüsselaustausch \(DHKE\) durchführen, um ein gemeinsames Geheimnis kM zu berechnen.

**Phase 2:** Die Verschlüsselungsphase und Entschlüsselungsphase werden bei jedem Nachrichtenaustausch ausgeführt und basieren auf einem flüchtigen Schlüssel. Das Resultat ist, dass das Chiffrat zwei identischer Nachrichten unter Verwendung desselben öffentlichen Schlüssels mit hoher Wahrscheinlichkeit zwei unterschiedliche Chiffrate ergibt.

Somit kann man durch Abfangen der Nachricht nicht auf bestimmtes Grundverfahren abbilden.

