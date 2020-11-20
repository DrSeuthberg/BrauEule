# BrauEule
Dies dient als Sammlung von Anleitungen in Wartund und Pflege rund um die [Brumas BrauEule III](https://www.brumas.com/brumas/)

## Austasch Touchscreen
### Vorweg 
Beim letzen Brauvorgang habe ich beim Starten der BrauEule gemerkt, dass der Touchscreen nicht mehr reagiert. Mir fiel schon vorher ein Riss durch den Screen auf, ich hoffte aber immer, es betrifft nur das Schutzglas. Nach Konktakt zum Hersteller beschloss ich erstmal die Reperatur selber zu versuchen und schraubte die BrauEule auf. Daraus ist diese kleine Anleitung entstanden.

### Öffnen der BrauEule
Vorher unbedingt den Strom abschalten, am besten den Stecker ziehen und sicherstellen, dass keine Restspannung vorhanden ist. Zum Öffnen der BrauEule müssen die Schrauben des Metallgehäuses mit einem Torx-Schraubendreher gelöst werden. Anschließend kann man das Gehäuse vorsichtig nach hinten wegklappen. Achtet hier darauf keine Kabel oder andere Bauteile zu beschädigen.

### Ausbau des Boards mit Touchscreen
Das Board ist direkt hinter dem Touchscreen im vorderen Teil der BrauEule zu finden. Es ist mit vier Schrauben am Gehäuse befestigt, diese können von innen gelöst werden. Passt beim Abschrauben auf, dass ihr nicht die Abstandshalter verliert und sammelt diese mit dem Schrauben in einer Schale oder ähnlichem.

![1-board](img/1-board.png "Das Board")

Bevor ihr das Board entnehmen könnt, müssen vier Stecker gelöst werden. Als erstes solltet ihr den zweipoligen Stecker (+5V, GND) zur Spannungsversorgung lösen - im Bild rechts unten. Anschließend könnt ihr einfach die beiden breiten Stecker abziehen. Der letzte Anschluss, vom Lautsprecher, ist verlötet. Diesen müsst ihr entweder entlöten (saubere Lösung), oder das Kabel mit etwas Spielraum kappen, um es später wieder verbinden zu können (nicht so schön). Jetzt könnt ihr das Board entnehmen.

Beim verwendeten Board handelt es sich um ein [STM32F7 des Herstellers ST](https://www.st.com/en/microcontrollers-microprocessors/stm32f7-series.html). 

### Trennen des Touchscreens
Der Touchscreen ist von Haus aus verbaut und leider mit drei bis vier Klebestreifen auf dem Board befestigt. Um diese zu lösen, kann man von der Seite mit einer scharfen Klinge die Klebestreifen durchtrennen. Achtet drauf, dass ihr nichts beschädigt oder zerkratzt. Es muss nur an 3 von 4 Seiten durchtrennt werden. An der Seite mit den Flachkabeln (im Bild oben) verlief bei mir kein Klebestreifen. Seid ihr euch sicher, dass ihr alle Streifen durchgeschnitten habt, könnt ihr den Touchscreen mit Vorsicht aber etwas Kraft nach vorne wegklappen.

![2-glue-cutting](img/2-glue-cutting.png "Lösen des Touchscreens")
