> Was passiert, wenn ein Zufallsexperiment immer öfter wiederholt wird? Was ist die Wahrscheinlichkeit im Grenzfall ($n\to\infty$)?

- unendlich viele Würfe
- immer mehr Kugeln/Wiederholungen
- „mit welcher Wahrscheinlichkeit mindestens einmal …“

**„mindestens einmal“**

Erfolg pro Versuch mit Wahrscheinlichkeit (p>0).  
n unabhängige Versuche (mit Zurücklegen).

Gegenereignis:  
$P(\text{kein Erfolg})=(1-p)^n$

Grenzwert:  
$\lim_{n\to\infty}(1-p)^n=0$
$$\lim_{n\to\infty}P(\text{mindestens einmal})=1$$Wenn etwas eine positive Chance hat, passiert es irgendwann fast sicher.

**„mindestens ziehen, damit die Wahrscheinlichkeit ≥ 95 % ist?“**

$$1-(1-p)^n\ge 0.95$$  $$(1-p)^n\le 0.05$$ $$n\ge \frac{\ln(0.05)}{\ln(1-p)}$$
**Grenz-Wahrscheinlichkeit bei Anteilen**
Beispiel:
- Urne mit festem Verhältnis rot : weiß
- Ziehungen mit Zurücklegen

Dann:
- relative Häufigkeit → Erwartungswert
- Streuung → nimmt relativ ab

**Grenzfall bei geometrischer Wahrscheinlichkeit**

Beispiel:
- Immer feinere Gitterpunkte in einem Gebiet
- diskrete Wahrscheinlichkeit → kontinuierliche
geometrische Wahrscheinlichkeit ist oft Grenzfall einer diskreten