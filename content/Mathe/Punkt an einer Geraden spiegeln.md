1. Man sucht den **Lotfußpunkt** (F) (der Punkt auf (g), der am nächsten zu (A) liegt)
2. (F) ist die **Mitte** zwischen (A) und seinem Spiegelpunkt \(B\)
3. Die Gerade \(g\) ist die **Mittelsenkrechte** der Strecke \(AB\)

$B = A + 2 \cdot \overrightarrow{AF} = 2F - A$

1. Lotfußpunktverfahren (Standard, immer anwendbar)
2. Formelverfahren (schnell bei Koordinatenform der Geraden)
3. Abstandsverfahren (intuitiv, aber rechenintensiv)

 **1. Lotfußpunktverfahren**

**A. Gerade in Parameterform gegeben**
```
Gegeben: g: X = Q + t·v (Q Aufpunkt, v Richtungsvektor)
Punkt A soll gespiegelt werden
```

**Schritte:**
```
1. Lotfußpunkt F parametrisieren:
   F = Q + t₀·v   (t₀ unbekannt)
   
2. Vektor AF = F - A berechnen
   
3. Orthogonalitätsbedingung:
   AF · v = 0   (Lot steht senkrecht auf Gerade)
   
4. Nach t₀ auflösen:
   (F - A)·v = 0
   (Q + t₀·v - A)·v = 0
   (Q - A)·v + t₀(v·v) = 0
   t₀ = -[(Q - A)·v] / (v·v)
   
5. t₀ in F einsetzen → Koordinaten von F
   
6. Spiegelpunkt B berechnen:
   B = 2F - A
```

**B. Gerade in Koordinatenform gegeben**
\(g: ax + by = c\) oder \(ax + by + c = 0\)

**Umwandlung nötig:**
```
1. Richtungsvektor v aus Normalenvektor n=(a,b) bestimmen:
   v = (-b, a) oder (b, -a) (beide senkrecht zu n)
   
2. Aufpunkt Q finden: Setze x=0 → y=c/b (falls b≠0)
   oder y=0 → x=c/a
   
3. Jetzt: Gerade in Parameterform, weiter wie oben
```

**2. Formelverfahren**

Nur anwendbar, wenn die Gerade in der Form \(ax + by + c = 0\) gegeben ist.

Für \(A(x_A|y_A)\) und Gerade \(g: ax + by + c = 0\):

$$d = \frac{a x_A + b y_A + c}{a^2 + b^2}$$

---
#### **Herleitung der Formel**

##### **1. Lotfußpunkt F bestimmen**

Der Lotfußpunkt FF liegt auf der Geraden gg **und** auf der Geraden durch AA in Richtung des Normalenvektors n⃗n.

Sei F=A+λn⃗F=A+λn für ein λ∈Rλ∈R.  
Da FF auf gg liegt, muss gelten:

a⋅(xA+λa)+b⋅(yA+λb)+c=0a⋅(xA​+λa)+b⋅(yA​+λb)+c=0

Das lösen wir auf:

axA+λa2+byA+λb2+c=0axA​+λa2+byA​+λb2+c=0(axA+byA+c)+λ(a2+b2)=0(axA​+byA​+c)+λ(a2+b2)=0λ(a2+b2)=−(axA+byA+c)λ(a2+b2)=−(axA​+byA​+c)λ=−axA+byA+ca2+b2λ=−a2+b2axA​+byA​+c​

##### **2. Die Größe d definieren**

Jetzt setzen wir **per Definition**:

d:=axA+byA+ca2+b2d:=a2+b2axA​+byA​+c​

Dann ist λ=−dλ=−d.

Warum diese Definition? Weil:

- Der **wirkliche Abstand** (positiv) von AA zu gg ist ∣d∣⋅∥n⃗∥=∣d∣⋅a2+b2∣d∣⋅∥n∥=∣d∣⋅a2+b2​
    
- dd selbst ist ein **vorzeichenbehafteter Abstand**, der die Richtung angibt
    

