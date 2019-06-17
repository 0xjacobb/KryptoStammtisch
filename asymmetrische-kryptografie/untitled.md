---
description: 'Quellen: [2], [8], [26]'
---

# Einführung

Die Asymmetrische Kryptografie \(auch Public-Key-Kryptografie genannt\), wurde 1976 von Diffie- Hellmann-Merkle vorgestellt. Britische Geheimdienstler hatten das Verfahren anscheinend schon 1972 entdeckt und genutzt. Sie hatten die revolutionäre Idee, dass es nicht notwendig sei den Schlüssel der Person welche die Nachricht **verschlüsselt** geheim zu halten. Wicht sei, dass der Empfänger die Nachricht mit einem geheimen Schlüssel **entschlüsseln** kann.

Asymmetrische Verfahren unterscheiden sich komplett von Symmetrischen Verfahren, da es sich bei asymmetrischen Verfahren basierend auf zahlentheoretischen Verfahren handelt. Das heisst, es handelt sich um mathematische Zusammenhänge zwischen Eingang und Ausgang.

Bei der asymmetrischen Verschlüsselung gibt es im Gegensatz zu einem Symmetrischen, nicht nur ein Schlüssel, sondern gleich **zwei**. Dieses sogenannte Schlüsselpaar setzt sich aus einem privaten Schlüssel \(Privater Schlüssel -&gt; Private Key\) und einem öffentlichen Schlüssel \(nicht geheim -&gt; Public Key\) zusammen.

Mit dem **privaten Schlüssel** werden Daten **Entschlüsselt** oder eine digitale Signatur erzeugt. Mit dem **öffentlichen Schlüssel** kann man Daten **verschlüsseln** und Signaturen auf ihre Authentizität überprüfen. 

1.    Entschlüsseln und Signaturen erzeugen \(Private Key\)

2.    Verschlüsseln und Verifizieren von Signaturen \(Private Key\)

Ein wichtiger Unterschied der asymmetrischen zur symmetrischer Kryptografie besteht auch darin, dass bei symmetrischer Kryptografie alle beteiligten Parteien Ver- wie auch Entschlüsseln können. 

Das bedeutet, dass zum Beispiel bei einem Online Kauf durch den Käufer die Möglichkeit besteht nachträglich nach Erhalt der Wahre zu behaupten, er hätte den Kauf nie getätigt, sondern der Verkäufer hätte diesen Kauf initiiert. Wieso kann der Verkäufer dies behaupten? Weil beiden den gleichen Schlüssel zum Geheimnis besitzen! 

Asymmetrische Kryptografie löst dieses Problem der **Nichtzurückweisbarkeit** mittels digitalen Signaturen, welche als Unterschrift dem Kauf oder der Nachricht hinzugefügt werden und eindeutig beweisen, wer den Kauf oder die Nachricht erstellt hat.

In der heutigen Zeit gibt es unter anderem folgende wichtigen Asymmetrische Verschlüsselungen im Einsatz:

* **RSA** \(Erfinder: Ronald L. **R**ivest, Adi **S**hamir und Leonard **A**dleman\)
* **Elgamal** \(basierend auf diskretem Logarithmus\)
* **Elliptische Kurven \(ECC\)** 

**Vorteile:**

* Relativ hohe Sicherheit
* Es werden nicht so viele Schlüssel benötigt wie bei einem symmetrischen Verschlüsselungsverfahren, somit weniger Aufwand der Geheimhaltung des Schlüssels
* Kein Schlüsselverteilungsproblem, da Public Key für jeden ohne Probleme zu erreichen ist
* Möglichkeit der Authentifikation durch elektronische Unterschriften \(digitale Signaturen\)

**Nachteile:**

* Asymmetrischen Algorithmen arbeiten sehr langsam ca. 10 000 Mal langsamer als symmetrische.
* Grosse benötigte Schlüssellänge 
* Probleme bei mehreren Empfänger einer verschlüsselten Nachricht, da jedes Mal die Nachricht extra verschlüsselt werden muss -&gt; Abhilfe schaffen hybride Verfahren - Sicherheitsrisiko durch für jeden zugänglichen Public Key -&gt; Man in the Middle





