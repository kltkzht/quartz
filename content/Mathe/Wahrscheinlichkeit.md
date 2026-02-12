[[Mathe/Laplace-Modell]]
[[Mathe/Mehrstufige Experimente]]
[[Mathe/Bedingte Wahrscheinlichkeit]]
[[Mathe/Gegenwahrscheinlichkeit]]

A) MIT Zurücklegen – wie rechnet man?
A1) „Genau k-mal Erfolg in n Zügen“ → [[Mathe/Binomialverteilung]]
$$P(X=k)=\binom{n}{k}p^k(1-p)^{n-k}  $$
A2) „Mindestens einmal“ → [[Mathe/Gegenwahrscheinlichkeit]]
$$P(\ge 1)=1-(1-p)^n  $$
B) OHNE Zurücklegen – wie rechnet man?
B1) Pfad-Methode (Kettenregel)

B2) Kombinatorik-Methode ([[Mathe/Hypergeometrische Verteilung]]) – super für „genau k aus n“

Wenn du ohne Zurücklegenn Ziehungen machst und „genau k weiße“ willst:

Urne: (W) weiße, (R) rote, total (N=W+R). Ziehe (n) Kugeln.  
$$P(X=k)=\frac{\binom{W}{k}\binom{R}{n-k}}{\binom{N}{n}}  $$