##### **3. Vom Lotfußpunkt zum Spiegelpunkt**

Der Lotfußpunkt ist:

F=A+λn⃗=A−d⋅n⃗F=A+λn=A−d⋅n

Da FF der Mittelpunkt zwischen AA und BB ist:

F=A+B2F=2A+B​A−dn⃗=A+B2A−dn=2A+B​2A−2dn⃗=A+B2A−2dn=A+BB=A−2dn⃗B=A−2dn

In Koordinaten:

B=(xAyA)−2d(ab)=(xA−2adyA−2bd)B=(xA​yA​​)−2d(ab​)=(xA​−2adyA​−2bd​)

---

##### **Warum heißt es "vorzeichenbehafteter Abstand"?**

Das ist das Wichtigste zum Verständnis!

##### **Die Signifikanz des Vorzeichens von d**

1. **Gerade in Hessescher Normalform:**  
    Wenn wir gg normieren: aa2+b2x+ba2+b2y+ca2+b2=0a2+b2​a​x+a2+b2​b​y+a2+b2​c​=0  
    Dann ist der **Abstand** von AA zu gg:
    
    Abstand=∣axA+byA+ca2+b2∣Abstand=​a2+b2​axA​+byA​+c​​
    
    Das ist ∣d∣⋅a2+b2∣d∣⋅a2+b2​.
    
2. **Das Vorzeichen von d sagt:**
    
    - d>0d>0: Punkt AA liegt auf der Seite, **in die der Normalenvektor n⃗n zeigt**
        
    - d<0d<0: Punkt AA liegt auf der **entgegengesetzten Seite**
        
    - d=0d=0: Punkt AA liegt **auf** der Geraden
        

##### **Beispiel zur Veranschaulichung**

Gerade g:2x+3y−6=0g:2x+3y−6=0  
Normalenvektor n⃗=(2,3)n=(2,3) zeigt "nach oben-rechts"

Für A(4,1)A(4,1):

d=2⋅4+3⋅1−622+32=8+3−613=513>0d=22+322⋅4+3⋅1−6​=138+3−6​=135​>0

→ AA liegt auf der Seite, in die n⃗n zeigt.

Für A(0,0)A(0,0):

d=0+0−613=−613<0d=130+0−6​=−136​<0

→ AA liegt auf der entgegengesetzten Seite.
$$B = \begin{pmatrix} x_A - 2a \cdot d \\ y_A - 2b \cdot d \end{pmatrix}$$

1. \(d\) ist der **vorzeichenbehaftete Abstand** von A zur Geraden
2. Der Verschiebevektor von A zum Spiegelpunkt ist $-2d \cdot n$ (doppelter Abstand in Normalenrichtung)
3. \(n = (a,b)\) ist Normalenvektor

Beispiel:
\(g: 2x + 3y - 6 = 0\), \(A(4|1)\)
1. a=2, b=3, c=-6
2. $d = \frac{2·4 + 3·1 - 6}{2²+3²} = \frac{8+3-6}{13} = \frac{5}{13}$
3. $B = \begin{pmatrix}4 - 2·2·\frac{5}{13} \\ 1 - 2·3·\frac{5}{13}\end{pmatrix} = \begin{pmatrix}4 - \frac{20}{13} \\ 1 - \frac{30}{13}\end{pmatrix} = \begin{pmatrix}\frac{32}{13} \\ -\frac{17}{13}\end{pmatrix}$

---

#### **3. Abstandsverfahren (für Verständnis)**

**Idee:** Man nutzt aus, dass der Abstand von A zu g gleich dem Abstand von B zu g ist.

1. Gerade g in Koordinatenform: ax+by+c=0
2. Abstand von A zu g: $d_A = |ax_A+by_A+c|/√(a²+b²)$
3. Gerade h durch A, parallel zu g:
   h: ax+by = ax_A+by_A
4. Zwei Punkte auf h im Abstand d_A von A finden
   (kompliziert, daher selten praktisch)
Diese Methode ist **nicht prüfungstauglich** – zu umständlich!
