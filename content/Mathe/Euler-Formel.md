$$e^{i\varphi} = \cos\varphi + i\sin\varphi$$
sie aus Taylorreihen stammt
wissen, warum sie nützlich ist
![Image](https://images.nagwa.com/figures/explainers/464129159632/1.svg)

[[UniWien/Beweis]]
$$e^{x}=\lim_{x \to \infty } (1+\frac{x}{n})^{n} \iff e^{i \varphi}=\lim_{x \to \infty } (1+i\frac{\varphi}{n})^{n}$$
$$lim_{n \to \infty } \cos\left( \frac{\varphi}{n} \right) = 1; \; lim_{n \to \infty } sin\left( \frac{\varphi}{n} \right) = \frac{\varphi}{n}$$
$$cos(\varphi) + i sin(\varphi) = \left( cos\left( \frac{\varphi}{n} \right) + i sin\left( \frac{\varphi}{n} \right) \right)^{n} = \lim_{n \to \infty } \left( 1+i \frac{\varphi}{n} \right)^{n}=e^{i\varphi}$$
Von der Polarform zur Exponentialform: $z = r(\cos\varphi + i\sin\varphi)$  
  
$e^{i\varphi} = \cos\varphi + i\sin\varphi$  
$$\boxed{z = re^{i\varphi}}$$( r = |z| ) → Betrag (Abstand vom Ursprung)
( $\varphi = arg(z)$ ) → Argument (Winkel zur reellen Achse)

Anwendungen:
$(re^{i\varphi})^{n} = r^{n} e^{in\varphi} \quad$

**Multiplikation**
$$z_1 z_2 = (r_1 e^{i\varphi_1})(r_2 e^{i\varphi_2}) = (r_1r_2)e^{i(\varphi_1+\varphi_2)}$$ **Division**
$$\frac{z_1}{z_2}  
= \frac{r_1}{r_2} e^{i(\varphi_1-\varphi_2)}$$
**Potenzen**  
$$z^n = (re^{i\varphi})^n = r^n e^{in\varphi}$$ 
Geometrische Interpretation

Exponentialform beschreibt zwei unabhängige Effekte:
- Betrag ( r )→ Streckung / Stauchung
- Exponent ( $e^{i\varphi}$ )→ Rotation um den Winkel ( \varphi )



Taylorpolynom

Erste Vereinfachung: Lineare Näherung (Tangente)

$$f(x) \approx f(x_0) + f'(x_0)(x - x_0)$$  

- an einem Punkt exakt passt  
- dort dieselbe Steigung hat
- dort dieselbe Krümmung hat
- usw.
    
$$P(x) = a_0 + a_1(x-x_0) + a_2(x-x_0)^2 + \dots$$  
1. (P(x_0) = f(x_0))
2. (P'(x_0) = f'(x_0))
3. (P''(x_0) = f''(x_0))
      
$$\boxed{  
f(x)= f(x_0)

- f'(x_0)(x-x_0)
    
- \frac{f''(x_0)}{2!}(x-x_0)^2
    
- \frac{f'''(x_0)}{3!}(x-x_0)^3
    
- \dots  
    }  $$
Exponentialfunktion
$$e^x = 1 + x + \frac{x^2}{2!} + \frac{x^3}{3!} + \dots$$  
$$z \in \mathbb{C}$$  
$$e^z = 1 + z + \frac{z^2}{2!} + \frac{z^3}{3!} + \dots$$  
$$e^{ix}  
= 1 + ix - \frac{x^2}{2!} - i\frac{x^3}{3!} + \dots$$  $$\boxed{e^{ix} = \cos x + i \sin x}$$  