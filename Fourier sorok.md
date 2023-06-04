---
tags: OE/ALKMAT/Fourier  
aliases: []
TARGET DECK: 02::Fourier::vizsga
---

# Fourier sorok megállapítása
1. Megnézzük, hogy páros vagy páratlan-e a függvény 
	- $f(x) = -f(-x) \to$ akkor páratlan funkció
	- $f(-x) = f(x) \to$ ekkor páros funkció
2. integrálunk úgy, hogy $$furi =\int_{a}^b f(x)*trig(k*x)dx$$
	- Ha páros, akkor a $trig = \cos$
	- ha páratlan, akkor a $trig=\sin$
3. az eredményt kiírjuk így $\sum(furi*trig(k*x))$

# Fourier sorok és a [[trigonometrikus rendszer]]
$$f(x) = \dfrac{a_0}{2} + \sum_{k=1}^n(a_k*\cos(k*x) +b_k \sin(k*x))$$
- $f$ egy $\mathcal{L}^2 (\Omega)$ térbéli mérhető függvény
- $a_k, b_k$ [[Fourier együttható|Fourier együtthatók]]

# Fourier sor komplex alakja
![[Fourier transzformáció#Euler cosinus összefügések]]
Ebből következik az összefüggés, hogy

$$\begin{align}
	&\dfrac{a_0}{2}+\sum_{k=1}^\infty (a_k*\cos(k*x) + b_k*\sin(k*x)) = &  \tag{FS.K.1} \\
	&=  \sum_{k=\infty}^\infty c_k e^{i*k*x} & \tag{FS.K.2} \\
	&= c_0 + \sum_{n=1}^\infty(c_k + c_{-k})*\cos(k*x) + i*(c_k - c_{-k})\sin(k*x) & \tag{FS.K.3} \\
	&a_0 = 2*c_0 & \tag{FS.K.4} \\
	&a_n = c_n + c_{-n} & \tag{FS.K.5} \\
	& b_n = i*(c_n-c_{-n}) & \tag{FS.K.6} \\
	& c_0 = \dfrac{1}{2}*a_0 & \tag{FS.K.7} \\
	& c_k = \dfrac{1}{2}*(a_k-i*b_k) & \tag{FS.K.8} \\
	& c_{-k} = \dfrac{1}{2}*(a_k + i*b_k) & \tag{FS.K.9}
\end{align}$$
^FourierSorKomplexAlak

## Komplex Fourier teljessége
- [[Trigonometrikus rendszer]] és ortogonális, mert $$ \begin{align} \int_\Omega e^{i*m*x}*e^{-i*n*x}dx = \int_\Omega e^{i(m-n)*x}dx \\ \dfrac{1}{m-n} \left[ e^{i*(m-n)x} \right]_{- \pi} ^\pi= 0 \end{align}$$
- ortonormált lesz, ha megszorozzuk $\dfrac{1}{\sqrt{2*\pi}}$ 

# kártyák
START
Basic
Front:
Fourier sor általánosan
Back:
$$f(x) = \dfrac{a_0}{2} + \sum_{k=1}^n(a_k*\cos(k*x) +b_k \sin(k*x))$$
- $f$ egy $\mathcal{L}^2 (\Omega)$ térbéli mérhető függvény
- $a_k, b_k$ [[Fourier együttható|Fourier együtthatók]]
<!--ID: 1685832331997-->
END


START
Basic
Front:
Mi a folyamata a fourier sor fejtésnek?
Back:
1. Megnézzük, hogy páros vagy páratlan-e a függvény 
	- $f(x) = -f(-x) \to$ akkor páratlan funkció
	- $f(-x) = f(x) \to$ ekkor páros funkció
2. integrálunk úgy, hogy $$furi =\int_{a}^b f(x)*trig(k*x)dx$$
	- Ha páros, akkor a $trig = \cos$
	- ha páratlan, akkor a $trig=\sin$
3. az eredményt kiírjuk így $\sum(furi*trig(k*x))$
<!--ID: 1685661012152-->
END

START
Basic
Front:
Fourier sora $f(x) = \dfrac{\pi - x}{2}$, $[0, 2\pi]$
Back:
![[Pasted image 20230602220514.png]]
<!--ID: 1685736420375-->
END

START
Basic
Front:
Fourier sora: $f(x) = 2 + sin^2(x) - 2*cos^3(x)$
Back:
![[Pasted image 20230602223503.png]]
<!--ID: 1685738143978-->
END

START
Basic
Front:
Fourier sora $|sin(x)|$-nek
Back:
![[Pasted image 20230602230153.png]]
<!--ID: 1685739717802-->
END

START
Basic
Front:
$cos(x)$ $[0,\pi]$ $\sin$-es sora
Back:
![[Pasted image 20230602232621.png]]
<!--ID: 1685741186151-->
END

START
Basic
Front:
Mi a Fourier-sor képlete?
Back:
$$\dfrac{a_0}{2}+\sum_{k=1}^\infty (a_k*\cos(k*x) + b_k*\sin(k*x))$$
<!--ID: 1685912384737-->
END

START
Basic
Front:
Mi a Fourier-sor komplex alakja?
Back:
$$\sum_{k=\infty}^\infty c_k e^{i*k*x}$$
<!--ID: 1685912384742-->
END

START
Basic
Front:
Mi a Fourier-sor komplex alakjának kifejtése?
Back:
$$c_0 + \sum_{n=1}^\infty(c_k + c_{-k})*\cos(k*x) + i*(c_k - c_{-k})\sin(k*x)$$
<!--ID: 1685912384747-->
END

START
Basic
Front:
Mi a kapcsolat a valós Fourier sor kezdő tagja és a komplex fourier sor kezdő tagja között?
Back:
$$a_0 = 2*c_0$$
<!--ID: 1685912384752-->
END
START
Basic
Front:
Mi a kapcsolat a Fourier valós cosinuszos együtthatója és a Fouerier komplex együtthatója között?
Back:
$$a_n = c_n + c_{-n}$$
<!--ID: 1685912384758-->
END
START
Basic
Front:
Mi a kapcsolat a Fourier valós sinuszos együtthatója és a Fouerier komplex együtthatója között?
Back:
$$b_n = i*(c_n - c_{-n})$$
<!--ID: 1685912384763-->
END

START
Basic
Front:
Komplex Fourier sor teljessége?
Back:
- [[Trigonometrikus rendszer]] és ortogonális, mert $$ \begin{align} \int_\Omega e^{i*m*x}*e^{-i*n*x}dx = \int_\Omega e^{i(m-n)*x}dx \\ \dfrac{1}{m-n} \left[ e^{i*(m-n)x} \right]_{- \pi} ^\pi= 0 \end{align}$$
- ortonormált lesz, ha megszorozzuk $\dfrac{1}{\sqrt{2*\pi}}$ 
<!--ID: 1685914965533-->
END