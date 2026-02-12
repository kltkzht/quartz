#BigTopic #Mathe
[[Mathe/Kombinatorik]]
[[Mathe/Wahrscheinlichkeit]]
[[Mathe/Erwartungswert]]
[[Mathe/Varianz]]
[[Mathe/Binomialverteilung]]
[[Mathe/Geometrische Wahrscheinlichkeiten]]
[[Mathe/Grenz-Wahrscheinlichkeit]]

Beispiele:
1. Mindestens k Erfolge mit Zurücklegen:
Binomialverteiltung (n k) * (p)^k * (1-p)^(n-k). Rechnen für (n k), (n k+1) usw.
2. Wahrscheinlichkeit, dass höchstens n Erfolge bei Ziehen ohne Zurücklegen. 
(K k)(N-K n-k)/(N n), wo N ganze Menge ist, K erfolgreiche Menge, n Anzahl von Ziehungen, k Anzahl von erwünschte Anzahl von ziehungen. Rechnen für k, k-1, k-2 usw.
3. Wahrscheinlichkeit von Erfolg bei gleichzeitig ziehen ist gegeben. Wie groß ist erfolgreiche Menge
(K k)(N-K n-k)/(N n) = P und rechnen für K
4. Wie oft muss mit Zurücklegen gezogen werden, um Wahrscheinlichkeit von Erfolg > P zu sein
(1-p)^n < P, lösen nach n (log(P)/log(1-p)<n)
5. Ohne Zurücklegen gezogen bis erste Erfolg. E(X). X - Anzahl von Ziehungen. E(X)=X * p(X). p(X) durch Baum berechnen (P(x) = SUmme von alle Weg bis zum Erfolg)