---
tags: OE/ALKMAT/Fourier 
aliases: []
TARGET DECK: 02::Fourier::vizsga::trig
---

# átváltás
$$\begin{align}
	sin^2(x)&= & 1 - \cos^2(x) & \tag{1.1} \\
	\cos(x) & = & \sin(90°-x) & \tag{1.2}
\end{align}$$
# addíciós tételek
$$\begin{align}
		\sin(x+y) & = & \sin(x)*\cos(y) + \cos(x)*\sin(y) & \tag{2.1} \\
		\sin(x-y) & = & \sin(x)*\cos(y)-cos(x)*\sin(y) & \tag{2.2} \\
		\cos(x-y) & = & \cos(x)*\cos(y)+\sin(x)*\sin(y) &\tag{2.3} \\
		\cos(x+y) & = & \cos(x)*\cos(y)-\sin(x)*\sin(y) & \tag{2.4}
\end{align}$$
# szorzattá alakítás
$$\begin{align}
	\sin(x)+\sin(y) & = & 2*\sin\left(\dfrac{x+y}{2}\right)*\cos \left( \dfrac{x-y}{2} \right) & \tag{3.1} \\
	\sin(x) -\sin(y) &= & 2*\cos\left( \dfrac{x+y}{2} \right)*\sin \left( \dfrac{x-y}{2} \right) \tag{3.2} \\
	\cos(x) + \cos(y) &= & 2*\cos \left( \dfrac{x+y}{2} \right)*\cos \left( \dfrac{x-y}{2} \right) & \tag{3.3} \\
	\cos(x) - \cos(y) &= & -2*\sin \left( \dfrac{x+y}{2} \right)* \sin \left( \dfrac{x-y}{2} \right) \tag{3.4}
\end{align}$$
# 2x szögfüggvények
$$\begin{align}
	\sin(2*x) &= & 2*\sin(x)*\cos(x) & \tag{4.1} \\
	\cos(2*x) &= & \cos^2(x)-\sin^2(x) & \tag{4.2}
\end{align}$$
# /2 szögfüggvények
$$\begin{align}
	\sin^2 \left( \dfrac{x}{2} \right)&=& \dfrac{1-\cos(x)}{2} & \tag{5.1} \\
	\cos^2 \left( \dfrac{x}{2} \right) & = & \dfrac{1+ \cos(x)}{2} & \tag{5.2}
\end{align}$$
# integrálok
$$\begin{align}
	\int\sin(kx)dx & = & - \dfrac{\cos(kx)}{k} & \tag{6.1} \\
	\int \cos(kx)dx & = & \dfrac{\sin(kx)}{k} & \tag{6.2}
\end{align}$$
# szorzatos összefüggések
$$\begin{align}
	\cos(l*x)*\cos(k*x) = \dfrac{1}{2}*(\cos(l+k)*x+\cos(l-k)*x) \tag{6.1} \\
	\cos(l*x)*\sin(k*x) = \dfrac{1}{2}*(\sin(l+k)*x-\cos(l-k)*x) \tag{6.2} \\
	\sin(l*x)*\sin(k*x) = \dfrac{1}{2}*(\cos(l-k)*x-\cos(l+k)*x) \tag{6.3}
\end{align}$$
# kártya
START
Basic
Front:
$$\cos(l*x)*\cos(k*x)$$
Back:
$$\dfrac{1}{2}*(\cos(l+k)*x+\cos(l-k)*x)$$
<!--ID: 1685836035019-->
END

START
Basic
Front:
$$\sin(l*x)*\sin(k*x)$$
Back:
$$\dfrac{1}{2}*(\cos(l-k)*x-\cos(l+k)*x)$$
<!--ID: 1685836035024-->
END

START
Basic
Front:
$$\cos(l*x)*\sin(k*x)$$
Back:
$$\dfrac{1}{2}*(\sin(l+k)*x-\cos(l-k)*x)$$
<!--ID: 1685836035030-->
END
## átváltás
START
Basic
Front:
váltsd $\cos$-ra
$$\sin^2(x)=$$
Back:
$$\sin^2(x) = 1 - \cos^2(x)$$
<!--ID: 1685651717276-->
END

START
Basic
Front:
váltsd $\sin$-re
$$\cos(x)$$
Back:
$$\sin(90°-x)$$
<!--ID: 1685651717284-->
END

## addíciós tételek
START
Basic
Front:
$$\sin(x+y)=?$$
Back:
$$\sin(x)*\cos(y) + \cos(x)*\sin(y)$$
<!--ID: 1685651717288-->
END

START
Basic
Front:
$$\sin(x-y) = ?$$
Back:
$$\sin(x)*\cos(y)-cos(x)*\sin(y)$$
<!--ID: 1685651717305-->
END

START
Basic
Front:
$$\cos(x+y)=?$$
Back:
$$\cos(x)*\cos(y)-\sin(x)*\sin(y)$$
<!--ID: 1685651717310-->
END

START
Basic
Front:
$$\cos(x-y)=?$$
Back:
$$\cos(x)*\cos(y)+\sin(x)*\sin(y)$$
<!--ID: 1685651717315-->
END

## szorzattá alakítás
START
Basic
Front:
$$\sin(x)+\sin(y)=?$$
Back:
$$2*\sin\left(\dfrac{x+y}{2}\right)*\cos \left( \dfrac{x-y}{2} \right)$$
<!--ID: 1685651717319-->
END

START
Basic
Front:
$$\sin(x) -\sin(y)=?$$
Back:
$$2*\cos\left( \dfrac{x+y}{2} \right)*\sin \left( \dfrac{x-y}{2} \right)$$
<!--ID: 1685651717325-->
END

START
Basic
Front:
$$\cos(x) + \cos(y)=?$$
Back:
$$2*\cos \left( \dfrac{x+y}{2} \right)* \cos\left( \dfrac{x-y}{2} \right)$$
<!--ID: 1685651717329-->
END

START
Basic
Front:
$$\cos(x) - \cos(y)=?$$
Back:
$$-2*\sin \left( \dfrac{x+y}{2} \right)* \sin \left( \dfrac{x-y}{2} \right)$$
<!--ID: 1685651717334-->
END

## 2x szögfüggvények
START
Basic
Front:
$$\sin(2*x)=?$$
Back:
$$2*\sin(x)*\cos(x)$$
<!--ID: 1685651717339-->
END

START
Basic
Front:
$$\cos(2*x)=?$$
Back:
$$\cos^2(x)-\sin^2(x)$$
<!--ID: 1685651717344-->
END

## /2 szögfüggvények
START
Basic
Front:
$$\sin^2 \left( \dfrac{x}{2} \right)=?$$
Back:
$$\dfrac{1-\cos(x)}{2}$$
<!--ID: 1685651717348-->
END

START
Basic
Front:
$$\cos^2 \left( \dfrac{x}{2} \right)$$
Back:
$$\dfrac{1+ \cos(x)}{2}$$
<!--ID: 1685651717353-->
END

## integrálok
START
Basic
Front:
$$\int\sin(kx)dx$$
Back:
$$- \dfrac{\cos(kx)}{k}$$
<!--ID: 1685661378900-->
END

START
Basic
Front:
$$\int \cos(kx)dx$$
Back:
$$\dfrac{\sin(kx)}{k}$$
<!--ID: 1685661378908-->
END