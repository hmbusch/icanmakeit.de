---
date: "2009-01-25T00:03:37+01:00"
title: "Pickup-Umschalter (5-Wege)"
draft: false
url: "/e-gitarre-dies-und-das/pickup-umschalter-5-wege/"
categories:
- Technik
tags:
- e-gitarre
- technik
- howto
- page
comments:       false
showDate:       true
showSocial:     false
showTags:       false
showPagination: false
---

Meine erste Gitarre stammt aus einem Starterpaket bestehend aus Verstärker, Gitarre und Zubehör. Den Verstärker habe ich mittlerweile durch einen Modeler ersetzt, die Gitarre verwende ich aber weiterhin, da sie eigentlich sehr solide ist. Es handelt sich um ein Stratocaster-Kopie mit der typischen Tonabnehmerbestückung SSH (zwei Single Coil-Pickups, ein Humbucker).

<!-- more -->

[{{< image classes="left fig-33" src="https://upload.wikimedia.org/wikipedia/commons/9/95/Pickups_Humb_2Single.jpg" title="Tonabnehmerkombination SSH (Quelle: Wikimedia Commons)">}}](https://commons.wikimedia.org/wiki/File:Pickups_Humb_2Single.jpg)

Um zwischen den Pickups umschalten zu können verfügt die Gitarre über einen 5-Wege-Schalter, mit dem man unterschiedliche Kombinationen der Pickups einstellen kann. Dieser Schalter machte recht schnell Probleme, wenn man den Humbucker auswählte gab die Gitarre keinen Ton mehr von sich. Mit Kontaktspray ließ sich das Problem kurzzeitig beheben, tauchte aber bald wieder ab. Also wollte ich mir Ersatz besorgen, der länger hält. Meine Wahl fiel auf ein Original-Fender-Ersatzteil (5-Way Selector Switch, 0991367000), der allerdings anders belegt war als der Schalter in der Gitarre. Ich musste mich entsprechend schlau machen, wie man die Schalter gegeneinander tauscht und als Gedankenstütze für mich und andere Interessierte gibt es hier eine kleine Schalterkunde.

# Schaltschema

Beide Schalter haben zwei Ebenen, was bedeutet, dass es sich eigentlich um zwei einzelne Schalter mit je einem Aus- und drei Eingängen handelt, die aber über einen gemeinsamen Hebel gleichzeitig geschaltet werden. Es gibt auch andere 5-Wege-Schalter, die bis zu 6 getrennte Schaltungen unterstützen (4 Layer Switches, 6 Layer Switches). In der folgenden Aufstellung gelten folgende Konventionen: die erste Schaltung besteht aus den Kontakten A, 1, 2 und 3, die zweite Schaltung besteht aus den Kontakten B, 5 ,6 und 7, wobei ich die mit einem Buchstaben bezeichneten Kontakte als „Ausgang“ bezeichne, der in jedem Zustand geschaltet ist. Bei Schaltern mit zwei Ebenen wie den vorliegenden gibt es folgende Schaltzustände:


| Schalterstellung |               Schaltung 1                    |                 Schaltung 2                    |
|:----------------:|:--------------------------------------------:|:----------------------------------------------:|
| 1                | {{< hl-text red >}}A – 3{{< /hl-text >}}     | {{< hl-text blue >}} B – 4{{< /hl-text >}}    |
| 2                | {{< hl-text red >}}A – 2 – 3{{< /hl-text >}} | {{< hl-text blue >}}B – 4 – 5{{< /hl-text >}} |
| 3                | {{< hl-text red >}}A – 2{{< /hl-text >}}     | {{< hl-text blue >}}B – 5{{< /hl-text >}}     |
| 4                | {{< hl-text red >}}A – 1 – 2{{< /hl-text >}} | {{< hl-text blue >}}B – 5 – 6{{< /hl-text >}} |
| 5                | {{< hl-text red >}}A – 1{{< /hl-text >}}     | {{< hl-text blue >}}B – 6{{< /hl-text >}}     |

# Fernost 5-Wege-Schalter (z.B. EL5PL)

{{< image classes="fancybox left fig-33" thumbnail="https://res.cloudinary.com/dfgqwk8cx/image/upload/t_thumb_240/icanmakeit.de/pages/generic-5-way-switch.jpg" src="https://res.cloudinary.com/dfgqwk8cx/image/upload/q_auto/icanmakeit.de/pages/generic-5-way-switch.jpg" title="Kontaktbelegung eines generischen 5-Wege-Schalters">}}

Diese Schalterart basiert auf einer Platine mit 8 Kontakten und einem beweglichen Schalter mit Schleifkontakten. Solche Schalter sind im Zubehörhandel recht günstig zu bekommen (ca. 5 Euro) und erfüllen ihren Zweck. Bedingt durch die Platinenbauweise verschleißen sie aber schneller. Die Kontaktflächen der einzelnen Kontakte sind auf die Platine aufgedruckt und nicht so abriebfest wie die einzelnen Metalllaschen des Fender-Schalters. Mit zunehmendem Abrieb steigt die Wahrscheinlichkeit, dass die Kontake oxidieren und/odr der Schalter falsch oder gar nicht mehr schaltet. Die Belegung des Schalters ist in folgendem Bild ersichtlich:
Generic 5-Way Switch (2 Layers) for Stratocaster guitars

Hinweis: Bei einigen Schalterausführungen aus Fernost scheint es so zu sein, dass A und B zu nur als ein einzelner, gemeinsamer Kontakt ausgeführt sind, so z.B. bei dem, den ich aus meiner Gitarre ausgebaut habe. Wenn dieser Schalter ausgetauscht wird, kann es notwendig sein, am neuen Schalter A und B ebenfalls miteinander zu verlöten.

# Original Fender 5-Wege-Schalter

{{< image classes="fancybox right fig-33" thumbnail="https://res.cloudinary.com/dfgqwk8cx/image/upload/t_thumb_240/icanmakeit.de/pages/fender-5-way-switch_ibn1ah.jpg" src="https://res.cloudinary.com/dfgqwk8cx/image/upload/q_auto/icanmakeit.de/pages/fender-5-way-switch_ibn1ah.jpg" title="Kontaktbelegung eines original Fender 5-Wege-Schalters">}}

Als Alternative zum „08/15-Schalter“ gibt es einen Schalter aus dem Ersatzteilsortiment von Fender. Dieser Schalter funktioniert, wie bereits oben erwähnt, genauso wie sein Fernostkollege, ist aber anders aufgebaut und hat eine abweichende Anordnung der Kontakte. Statt einer Platine sind die Kontakte dieses Schalters als kleine Metalllaschen realisiert, unter denen eine kreisförmige Kontaktplatte hin und her bewegt wird. Hier sind die zwei Ebenen des Schalters dann auch als solche zu erkennen. Die Belegung des Schalters (immer im Vergleich zu dem anderen vorgestellten Schalter zu sehen) kann diesem Bild entnommen werden:

# Umbau

Alle hier vorgestellten Schalter sind bequem gegeneinander austauschbar, sie schalten gleich und verfügen über identische Befestigungslöcher. Der Umbau ist denkbar einfach, wenn man den oben abgebildeten Schaltbildern folgt, die genau zeigen, welches Kabel an welchen Kontakt zu löten ist. Bei einigen Fernost-Schaltern sind eventuell die Kontakte A und B direkt um Schalter miteinander verbunden. In diesem Fall müssen beim Umbau auf den Fender-Schalter dort ebenfalls die Kontakte A und B miteinander verbunden werden, damit die Gitarre nachher noch funktioniert. Abschließend noch zwei Fotos, das linke zeigt die Verkabelung vor dem Umbau, das rechte die Verkabelung mit dem original Fender-Schalter:

{{< image classes="fancybox fig-50 nocaption" thumbnail="https://res.cloudinary.com/dfgqwk8cx/image/upload/t_thumb_240/icanmakeit.de/pages/5-way-switch-vorher.jpg" src="https://res.cloudinary.com/dfgqwk8cx/image/upload/q_auto/icanmakeit.de/pages/5-way-switch-vorher.jpg" title="Verkabelung mit einem Fernost-5-Wege-Schalter" group="umbau">}}

{{< image classes="fancybox fig-50 nocaption" thumbnail="https://res.cloudinary.com/dfgqwk8cx/image/upload/t_thumb_240/icanmakeit.de/pages/5-way-switch-nachher.jpg" src="https://res.cloudinary.com/dfgqwk8cx/image/upload/q_auto/icanmakeit.de/pages/5-way-switch-nachher.jpg" title="Umgebaute Verkabelung mit einem Fender-5-Wege-Schalter" group="umbau">}}
