# Siedler von Catan: Deck Building
University of Applied Sciences Lucerne

Autoren: Nicola Hermann, Luca Kyburz

Siedler von Catan: Deck Building ist ein Deck Building Spiel, das stark vom klassischen Brettspiel Siedler von Catan inspiriert ist. Im Gegensatz zum Original geht es also nicht darum auf einem Spielbrett möglichst viele Siedlungen und Städte zu bauen, sondern sich ein Deck mit möglichst starken Karten zusammenzustellen, um so als erster die Siegesbedingungen zu erfüllen.

# Ziel des Spiels

# Spielmaterial
<!-- Anzahl Spieler: 2
Karten:
- Weide: 6x
- Getreide: 6x -->

## Kartenübersicht

### Resourcenkarten
Es gibt Insgesammt 5 verschiedene Ressourcenkarten. Diese werden nur für den Kauf von Aktionskarten verwendet und haben keine weiteren funktionen. Es können keine weiteren Ressourcenkarten im Verlauf des Spiels dazugekauft werden:
- **Erz** (*E*) <br>
<img src="images/cards/Erz.jpeg" alt="erz" width="200"/>
- **Lehm** (*L*) <br>
<img src="images/cards/Lehm.jpeg" alt="lehm" width="200"/>
- **Getreide** (*G*) <br>
<img src="images/cards/Getreide.jpeg" alt="getreide" width="200"/>
- **Holz** (*H*) <br>
<img src="images/cards/Holz.jpeg" alt="holz" width="200"/>
- **Weide** (*W*) <br>
<img src="images/cards/Weide.jpeg" alt="weide" width="200"/>

### Geländekarten
Geländekarten sind grösstenteils unnütze Karten, die das Deck verschlechtern. Es können keine weiteren Geländekarten im Verlauf des Spiels dazugekauft werden.Es gibt 2 Geländekarten.
- **Meer** - Nur nützlich in kombination mit einem Hafen <br>
<img src="images/cards/Meer.jpeg" alt="meer" width="200"/>
- **Wüste** - Muss auf der Hand sein, um einen Banditen zu kaufen <br>
<img src="images/cards/Wüste.jpeg" alt="wüste" width="200"/>

### Aktionskarten
Als Aktionskarten werden alle Karten bezeichnet, die man aus dem Vorrat kaufen kann. Sie haben alle spezielle Effekte und kosten Ressources um sie aus dem Vorrat zu erwerben.

---
- **Bandit** <br>
<img src="images/cards/Bandit.jpeg" alt="bandit" width="200"/><br>
        **Kosten**: 2x Weide, 1x Getreide<br> 
        **Kurzbeschrieb**: +1 Karte, Klaue eine Handkarte des Gegners und lege diese auf deinen Ablagestapel.<br>
        **Beschreibung**: Ziehe eine Karte von deinem Nachziehstapel. Bitte deinen Gegner seine Handkarten aufzufächern. Ziehe nun eine zufällige Handkarte deines Gegners. Schaue dir die Karte an und entscheide, ob du diese auf Deinen Ablagestapel legen möchtest oder diese deinem Gegner zurück geben willst.

---
- **Ritter (Defensiv)** <br>
<img src="images/cards/Ritter(Defensiv).jpeg" alt="ritter_def" width="200"/><br>
        **Kosten**: 1x Weide, 1x Getreide, 1x Holz<br> 
        **Kurzbeschrieb**: +1 Karte, Reflektiere einen Angriff deines Gegners<br>
        **Beschreibung**: Wenn dein Gegner einen Angriff (Ritter (Offensiv) oder Bandit) ausspielt kannst du diese Karte vorzeigen. Ziehe dann eine Karte von deinem Nachziehstapel und führe den reflektierten Angriff auf deinen Gegner aus. Falls dieser auch einen Ritter (Defensiv) vorzeigt, hat der Angriff auf keinen Spieler einen Einfluss. Ein Ritter (Defensiv) kann nur einen einzelnen Angriff abblocken. Falls der Ritter (Defensiv) keinen Angriff abgeblockt hat, kann dieser benutzt werden um eine Karte vom Nachziehstapel zu ziehen.

