#flashcards #deck/mathe
## Ableitung: Begriff, Regeln, Beweise

Was ist die Ableitung (allgemein)?::Die Ableitung f′(x0​) beschreibt die momentane Änderungsrate von f bei x0 und entspricht geometrisch der Steigung der Tangente an den Graphen in diesem Punkt. Formal ist sie der Grenzwert des Differenzenquotienten.
<!--SR:!2025-12-28,1,226-->

Was ist die Steigung an einem Punkt?::Die Steigung an einem Punkt ist die Tangentensteigung und wird durch f′(x) gegeben.
<!--SR:!2025-12-29,2,246-->

Ist es ein Maximum oder Minimum (bei x0x_0x0​)?::Entscheidung läuft über die Ableitung: Kandidaten durch f′(x0)=0f'(x_0)=0f′(x0​)=0 (oder nicht definiert) finden. Dann: (1) **Vorzeichenwechseltest**: f′f'f′ wechselt von + nach − ⇒ lokales Maximum; von − nach + ⇒ lokales Minimum. (2) **2. Ableitungstest**: f′′(x0)<0f''(x_0)<0f′′(x0​)<0 ⇒ Maximum, f′′(x0)>0f''(x_0)>0f′′(x0​)>0 ⇒ Minimum; bei f′′(x0)=0f''(x_0)=0f′′(x0​)=0 ist der Test unentschieden, dann Vorzeichenwechsel oder höhere Ableitungen prüfen.

Was beschreibt die zweite Ableitung?::f′′(x) beschreibt die Änderung der Steigung (also die „Steigung der Steigung“) und geometrisch die Krümmung/Konkavität.
<!--SR:!2025-12-28,1,226-->

Wenn die zweite Ableitung negativ ist, was bedeutet das?::f′′(x)<0 bedeutet: Die Steigung f′(x) nimmt ab, der Graph ist konkav, lokales Maximum.
<!--SR:!2025-12-28,1,226-->

Welche Ableitungsregeln können Sie nennen?::Wichtige Regeln: (1) **Summenregel** (u+v)′=u′+v′(u+v)'=u'+v'(u+v)′=u′+v′. (2) **Faktorregel** (c⋅u)′=c⋅u′(c\cdot u)'=c\cdot u'(c⋅u)′=c⋅u′. (3) **Potenzregel** (xn)′=nxn−1(x^n)'=n x^{n-1}(xn)′=nxn−1 (für passende nnn). (4) **Produktregel** (uv)′=u′v+uv′(uv)'=u'v+uv'(uv)′=u′v+uv′. (5) **Quotientenregel** (uv)′=u′v−uv′v2\left(\frac{u}{v}\right)'=\frac{u'v-uv'}{v^2}(vu​)′=v2u′v−uv′​ (mit v≠0v\neq 0v=0). (6) **Kettenregel** (f(g(x)))′=f′(g(x))⋅g′(x)(f(g(x)))'=f'(g(x))\cdot g'(x)(f(g(x)))′=f′(g(x))⋅g′(x). Ergänzend: Ableitungen von ex,ln⁡x,sin⁡x,cos⁡xe^x,\ln x,\sin x,\cos xex,lnx,sinx,cosx usw.

Schreiben Sie die allgemeine Form der Quotientenregel auf.::Für f(x)=u(x)/v(x)​ gilt: f′(x)=u′(x)v(x)−u(x)v′(x)/(v(x))^2
<!--SR:!2025-12-31,4,270-->

Schreiben Sie die Produktregel auf.::Für f(x)=u(x)⋅v(x)f(x)=u(x)\cdot v(x)f(x)=u(x)⋅v(x) gilt: f′(x)=u′(x)v(x)+u(x)v′(x)f'(x)=u'(x)v(x)+u(x)v'(x)f′(x)=u′(x)v(x)+u(x)v′(x). Interpretation: Beide Faktoren können sich ändern, daher zwei Beiträge.

Wie könnte man die Produktregel herleiten?::![[nicht ETH/Images/Pasted image 20251227200954.png]]
<!--SR:!2025-12-28,1,226-->

Schreiben Sie die allgemeine Form der Kettenregel auf.::Für f(x)=F(g(x)) gilt: f′(x)=F′(g(x))⋅g′(x)
<!--SR:!2025-12-31,4,270-->

