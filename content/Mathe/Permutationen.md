alles wird angeordnet (n=k), Reihenfolge zählt
### **Fakultät**
> „In wie vielen Reihenfolgen kann ich alle **n verschiedene** Dinge anordnen?“

n!

Du ordnest n verschiedene Objekte an.
- 1. Platz: **n** Möglichkeiten
- 2. Platz: **n−1** (eins ist weg)
- 3. Platz: **n−2**
- ...
- letzter Platz: **1**
    
$n! = n\cdot(n-1)\cdot(n-2)\cdots 1$ 

### **mit gleichen Objekten**
$$\frac{n!}{k_1!,k_2!,\dots} $$
Angenommen:
- n Objekte insgesamt
- aber einige sind identisch

Wenn du einfach (n!) nimmst, zählst du identische Anordnungen mehrfach.
Für jede Gruppe identischer Objekte teilst du durch deren Fakultät.