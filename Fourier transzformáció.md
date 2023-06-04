---
tags: OE/ALKMAT/Fourier  
aliases: []
TARGET DECK: 02::Fourier::vizsga
---

# Fourier-transzformáció tldr
$$\begin{align}
	\mathcal{F}(f)(u) &=  \dfrac{1}{\sqrt{2* \pi}} \int_{-\infty}^\infty f(x) e^{-i*u*x} dx &\tag{FT.1} \\
	f(x) &= \dfrac{1}{\sqrt{2*\pi}} \int_{-\infty}^\infty  \mathcal{F}(f)(u)*e^{i*u*x}du & \tag{FT.2}
\end{align}
$$
# Euler cosinus összefügések
$$\begin{align}
&e^{ix} &= \cos(x)+i \sin(x) & \tag{FT.3} \\
&\cfrac{e^{ix}-e^{-ix}}{2i} &= \sin(x) & \tag{FT.4} \\
&\cfrac{e^{ix}+e^{-ix}}{2} &= \cos(x) & \tag{FT.5}

\end{align}$$

# Fourier-transzformáció tulajdonságai
- Minden $\mathbb{R}$-en [[Lebesgue]]-integrálható függvény Fourier-transzformáltja folytonos függvény.
- ha az $f (x)$ és az $\bar{f} (x) = x*f(x)$ függvények [[Lebesgue]]-integrálhatók $\mathbb{R}$-en, akkor érvényes $\mathcal{F}(\bar{f} )(u) = i*\dfrac{d}{dz} \mathcal{F}(f )(u)$,
- Ha $f (x)$ az $f^\prime(x)$ deriváltfüggvényének integrálfüggvénye, továbbá $f (x)$ és $f^\prime(x)$ [[Lebesgue]]-integrálhatók $\mathbb{R}$-en, akkor $\mathcal{F} (f^\prime)(u) = i*u \mathcal{F} (f)(u)$.
# kártyák
## Fourier transzformáció tulajdonságai
START
Basic
Front:
Mik a Fourier transzformáció tulajdonságai?
Back:
- Minden $\mathbb{R}$-en [[Lebesgue]]-integrálható függvény Fourier-transzformáltja folytonos függvény.
- ha az $f (x)$ és az $\bar{f} (x) = x*f(x)$ függvények [[Lebesgue]]-integrálhatók $\mathbb{R}$-en, akkor érvényes $\mathcal{F}(\bar{f} )(u) = i*\dfrac{d}{dz} \mathcal{F}(f )(u)$,
- Ha $f (x)$ az $f^\prime(x)$ deriváltfüggvényének integrálfüggvénye, továbbá $f (x)$ és $f^\prime(x)$ [[Lebesgue]]-integrálhatók $\mathbb{R}$-en, akkor $\mathcal{F} (f^\prime)(u) = i*u \mathcal{F} (f)(u)$.
<!--ID: 1685916485049-->
END

## Fourier transzformációhoz
START
Basic
Front:
Mi a Fourier-transzformáció (FT) képlet?
Back:
$$\mathcal{F}(f)(u) = \dfrac{1}{\sqrt{2 * pi}}* \int_{-\infty}^{\infty} f(x) * e^{-i * u * x} dx$$
<!--ID: 1685819889263-->
END

START
Basic
Front:
Mi a visszafordított Fourier-transzformáció képlete?
Back:
$$f(x) = \dfrac{1}{\sqrt{2 * \pi}} \int_{-\infty}^{\infty} \mathcal{F}(f)(u) e^{i * u * x} du$$
<!--ID: 1685819889275-->
END

## példák
START
Basic
Front:
Fourier-transzformátlja a
$$f(x) = \begin{cases}
	x & -1 < x < 1 \\
	0 & \text{egyébként}
\end{cases}$$
Back:
![[Pasted image 20230603175711.png]]
<!--ID: 1685819889283-->
END

START
Basic
Front:
Fourier transzformáltja a $$f(x)= \begin{cases} 1 & -1 < x < 1 \\ 0 & \text{egyébként} \end{cases}$$
Back:
![[Pasted image 20230603203613.png]]
<!--ID: 1685819889289-->
END

START
Basic
Front:
Fourier transzformáltja a $$f(x)= \begin{cases} \cos(x) & -1 < x < 1 \\ 0 & \text{egyébként} \end{cases}$$
Back:
![[Pasted image 20230603211803.png]]
<!--ID: 1685819889296-->
END