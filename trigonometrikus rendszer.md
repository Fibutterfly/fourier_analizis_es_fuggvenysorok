---
tags: OE/ALKMAT/Fourier  
aliases: []
TARGET DECK: 02::Fourier::vizsga
---

# trigonometrikus rendszer
$\sin(k*x)$ és $\cos(k*x)$ függvényekből álló rendszer
- $\Omega = [-\pi, \pi]$
- ortogonálisak, mert merőlegesek pontonként és egység hosszan dolgozunk

# trigonometrikus rendszer teljessége
- $\cos^k(x)$ függvény előállítható trigonometrikus polinomként tetszőleges $k$ természetes számra [[#cosk]]
- ha $\mathcal{L}^2 (\Omega)$ térbeli $f(x)$ ortogonális, a trigonometrikus rendszer minden elemére, akkor majdnem mindenütt f(x)=0
- A $(0, π)$ intervallumon értelmezett $\mathcal{L}2(0, π)$ függvénytérben mind a koszinusz rendszer, mind pedig a szinus rendszer teljes ortogonális rendszer.
- Egy $\mathcal{L}^2(Ω)$ térbeli $f(x)$ függvény Fourier-sora négyzetintegrálra $f(x)$-hez tart és érvényes a Parseval-képlet: $\int_{\Omega}^2(x)dx = \pi*\left( \dfrac{a^2_0}{2} \sum_{k=1}^2 a_k^2 + b_k^2 \right)$
## bizonyítások
## cosk
[[Teljes indukció]]
$k=0, k=1$-re igaz
tegyük fel, hogy $\cos^k(x) = p(x)$ trigonometrikus polinom
$\cos^{k+1}(x) = cos(x)*p(x)$-re alkalmazzuk a 
$$\begin{align}
	\cos(x)*\cos(k*x) = \dfrac{1}{2}*(\cos(1+k)*x+\cos(1-k)*x) \tag{T.B.1} \\
	\cos(x)*\sin(k*x) = \dfrac{1}{2}*(\sin(1+k)*x-\cos(1-k)*x) \tag{T.B.2} \\
	\sin(x)*\sin(k*x) = \dfrac{1}{2}*(\cos(1-k)*x-\cos(1-k)*x) \tag{T.B.3}
\end{align}$$
és ebből meg is kapjuk, hogy igaz


# kártyák 
START
Basic
Front:
trigonometrikus rendszer
Back:
$\sin(k*x)$ és $\cos(k*x)$ függvényekből álló rendszer
- $\Omega = [-\pi, \pi]$
- ortogonálisak, mert merőlegesek pontonként és egység hosszan dolgozunk
<!--ID: 1685831834835-->
END

START
Basic
Front:
Bizonyítsd, hogy $\cos^k(x)$ függvény előállítható trigonometrikus polinomként tetszőleges $k$ természetes számra
Back:
[[Teljes indukció]]
$k=0, k=1$-re igaz
tegyük fel, hogy $\cos^k(x) = p(x)$ trigonometrikus polinom
$\cos^{k+1}(x) = cos(x)*p(x)$-re alkalmazzuk a 
$$\begin{align}
	\cos(x)*\cos(k*x) = \dfrac{1}{2}*(\cos(1+k)*x+\cos(1-k)*x) \tag{T.B.1} \\
	\cos(x)*\sin(k*x) = \dfrac{1}{2}*(\sin(1+k)*x-\cos(1-k)*x) \tag{T.B.2} \\
	\sin(x)*\sin(k*x) = \dfrac{1}{2}*(\cos(1-k)*x-\cos(1-k)*x) \tag{T.B.3}
\end{align}$$
és ebből meg is kapjuk, hogy igaz
<!--ID: 1685836035011-->
END

START
Basic
Front:
Trigonometrikus rendszer teljessége
Back:
- $\cos^k(x)$ függvény előállítható trigonometrikus polinomként tetszőleges $k$ természetes számra [[#cosk]]
- ha $\mathcal{L}^2 (\Omega)$ térbeli $f(x)$ ortogonális, a trigonometrikus rendszer minden elemére, akkor majdnem mindenütt f(x)=0
- A $(0, π)$ intervallumon értelmezett $\mathcal{L}2(0, π)$ függvénytérben mind a koszinusz rendszer, mind pedig a szinus rendszer teljes ortogonális rendszer.
- Egy $\mathcal{L}^2(Ω)$ térbeli $f(x)$ függvény Fourier-sora négyzetintegrálra $f(x)$-hez tart és érvényes a Parseval-képlet: $\int_{\Omega}^2(x)dx = \pi*\left( \dfrac{a^2_0}{2} \sum_{k=1}^2 a_k^2 + b_k^2 \right)$
<!--ID: 1685912384728-->
END