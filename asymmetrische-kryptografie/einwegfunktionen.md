---
description: 'Quellen: [2]'
---

# Einwegfunktionen

Die asymmetrische Kryptografie basiert auf der mathematischen Einwegfunktion und stützt sich dabei darauf, dass es rechentechnisch einfach ist zu erstellen aber unmöglich zurückzurechnen. Man kann sich das bildlich so vorstellen, dass man aus einem Ei sehr einfach ein kaputtes Ei machen kann, aber umgekehrt wird es sehr sehr schwer.

![Einwegfunktion in der Kryptografie](../.gitbook/assets/ei.png)

Es gibt heute zwei-ein-halb solcher Einwegfunktionen oder Algorithmen Funktionen:

* **Faktorisierungsproblem \(RSA\):** Aus zwei gegeben Primzahlen ist es einfach das Produkt zu berechnen. Es ist jedoch sehr schwierig, ein gegebenes Produkt aus zwei Primzahlen zu faktorisieren \(zerlegen in nicht triviale Faktoren\). Grosse Zahlen welche nur wenige Primzahlen haben zu faktorisieren ist schwierig.
* **diskretes Logarithmusproblem \(DLP\)**: Die Umkehrfunktion des diskreten Logarithmus, die diskrete Exponentialfunktion lässt sich leicht berechnen im Gegensatz zum diskreten Logarithmus und stellt somit eine Einwegfunktion dar.
* **Elliptische Kurven \(Teil von diskretem Log Problem\)**: Verallgemeinerung des diskreten Logarithmusproblems

$$
x=f^(^-1) (y)
$$

