---
outdated_translation: true
outdated_since: 64371c026467a1a6f68b477c908674ffe23da6e2
---

# osu!stream

![](img/Os-Logo.jpg "Logo von osu!stream")

**osu!stream** ist eine Version von osu!, die von Grund auf neu entwickelt wurde und extra für touch-fähige Geräte ausgelegt ist. Aktuell ist sie nur für Apples [iOS](http://en.wikipedia.org/wiki/IOS)-Plattform verfügbar. Ein [Android](http://en.wikipedia.org/wiki/Android_%28operating_system%29)-Port war geplant und beinahe fertig, wurde aber noch nicht veröffentlicht, da es Probleme bei der Audiolatenz gab, die den Spielspaß massiv beeinträchtigten.

Enthalten ist ein komplett überarbeitetes Spielsystem mit neuen Spielelementen wie den Hold-Circles und verbundenen Beats. Klassische osu! Beatmaps werden nicht ohne manuelle Umwandlung unterstützt. Stattdessen wurden neue Beatmaps explizit von einem besonderen Team an Mappern erstellt, um die Chance der neuen Spielelemente auszunutzen. Diese neuen Beatmaps haben einen [strikteren Standard](https://docs.google.com/document/d/1FYmHhRX-onR-osgTS6uHSOZuu_0JEbfRZePVySvvr9g).

[osu!stream wurde in osu!monthly \#5 zusammen mit einem Interview vorgestellt.](https://osu.ppy.sh/community/forums/topics/59924)

Die Entwicklung für diese Version endete in 2020. Für mehr Informationen lies den [Blog-Beitrag](https://blog.ppy.sh/osu-stream-2020-release/) über ihre letzte Veröffentlichung. Der Quellcode zusammen mit den Beatmap-Konvertierungs- und Test-Tools wurde im selben Jahr unter einer freien Lizenz auf [GitHub](https://github.com/ppy/osu-stream) zur Verfügung gestellt. Alle zuvor kostenpflichtigen Beatmaps sind jetzt kostenlos im in-game "Store" erhältlich.

## Installation

![](img/Os-Devices.jpg "osu!stream auf iOS-Geräten")

### iOS App Store Methode (empfohlen)

**Versichere dich, dass dein iOS-Gerät sich mit dem Internet verbinden kann (entweder über WLAN oder 3G/4G).**

- Gehe zu "App Store" auf deinem iOS-Gerät
- Suche nach osu!stream
- Installiere osu!stream
  - Wenn nach der Apple ID und dem Passwort gefragt wird, gib diese bitte ein.
- osu!stream kann gespielt werden, nachdem die App heruntergeladen und installiert wurde.
  - Es wird empfohlen, auch das "Beatmaps hinzufügen" Kapitel zu lesen, um an die neusten kostenlosen Songs zu kommen. Der aktuelle Download enthält nur zwei Songs.

### Methode über USB

**Das Gerät muss [iTunes](https://www.apple.com/itunes/) installiert haben.**

- Gehe zu [diesem Link und lade es dir herunter](http://itunes.apple.com/us/app/osu!stream/id436952197?ls=1&mt=8).
  - Wenn nach der Apple ID gefragt wird, gib die Apple ID und das Passwort ein.
- Stecke dein iOS-Gerät in dein Gerät (welches osu!stream hat).
- Transferiere die osu!stream Dateien mit iTunes.
- Entferne das iOS-Gerät und osu!stream kann gespielt werden.

## Beatmaps hinzufügen

**Versichere dich, dass das iOS-Gerät sich mit dem Internet verbinden kann (entweder über WLAN oder 3G/4G).**

- Öffne osu!stream.
- Drücke auf das osu! Symbol und du solltest direkt in das Hauptmenü weitergeleitet werden (oder das Tutorial beim ersten Mal)
- Drücke die "Store" Leiste
  - Alternativ kannst du auch in der "Play" Sektion auf "Download more songs!" drücken.
- Wähle ein gewünschtes Paket aus.

## Was ist der Unterschied?

- **Nur auf iOS-Geräten spielbar.** (aktuell)
- Beatmaps sind von Grund auf neu gemacht.
- Es wird kein Account zum Herunterladen von Songpaketen benötigt.
- osu!stream kann mit einem Twitterkonto genutzt werden.
- Highscores können anonym zur Seite als "Guest" gesendet werden (benötigt eine Internetverbindung).
- Der Circle-Timer wird ersetzt und befindet sich nun unten mit einer kleinen Grenzlinie, die abhängig von der Genauigkeit des Spielverlaufs gefärbt ist. \[Bottom(Long)\]
- Die **Durchschnittliche Abweichung** wird am Ergebnisbildschirm angezeigt.
- Alte Rekorde und Aufzeichnungen können nicht gespeichert werden.
- Der Skin kann nicht gewechselt werden und Mods sind nicht auswählbar (bislang).
- Easter Eggs können gefunden werden, aber es gibt noch keine Seite für Errungenschaften...

### Neues Spielsystem

**Anmerkung:** Teste die neuen Spielelemente im "Tutorial" Bildschirm.

#### Fingerführungsanzeige

![](img/Os-FG.jpg "Fingerführungsanzeige")

- Die zwei transparenten Kreise, die im Spiel auftauchen, helfen Anfängern zu wissen, wann sie die Objekte treffen müssen.
  - Es zeigt die empfohlene Methode, um die Map perfekt abzuschließen.
- Die grüne Farbe ist für die linke Hand und die rote Farbe ist für die rechte Hand.
- Diese Funktion kann im Optionsmenü oder nach dem Beenden des Tutorials deaktiviert werden.

#### Verbundene Beats

![](img/Os-CB.png "Verbundene Beats")

- Bei verbundenen Beats, wie der Titel vermuten lässt, muss der Spieler beide Objekte gleichzeitig drücken.
  - Verbundene Beats sind nicht nur auf "hit circle-hit circle" beschränkt, es kann auch "hit circle-slider", "hold circle-slider" und so weiter sein.
- Verbundene Beats sind durch eine weiße Linie, die mit einem anderen Objekt verbunden ist, gekennzeichnet.

#### Hold-Circle

![](img/Os-HC.jpg "Hold-Circle 1")

---

![](img/Os-HC2.jpg "Hold-Circle 2")

- Hold-Circles müssen vom Spieler längere Zeit gehalten werden, bis der Kreis "explodiert".
- Die Treffergenauigkeit wird dadurch bestimmt, wie früh oder spät der Kreis getroffen wurde und ob dieser bis zum Ende gehalten wurde.
  - Wenn der Finger hochgehoben wurde, bevor der Kreis "explodierte", wird der Combo-Multiplikator auf 0 zurückgesetzt. Allerdings erhält man keinen Miss, solange der Hold-Circle getroffen wurde.
  - Wenn der Spieler den Kreis nicht gehalten hat, werden solange Lebenspunkte abgezogen, bis der Hold-Circle explodiert ist.

### Neue Modi, welche die Schwierigkeit ersetzen

---

![](img/Os-PlayEasy.png "Leicht")

---

![](img/Os-PlayNormal.png "Normal")

---

![](img/Os-PlayHard.png "Schwer")

---

![](img/Os-PlayExpert.jpg "Experte")

---

#### Leichter Modus

![](img/Os-ModeEasy.jpg "Leichter Modus")

**Schwierigkeitsgrad: Easy + [NoFail](/wiki/Gameplay/Game_modifier/No_Fail)**

Der leichte Modus ist für Anfänger gedacht, die sich an die Spieltechnik von osu!stream gewöhnen müssen. Der Spielverlauf ist wesentlich langsamer, sodass neue Spieler den Flow und das Timing zum Treffen verstehen können. Lebensleisten werden nicht vergeben und durch das Spielen des leichten Modus wird der Expertenmodus nicht freigeschaltet.

Die Hintergrundfrabe ist grün.

#### Streammodus

![](img/Os-ModeStream.jpg "Streammodus")

**Schwierigkeitsgrad: Easy ("Stream Down!" von Normal aus) ~ Normal (Startpunkt) ~ Hard ("Stream Up!" von Normal aus)**

Der Streammodus ist ein exklusiver Modus in osu!stream. In diesem Modus starten Spieler mit einer zur Hälfte gefüllten "zweiten" Lebensleiste und der normale Schwierigkeitsgrad ist eingestellt. Der Spieler muss darauf die Lebensleiste füllen, um "Stream Up!" zu aktivieren, was im Grunde die Schwierigkeit erhöht (durch das Hinzufügen von weiteren Objekten und dem Wechsel zum schweren Schwierigkeitsgrad der Map). Dies ist aber immer noch bedeutend einfacher als der Expertenmodus. Wenn der Spieler in den "Stream Up!" Modus gelangt, dann wird eine Lebensleiste vergeben. Sollte diese Lebensleiste leer werden, wird "Stream Down!" erscheinen. Der Schwierigkeitsgrad geht danach zurück auf Normal oder Leicht, abhängig von der Anzahl der Lebensleisten.

Lange Rede kurzer Sinn, der Spieler startet zwischen Leicht und Schwer.

Beachte, dass der Spieler **mindestens einen A Rang (>80% Genauigkeit) in diesem Modus haben muss, um den Expertenmodus des Songs freizuschalten**. Eine Genauigkeit von weniger als 80%, auch wenn es eine volle Combo war, zählt nicht als A (Es gilt dann wie üblich als B).

Die Hintergrundfarbe ist grün (Leicht), blau (Normal), und pink (Schwer).

---

![](img/Os-SU.png "Stream Up!")

---

![](img/Os-SD.png "Stream Down!")

---

![](img/Os-Zero1.png "Kritische Gesundheit")

---

![](img/Os-Zero2.png "Spiel vorbei")

---

#### Expertenmodus

![](img/Os-ModeExpert.jpg "Expertenmodus")

**Schwierigkeitsgrad: Experte**

Am Anfang gesperrt und nur durch ein A oder besser im Streammodus freischaltbar. Der Expertenmodus ist für Spieler, die eine größere Herausforderung suchen. In diesem Modus erhalten die Spieler einen vollen Lebensbalken und müssen ihn bis zum Ende des Liedes erhalten. Der erfolgreiche Abschluss schaltet nichts frei außer dem Recht zum Angeben.

Die Hintergrundfarbe ist violett und die Lichter verdunkeln sich, abhängig von den aktuellen Lebenspunkten

## Benutzeroberfläche

---

![](img/Os-MM.png "Hauptmenü")

---

![](img/Os-SL.jpg "Songliste")

---

![](img/Os-Store.jpg "Store")

---

![](img/Os-DS.png "Wahl des Schwierigkeitsgrad")

---

![](img/Os-SI.png "Songinformationen")

---

![](img/Os-PlayExpert.jpg "Expertenmodus")

---

![](img/Os-Pause.png "Pausenmenü")

---

![](img/Os-FM.png "Menü bei einem gescheiterten Versuch")

---

![](img/Os-SC.png "Stage cleared!")

---

![](img/Os-Grade.jpg "Ergenisbildschirm")

---

![](img/Os-O1.png "Optionsmenü 1")

---

![](img/Os-O2.png "Optionsmenü 2")

---

## Songliste

***[Klicke hier für die gesamte Liste](Song_List)***

## Punktevergabe

*Hinweis: Die Rangliste kann noch im Spiel angesehen werden, allerdings werden keine neuen Punktestände mehr angenommen.*

### Genauigkeit

`Genauigkeit = Trefferwert / (perfekter Trefferwert)`

| Begriff | Formel |
| :-: | :-- |
| **Trefferwert** | (Anzahl der Misses \* 0 + Anzahl der 50er \* 1 + Anzahl der 100er \* 2 + Anzahl der 300er \* 4) |
| **perfekter Trefferwert** | (Anzahl der Misses + Anzahl der 50er + Anzahl der 100er + Anzahl der 300er) \* 4 |

Mit anderen Worten, jeder Miss ist 0%, jeder 50er ist 25%, jeder 100er ist 50% und jeder 300er ist 100% Genauigkeit wert.

### Punkte

Die Punkte, die von jedem Hit-Circle und jedem Ende eines Sliders vergeben werden, werden mit folgender Formel berechnet:

`Punkte = Trefferwert + Trefferwert * (Combo-Multiplikator * fester Multiplikator) / 25`

| Begriff | Bedeutung |
| :-: | :-- |
| **Trefferwert** | Die [Bewertung](/wiki/Gameplay/Judgement) des Hit-Circles (50, 100 oder 300). |
| **Combo-Multiplikator** | (Combo vor dem Treffer - 1) oder 0; abhängig davon, was höher ist. |
| **Fester Multiplikator** | Der Multiplikator, der den Punktestand bei 600.000 fixiert. |

Außerdem gibt es für jeden Start-, End- und Wiederholungstick eines Sliders 30 Punkte und für jede volle Umdrehung eines Spinners 100 Punkte. Es gibt einen weiteren Bonus von 10 Punkten, abhängig von den Umdrehungen pro Minute, nachdem die Spinnermessleiste gefüllt ist.

### Bewertung des Hit-Circles

**Hit-Circles**

- Ein 300er, 100er oder 50er wird bei einem normalen Hit-Circle verliehen, abhängig von der Treffgenauigkeit.
- Ein Miss wird vergeben, wenn ein Hit-Circle zu früh oder überhaupt nicht getroffen wurde.
  - Wenn das Objekt sehr, sehr früh getroffen wird, wackelt es stattdessen. Dabei passiert technisch gesehen nichts, außer dass man visuell erkennen kann, dass es zu früh angetippt wurde.

**Hold-Circle**

- Die Bewertung des Hold-Circles hängt von der anfänglichen Berührung und der Haltezeit vor der Explosion ab.
  - 300 bei perfekter Ausführung.
  - 100 für einen weniger präzisen anfänglichen Treffer und das richtige Halten.
  - 50 dafür, dass er zumindest berührt wurde.
  - 30 für jede Explosion.
  - Der Multiplikator wird zurückgesetzt, wenn die Kreise nicht korrekt gehalten wurden. Ein Miss wird vergeben, wenn die Kreise überhaupt nicht gehalten wurden.

**Slider**

- **Die Bewertung von Slidern hängt von der Genauigkeit der anfänglichen Berührung ab**.
- Slider bestehen aus Sliderticks, die den Start, das Ende und die repeat points des Sliders einbeziehen.
  - Einen 300er, wenn man alle Sliderticks erreicht und einen genauen ersten Treffer hat.
  - Einen 100er, wenn mindestens die Hälfte des Sliders mit einem guten ersten Treffer getroffen wurde.
  - Einen 50er, wenn mindestens ein Slidertick oder der erste Treffer getroffen wurde.
- **Einen Slider viel zu früh zu tippen** wird keinen Miss erzeugen, aber **wird den Punktemultiplikator auf 0 zurücksetzen**.
- Ein Miss, wenn der Slider überhaupt nicht gehalten wurde.

**Spinner**

- Für einen Spinner werden 300er, 100er oder 50er vergeben, abhängig von der Anzahl der gemachten Spins verglichen mit der Länge des Spinners.
- Ein Miss, wenn die Spinnermessleiste, die auf beiden Seiten des Spinners zu sehen ist, nicht gefüllt wurde.

### Multiplikator

Das Folgende erhöht den Punktemultiplikator um jeweils einen Punkt:

- Treffer auf einem Hit-Circle.
- Der Start, das Ende und jeder Hold-Tick eines Hold-Circles.
- Der Start, das Ende und jeder Slidertick eines Sliders.
- Einen Spinner vervollständigen.

Das Folgende setzt den Punktemultiplikator auf null zurück:

- Einen Hit-Circle verfehlen.
- Den Hold-Circle loszulassen, bevor dieser explodiert ist.
- Die verbundenen Beats nicht gleichzeitig treffen. (Einen treffen und den anderen verfehlen)
- Einen Slider zu früh klicken.
- Den Sliderstart oder einen Slidertick verfehlen.
- Die Spinnermessleiste nicht vollständig füllen.

Das Folgende wird den Punktemultiplikator weder erhöhen noch zurücksetzen:

- Ein Sliderende verfehlen. (Es wird ein Good! oder ein 100/50 Treffer vergeben)
- Punktebonus eines Spinners

### Benotung

![](img/Os-Grade.jpg "Ergebnisbildschirm")

**Normale Noten**

- SS = 100% Genauigkeit
- S = Über 90% Genauigkeit
- A = Über 80% Genauigkeit
- B = Über 70% Genauigkeit
- C = Über 60% Genauigkeit
- D = Alles andere.

### Lebensanzeige

Die Lebensanzeige in osu!stream ist anders, da sie im Gegensatz zu osu! auf dem Spielmodus basiert.

Im **leichten Modus ist die Lebensleiste nicht vorhanden**.

![](img/Os-SUN.jpg "Beispiel eines Stream Up! von Normal aus")

Im **Streammodus** erhält der Spieler drei Lebensleisten und startet mit der zweiten zur Hälfte gefüllten Lebensleiste. Spieler bewegen sich zwischen diesen beiden Lebensleisten via den **Stream Up!** und **Stream Down!** Systemen, die aktiviert werden, wenn die Lebensleiste komplett gefüllt oder geleert wird. Nach einer Ankündigung wechselt das Spiel zum neuen "Stream" durch das Austauschen des Hintergrunds und einem nahtlosem Wechsel zu einem höheren oder niedrigeren Schwierigkeitsgrad der Beatmap sowie das Tauschen der Lebensleisten. Wenn ein Stream Down! erscheint, bekommt der Spieler temporäre Unbesiegbarkeit, während die Lebensleiste zu einem niedrigeren Schwierigkeitsgrad wechselt.

Im **Expertenmodus wird stattdessen eine volle Lebensleiste vergeben**.

Das Folgende füllt die Lebensleiste:

- Spinner und Hold-Circles vervollständigen.
- Ein osu!, gold good!, green good!, 300er, oder 100er treffen,
  - Bei Hit-Circles füllen bessere Bewertungen die Lebensleiste mehr. Der letzte Hit-Circle in einer farbigen Combo vergibt mehr Lebenspunkte.
  - Bei Slidern wird die Lebensleiste abhängig von den vervollständigten Teilen gefüllt, nachdem der Slider beendet wurde.

Das Folgende reduziert die Lebensleiste:

- Einen 50er erhalten.
- Ein Hit-Object oder einen Slider verfehlen.
- Nicht im Follow-Circle eines Sliders bleiben.
- Einen Hold-Circle nicht halten, bis er explodiert.
- Einen Spinner nicht drehen.
- Einen Spinner nicht mit einer "Clear" Nachricht vervollständigen.

Im Gegensatz zu anderen Versionen von osu! reduziert sich die Lebensleiste hier nicht von selbst.

## Fragen

### Warum ist (füge hier irgendeinen urheberrechtlich geschützten Song ein) nicht enthalten?

Wegen der Schwierigkeit, eine Lizenz für den oben genannten Song zu bekommen.

### Wie komme ich an mehr Beatmaps?

Gehe zu der "Store" Sektion im Spiel oder drücke den Button "Download more songs..." in der "Play" Sektion.

### Was ist die Titelmelodie von osu!stream?

[nekodex - osu!stream theme (1.48)](https://soundcloud.com/nekodex/osu-stream-theme).
Meistens im Hauptmenü und im Tutorial zu hören.

### Credits?

![](img/Os-Credit.jpg "Credits")

## Links

- [Offizielle Webseite](http://www.osustream.com) (nicht mehr aktuell)
- [Diskussionsforum (osu! Webseite)](https://osu.ppy.sh/community/forums/79)
- [GitHub Repository](https://github.com/ppy/osu-stream)
- [Blog-Beitrag](https://blog.ppy.sh/osu-stream-2020-release/)
