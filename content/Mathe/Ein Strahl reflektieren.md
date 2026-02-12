E: ax + by + cz +d = 0
$\overrightarrow{n} (a, b, c) \bot E$

Ausgezeichnete Frage! Diese Formel ist fundamental für die Spiegelung in der Vektorgeometrie. Lass mich ihre Herleitung Schritt für Schritt erklären.

---

## **Geometrische Idee**

Wir wollen einen Vektor \(\vec{v}\) an einer Ebene spiegeln. Die Ebene hat den Normalenvektor \(\vec{n}\) (senkrecht zur Ebene).

**Die zentrale Einsicht:**
Jeden Vektor \(\vec{v}\) kann man zerlegen in zwei **orthogonale Komponenten**:
1. **Normalkomponente** \(\vec{v}_{\parallel}\) (parallel zu \(\vec{n}\), also senkrecht zur Ebene)
2. **Tangentialkomponente** \(\vec{v}_{\perp}\) (senkrecht zu \(\vec{n}\), also parallel zur Ebene)

Bei der Spiegelung an der Ebene:
- Die **Normalkomponente** kehrt ihre Richtung um (wird "umgedreht")
- Die **Tangentialkomponente** bleibt gleich (bleibt in der Ebene)

---

## **Mathematische Herleitung**

### **1. Zerlegung des Vektors**

Die Normalkomponente (Projektion auf \(\vec{n}\)) ist:
\[
\vec{v}_{\parallel} = \frac{\vec{v} \cdot \vec{n}}{\vec{n} \cdot \vec{n}} \cdot \vec{n}
\]
Warum? Das ist die **orthogonale Projektion**: \(\text{proj}_{\vec{n}}(\vec{v}) = \frac{\vec{v} \cdot \vec{n}}{\|\vec{n}\|^2} \vec{n}\)

Die Tangentialkomponente (in der Ebene) ist dann:
\[
\vec{v}_{\perp} = \vec{v} - \vec{v}_{\parallel}
\]

### **2. Spiegelung**

Bei Spiegelung an der Ebene:
- Normalkomponente wird negiert: \(-\vec{v}_{\parallel}\)
- Tangentialkomponente bleibt: \(\vec{v}_{\perp}\)