Was ist die Ableitung von x2x^2x2?::Die Ableitung ist 2x2x2x. Begründung per Potenzregel oder per Grenzwertdefinition: f′(x)=lim⁡h→0(x+h)2−x2h=lim⁡h→02xh+h2h=lim⁡h→0(2x+h)=2xf'(x)=\lim_{h\to 0}\frac{(x+h)^2-x^2}{h}=\lim_{h\to 0}\frac{2xh+h^2}{h}=\lim_{h\to 0}(2x+h)=2xf′(x)=limh→0​h(x+h)2−x2​=limh→0​h2xh+h2​=limh→0​(2x+h)=2x.

Wie würden Sie einem Schüler erklären, was eine Ableitung ist?::Die Ableitung misst, wie stark sich f(x) in diesem Moment verändert – wie die Momentangeschwindigkeit bei einer Weg-Zeit-Funktion. Geometrisch ist es die Steigung der Tangente: die beste lineare Annäherung an den Graphen nahe x. Beispiel: Änderung der Geschwindigkeit
<!--SR:!2025-12-28,1,230-->

Beweisen Sie, dass die Ableitung von x2x^2x2 gleich 2x2x2x ist.::Mit Grenzwert: f(x)=x2f(x)=x^2f(x)=x2. f′(x)=lim⁡h→0(x+h)2−x2h=lim⁡h→0x2+2xh+h2−x2h=lim⁡h→0(2x+h)=2xf'(x)=\lim_{h\to0}\frac{(x+h)^2-x^2}{h}=\lim_{h\to0}\frac{x^2+2xh+h^2-x^2}{h}=\lim_{h\to0}(2x+h)=2xf′(x)=limh→0​h(x+h)2−x2​=limh→0​hx2+2xh+h2−x2​=limh→0​(2x+h)=2x. Der entscheidende Schritt ist das Kürzen von hhh und dass h→0h\to0h→0.

Was ist die Ableitung von f(x)=x3+2xf(x)=x^3+2xf(x)=x3+2x? Können Sie das beweisen?::Ableitung: f′(x)=3x2+2f'(x)=3x^2+2f′(x)=3x2+2. Beweis (Grenzwert): (x+h)3+2(x+h)−(x3+2x)h=3x2h+3xh2+h3+2hh=3x2+3xh+h2+2→3x2+2\frac{(x+h)^3+2(x+h)-(x^3+2x)}{h}=\frac{3x^2h+3xh^2+h^3+2h}{h}=3x^2+3xh+h^2+2\to 3x^2+2h(x+h)3+2(x+h)−(x3+2x)​=h3x2h+3xh2+h3+2h​=3x2+3xh+h2+2→3x2+2.

Welche Funktionen sind undifferenzierbare?::Funktionen, bei denen an mindestens einer Stelle der Grenzwert des Differenzenquotienten nicht existiert, also keine Ableitung definiert werden kann. Typische Ursachen sind Sprungstellen, Spitzen/Ecken/Ecken oder horizontale Knicke, bei denen von links und rechts unterschiedliche Tangentensteigungen vorliegen.

Es gibt sogar stetige Funktionen, die an jeder Stelle undifferenzierbar sind (Weierstraß-Funktion)
​
<!--SR:!2025-12-28,1,226-->

Warum besitzt eine Funktion an einer Unstetigkeitsstelle keine Ableitung?::Ableitung setzt lokale Linearität voraus; Unstetigkeit bedeutet, dass der Funktionswert bei x nicht als Grenzwert der Umgebung passt. Dann kann der Differenzenquotient nicht zu einem endlichen Grenzwert konvergieren (Zähler „springt“).
<!--SR:!2025-12-29,2,246-->

---

## Kurvendiskussion: Skizzieren, Extrema, Wendepunkte

Skizzieren Sie den Graphen (allgemeines Vorgehen).::Standard-Plan: (1) **Definitionsbereich** und ggf. Symmetrie bestimmen. (2) **Nullstellen** und Achsenschnittpunkte. (3) **Verhalten im Unendlichen** (Grenzwerte, Asymptoten). (4) **1. Ableitung**: Extremstellen via f′=0f'=0f′=0, Monotonieintervalle. (5) **2. Ableitung**: Wendepunkte via f′′=0f''=0f′′=0 + Vorzeichenwechsel, Krümmung. (6) markante Punkte eintragen und qualitativ verbinden.

Berechnung von Extrema und Wendepunkten: was tun?::Extrema: f′(x)=0f'(x)=0f′(x)=0 (oder f′f'f′ nicht definiert), dann Klassifikation durch Vorzeichenwechsel von f′f'f′ oder f′′f''f′′. Wendepunkt: f′′(x)=0f''(x)=0f′′(x)=0 (Kandidat) und Krümmungswechsel nachweisen (Vorzeichenwechsel von f′′f''f′′ oder f′′′(x)≠0f'''(x)\neq 0f′′′(x)=0 als hinreichendes Kriterium).

