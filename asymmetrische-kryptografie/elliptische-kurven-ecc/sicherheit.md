# Sicherheit

Bei Elliptischen Kurven ist das Lösen des diskreten Logarithmusproblems noch viel schwerer womit die Elliptische Kurve als eine besonders gute Einwegfunktion gilt. Dies weil das erstellen des Private Keys durch eine Multiplikation stattfindet und das RPckrechnen, die Division, auf Elliptischen Kurven nicht vorhanden ist.

Es sollte aber betont werden, dass die gute Sicherheit nur erreicht wird, wenn kryptografisch starke elliptische Kurven benutzt werden. in der Praxis werden oft standardisierte Kurven eingesetzt.

Eine 256-Bit Kurve benötigt auf einem Rechner mit 3GHz Taktung ca. 1ms auf einem Smartphone ca 10ms auf Webservern mit Hardwarebeschleuniger 10us. Um die Sicherheit zu erhöhen, könnte man die Bitlänge um zwei Bits erhöhen und der Aufwand für den Attacker würde sich verdoppeln.

Die gängige Meinung heutzutage ist, dass elliptische Verfahren als sehr sicher gelten und daher auch in verschiedensten Anwendung in US Bankenstandards eingesetzt werden. Auf Grund der geringen Rechenleistung werden sie auch oft in Embedded Systemen eingesetzt.

Nach den Enthüllungen von Edward Snowden 2015 hat man einige Bedenken, dass die vom NIST standardisierten Kurven Schwachstellen aufweisen könnten und es werden vermehrt anderen Kurven eingesetzt. Konkrete Beweise gibt es nicht.  