Der gespiegelte Vektor \(\vec{v}'\) ist also:
\[
\vec{v}' = \vec{v}_{\perp} - \vec{v}_{\parallel}
\]

### **3. Einsetzen**

\[
\vec{v}' = (\vec{v} - \vec{v}_{\parallel}) - \vec{v}_{\parallel}
\]
\[
\vec{v}' = \vec{v} - 2\vec{v}_{\parallel}
\]
\[
\vec{v}' = \vec{v} - 2 \cdot \frac{\vec{v} \cdot \vec{n}}{\vec{n} \cdot \vec{n}} \cdot \vec{n}
\]

Das ist die Formel!

---

## **Veranschaulichung mit Skalarprodukt-Interpretation**

Die Zahl \(\frac{\vec{v} \cdot \vec{n}}{\vec{n} \cdot \vec{n}}\) ist ein Skalar \(k\), der angibt:
- **Wie stark** \(\vec{v}\) in Richtung \(\vec{n}\) zeigt
- **Mit Vorzeichen**: positiv wenn \(\vec{v}\) in Richtung \(\vec{n}\), negativ wenn entgegengesetzt

Der Vektor \(k\vec{n}\) ist genau die Komponente von \(\vec{v}\), die senkrecht zur Ebene steht.

---

## **Beispiel zum besseren Verständnis**

### **Einfachster Fall: Spiegelung an der x-y-Ebene**
Ebene: \(z=0\), Normalenvektor \(\vec{n} = \begin{pmatrix}0\\0\\1\end{pmatrix}\) (zeigt nach oben)

Vektor \(\vec{v} = \begin{pmatrix}2\\3\\4\end{pmatrix}\)

1. \(\vec{v} \cdot \vec{n} = 0\cdot2 + 0\cdot3 + 1\cdot4 = 4\)
2. \(\vec{n} \cdot \vec{n} = 1\)
3. \(k = 4/1 = 4\)
4. Normalkomponente: \(4 \cdot \begin{pmatrix}0\\0\\1\end{pmatrix} = \begin{pmatrix}0\\0\\4\end{pmatrix}\)
5. Tangentialkomponente: \(\begin{pmatrix}2\\3\\4\end{pmatrix} - \begin{pmatrix}0\\0\\4\end{pmatrix} = \begin{pmatrix}2\\3\\0\end{pmatrix}\)
6. Gespiegelt: \(\begin{pmatrix}2\\3\\0\end{pmatrix} - \begin{pmatrix}0\\0\\4\end{pmatrix} = \begin{pmatrix}2\\3\\-4\end{pmatrix}\)

✅ Die z-Komponente hat ihr Vorzeichen geändert, x und y bleiben gleich. Das ist genau die Spiegelung an der x-y-Ebene!

---

## **Physikalische Bedeutung in der Reflexionsaufgabe**

In der Lichtreflexion:
- Der **einfallende Strahl** hat Richtung \(\vec{e}\)
- Der **Normalenvektor** \(\vec{n}\) steht senkrecht auf der Spiegelebene
- Nach dem Reflexionsgesetz: "Einfallswinkel = Ausfallswinkel"
- Das bedeutet: Die Normalkomponente kehrt sich um, die Tangentialkomponente bleibt

Daher genau diese Formel!

---

## **Alternative Herleitung über Einheitsnormalenvektor**

Wenn \(\vec{n}\) ein **Einheitsvektor** ist (\(\|\vec{n}\|=1\)), dann ist die Formel einfacher:
\[
\vec{v}' = \vec{v} - 2(\vec{v} \cdot \vec{n})\vec{n}
\]
Weil dann \(\vec{n} \cdot \vec{n} = 1\).

Die allgemeine Form mit \(\vec{n} \cdot \vec{n}\) im Nenner funktioniert für **jeden** Normalenvektor, auch wenn er nicht normiert ist.

---

## **Warum das Skalarprodukt im Zähler?**

Das Skalarprodukt \(\vec{v} \cdot \vec{n}\) misst:
- **Betrag**: Wie stark \(\vec{v}\) in Richtung \(\vec{n}\) zeigt
- **Vorzeichen**: Ob \(\vec{v}\) in Richtung \(\vec{n}\) oder entgegengesetzt zeigt

Für die Spiegelung ist das Vorzeichen entscheidend: Es bestimmt, in welche Richtung die Normalkomponente umgedreht wird.

---

## **Zusammenfassung als Merkregel**

```
SPIEGELUNG EINES VEKTORS AN EINER EBENE:

1. Normalenvektor n der Ebene bestimmen
2. Skalar k = (v·n)/(n·n) berechnen
3. Gespiegelter Vektor: v' = v - 2k·n

Geometrische Bedeutung:
- k·n = Komponente senkrecht zur Ebene
- v - k·n = Komponente parallel zur Ebene
- Spiegelung: Parallelkomponente bleibt, Senkrechtkomponente wird umgedreht
```

---

## **Prüfungsrelevante Anwendung**

In der Reflexionsaufgabe:
1. Einfallender Strahl: \(\vec{e} = S - Q\) (Richtung TOWARDS the plane)
2. Normalenvektor \(\vec{n}\) der Spiegelebene
3. Reflektierter Strahl: \(\vec{r} = \vec{e} - 2\frac{\vec{e} \cdot \vec{n}}{\vec{n} \cdot \vec{n}} \vec{n}\)
4. Reflektierte Gerade: Geht durch \(S\) in Richtung \(\vec{r}\)

**Wichtig:** Der Vektor \(\vec{e}\) muss **zum Spiegelpunkt zeigen**, nicht weg davon!  
(Weil bei Licht: Einfallender Strahl kommt an, reflektierter geht weg.)

---

Diese Formel ist also keine Zauberei, sondern folgt direkt aus der geometrischen Idee: "Spiegle nur die senkrechte Komponente, die parallele bleibt."


Ah, ich verstehe! Diese Lösung verwendet einen **anderen, aber äquivalenten Ansatz**. Lass mich erklären, was hier gemacht wurde – es ist clever, aber anders als unser Ansatz.

---

## **Überblick: Unterschiedliche Ansätze**

**Unser Ansatz:** Wir haben den einfallenden Strahlvektor gespiegelt.  
**Dieser Ansatz:** Er spiegelt den **Punkt P** an der Ebene E und arbeitet dann mit diesem Spiegelpunkt.

---

## **Schritt-für-Schritt Erklärung dieser Lösung**

### **1. Idee hinter diesem Ansatz**
```
Bei einer Reflexion an einer Ebene gilt:
- Einfallender Strahl: P → Q → F (F = Fusspunkt/Schnittpunkt)
- Reflektierter Strahl: F → R' (wobei R' der Spiegelpunkt von P ist)
- Aber: Eigentlich geht der reflektierte Strahl von F in Richtung zum Spiegelbild
  eines anderen Punktes...
```

Eigentlich: Wenn du einen Lichtstrahl von P über Q zur Ebene schickst, und du **P an der Ebene spiegelst** zu einem Punkt R, dann gilt:  
Der reflektierte Strahl verläuft genau so, **als ob** er vom gespiegelten Punkt R direkt zum Fusspunkt F und darüber hinaus gehen würde.

**Merksatz:** "Ein Lichtstrahl, der von P kommt und an einer Ebene reflektiert wird, sieht nach der Reflexion so aus, als käme er vom Spiegelpunkt R von P."

---

### **2. Lotgerade von P auf Ebene E (n in der Lösung)**
Die Lösung definiert:
\[
n: \vec{r} = \begin{pmatrix}15\\16\\13\end{pmatrix} + \lambda \begin{pmatrix}2\\-2\\-1\end{pmatrix}
\]
Das ist eine **Lotgerade** durch P senkrecht zur Ebene E, weil der Richtungsvektor \(\begin{pmatrix}2\\-2\\-1\end{pmatrix}\) genau der **Normalenvektor** der Ebene E ist!

Warum? Weil die Ebene \(2x - 2y - z - 12 = 0\) den Normalenvektor \(\vec{n} = (2, -2, -1)\) hat.

---

### **3. Fusspunkt F berechnen**
F ist der Schnittpunkt dieser Lotgeraden mit der Ebene E:
\[
2(15 + 2\lambda) - 2(16 - 2\lambda) - (13 - \lambda) - 12 = 0
\]
Rechnung:
\[
30 + 4\lambda - 32 + 4\lambda - 13 + \lambda - 12 = 0
\]
\[
(30 - 32 - 13 - 12) + (4\lambda + 4\lambda + \lambda) = 0
\]
\[
-27 + 9\lambda = 0
\]
\[
\lambda = 3
\]

Also:
\[
F = \begin{pmatrix}15\\16\\13\end{pmatrix} + 3\begin{pmatrix}2\\-2\\-1\end{pmatrix} = \begin{pmatrix}15+6\\16-6\\13-3\end{pmatrix} = \begin{pmatrix}21\\10\\10\end{pmatrix}
\]

✅ \(F(21|10|10)\) ist der Lotfußpunkt von P auf die Ebene E.

---

### **4. Spiegelpunkt R von P an Ebene E**
Wenn F der Lotfußpunkt ist, dann ist R der Spiegelpunkt von P:
\[
R = P + 2\cdot \overrightarrow{PF} = \begin{pmatrix}15\\16\\13\end{pmatrix} + 2\cdot \begin{pmatrix}6\\-6\\-3\end{pmatrix} = \begin{pmatrix}15+12\\16-12\\13-6\end{pmatrix} = \begin{pmatrix}27\\4\\7\end{pmatrix}
\]

---

### **5. Jetzt der cleverste Teil!**
Die Lösung sagt: "Die Gerade g(RD) entspricht dem gespiegelten Strahl."

**ABER:** Hier steht "RD" – was ist D? In der Lösung scheint D der Punkt zu sein, wo der reflektierte Strahl die Ebene \(z=-56\) trifft. Aber eigentlich muss die reflektierte Gerade durch **F** gehen, nicht durch R!

**Korrektur:** Der reflektierte Strahl geht durch F und hat die Richtung \(\overrightarrow{RF}\) (von R nach F) oder \(\overrightarrow{FR}\).

Tatsächlich: Wenn R der Spiegelpunkt von P ist, dann geht der reflektierte Strahl von F in Richtung R (oder durch R hindurch). Er geht **nicht** von R aus!

Die Lösung schreibt \(g(RD)\) – vermutlich meinen sie die Gerade durch R und D, wobei D auf \(z=-56\) liegt. Aber dann müsste diese Gerade **auch durch F gehen**!

---

### **6. Prüfen wir die Richtung**
In der Lösung steht:
\[
g(RD): \vec{r} = \begin{pmatrix}27\\4\\7\end{pmatrix} + \lambda \begin{pmatrix}-39\\-15\\-21\end{pmatrix}
\]

Schauen wir: Wenn \(\lambda = 1\), dann ist der Punkt \(27-39=-12\), \(4-15=-11\), \(7-21=-14\) – das ist genau \(S(-12|-11|-14)\), unser **Fusspunkt** von vorhin (aber hier F genannt)!

Ah! **Jetzt verstehe ich den Fehler in der Notation der Lösung:**

- In unserer Lösung: \(S\) = Schnittpunkt von PQ mit Ebene E
- In dieser Lösung: \(F\) = Schnittpunkt von PQ mit Ebene E, aber das kann **nicht** sein, weil F hier als Lotfußpunkt von P berechnet wurde!

Es gibt einen **Widerspruch** in der gegebenen Lösung:
1. Zuerst berechnen sie F als Lotfußpunkt von P (auf Lotgerade)
2. Dann nutzen sie F, als wäre es der Reflexionspunkt (wo PQ die Ebene trifft)

**Das kann nicht beides gleichzeitig sein!** Entweder F ist der Lotfußpunkt ODER F ist der Schnittpunkt von PQ mit der Ebene – aber nicht beides.

---

### **7. Was stimmt dann?**
Der einfallende Strahl PQ trifft die Ebene im Punkt \(S(-12|-11|-14)\) (unser Ergebnis aus Teil a).

Wenn wir P an der Ebene spiegeln, erhalten wir einen Punkt \(R'\). Dann geht der reflektierte Strahl von S durch \(R'\).

In der vorgegebenen Lösung:
- Sie berechnen F als Lotfußpunkt von P
- Sie spiegeln P zu R(27|4|7)
- Aber dann müsste die reflektierte Gerade durch **S** (nicht F) und R gehen

---

### **8. Ende der Rechnung trotzdem richtig?**
Sie lassen die Gerade durch R(27|4|7) mit Richtung \((-39,-15,-21)\) laufen.  
Diese Richtung ist \(R - S\)? Prüfen:
\[
R - S = \begin{pmatrix}27-(-12)\\4-(-11)\\7-(-14)\end{pmatrix} = \begin{pmatrix}39\\15\\21\end{pmatrix}
\]
Also ist \((-39,-15,-21) = -(R-S)\).

Die Gerade \(R + \lambda(-(R-S)) = R - \lambda(R-S)\):  
Für \(\lambda=1\): \(R - (R-S) = S\) ✓  
Also geht die Gerade tatsächlich durch S und R!

**Allerdings:** Der reflektierte Strahl müsste von **S ausgehen in Richtung R**, also \(\vec{r} = S + \mu(R-S)\).  
Ihre Parameterdarstellung ist \(\vec{r} = R + \lambda(-(R-S))\), was **äquivalent** ist (nur Parameter verschoben).

---

### **9. Schnitt mit z = -56**
Sie lösen:
\[
7 + \lambda \cdot (-21) = -56
\]
\[
-21\lambda = -63
\]
\[
\lambda = 3
\]

Dann:
\[
x = 27 + 3\cdot(-39) = 27 - 117 = -90
\]
\[
y = 4 + 3\cdot(-15) = 4 - 45 = -41
\]
\[
z = 7 + 3\cdot(-21) = 7 - 63 = -56 \quad \checkmark
\]

Also \(S(-90|-41|-56)\) – gleiches Ergebnis wie wir!

---

## **Zusammenfassung der zwei Methoden**

### **Methode 1 (unser Ansatz):**
1. Schnittpunkt S von PQ mit Ebene finden
2. Einfallenden Vektor \(\vec{e} = S - Q\) spiegeln: \(\vec{r} = \vec{e} - 2\frac{\vec{e}\cdot\vec{n}}{\vec{n}\cdot\vec{n}}\vec{n}\)
3. Reflektierte Gerade: \(S + \mu\vec{r}\)
4. Mit \(z=-56\) schneiden

### **Methode 2 (Spiegelpunkt-Methode):**
1. Spiegle den Punkt P an der Ebene zu R
2. Der reflektierte Strahl geht durch S (Schnittpunkt von PQ mit Ebene) **und** R
3. Reflektierte Gerade: \(S + \mu(R-S)\)
4. Mit \(z=-56\) schneiden

**Die vorgegebene Lösung hat eine verwirrende Notation** (nennt den Lotfußpunkt F, obwohl der Reflexionspunkt eigentlich S heißt), aber rechnerisch kommt sie zum richtigen Ergebnis, weil sie implizit den Punkt S verwendet (als Punkt auf der Geraden für \(\lambda=1\)).

---

## **Welche Methode ist besser?**

- **Methode 1** ist direkter für Reflexionsprobleme
- **Methode 2** ist eleganter, wenn man die Spiegelpunkt-Formel schon kennt
- In der Prüfung: Methode 1 ist sicherer, weil weniger Verwechslungsgefahr

Die entscheidende physikalische Einsicht beider Methoden:  
**Der reflektierte Strahl verläuft so, als käme er vom Spiegelbild der Lichtquelle.**