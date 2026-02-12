> Wie stark schwanken die Werte um diesen Mittelpunkt?

Zwei Zufallsvariablen können denselben Erwartungswert haben, aber völlig unterschiedlich streuen.
Wie weit liegen die Werte typischerweise vom Erwartungswert entfernt?

NICHT $E(X-\mu) \quad\text{mit}\quad \mu=E(X)$ - positive und negative Abweichungen heben sich auf, Ergebnis immer 0

Abweichung:  
$$(X-\mu)^2  $$
- immer ≥ 0
- große Abweichungen zählen stärker

Varianz

Für eine diskrete Zufallsvariable (X):
$$\operatorname{Var}(X) =
E\big[(X-E(X))^2\big]$$
 
$$(X-\mu)^2 = X^2 - 2\mu X + \mu^2  $$

Erwartungswert ->
$$E(X^2 - 2\mu X + \mu^2)  $$
Linearität ->
$$E(X^2) - 2\mu E(X) + \mu^2  $$
Da ($E(X)=\mu$):
$$E(X^2) - 2\mu^2 + \mu^2

E(X^2) - \mu^2  $$
$$\operatorname{Var}(X)=E(X^2)-[E(X)]^2  $$

$$E(X^2)=\sum_i x_i^2\cdot P(X=x_i)  $$

Standardabweichung

Die Varianz hat die Einheit Quadrat der Einheit von (X)

Deshalb:  
$$\boxed{  
\sigma_X=\sqrt{\operatorname{Var}(X)}  
} $$
Standardabweichung = „typische Entfernung vom Mittelwert“

---

**Wichtige Rechenregeln**
1. Konstante verschieben
$$\operatorname{Var}(X+c)=\operatorname{Var}(X)  $$
Alle Werte verschieben sich gleich → Abstände bleiben gleich.
2. Skalierung
$$\operatorname{Var}(aX)=a^2\operatorname{Var}(X)$$
Abweichungen werden mit (a) multipliziert → Quadrate mit (a^2).
3. Summe unabhängiger Zufallsvariablen
$$\operatorname{Var}(X+Y)=\operatorname{Var}(X)+\operatorname{Var}(Y) $$


Varianz bei Bernoulli-Experiment
  
$$X=  
\begin{cases}  
1 & \text{Erfolg} \\  
0 & \text{Misserfolg}  
\end{cases}  
\quad  
P(X=1)=p  $$
E(X)=p  
E(X^2)=p $\quad(\text{weil }1^2=1,;0^2=0)$ 
$$\operatorname{Var}(X)=p(1-p) $$