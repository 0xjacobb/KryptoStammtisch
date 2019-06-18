---
description: 'Quellen: [2], [8], [26]'
---

# Einführung

Die Asymmetrische Kryptografie \(auch Public-Key-Kryptografie genannt\), wurde 1976 von Diffie- Hellmann-Merkle vorgestellt. 

Sie hatten die revolutionäre Idee, dass es nicht notwendig sei den Schlüssel der Person welche die Nachricht **verschlüsselt** geheim zu halten. Wicht sei, dass der Empfänger die Nachricht mit einem geheimen Schlüssel **entschlüsseln** kann. Dadurch kann man Schlüssel nud Nachricht über einen unsicheren Kanal verschicken ohen das jemand die Nachricht lesen kann. 

Britische Geheimdienstler hatten das Verfahren anscheinend schon 1972 entdeckt und genutzt der Erfolg wurde aber den drei Herren oben gewidmet.

Asymmetrische Verfahren unterscheiden sich komplett von Symmetrischen Verfahren, da es sich bei asymmetrischen Verfahren um ein Mechaismus basierend auf zahlentheoretischen Verfahren handelt. Das heisst, es handelt sich um mathematische Zusammenhänge zwischen Eingang und Ausgang.

Bei der asymmetrischen Verschlüsselung gibt es im Gegensatz zu einem Symmetrischen, nicht nur ein Schlüssel, sondern gleich **zwei**. 

Dieses sogenannte Schlüsselpaar setzt sich aus einem privaten Schlüssel \(Privater Schlüssel -&gt; Private Key\) und einem öffentlichen Schlüssel \(nicht geheim -&gt; Public Key\) zusammen.

Gemäss Wikipedia: 

_"Jeder Benutzer erzeugt sein eigenes Schlüsselpaar, das aus einem geheimen Teil \(_[_privater Schlüssel_](https://de.wikipedia.org/wiki/Privater_Schl%C3%BCssel)_\) und einem nicht geheimen Teil \(_[_öffentlicher Schlüssel_](https://de.wikipedia.org/wiki/%C3%96ffentlicher_Schl%C3%BCssel)_\) besteht. Der öffentliche Schlüssel ermöglicht es jedem, Daten für den Besitzer des privaten Schlüssels zu_ [_verschlüsseln_](https://de.wikipedia.org/wiki/Verschl%C3%BCsselung)_, dessen digitale Signaturen zu prüfen oder ihn zu authentifizieren. Der private Schlüssel ermöglicht es seinem Besitzer, mit dem öffentlichen Schlüssel verschlüsselte Daten zu_ [_entschlüsseln_](https://de.wikipedia.org/wiki/Entschl%C3%BCsselung)_,_ [_digitale Signaturen_](https://de.wikipedia.org/wiki/Digitale_Signatur) _zu erzeugen oder sich zu_ [_authentisieren_](https://de.wikipedia.org/wiki/Authentifizierung)_."_

Ein wichtiger Unterschied der asymmetrischen zur symmetrischer Kryptografie besteht auch darin, dass bei symmetrischer Kryptografie alle beteiligten Parteien Ver- wie auch Entschlüsseln können. Das heisst beide Parteien können beide Funktion durchführen, was zu gewissen Problemen führen kann. 

Ein theoretisches Beispiel: Nach dem ein Käufer Online eine Wahre gekauft und auch erhalten hat, könnte dieser nachträglich behaupten, er hätte den Kauf nie getätigt, sondern der Verkäufer hätte diesen Kauf initiiert. Wieso kann der Verkäufer dies behaupten? Weil beide den gleichen Schlüssel zum Geheimnis besitzen und nicht ausgeschlossen werden kann, dass der Verkäufer tatsächlich böswillig gehandelt hat! 

Asymmetrische Kryptografie löst dieses Problem der **Nichtzurückweisbarkeit** mittels digitalen Signaturen, welche als Unterschrift dem Kauf oder der Nachricht hinzugefügt werden und eindeutig beweisen, wer den Kauf oder die Nachricht erstellt hat.

In der heutigen Zeit gibt es unter anderem folgende wichtigen Asymmetrische Verschlüsselungen im Einsatz:

* **RSA** \(Erfinder: Ronald L. **R**ivest, Adi **S**hamir und Leonard **A**dleman\)
* **Elgamal** \(basierend auf diskretem Logarithmus\)
* **Elliptische Kurven \(ECC\)** 

**Vorteile der asymmetrischen Kryptografie:**

* Relativ hohe Sicherheit
* Es werden nicht so viele Schlüssel benötigt wie bei einem symmetrischen Verschlüsselungsverfahren, somit weniger Aufwand der Geheimhaltung des Schlüssels
* Kein Schlüsselverteilungsproblem, da Public Key für jeden ohne Probleme zu erreichen ist
* Möglichkeit der Authentifikation durch elektronische Unterschriften \(digitale Signaturen\)

**Nachteile der asymmetrischen Kryptografie:**

* Asymmetrischen Algorithmen arbeiten sehr langsam ca. 10 000 Mal langsamer als symmetrische.
* Grosse benötigte Schlüssellänge 
* Probleme bei mehreren Empfänger einer verschlüsselten Nachricht, da jedes Mal die Nachricht extra verschlüsselt werden muss -&gt; Abhilfe schaffen hybride Verfahren - Sicherheitsrisiko durch für jeden zugänglichen Public Key -&gt; Man in the Middle





