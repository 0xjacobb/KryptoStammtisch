# Funktionsprinzip der asymmetrischen Kryptografie

Anders als bei der symmetrischen Verschlüsselung, steht bei asymmetrischen Verschlüsselungsverfahren der Empfänger am Anfang. Dieser generiert zwei verschiedene Schlüssel:

* Zum einen den **Private Key**, den privaten Schlüssel, mit dem man entschlüsseln respektive decodieren kann. Dieser Schlüssel verbleibt beim Empfänger.
* Zum anderen den **Public Key**, den öffentlichen Schlüssel, mit dem man verschlüsseln respektive codieren kann - und nichts anderes. Allein aus der Kenntnis des Public Keys kann man die Nachricht nicht entschlüsseln, nur verschlüsseln.

Der Public Key vom Empfänger wird nun dem Sender zugänglich gemacht. Das kann zum einen durch einen ganz einfachen Transport geschehen per e-Mail oder auch durch Zertifizierungsstellen oder Key-Server bei denen die Schlüssel hinterlegt werden und für jeden zugänglich sind. Wichtig ist, der Public Key darf jeder kennen, auch der Angreifer!

Der Sender verschlüsselt nun seine Nachricht mit dem Public Key des Empfängers. Einmal verschlüsselt, kann auch der Sender die Nachricht nicht mehr entschlüsseln, da ihm der Private Key zu dem Public Key des Empfängers fehlt. 

Der Geheimtext wird nun dem Empfänger über einen unsicheren Kanal geschickt, was aber nicht von Bedeutung ist.

Selbst wenn jemand sowohl den Geheimtext als auch den Public Key abfängt, kann er  die Nachricht nicht entschlüsseln. Dazu ist allein der Private Key des Empfängers im Stande, welcher nicht transportiert werden musste und beim Empfänger hoffentlich sicher gelagert ist. 

Nach Empfangen der Nachricht wird  diese schliesslich durch den Empfänger und dessen Private Key entschlüsselt.

