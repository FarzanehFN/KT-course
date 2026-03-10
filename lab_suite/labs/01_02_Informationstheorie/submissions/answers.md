# Fragebogen: Entropie-Analyse (entropy1.py)

Nach dem Ausführen von `entropy1.py` mit eigenem Text in `sampletext.txt`:

**Konsolenausgabe einfügen:** Nutze das Merge-Symbol in der Task-Card, um die Ausgabe aus `console_log.txt` hier einzufügen. Anschließend die Ausgabe **kommentieren**.

**1. Konsolenausgabe**

*(Wird per „Konsolenausgabe einfügen“ unten eingefügt. Danach bitte kommentieren.)*


-----File Contents:---------------------------------------------------
Dies ist ein kurzer Testtext für die Entropieanalyse.

Hier kommen verschiedene Buchstaben vor.
Number of characters: 94
Character Dictionary: {'D': 1, 'i': 7, 'e': 15, 's': 6, ' ': 11, 't': 6, 'n': 6, 'k': 2, 'u': 2, 'r': 7, 'z': 1, 'T': 1, 'x': 1, 'f': 1, 'ü': 1, 'd': 2, 'E': 1, 'o': 3, 'p': 1, 'a': 3, 'l': 1, 'y': 1, '.': 2, '\n': 1, 'H': 1, 'm': 2, 'v': 2, 'c': 2, 'h': 2, 'B': 1, 'b': 1}

-------Table of characters:----------------
 e     | cnt= 15    p=0.160   H=2.648 bit/char  H_av=0.423 bit/char
       | cnt= 11    p=0.117   H=3.095 bit/char  H_av=0.362 bit/char
 i     | cnt=  7    p=0.074   H=3.747 bit/char  H_av=0.279 bit/char
 r     | cnt=  7    p=0.074   H=3.747 bit/char  H_av=0.279 bit/char
 s     | cnt=  6    p=0.064   H=3.970 bit/char  H_av=0.253 bit/char
 t     | cnt=  6    p=0.064   H=3.970 bit/char  H_av=0.253 bit/char
 n     | cnt=  6    p=0.064   H=3.970 bit/char  H_av=0.253 bit/char
 o     | cnt=  3    p=0.032   H=4.970 bit/char  H_av=0.159 bit/char
 a     | cnt=  3    p=0.032   H=4.970 bit/char  H_av=0.159 bit/char
 k     | cnt=  2    p=0.021   H=5.555 bit/char  H_av=0.118 bit/char
 u     | cnt=  2    p=0.021   H=5.555 bit/char  H_av=0.118 bit/char
 d     | cnt=  2    p=0.021   H=5.555 bit/char  H_av=0.118 bit/char
 .     | cnt=  2    p=0.021   H=5.555 bit/char  H_av=0.118 bit/char
 m     | cnt=  2    p=0.021   H=5.555 bit/char  H_av=0.118 bit/char
 v     | cnt=  2    p=0.021   H=5.555 bit/char  H_av=0.118 bit/char
 c     | cnt=  2    p=0.021   H=5.555 bit/char  H_av=0.118 bit/char
 h     | cnt=  2    p=0.021   H=5.555 bit/char  H_av=0.118 bit/char
 D     | cnt=  1    p=0.011   H=6.555 bit/char  H_av=0.070 bit/char
 z     | cnt=  1    p=0.011   H=6.555 bit/char  H_av=0.070 bit/char
 T     | cnt=  1    p=0.011   H=6.555 bit/char  H_av=0.070 bit/char
 x     | cnt=  1    p=0.011   H=6.555 bit/char  H_av=0.070 bit/char
 f     | cnt=  1    p=0.011   H=6.555 bit/char  H_av=0.070 bit/char
 ü     | cnt=  1    p=0.011   H=6.555 bit/char  H_av=0.070 bit/char
 E     | cnt=  1    p=0.011   H=6.555 bit/char  H_av=0.070 bit/char
 p     | cnt=  1    p=0.011   H=6.555 bit/char  H_av=0.070 bit/char
 l     | cnt=  1    p=0.011   H=6.555 bit/char  H_av=0.070 bit/char
 y     | cnt=  1    p=0.011   H=6.555 bit/char  H_av=0.070 bit/char
 b'\n' | cnt=  1    p=0.011   H=6.555 bit/char  H_av=0.070 bit/char
 H     | cnt=  1    p=0.011   H=6.555 bit/char  H_av=0.070 bit/char
 B     | cnt=  1    p=0.011   H=6.555 bit/char  H_av=0.070 bit/char
 b     | cnt=  1    p=0.011   H=6.555 bit/char  H_av=0.070 bit/char
-------------------------------------------

Average Entropy H = 4.342 bit/char
Total Entropy of 94 characters H=408.13 bit = 52.00 byte

---

**2. Deine Kommentierung:**

- Was fällt dir bei der Entropie deines Textes auf?  
  *[z. B. Vergleich mit anderen Texten, Zeichenverteilung, Redundanz]*

 Die Entropie meines Textes beträgt etwa 4,34 bit pro Zeichen. Häufige Zeichen wie „e“ oder Leerzeichen kommen oft vor und haben deshalb weniger Informationsgehalt. Seltene Zeichen enthalten mehr Information. Eine ungleichmäßige Zeichenverteilung führt zu einer niedrigeren Entropie, weil der Text dadurch besser vorhersagbar ist. Bei einer gleichmäßigeren Verteilung der Zeichen wäre die Entropie höher.