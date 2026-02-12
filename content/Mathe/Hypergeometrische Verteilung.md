- Zufallsexperiment mit Erfolg/Nicht-Erfolg
- endliche Urne
- ohne Zurücklegen
- feste Anzahl Ziehungen (n)
- Frage: Wie viele Erfolge sind darunter?
X HG(N, K, n)
N - insgesamt
K - Erfolg
n - gezogene Elemente
$$\boxed{  
P(X=k)

\frac{\binom{K}{k}\binom{N - K}{n-k}}{\binom{N}{n}}  
} $$ E(x) = n * K/N
Var(x) = n * K/N * (1-K/N) * (N-n)/(N-1)

![[Images/Pasted image 20260106152249.png]]
    

👉 **Zähler**: günstige Auswahlen  
👉 **Nenner**: alle möglichen Auswahlen



Für kleine Ziehungen (2–3 Kugeln) ist das Pfadmodell oft sogar besser:

$$P(\text{rot dann weiß})

\frac{R}{N}\cdot\frac{W}{N-1}  $$

|Situation|Richtige Methode|
|---|---|
|mit Zurücklegen|Binomial|
|ohne Zurücklegen|**Hypergeometrisch**|
|gleichzeitig gezogen|**Hypergeometrisch**|
|feste Anzahl Ziehungen|Hypergeometrisch|
|„mindestens einmal“ mit Zurücklegen|Gegenwahrscheinlichkeit|
|„mindestens einmal“ ohne Zurücklegen|Produkt ohne Zurücklegen|

Wenn dich ein Prüfer mündlich fragt:

 „Brauchen wir hier die hypergeometrische Verteilung?“

„Da ohne Zurücklegen gezogen wird, sind die Ziehungen abhängig. Die Wahrscheinlichkeit berechnet man daher über Kombinationen, also hypergeometrisch.“
