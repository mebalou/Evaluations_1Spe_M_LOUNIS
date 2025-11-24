---
layout: default
title: "Évaluations 1ère Spé"
---
# 1ere Spe : Correction de l'interrogation n°2

## 📘 Correction : Sujet B

## Corrigé de l'exercice 1
1. On a : $$\frac{(4+h)^2-6(4+h)-4^2+24}{h}=\frac{16+8h+h^2-24-6h-16+24}{h}
=\frac{h^2+2h}{h}=\frac{h(h+2)}{h}=h+2$$

2. On a $$\frac{f(4+h)-f(4)}{h}=\frac{(4+h)^2-6(4+h)-(4^2-6\times 4)}{h}=\frac{(4+h)^2-6(4+h)-4^2+24}{h}=h+2
$$. 

De plus $\displaystyle\lim_{h\mapsto 0}  (h+2)=2$, on en déduit que $f$ est dérivable en $4$ et on a $f'(4)=2$. 

---
## Corrigé de l'exercice 2

On a : $g(x)=\sqrt{x+9}$.
1. $(\sqrt{9+h}-3)(\sqrt{9+h}+3)=(\sqrt{9+h})^2-3^2=9+h-9=h$
2. 
$$ \frac{g(0+h)-g(0)}{h}=\frac{\sqrt{h+9}-3}{h}
   =\frac{(\sqrt{h+9}-3)(\sqrt{h+9}+3)}{h(\sqrt{h+9}+3)}
=\frac{h}{h(\sqrt{h+9}+3))}
   =\frac{1}{\sqrt{h+9}+3}$$



3. On a :

$$\lim_{h\mapsto 0} \frac{g(0+h)-g(0)}{h} 
 =\lim_{h\mapsto 0} \frac{1}{\sqrt{h+9}+3} 
=\frac{1}{\sqrt{0+9}+3}
   =\frac{1}{6}$$
   
---
## Corrigé de l'exercice 3
Pour $x\neq -1$ on $f(x)=-\dfrac{4}{x-2}$.
1. a) Le taux de variation de $f$ entre $1$ et $1+h$ est : 
 $$\frac{f(1+h)-f(1)}{h}
=\frac{1}{h}\Big(-\frac{4}{h-1}-4\Big)
=\frac{1}{h}\Big(\frac{-4}{h-1}-\frac{4(h-1)}
{h-1}\Big)
=\frac{1}{h}\Big(\frac{-4-4h+4}{h+1}\Big)
=\frac{1}{h}\Big(\frac{-4h}{h-1}\Big)
=\frac{-4}{h-1} $$

 b) On a : 

 $$
 \lim_{h\mapsto 0} \frac{f(1+h)-f(1)}{h} 
 =\lim_{h\mapsto 0} \frac{-4}{h-1} 
=\frac{-4}{0-1}
=4
 $$

On en déduit que $f$ est dérivable en $1$ et on a $f'(1)=4$.

2. On a pour tout $h\neq 0$ :
$$\frac{g(2+h)-g(2)}{h}=\frac{(2+h)^2-5(2+h)-(2^2-5\times 2)}{h}
=\frac{4+4h+h^2-10-5h-4+10}{h}
=\frac{h^2-h}{h}
=\frac{h(h-1)}{h}=h-1$$

$\displaystyle\lim_{h\mapsto 0} \frac{g(2+h)-g(2)}{h}=\lim_{x\mapsto 0} (h-1)=-1$

On en déduit que $g$ est dérivable en $2$ et on a : $g'(2)=-1$.

## Corrigé de l'exercice 4
On a $f(x)=\frac{1}{x^2}$.

1. Pour $h\neq 0$ et $h\neq -1$, on a :
$$\frac{f(2+h)-f(2)}{h} 
 = \frac{1}{h}\Big(\frac{1}{(2+h)^2}-\frac{1}{4}\Big) 
 = \frac{1}{h}\Big(\frac{4}{4(2+h)^2}-\frac{(2+h)^2}{4(h+2)^2}\Big)
 =\frac{1}{h}\Big(\frac{4-(4+4h+h^2)}{4(2+h)^2}\Big)
 =\frac{1}{h}\Big(\frac{-4h-h^2}{4(2+h)^2}\Big)
 = \frac{1}{h}\Big(\dfrac{h(-4-h)}{4(2+h)^2}\Big) 
 = \frac{-4-h}{4(2+h)^2}
$$
2. On a :
   $$\lim_{h\mapsto 0} \frac{f(2+h)-f(2)}{h} 
=\lim_{h\mapsto 0} \frac{-4-h}{4(2+h)^2} 
=\frac{-4-0}{4(2+0)^2}
=\frac{-4}{16}
   =-\frac{1}{4}$$
<script src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
