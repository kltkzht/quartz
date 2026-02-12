gerechtes Spiel: E(X) = P(x) * x = Einsatz

> der langfristige Durchschnitt, den du erhältst,  wenn du ein Zufallsexperiment sehr oft wiederholst. Wo liegt der Mittelpunkt?

Eine Zufallsvariable (X):
- ordnet jedem Ergebnis eine Zahl zu
- z.B. Augenzahl, Gewinn, Anzahl Ziehungen

- mögliche Werte ($x_1,x_2,\dots$)
- mit Wahrscheinlichkeiten ($P(X=x_i)$)
$$E(X)=\sum_i x_i\cdot P(X=x_i)  $$

- Du wiederholst das Experiment (N)-mal
- (x_i) tritt etwa ($N\cdot P(X=x_i)$)-mal auf

Gesamtsumme aller Ergebnisse:  $\sum_i x_i\cdot (N\cdot P(X=x_i))$
Durchschnitt:
$$\frac{1}{N}\sum_i x_i\cdot (N\cdot P(X=x_i)) = \sum_i x_i\cdot P(X=x_i)$$
Erwartungswert = gewichteter Mittelwert

Wichtigste Eigenschaft: **Linearität**
$$E(aX+bY+c)=aE(X)+bE(Y)+c  $$
Das gilt IMMER, auch wenn (X) und (Y) abhängig sind/ ohne Zurücklegen gezogen wird


Beispiel: Summe mehrerer Zufallsvariablen
$S=X_1+X_2+\cdots+X_n$
Dann:  
$E(S)=E(X_1)+\cdots+E(X_n)$



**Gerechtes Spiel**
Ein Spiel ist gerecht, wenn:  
$$E(\text{Gewinn})=0$$


**Erwartungswert bei „ziehen bis …“**
> „Wie viele Ziehungen erwartet man, bis erstmals … erscheint?“

Das ist der geometrische Erwartungswert.

Erfolg mit Wahrscheinlichkeit (p).
Erwartungswert:  
$$E(N)=\frac{1}{p}  $$Je seltener der Erfolg, desto länger wartet man
    
**Erwartungswert [[Mathe/ohne Zurücklegen]]**

Beispiel:  
Urne: 3 rot, 2 weiß  
Ziehe eine Kugel
$$X=  
\begin{cases}  
1,&\text{wenn rot}\\  
0,&\text{sonst}  
\end{cases}  $$
$$E(X)=1\cdot\frac{3}{5}+0\cdot\frac{2}{5}=\frac{3}{5}$$ 

Erwartungswert ist nicht wahrscheinlichstes Ergebnis
Erwartungswert ist nicht garantiertes Ergebnis
Linearität nicht nur bei Unabhängigkeit