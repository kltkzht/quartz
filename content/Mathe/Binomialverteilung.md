Die Binomialverteilung beschreibt genau diese Situation:
- Ein Experiment wird n-mal wiederholt
- Jeder Versuch hat nur zwei mögliche Ausgänge  
    → Erfolg / Misserfolg
- Die Erfolgswahrscheinlichkeit (p) ist in jedem Versuch gleich
- Die Versuche sind unabhängig  
    → praktisch immer: mit Zurücklegen

Zufallsvariable:  
$$X=\text{„Anzahl der Erfolge in n Versuchen“}$$


1. Fixiere **genau k Erfolge**
In wie vielen Wegen können **genau k Erfolge** auftreten?
2. Wahrscheinlichkeit **einer festen Reihenfolge**
Beispiel (n=5, k=2):  
EEMMM
- Wahrscheinlichkeit für diese eine konkrete Reihenfolge:  
    $$p^k(1-p)^{n-k} $$
Unabhängigkeit ⇒ Produktregel

p^k - Erfolge
(1-p)^(n-k) - Gegenwahrscheintlichkeit, Misserfolge

3. Wie viele solche Reihenfolgen gibt es?
Auf wie viele Arten kann man k Erfolge auf n Positionen verteilen?
$$\binom{n}{k}$$4. Alles zusammenführen
Alle diese Reihenfolgen sind:
- disjunkt
- gleich wahrscheinlich
$$P(X=k)=\binom{n}{k}p^k(1-p)^{n-k}$$ 

| Teil             | Bedeutung                    |
| ---------------- | ---------------------------- |
| $(\binom{n}{k})$ | Anzahl möglicher Anordnungen |
| $(p^k)$          | k Erfolge                    |
| $((1-p)^{n-k})$  | n−k Misserfolge              |

**[[Mathe/Erwartungswert]] der Binomialverteilung**

1. Zerlegung in Bernoulli-Variablen
$$X_i=  
\begin{cases}  
1 & \text{Erfolg im i-ten Versuch} \\  
0 & \text{sonst}  
\end{cases} $$$$X=X_1+X_2+\cdots+X_n$$ 2. Erwartungswert eines Bernoulli-Versuchs
$$E(X_i)=1\cdot p+0\cdot(1-p)=p$$ 3. Linearität
$$E(X)=E(X_1+\cdots+X_n)=np $$
$$E(X)=np$$  
**[[Mathe/Varianz]] der Binomialverteilung**
Für einen Bernoulli-Versuch:  
$\operatorname{Var}(X_i)=p(1-p)$  

Unabhängigkeit ⇒ Varianzen addieren sich:
$$\operatorname{Var}(X)=np(1-p)$$

$\sigma=\sqrt{np(1-p)}$ 

**Typische Formate**
1. Genau k Erfolge
P(X=k)=\binom{n}{k}p^k(1-p)^{n-k}  
2. Mindestens / höchstens k
Summieren:
P(X\ge k)=\sum_{i=k}^n P(X=i)  
oder Gegenwahrscheinlichkeit:  
P(X\ge k)=1-P(X\le k-1)  
3. Wie oft ziehen, damit ≥ 95 % …“
1-(1-p)^n\ge0.95  
logarithmisch nach (n) auflösen  

**Nicht Binomial**:

|Situation|Warum nicht|
|---|---|
|ohne Zurücklegen|p ändert sich|
|mehr als 2 Ausgänge|nicht Bernoulli|
|p nicht konstant|kein i.i.d.|
|gleichzeitig ziehen|Abhängigkeit|


[[UniWien/Negativ-Binomialverteilung]] 