Was ist ein Wendepunkt (präzise)?::Ein Wendepunkt ist eine Stelle, an der die Krümmung wechselt: von konvex (f′′>0) zu konkav (f′′<0) oder umgekehrt.
<!--SR:!2025-12-28,1,230-->

Kann man an einer Funktion Extrempunkte finden, ohne explizit abzuleiten?::Manchmal ja: durch **Faktorisierung/Produktstruktur** und Argumente über Nullstellen/Mehrfachnullstellen. Beispiel: Wenn f(x)=(x+1)2(x−2)f(x)=(x+1)^2(x-2)f(x)=(x+1)2(x−2), dann ist x=−1x=-1x=−1 eine doppelte Nullstelle; dort „berührt“ der Graph die x-Achse. Zusätzlich kann man zeigen, dass f′(−1)=0f'(−1)=0f′(−1)=0 (z.B. Produktregel/Struktur), also ist x=−1x=-1x=−1 kritisch und typischerweise Extremum.

Warum muss man bei Skizzen oft über Vorzeichen sprechen?::Weil Monotonie und Krümmung qualitative Eigenschaften sind. Prüfer wollen sehen, dass du aus f′f'f′ (Vorzeichen) auf „steigt/fällt“ schließt und aus f′′f''f′′ auf „links-/rechtsgekrümmt“.

---

## Integral & Stammfunktion: Begriff, Fläche, uneigentlich

Was ist eine Stammfunktion?::Rückwärts zur Ableitung – sie beschreibt die aufsummierte Änderungsrate.
<!--SR:!2025-12-28,1,226-->

Was ist das bestimmte Integral inhaltlich?::∫abf(x) dx\int_a^b f(x)\,dx∫ab​f(x)dx ist der Grenzwert von Riemannsummen und entspricht der **orientierten Fläche** zwischen Graph und x-Achse von aaa bis bbb: Bereiche über der Achse zählen positiv, darunter negativ.
<!--SR:!2025-12-30,3,266-->

Warum benutzt man Integrale, um Flächen zu berechnen?::Weil Fläche als Grenzfall einer Summe vieler schmaler Rechtecke verstanden wird: Fläche≈∑f(xi)Δx. Lässt man Δx→0, erhält man genau das Integral als Grenzwert (Riemannsumme).
<!--SR:!2025-12-28,1,226-->

Was ist die Definition des Integrals ohne Stammfunktion?::Das Integral wird als Grenzwert von Riemannsummen definiert: Zerlege [a,b] in Teilintervalle, ∑f(xi∗​)Δxi und lasse die maximale Teilintervalllänge gegen 0 gehen.
<!--SR:!2025-12-28,1,226-->

Warum ist das Integral eine Grenzwert-Idee?::Weil „unendlich viele“ infinitesimal schmale Beiträge summiert werden. Eine endliche Summe ist nur Näherung; erst im Grenzprozess wird die exakte Fläche/akkumulierte Größe definiert.
<!--SR:!2025-12-28,1,226-->

Warum kann man nicht „direkt“ integrieren, um die Fläche zu berechnen?::Weil das Integral die orientierte Fläche liefert: positive und negative Anteile können sich aufheben. Für die geometrische Fläche muss man Beträge nehmen bzw. in Intervalle teilen
<!--SR:!2025-12-28,1,226-->

Was ist ein uneigentliches Integral und wann braucht man es?::Ein uneigentliches Integral ist ein Integral, bei dem mindestens eine Integrationsgrenze unendlich ist oder die Funktion an einer Grenze oder inneren Stelle unbeschränkt wird (Singularität).Man braucht es, um Flächen unter Kurven über unendliche Intervalle oder bei Polstellen zu berechnen, (z. B. in der Normalverteilung) und existiert (konvergiert), wenn dieser Grenzwert endlich ist.
<!--SR:!2025-12-28,1,226-->

Wie erkennt man ein Problem beim bestimmten Integral (z.B. Logarithmus/Polstelle im Intervall)?::Man prüft den **Definitionsbereich** des Integranden auf [a,b][a,b][a,b]. Wenn im Intervall eine Stelle liegt, an der der Integrand nicht definiert ist (z.B. Nenner 0, ln⁡(0)\ln(0)ln(0), ln⁡(negativ)\ln(\text{negativ})ln(negativ)), ist das Integral uneigentlich und muss aufgespalten und als Grenzwert betrachtet werden.

