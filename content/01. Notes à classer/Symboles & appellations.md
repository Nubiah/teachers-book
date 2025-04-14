---
tags:
  - quantificateur
  - ensemble
  - probabilité
title: Symboles & appellations
draft: true
---
# Quantificateurs
- $\forall$ : 
# Ensemble
## Bibliographie
- Vidéo sur la théorie des ensembles Bac+1 : https://youtu.be/EJ3TxWaVyFw
## Généralités
- $Card(E)$ : Cardinal = nombre d'élément(s) d'un ensemble
- Un ensemble contenant un seul élément est un *singleton*, avec deux éléments c'est une *paire*
	- Attention, une paire $\neq$ un couple. Paire : {a,b} = {b,a}, couple : (a,b) $\neq$ (b,a)
- Deux ensembles sont *égaux* s'ils ont exactement les mêmes éléments, peu importe l'ordre 
	- E {1, 2, 3} = F {2, 1, 3}
- On dit que E est *inclus* dans G si tous les éléments de E sont des éléments de G
	- Lorsqu'un ensemble E est inclus dans F, on dit que E est un *sous-ensemble (une partie)* de F
	- On l'écrit $E\subset F$, E est inclus dans F
	- Il existe aussi le symbole $\subseteq$ qui correspond à une *inclusion large* si c'est spécifié
- On appelle l'*ensemble des parties*, noté $P(E)$, l'ensemble de tous les ensembles inclus dans un ensemble.
	- Pour faire simple toutes les compositions possibles avec les éléments d'un ensemble
	- $P(E)=$ {$A|A\subset E$}
	- $\varnothing\in P(E)$
	- $E\in P(E)$
	- $A\in P(E)\leftrightarrow A\subset E$
		- *Exemples* : 
			- P({1}) = {$\varnothing$,{1}}
			- P({1,2}) = {$\varnothing$, {1},{2},{1,2}}
## Définitions
Trois méthodes de définition
- Définition en extension 
	- E = {1, 2, 3}
- Définition par un diagramme de Venn
- Définition en compréhension : on donne une propriété que les éléments de l'ensemble doivent vérifier
	- $E=n\in\mathbb{N}\ |\ 1\leq n\leq{3}$
# Probabilité
- $P_B(A)$ : probabilité de A sachant B
- $P\left(A\cap B \right)$ : probabilité de A inter B. C'est uniquement l'intersection entre l'évènement A et B
- $P(A\cup B)$ : probabilité de A union B. C'est l'évènement A et l'évènement B, en ne comptant pas deux fois l'intersection