---
tags:
  - démonstration
  - pascal
  - combinaison
  - factorielle
title: Formule de Pascal
draft: false
---
>[!note] **Enoncé**
> Pour tout entier naturel $p$ tel que $0\leq p\leq n$ : $(^n_{p})+(^n_{p+1})=(^{n+1}_{p+1})$

>[!check] **Notions impliquées**
>- Définition d'une combinaison : $(^n_{p})=(^{n!}_{p!(n-p!)})$
>- Définition factorielle

# Démonstration
On a $(^n_{p})+(^n_{p+1})=\frac{n!}{p!(n-p)!}+\frac{n!}{(p+1)!(n-(p+1))!}=\frac{n!}{p!(n-p)!}+\frac{n!}{(p+1)!(n-p-1))!}$

Donc :
- $(^n_{p})+(^n_{p+1})=\frac{n!}{p!(n-p)!}+\frac{n!}{(p+1)!(n-p-1))!}$ Or $(p+1)! =p!(p+1)$ et $(n-p)! =(n-p-1)!(n-p)$
- $(^n_{p})+(^n_{p+1})=\frac{n!}{p!(n-p-1)!(n-p)}+\frac{n!}{p!(p+1)(n-p-1)}$
- $(^n_{p})+(^n_{p+1})=\frac{n!}{p!(n-p-1)!}*\left( \frac{1}{n-p}+\frac{1}{p+1} \right)$
- $(^n_{p})+(^n_{p+1})=\frac{n!}{p!(n-p-1)!}* \frac{p+1+n-p}{(n-p)(p+1)}$
- $(^n_{p})+(^n_{p+1})=\frac{n!}{p!(n-p-1)!}+\frac{n+1}{(n-p)(p+1)}$
- $(^n_{p})+(^n_{p+1})=\frac{n!(n+1)}{p!(n-p-1)!(n-p)(p+1)}$ Or $(p+1)! =p!(p+1)$ et $(n-p)! =(n-p-1)!(n-p)$
- $(^n_{p})+(^n_{p+1})=\frac{(n+1)!}{(p+1)!(n-p)!}$

Et selon la définition des combinaisons, $(^{n+1}_{p+1})=\frac{(n+1)!}{(p+1)!(n+1-(p+1))!}=\frac{(n+1)!}{(p+1)!(n-p)!}$