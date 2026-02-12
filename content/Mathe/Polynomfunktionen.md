$f(x) = a_n x^n + a_{n-1}x^{n-1} + \dots + a_1 x + a_0$  

- Definitionsbereich:  
    \mathbb{R}  
- Stetig und differenzierbar auf ganz (\mathbb{R})
- Keine Asymptoten
- Verhalten im Unendlichen hängt **nur** von:
    - Grad (n)
    - Leitkoeffizient (a_n)

Endverhalten

**Gerader Grad**
- (a_n > 0):  
    beide Enden → (+\infty)
- (a_n < 0):  
    beide Enden → (-\infty)

**Ungerader Grad**
- (a_n > 0):  
    links ↓, rechts ↑
- (a_n < 0):  
    links ↑, rechts ↓
    
**Nullstellen**  
f(x_0)=0  
**Zusammenhang Faktor ↔ Nullstelle**
$f(x) = (x-x_0)^k \cdot g(x)$ 
- (k=1): einfache Nullstelle → **Graph schneidet**
- (k) gerade: → **Graph berührt**
- (k) ungerade (>1): → schneidet mit Abflachung

**Ableitungen**
**Ableitungsregel**  
$(x^n)' = n x^{n-1}$
- (f'(x)=0): Extremstellen (Kandidaten)
- (f''(x)=0): Wendestellen (Kandidaten)

- doppelte Nullstelle → auch Nullstelle der Ableitung
- Wendepunkt ↔ Krümmungswechsel

**Extremstellen**
1. (f'(x)=0) lösen
2. Klassifizieren mit:
    - Vorzeichenwechsel von (f')
    - oder (f''(x))

**Merkregeln**
- (f''(x_0) > 0): Minimum
- (f''(x_0) < 0): Maximum
    
**Wendepunkte**
- Krümmungswechsel
- mathematisch:  
    f''(x_0)=0 \quad \text{und Vorzeichenwechsel}
 - Polynom 3. Grades: **genau ein Wendepunkt**
 - Polynom 4. Grades: **0–2 Wendepunkte**
    

**Symmetrie**
- nur gerade Exponenten → achsensymmetrisch
- nur ungerade Exponenten, kein Absolutglied → punktsymmetrisch
- gemischte Exponenten → keine Symmetrie

### **Anwendungen**

**1. Grad und Endverhalten erkennen**
1. **Aufgabe (allgemein):**  
    „Beschreiben Sie das Verhalten des Polynoms für (x \to \pm\infty).“
2. **Eigenschaften:**  
    Grad des Polynoms, Leitkoeffizient
3. **Grundidee:**  
    Höchster Term dominiert → Vorzeichen + Grad entscheiden

**2. Anzahl möglicher Nullstellen**
1. **Aufgabe:**  
    „Wie viele reelle Nullstellen kann das Polynom maximal haben?“
2. **Eigenschaften:**  
    Grad des Polynoms
3. **Grundidee:**  
    Maximal so viele Nullstellen wie der Grad

**3. Nullstellen aus Faktorform**
1. **Aufgabe:**  
    „Bestimmen Sie die Nullstellen von $(f(x)=(x-2)^2(x+1))$.“
2. **Eigenschaften:**  
    Faktor ↔ Nullstelle
3. **Grundidee:**  
    Jeden Faktor = 0 setzen

**4. Art der Nullstelle (schneiden / berühren)**
1. **Aufgabe:**  
    „Wie verhält sich der Graph bei der Nullstelle (x=1)?“
2. **Eigenschaften:**  
    Vielfachheit der Nullstelle
3. **Grundidee:**  
    Gerade Vielfachheit → Berührung  
    Ungerade → Schneiden


**5. Symmetrie eines Polynoms**
1. **Aufgabe:**  
    „Untersuchen Sie die Symmetrie des Polynoms.“
2. **Eigenschaften:**  
    gerade / ungerade Exponenten
3. **Grundidee:**  
    Nur gerade → y-Achse  
    Nur ungerade (ohne Absolutglied) → Ursprung

**6. Ableitung bilden**
1. **Aufgabe:**  
    „Bestimmen Sie die Ableitungsfunktion.“
2. **Eigenschaften:**  
    Potenzregel
3. **Grundidee:**  
    Exponent nach vorne, Grad −1

**7. Extremstellen bestimmen**
1. **Aufgabe:**  
    „Bestimmen Sie die Extremstellen des Polynoms."
2. **Eigenschaften:**  
    Zusammenhang Funktion ↔ Ableitung
3. **Grundidee:**  
    (f'(x)=0) lösen

**8. Art der Extremstelle (Max / Min)**
1. **Aufgabe:**  
    „Handelt es sich um ein Maximum oder Minimum?“
2. **Eigenschaften:**  
    Zweite Ableitung
3. **Grundidee:**  
    (f''>0) → Minimum  
    (f''<0) → Maximum

**9. Wendepunkte**
1. **Aufgabe:**  
    „Bestimmen Sie die Wendepunkte.“
2. **Eigenschaften:**  
    Zweite Ableitung, Krümmung
3. **Grundidee:**  
    (f''(x)=0) + Vorzeichenwechsel

**10. Zusammenhang Nullstelle ↔ Ableitung**
1. **Aufgabe:**  
    „Warum ist (x=2) auch Nullstelle der Ableitung?“
2. **Eigenschaften:**  
    Mehrfache Nullstellen
3. **Grundidee:**  
    Berührpunkt → horizontale Tangente

**11. Polynom aus Bedingungen bestimmen (ETH-Klassiker)**
1. **Aufgabe:**  
    „Bestimmen Sie das Polynom 3. Grades mit gegebenen Eigenschaften.“
2. **Eigenschaften:**  
    Funktionswert, Extrem- / Wendepunkt
3. **Grundidee:**  
    Allgemeiner Ansatz → Gleichungssystem

**12. Polynom aus Graph rekonstruieren**
1. **Aufgabe:**  
    „Bestimmen Sie die Funktionsgleichung anhand des Graphen.“
2. **Eigenschaften:**  
    Nullstellen, Endverhalten, Symmetrie
3. **Grundidee:**  
    Faktorform + Skalierung

**13. Skizzieren eines Polynoms**
1. **Aufgabe:**  
    „Skizzieren Sie den Graphen.“
2. **Eigenschaften:**  
    Endverhalten, Nullstellen, Extremstellen
3. **Grundidee:**  
    Schrittweise qualitative Analyse

**14. Zuordnung: Funktion ↔ Graph**
1. **Aufgabe:**  
    „Welcher Graph gehört zu welchem Polynom?“
2. **Eigenschaften:**  
    Grad, Vorzeichen, Nullstellen
3. **Grundidee:**  
    Grobe Form erkennen, Details abgleichen

**15. Zuordnung: Funktion ↔ Ableitung**
1. **Aufgabe:**  
    „Welcher Graph stellt die Ableitung dar?“
2. **Eigenschaften:**  
    Steigung, Extremstellen
3. **Grundidee:**  
    Nullstellen von (f') ↔ Extrema von (f)

**16. Schnittwinkel zweier Polynome**
1. **Aufgabe:**  
    „Bestimmen Sie den Schnittwinkel zweier Graphen.“
2. **Eigenschaften:**  
    Ableitung, Tangenten
3. **Grundidee:**  
    Steigungen vergleichen

**17. Fläche mit Polynomgrenzen**
1. **Aufgabe:**  
    „Berechnen Sie den Flächeninhalt zwischen Polynom und Achse.“
2. **Eigenschaften:**  
    Integral von Polynomen
3. **Grundidee:**  
    Stammfunktion bilden, Grenzen einsetzen

**18. Monotonieintervalle**
1. **Aufgabe:**  
    „Bestimmen Sie die Intervalle, in denen das Polynom wächst.“
2. **Eigenschaften:**  
    Vorzeichen von (f'(x))
3. **Grundidee:**  
    Vorzeichentabelle der Ableitung

**19. Qualitative Aussagen (mündlich!)**
1. **Aufgabe:**  
    „Wie viele Extremstellen kann dieses Polynom haben?“
2. **Eigenschaften:**  
    Grad der Ableitung
3. **Grundidee:**  
    Grad (n) → max. (n-1) Extrema

**20. Fehler finden / Aussagen prüfen**
1. **Aufgabe:**  
    „Ist folgende Aussage richtig?“
2. **Eigenschaften:**  
    Theorie zu Grad, Nullstellen, Ableitungen
3. **Grundidee:**  
    Gegenbeispiel oder allgemeine Regel