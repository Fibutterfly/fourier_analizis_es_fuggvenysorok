---
tags: OE/ALKMAT/Fourier  
aliases: []
TARGET DECK: 02::Fourier::vizsga
---

# Haar TLDR
## Definíciója
$$\begin{align}
	\chi_n^k(x) =& \begin{cases}
			\sqrt{2^n}, & \dfrac{k-1}{2^n} \le x < \dfrac{k-\dfrac{1}{2}}{2^n} \\
			0, & x=\dfrac{k-\dfrac{1}{2}}{2^n} \\
			-\sqrt{2^n}, & \dfrac{k-\dfrac{1}{2}}{2^n} < x \le \dfrac{k}{2^n}
		\end{cases} & \tag{H.1} \\
	\chi_0^0  = & \begin{cases}0, & 0\le x \le 1 \end{cases} & \tag{H.2} 
\end{align}$$
# Hogyan kell kiszámolni a Haar transzfomáltják valaminek?
1. Megkeresem azt a $\chi_n^k$-t ami egyáltalán értelmezve van az értelmezett tartományon, tehát $\dfrac{k-1}{2^n}<=a$
	- ezt érdemes úgy nézni, hogy elindulok $(0,0)$-tól és mindig $k$-t léptetem elsőnek
2. $f(x)=\sum_{k,n}\int_a^b\chi_n^k(t)f(t)*\chi_n^k(x)$

# kártyák
## Haar alapok
START
Basic
Front:
Mi az $\chi_n^k(x)$ függvény definíciója?
Back:
$$\chi_n^k(x) = \begin{cases}
\sqrt{2^n}, & \dfrac{k-1}{2^n} \le x < \dfrac{k-\dfrac{1}{2}}{2^n} \\
0, & x=\dfrac{k-\dfrac{1}{2}}{2^n} \\
-\sqrt{2^n}, & \dfrac{k-\dfrac{1}{2}}{2^n} < x \le \dfrac{k}{2^n}
\end{cases}$$
<!--ID: 1685827602868-->
END

START
Basic
Front:
Mi az $\chi_0^0(x)$ függvény definíciója?
Back:
$$\chi_0^0(x) = \begin{cases}
0, & 0\le x \le 1
\end{cases}$$
<!--ID: 1685827602881-->
END

START
Basic
Front:
Hogyan kell kiszámolni a Haar transzfomáltják valaminek?
Back:
1. Megkeresem azt a $\chi_n^k$-t ami egyáltalán értelmezve van az értelmezett tartományon, tehát $\dfrac{k-1}{2^n}<=a$
	- ezt érdemes úgy nézni, hogy elindulok $(0,0)$-tól és mindig $k$-t léptetem elsőnek
2. $f(x)=\sum_{k,n}\int_a^b\chi_n^k(t)f(t)*\chi_n^k(x)$
<!--ID: 1685827602889-->
END

START
Basic
Front:
Haar $f(x)=\begin{cases} 2 & 0 \le x \le \dfrac{1}{4} \\ 0 & \dfrac{1}{4} < x \le 1 \end{cases}$
Back:
![[Pasted image 20230603232415.png]]
<!--ID: 1685827602897-->
END

START
Basic
Front:
![[Pasted image 20230603232534.png]]
Back:
![[Pasted image 20230603232605.png]]
<!--ID: 1685827602905-->
END
