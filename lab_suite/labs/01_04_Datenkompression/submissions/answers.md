# Fragebogen: Wort-Entropie (word_dictionary.py)

Nach dem Ausführen von `word_dictionary.py` mit eigenem Text in `sampletext.txt`:

**Konsolenausgabe einfügen:** Nutze das Merge-Symbol in der Task-Card, um die Ausgabe aus `console_log.txt` hier einzufügen. Anschließend die Ausgabe **kommentieren**.

---

**1. Konsolenausgabe**

*(Wird per „Konsolenausgabe einfügen“ unten eingefügt. Danach bitte kommentieren.)*

---

**2. Deine Kommentierung**

- Wie unterscheidet sich die Wort-Entropie von der Zeichen-Entropie (entropy1.py)?  
 Die Zeichen-Entropie betrachtet einzelne Buchstaben, während die Wort-Entropie ganze Wörter analysiert. Dadurch wird die Struktur des Textes besser berücksichtigt, da Wörter unterschiedliche Häufigkeiten haben.

- Was sagt die Entropie in Byte im Vergleich zur tatsächlichen Dateigröße aus?  
  Die Entropie in Byte zeigt die theoretisch minimale Größe, die der Text nach optimaler Kompression haben könnte. Die tatsächliche Dateigröße ist meist größer, weil Dateien zusätzliche Informationen wie Format oder Kodierung enthalten.
---

## Konsolenausgabe

```
Analyze the file:  /Users/fn/Git/KT-course/lab_suite/labs/01_04_Datenkompression/sampletext.txt
Total number of words:     13
Number of different words: 13

-------Table of words:-----------------------------------------
                           Dies | cnt=  1    p=0.077   H=3.700 bit/word   H_av=0.285 bit/word
                            ist | cnt=  1    p=0.077   H=3.700 bit/word   H_av=0.285 bit/word
                            ein | cnt=  1    p=0.077   H=3.700 bit/word   H_av=0.285 bit/word
                         kurzer | cnt=  1    p=0.077   H=3.700 bit/word   H_av=0.285 bit/word
                       Testtext | cnt=  1    p=0.077   H=3.700 bit/word   H_av=0.285 bit/word
                            für | cnt=  1    p=0.077   H=3.700 bit/word   H_av=0.285 bit/word
                            die | cnt=  1    p=0.077   H=3.700 bit/word   H_av=0.285 bit/word
                Entropieanalyse | cnt=  1    p=0.077   H=3.700 bit/word   H_av=0.285 bit/word
                           Hier | cnt=  1    p=0.077   H=3.700 bit/word   H_av=0.285 bit/word
                         kommen | cnt=  1    p=0.077   H=3.700 bit/word   H_av=0.285 bit/word
                   verschiedene | cnt=  1    p=0.077   H=3.700 bit/word   H_av=0.285 bit/word
                     Buchstaben | cnt=  1    p=0.077   H=3.700 bit/word   H_av=0.285 bit/word
                            vor | cnt=  1    p=0.077   H=3.700 bit/word   H_av=0.285 bit/word
-----------------------------------------------------------------

Average Entropy H = 3.700 bit/word
Total Entropy of 13 words H=48.106 bit (7 bytes)
Size of text file: 95 bytes
```
