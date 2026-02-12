1. Vektor-/Normalenmethode (allgemein, immer anwendbar)
2. Polarform (schnellste, wenn Kreis in Mittelpunktsform)
3. Differenzialrechnung (wenn Kreis als Funktion gegeben)

**1. Vektor-/Normalenmethode**

**Gegeben:** Mittelpunkt M und Punkt P auf Kreis  
**Geometrische Idee:** Der Radiusvektor MP steht senkrecht zur Tangente

1. Radiusvektor berechnen: v = P - M = (x₀-m_x, y₀-m_y)
   (Dies ist ein Normalenvektor n der Tangente)
2. Normalenform der Geraden:
   n·(X - P) = 0
   bzw. (x₀-m_x)(x-x₀) + (y₀-m_y)(y-y₀) = 0
3. Vereinfachen zu Ax+By+C=0

**2. Polarform**

**Gegeben:** Kreis in Mittelpunktsform (x₀-m_x)²+(y₀-m_y)²=r²  
**Punkt:** P(x0∣y0) liegt auf dem Kreis

1. Prüfe: Liegt P auf dem Kreis? (x₀-m_x)²+(y₀-m_y)²=r²
2. Anwendung der Polarform:
   Ersetze in der Kreisgleichung:
   (x-m_x)² → (x₀-m_x)(x-m_x)
   (y-m_y)² → (y₀-m_y)(y-m_y)
   Also: (x₀-m_x)(x-m_x) + (y₀-m_y)(y-m_y) = r²
3. Vereinfachen zur Geradengleichung Ax+By+C=0

**3. Differenzialrechnung**

**Gegeben:** Kreisgleichung nach y aufgelöst oder implizit  
**Idee:** Tangente = Ableitung im Punkt P

**Für Halbkreise (oberer/unterer):**

1. Kreis: (x-m_x)²+(y-m_y)²=r² nach y auflösen:
   y = m_y ± √[r² - (x-m_x)²]
2. Ableitung y'(x) bilden
3. y'(x₀) = Steigung m der Tangente
4. Punkt-Steigungsform: y-y₀ = m(x-x₀)

**Für implizite Kreise:**

1. Kreisgleichung: F(x,y)=0 (z.B. x²+y²+ax+by+c=0)
2. Implizite Ableitung: d/dx auf beiden Seiten
   Beispiel: x²+y²=r² → 2x + 2y·y' = 0
3. Nach y' auflösen: y' = -x/y
4. Im Punkt P(x₀,y₀): m = -x₀/y₀
5. Tangente: y-y₀ = m(x-x₀)




**Was oft schiefgeht:**
1. Punkt liegt **nicht** auf Kreis → gibt keine Tangente!
2. Vorzeichenfehler beim Normalenvektor: P−MP−M oder M−PM−P?  
    Beide sind Normalenvektoren, führen zur gleichen Tangente
3. Vereinfachungsfehler beim Ausmultipliziere