---

- **Ritter (Offensiv)** <br>
<img src="images/cards/Ritter(Offensiv).jpeg" alt="ritter_off" width="200"/><br>
        **Kosten**: 1x Weide, 1x Getreide, 1x Erz<br> 
        **Kurzbeschrieb**: +1 Karte, Dein Gegner muss 2 beliebige Karten ablegen.<br>
        **Beschreibung**: Ziehe eine Karte von deinem Nachziehstapel. Dein Gegner muss 2 Karten, die dein Gegner selbst aussuchen kann, auf seinen Ablagestapel ablegen. Es können mehrere Ritter (Offensiv) in einem Zug ausgespielt werden.

---

- **Hafen** <br>
<img src="images/cards/Hafen.jpeg" alt="hafen" width="200"/><br>
        **Kosten**: 2x Lehm, 1x Holz<br> 
        **Kurzbeschrieb**: +1 Karte, für jedes Meer: +1 Karte<br>
        **Beschreibung**: Zeige alle deine Meere und Str vor. Falls du eine oder mehrere Strassen besizt, zählen diese als insgesammt 1 Meer (Siehe Strasse). Ziehe nun 1 + Anzahl Meere Karten von deinem Nachziehstapel. Beispiele: <br>
        1) Hafen ohne Strassen oder Meere -> +1 Karte <br>
        2) Hafen ohne Strassen mit 2x Meere -> +3 Karten <br>
        3) Hafen mit 1x Strasse und 2x Meere -> +4 Karten <br>
        4) Haden mit 3x Strassen und 2x Meere -> +4 Karten <br>
        Falls mehrere Häfen in einer Runde ausgespielt werden können die Meere mehrmals gezählt werden.

---

- **Strasse** <br>
<img src="images/cards/Strasse.jpeg" alt="strasse" width="200"/><br>
        **Kosten**: 1x Lehm, 1x Holz<br> 
        **Kurzbeschrieb**: Gibt einen besseren Effekt, je mehr Strassen man gleichzeitig auspielt<br>
        **Beschreibung**: <br>
        1x Strasse -> 1 Meer <br>
        2x Strassen -> 1 Meer, 1 Ressource nach Wahl<br>
        3x Strassen -> 1 Meer, 3 Ressourcen nach Wahl<br>
        Für jede weitere Strasse -> +2 Ressourcen nach Wahl

---

- **Siedlung** <br>
<img src="images/cards/Siedlung.jpeg" alt="siedlung" width="200"/><br>
        **Kosten**: 1x Erz, 1x Weide, 1x Getreide, 1x Holz<br> 
        **Kurzbeschrieb**: 2 beliebige Ressourcen<br>
        **Beschreibung**: Zählt als 2 Ressourcen nach Wahl. Diese könne 2 unterschiedliche Resourcen sein. Die Siedlung wird benötigt um eine Stadt zu erwerben. Die Aktion der Siedlung kann nicht verwendet werden, um eine Stadt zu erwerben (Die Siedlung muss noch unausgespielt auf der Hand sein. Die Siedlung wird danach zurück auf den Vorrat gelegt).


---

- **Stadt** <br>
<img src="images/cards/Stadt.jpeg" alt="stadt" width="200"/><br>
        **Kosten**: 2x Erz, 2x Getreide, 1x Lehm, 1x Siedlung<br> 
        **Kurzbeschrieb**: 2 beliebige Ressourcen<br>
        **Beschreibung**: Zählt als 3 Ressourcen nach Wahl. Diese könne 3 unterschiedliche Resourcen sein. Die Stadt wird benötigt um das Spiel zu gewinnen. Die Aktion der Siedlung kann nicht verwendet werden, um eine Stadt zu erwerben (Die Siedlung muss noch unausgespielt auf der Hand sein. Die Siedlung wird danach zurück auf den Vorrat gelegt).

---


# Vorbereitung


# Spielablauf

## Spielbeginn

## 

## Spielende

# Frequently Asked Questions
[FAQ](FAQ.md)