Warum muss man bei Substitution die Grenzen mittransformieren?::Weil beim bestimmten Integral die Variable wechselt: u=g(x).
<!--SR:!2025-12-30,3,266-->

---

## Integrationstechniken: Substitution, partielle Integration

Was ist Substitution und warum funktioniert sie?::Wenn der Integrand eine innere Funktion g(x) und deren Ableitung g′(x) enthält, setzt man u=g(x), dann wird du=g′(x).
<!--SR:!2025-12-30,3,266-->

Geben Sie ein Beispiel, wo Substitution nötig ist (konzeptionell).::Typisch: ∫(2x−2)/(x2−2x)dx.
<!--SR:!2025-12-30,3,266-->

Was ist partielle Integration und wann nutzt man sie?::Man nutzt sie, wenn ein Produkt vorliegt, bei dem eine Komponente beim Ableiten „einfacher“ wird
<!--SR:!2025-12-30,3,266-->

Wie wählt man u bei partieller Integration?::Wähle u als den Teil, der beim Ableiten deutlich einfacher wird, und v′ als den Teil, den man gut integrieren kann.
<!--SR:!2025-12-28,1,226-->

---

## Fläche, Volumen, Körper: typische mündliche Themen

Wie berechnet man die Fläche zwischen Graph und x-Achse?::Geometrische Fläche ist. Praktisch: Nullstellen finden, Intervall in Abschnitte teilen, in denen f konstant positiv/negativ ist. Fläche=∑±∫f(x) dx
<!--SR:!2025-12-28,1,230-->

Wie berechnet man das Volumen eines Drehkegels?::Das Volumen eines Kegels ist V=1/3πr^2h. Ein Kegel hat ein Drittel des Volumens des entsprechenden Zylinders mit gleicher Grundfläche und Höhe.
<!--SR:!2025-12-28,1,230-->

Wie kann man die Kegelformel über Integrale herleiten?::f(x)=(r/h)x; V=π∫(f(x))2dx, o<x<π
<!--SR:!2025-12-28,1,226-->

Warum darf man Konstanten vor das Integral ziehen?:: Linearität erlaubt der Integration dies: Ein konstanter Faktor ändert sich nicht beim Integrieren, sondern wird einfach mit dem Ergebnis der Integration der variablen Funktion multipliziert.
<!--SR:!2025-12-28,1,230-->

---

## Extremalaufgaben / Optimierung

Wie löst man Extremalaufgaben mit Nebenbedingungen (Standard-Schema)?::(1) **Zielfunktion** aufstellen (das, was minimiert/maximiert wird). (2) **Nebenbedingung** formulieren (Geometrie/Physik/Angabe). (3) Nebenbedingung nutzen, um Zielfunktion auf **eine Variable** zu reduzieren. (4) Ableiten, kritische Punkte finden. (5) Prüfen (Randwerte, Vorzeichenwechsel, 2. Ableitung). (6) Ergebnis **interpretieren** (Einheiten, Sinn, Minimum/Maximum).

Was bedeutet „Minimumaufgabe“ in Geometrie (z.B. Gurtlänge)?::Man modelliert eine Länge als Funktion L(x) und minimiert sie.

---

## Graphen & Ableitungen zuordnen (mündliche Klassiker)

Wie ordnet man Graphen ihren Ableitungen zu (Qualitätskriterien)?::Man nutzt qualitative Zusammenhänge: (1) Wo fff steigt, ist f′>0f'>0f′>0; wo fff fällt, f′<0f'<0f′<0. (2) Extremstellen von fff entsprechen Nullstellen von f′f'f′. (3) Krümmung: wo fff „konvex“ ist, steigt f′f'f′; wo „konkav“, fällt f′f'f′. (4) Polstellen/Asymptoten: Eine gebrochenrationale Funktion kann Ableitungen mit anderen Polstellenordnungen erzeugen; man achtet auf Definitionslücken. (5) Grad: Parabel → lineare Ableitung; Kubik → quadratische Ableitung.

Warum kann man manchmal nicht alle Graphen eindeutig paaren?::Weil mehrere Funktionen qualitativ ähnliche Ableitungen haben können (z.B. vertikale Verschiebungen ändern Ableitung nicht) und weil in Aufgaben oft „Distraktoren“ enthalten sind, die nicht zugeordnet werden müssen.