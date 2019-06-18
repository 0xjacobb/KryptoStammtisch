# Anwendung der Elliptischen Kurve Kryptografie

Eine elliptische Kurve ist eine Sammlung von Punkten, die einer bestimmten Gleichung genügen meist in Form von:

$$
y^2=x^3+ax+b
$$

In der Kryptografie mit Elliptichen Kurven gibt es dabei immer eine fest definierte Kurvefunktion im Falle von Bitcoin wäre dies secp256k1. Dabei werden die Startpunkte a und b gewählt und allgemein spezifiziert, wie auch ein bekannter, immer gleichen Startpunkt  \(G\) definiert.

Elliptische Kurven werden zum Besipiel für die Berechnung von digitalen Signaturen \(Elliptic Curve Digital Signature Algorithm - ECDSA\) verwendete um wie in den vorherigen Kapitel beschrieben, das Problem der Echtheit des Senders zu gewährleisten. 

Digitale Signaturen werden später in im Kapitel [digitale Signaturen](../digitale-signaturen/) beschrieben. 

{% hint style="info" %}
Bei Bitcoin wird die Elliptische Kurven Kryptografie  verwendet um aus dem Private Key den Public Key zu erstellen. Der Endpunkt den man nach der Berechnung erreicht ist der Public Key. 
{% endhint %}

Um nun einen öffentlichen und einen geheimen Schlüssel zu erzeugen geht man wie folgt vor:

1. Man generiert eine zufällige \(prim\) Zahl \(s\), dies ist der Private Key
2. Man wählt eine Kurvenfunktion z.B secp256k1
3. Man multipliziert  den Private Key \(s\) mit dem allgmein bekannten Startpunkt \(G\) der Kurvenfunktion und erhält \(p\): s\*G = p
4. Das Ergebnis der Multiplikation ist wieder ein Punkt auf der Kurve, dies ist der Public Key

Elliptische Kurven nutzen nun das Problem aus, dass man eine Multiplikation von s\*G = p sehr schnell durchführen kann, die Rückrechnung auf \(s\) jedoch sehr schwierig ist. 

Man kann nicht einfach durch G teilen \(Division existiert bei Elliptischen Kurven nicht\), sondern braucht enormen Rechenaufwand für die Rückrechnung \(Diskretes Logarithmus Problem\).

Folgend ein konkretes Beispiel:

![Elliptische Kurven Kryptografie Prinzip](../../.gitbook/assets/ecc_2.png)

1.    Man zeichnet eine gerade Linie vom Startpunkt A zu einem beliebigen Punk B. Die Gerade schneidet die Kurve an einem zweiten Punkt.

2.    Dieser neue Schnittpunkt wird an der x-Achse gespiegelt und ergibt einen neun Punkt C. Man sagt dann: A + B = C

3.    Danach verbindet man diesen neuen Punkt C mit dem Startpunkt A und es ergibt sich wiederum ein neuer Schnittpunkt der an der x-Achse gespiegelt wird und woraus der neue Punkt D entsteht

4.    Zieht man wieder eine Linie zum Startpunkt A und spiegelt den Schnittpunkt an der x-Achse ergibt dies den neuen Punkt E.

Der Prozess wiederholt sich **n** mal, wobei **n** der Private Key als Zahl ist. Der Public Key ist schlussendlich der Endpunkt nach n-Mal ausführen des Prozesses. 

In unserem obigen Beispiel wäre der Public Key der Punkt E. Dieser Punkt E hat eine x- und y Koordinate welche zusammengeführt den Public Key ergeben. Das heisst beide Koordinaten \(x- und y Koordinate\) werden hintereinander zusammengefügt und diese neue Zahl ergibt den Public Key.

Verwednete man die gleiche Kurvenfunktion,  hat man als Startpunkt den gleichen Startpunkt, da dieser wie oben beschrieben in der Definition vom US National Institute of Standards and Technolgy \(NIST\) festgelegt wird. Das bedeutet, dass ein Private Key Multipliziert mit dem Startpunkt immer den gleichen Public Key ergeben wird. Das Rückrechnen aber dank der Mathematik praktisch unmöglich ist.

