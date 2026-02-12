#BigTopic #Physik
[[Physik/Harmonische Schwingungen]] beschreiben eine ideale, periodische Hin- und Herbewegung um eine Ruhelage, die durch eine rücktreibende Kraft proportional zur Auslenkung entsteht. Sie folgen direkt aus Newtons 2. Gesetz und erzeugen sinusförmige Bahnen, was sie mit [[Physik/Kreisbewegung]] verbindet. Das Warum liegt in der Balance zwischen Trägheit und Rückstellkraft, die Energie oszillierend umwandelt.​

Stell dir eine Feder vor: Ziehe sie auseinander (Auslenkung y), und sie zieht proportional zurück mit $F_H = -k y$ (Hookesches Gesetz, k Federkonstante). Das Minuszeichen sorgt dafür, dass die Kraft immer zur [[Physik/Ruhelage]] zeigt – je weiter weg, desto stärker zieht sie. Aus Newtons 2. Gesetz $$F = m \ddot{y}$$ folgt die Differentialgleichung 
$$
\ddot{y} + \omega^2 y = 0
$$
mit Kreisfrequenz $$ \omega = \sqrt{\frac{k}{m}} $$was erklärt, warum leichtere Massen schneller schwingen: Weniger Trägheit bedeutet höhere Frequenz.​

Die Lösung ist $$ y(t) = A \cos(\omega t + \varphi) $$
, wobei A [[Physik/Amplitude]], $\omega = 2\pi f$ Kreisfrequenz und φ [[Physik/Phase]] ist. Das folgt daraus, weil die Beschleunigung $$\ddot{y}=−\omega^2 y$$immer entgegengesetzt zur Position ist – genau wie bei gleichförmiger [[Physik/Kreisbewegung]], wo Radialbeschleunigung zentripetal wirkt. Deshalb ist [[Physik/Periodendauer]] $$T = 2\pi \sqrt{\frac{m}{k}} \quad \text{oder} \quad T = \frac{2\pi}{\omega}$$unabhängig von A: Größere Auslenkungen erfordern nur länger Weg, aber gleiche Zeit durch proportionale Kräfte.

In idealen Fällen (ohne Reibung) wandelt sich kinetische Energie $E_{\text{kin}} = \frac{1}{2} m v^2$ vollständig in potentielle $E_{\text{pot}} = \frac{1}{2} k y^2$ um – Gesamtenergie konstant. Ein Grund dafür ist das in einem Oszillator nur konservative Kräften wirken.
$$E_{\text{ges}} = \frac{1}{2} k A^2$$
Mit [[Dämpfung]] (z. B. Luftreibung) wird $$y(t) = A e^{-\gamma t} \cos(\omega t + \varphi)$$
, Amplitude nimmt exponentiell ab, weil Energie dissipiert wird. Das verbindet zu Impulssatz: Externe Dämpfungskräfte ändern den Gesamtimpuls allmählich.​

Federpendel: Schwingt harmonisch für kleine Amplituden, [[Physik/Frequenz]] hängt nur von k und m ab. Fadenpendel: Bei kleinen Winkeln (<5∘) approximiert $F_H \approx -\frac{m g}{l} y$, also $$\omega = \sqrt{\frac{g}{l}}$$ – länger, langsamer. Folge: Uhren, Gitarren (Frequenz fix trotz Anschlagsstärke), Erdbebenmodelle.