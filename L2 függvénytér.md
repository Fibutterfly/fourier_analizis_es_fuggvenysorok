---
tags: OE/ALKMAT/Fourier 
aliases: ["L2 függvénytéren","négyzetesen integrálható"]
TARGET DECK: 02::Fourier::vizsga
---
# $\cal{L}^2$  függvénytér $\Omega$ halmazon
Legyen:
$$f:\Omega \to \mathbb{R}$$ Akkor mondjuk négyzetesen integrálhatónak, ha
- Lebesuge-mérhető
- $f^2$ Lebesuge-integrálható
#Nagy_Péter/fourierjegyzet
# $\cal{L}^2$  függvénytér tulajdonságai
- Ha egy $f: \Omega \to \mathbb{R}$ négyzetesen integrálható, akkor integrálható és $|f(x)| < \dfrac{|f(x)|^2+1}{2}$
- Ha $f: \Omega \to \mathbb{R}$ és $g: \Omega \to \mathbb{R}$ négyzetesen integrálhatóak, akkor a szorzatuk is és $|f(x)g(x)| < \dfrac{|f(x)|^2+|g(x)|^2}{2}$
- Ha $f: \Omega \to \mathbb{R}$ és $g: \Omega \to \mathbb{R}$ négyzetesen integrálhatóak, akkor az összegük is és $|f(x)+g(x)|^2 < |f(x)|^2 + 2f(x)g(x) + |g(x)|^2$
- négyzetesen integrálható függvények vektorteret alkotnak
- skalárszorzata $\langle f, g \rangle = \int_\Omega f(x)*g(x)dx$
- Normája $||f||^2 = \langle f, f \rangle$
- Ha $f: \Omega \to \mathbb{R}$ és $g: \Omega \to \mathbb{R}$ négyzetesen integrálhatóak, akkor a Cauchy-Schwarcz egyenlőtlenség igaz rá
#Nagy_Péter/fourierjegyzet 
# Fourier bizonyítása a $\cal{L}^2$-nek

# Kártyák
START
Basic
Front:
Definiáld a négyzetes integrálható függvényeket
Back:
Legyen:
$$f:\Omega \to \mathbb{R}$$ Akkor mondjuk négyzetesen integrálhatónak, ha
- Lebesuge-mérhető
- $f^2$ Lebesuge-integrálható
<!--ID: 1685830021248-->
END

START
Basic
Front:
Négyzetesen integrálható függvények tulajdonságai
Back:
- Ha egy $f: \Omega \to \mathbb{R}$ négyzetesen integrálható, akkor integrálható és $|f(x)| < \dfrac{|f(x)|^2+1}{2}$
- Ha $f: \Omega \to \mathbb{R}$ és $g: \Omega \to \mathbb{R}$ négyzetesen integrálhatóak, akkor a szorzatuk is és $|f(x)g(x)| < \dfrac{|f(x)|^2+|g(x)|^2}{2}$
- Ha $f: \Omega \to \mathbb{R}$ és $g: \Omega \to \mathbb{R}$ négyzetesen integrálhatóak, akkor az összegük is és $|f(x)+g(x)|^2 < |f(x)|^2 + 2f(x)g(x) + |g(x)|^2$
- négyzetesen integrálható függvények vektorteret alkotnak
- skalárszorzata $\langle f, g \rangle = \int_\Omega f(x)*g(x)dx$
- Normája $||f||^2 = \langle f, f \rangle$
- Ha $f: \Omega \to \mathbb{R}$ és $g: \Omega \to \mathbb{R}$ négyzetesen integrálhatóak, akkor a Cauchy-Schwarcz egyenlőtlenség igaz rá
<!--ID: 1685830021253-->
END