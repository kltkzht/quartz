### **mit Wiederholung:**  
$$n^k$$

Du füllst **k Plätze**, und **jeder Platz** hat **n Möglichkeiten**.
- Platz 1: n
- Platz 2: n
- …
- Platz k: n

Produktregel:  
$n\cdot n\cdot \dots \cdot n = n^k$  

Typisch für Code, Passwort, Würfelwürfe

### **ohne Wiederholung**: 
$$V(n,k)=\frac{n!}{(n-k)!}  $$
Du ordnest **k verschiedene Plätze**, aber **kein Objekt darf doppelt vorkommen**.
- Platz 1: n Möglichkeiten
- Platz 2: n−1
- …
- Platz k: n−(k−1)

Produkt: $n\cdot(n-1)\cdot\ldots\cdot(n-k+1)$
$$n\cdot(n-1)\cdots(n-k+1) = \frac{n!}{(n-k)!}$$
Weil (n!) zu viel zählt (bis 1), wir aber **nur bis (n-k+1)** brauchen.
