(k aus n, Reihenfolge egal)
### **ohne Wiederholung**
> „Ich zähle Auswahlen, nicht Anordnungen.“

$$\binom{n}{k}=\frac{n!}{k!(n-k)!} $$
Wenn wir **k aus n** auswählen und Reihenfolge zählen:  
$$V(n,k)=\frac{n!}{(n-k)!}$$
Aber (k!) verschiedene Reihenfolgen derselben Auswahl
Jede Auswahl wurde **k!-mal gezählt**, also:  
$$\binom{n}{k}=\frac{V(n,k)}{k!}  
=\frac{n!}{k!(n-k)!}  $$
    
### **mit Wiederholung**:  
$$\binom{n+k-1}{k}  $$
- **k Objekte**
- aus **n Sorten**
- Sorten dürfen mehrfach vorkommen
- Reihenfolge egal

- k Sterne ★★★ (Objekte)
- n−1 Trennstriche | | (Sorten trennen)

- k Sterne
- n−1 Striche  
    → **k+n−1 Plätze**

Du wählst, wo die k Sterne liegen: $\binom{n+k-1}{k}$ 




