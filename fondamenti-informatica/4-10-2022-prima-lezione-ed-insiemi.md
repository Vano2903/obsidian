# INSIEMI E MATEMATICA DISCRETA
---
##### 4 Oct 2022
_Davide Vanoncini_

##### tags: #insiemi #matematica
---

## Matematica Discreta
La matematica discreta é quella matematica che usa un set di valori finiti o un inintiá numerabile

**Discreto**:  Tutto ció che é finito e misurabile
**Continuo**: Tutto ció che é incommensurabile

É possibile rendere un sistema continuo un sistema discreto usando l'**approssimazione** (anche detto campionamento), esso consiste nel dividere il sistema continuo in piccoole parti contabili e misurabili.

Esempi:
- Quando facciamo una foto di qualcosa stiamo approssimando la scena utilizzando dei blocchi che assumono un colore singolo (pixel) nonostante la materia sia formata da elementi ben piú piccoli dei pixel.

- Quando ascoltiamo la musica da un file mp3 stiamo ascoldando un onda sonora resa quadrata in modo che sia contabile ogni valore 
	![[../_assets/campionamento_suono.webp]]



---

## Insiemi
Gli insiemi piú noti/importanti:

- Naturali $\mathbb{N}$  : 
	Interi positivi $[0, +\infty]$
	Ha un **limite inferiore**, ovvero un numero piú piccolo di tutti ($0$) ma <u>**non ha**</u> un limite **superiore** (quindi é un insieme infinito)
	
	- I numeri naturali hanno uno $0$ (valore nullo)
	- ogni elemento $n \in \mathbb{N}, n \neq 0$ ha un successore $s(\mathsf{n})$
	- $0$ non é il successore di nessun numero
	- 2 elementi diversi hanno sempre successori diversi 
		- $n_{1} \neq n_{2} \Rightarrow s(n_{1}) \neq s(n_{2})$ 

- Interi $\mathbb{Z}$:
	Insieme dei numeri naturali con l'aggiunta dei segni + e -
	<u>Non ha</u> **ne limiti inferiori ne limiti superiori** ($-\infty$, +$\infty$)

	$\mathbb{N} \subseteq \mathbb{Z}$

- Razionali $\mathbb{Q}$:
	 Indica l'insieme delle proporzioni (tutti quei numeri ottenibili attraverso la divisione di due numeri interi)

	$n,m \in \mathbb{Z}, \frac{n}{m} \in \mathbb{Q}$ 

	I numeri razionali sono **densi** ovvero c'é sempre un numero in mezzo ad altri 2 numeri
	$a - c - b \Rightarrow c = \frac{a+b}{2}$ 

- Irrazionali $\mathbb{I}$ :
	É l'insieme di numeri che non sono esprimibili come frazioni di 2 interi (decimali infiniti e non periodici)

	$i.e$ 
		$\sqrt{2}, e$

- Reali $\mathbb{R}$: 
	$\mathbb{R} = \mathbb{Q} \cup \mathbb{I}$

- Complessi $\mathbb{C}$: 
	L'insieme dei complessi estende l'insieme $\mathbb{R}$ per permettere operazioni non definite altrimenti

	Si basa sulla combinazione tra 2 numeri reali e la $i$ che rappresenta l'unitá immaginaria: $i = \sqrt{-1}$  

	un numero complesso quidi é $a, b \in \mathbb{R}$ composto come $a + bi$ 
	dove la parte con $bi$ si dice immaginaria.

- Booleani $\mathbb{B} = \{0,1\}$:


Inoltre alcuni insiemi sono **discreti** quindi sono **finiti** e **contengono spazi vuoti** mentre gli **insiemi continui** **<u>non</u>** contengono **spazi vuoti** e sono **infinit** 

| insiemi discreti             | insiemi continui         |
| ---------------------------- | ------------------------ |
| naturali $\mathbb{N}$        | razionali $\mathbb{Q}$   |
| interi $\mathbb{Z}$          | irrazionali $\mathbb{I}$ |
| booleani $\mathbb{B}$        | reali $\mathbb{R}$       |
| insiemi finiti $\{1,5,6,9\}$ | complessi $\mathbb{C}$   |




