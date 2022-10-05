# ANALISI
---
##### 4 Oct 2022
_Davide Vanoncini_

##### tags: #insiemi #matematica #notazioni
---

## Notazioni
- $A, B, C$ = tutte le lettere **maiuscole** rappresentano un **insieme**
- $a, b, c$ = tutte le lettere **minuscole** rappresentano un **elemento**
- $:$ = il "due punti" vuole dire **tale/i che** 
- $\in$ = **appartiene** 
	$i.e$
	$a \in A$ significa "un elemento $a$ appartenente all'insieme $A$"
- $\notin$ = **non appartiene**
	$i.e$
	$a \notin A$ singifica "un elemento $a$ non appartenente all'insieme $A$"
- $\subset$ = **sottoinsieme**
	$i.e$
	$A \subset B$ significa "l'insieme $A$ é un sottoinsieme di $B$"
	$A = \{1,2,3\}$
	$B = \{1,2,3,4,5,6\}$
	In questo caso $A$ é un sottoinsieme di $B$ visto che tutti gli elementi di $A$ sono contenuti in $B$
- $\subseteq$ = **sottoinsieme stretto**
	$i.e$
	$A \subset B$ significa "l'insieme $A$ é un sottoinsieme o equivalente di $B$"
	$A = \{1,2,3\}$
	$B = \{1,2,3\}$
	In questo caso $A$ é equivalente $B$ visto $A$ e $B$ hanno gli stessi elementi
- $\not\subset$ = **non é sottoinsieme**
	$i.e$
	$A \not\subset B$ significa "l'insieme $A$ non é un sottoinsieme di $B$"
	$A = \{7,8,9\}$
	$B = \{1,2,3,4,5,6\}$
	In questo caso $A$ non é sottoinsieme di $B$ visto che nessun elemento di $A$ é contenuto in $B$
	**Peró é possibile che i due insiemi siano uguali**
- $\nsubseteq$ = **non é sottoinsieme stretto**
	$i.e$
	$A \subset B$ significa "l'insieme $A$ non é sottoinsieme o equivalente a $B$"
	$A = \{4,5,6\}$
	$B = \{1,2,3\}$
	In questo caso $A$ non é sottoinsieme $B$ visto $A$ e $B$ non hanno nessun elementi in comune ed é **impossibile** che i due insiemi siano uguali
- $\cup$ = **unione**
	Matematicamente: $A \cup B = \{x \in A \;o \;x \in B \}$
	Ovvero tutti gli elementi che sono sia dell'insieme $A$ che dell'insieme $B$
	![[Pasted image 20221005162359.png]]
- $\cap$ = intersezione
	Matematicamente: $A \cap B = \{x \in A \; e \; x \in B\}$ 
	Ovvero tuttli gli elementi che sono sia dell'insieme $A$ che dell'insieme $B$ 
	![[Pasted image 20221005162619.png]]
- \\ = **differenza**
	Matematicamente: $A$ \ $B = \{ x \in A \; \exists \; x \notin B\}$ 
	Proprietá:
	- $A - A = \emptyset$
	- $A - \emptyset = A$
	![[Pasted image 20221005164345.png]]
- $(a,b)$ = **coppia ordinata**
	$(a,b) \neq (b,a)$
- $\times$ = **prodotto cartesiano**
	Matematicamente: $A \times B = \{(a,b) : a \in A \wedge b \in B\}$
	$i.e$
	$A = \{1,2\}$
	$B = \{x,y\}$
	$A \times B = \{(1,x), (2,x), (1,y), (2,y)\}$	
- $|A|$ = **cardinalitá**
	Il simbolo del valore assoluto $|\;|$ se usato con all'iterno un insieme ne indica la sua cardinalitá ovvero il numero di elementi contenuti dall'insieme
	$i.e$
	$A = \{1,2,5\}$
	$|A| = 3$

	Proprietá: 
	La cardinalitá di un prodotto cartesiano é la moltiplicazione tra il prodotto cartesione del primo insieme e quello del secondo:
	$|A\times B| = |A| \times |B|$
- $\mathcal{P}(A)$ = **insiemi delle parti**
	L'insiemi delle parti indica tutti gli insiemi possibili che si possono comporre dato un isieme di partenza.
	$i.e$
	$A = \{1,2,3\}$
	$\mathcal{P}(A) = \{\{1,2,3\}, \{1,2\}, \{1,3\}, \{2,3\}, \{1\},\{2\},\{3\},\emptyset\}$ 

	Proprietá:
	il numero di insiemi possibli ottenibili da un insieme é dato da 2 elevato alla cardinalitá dell'insieme studiato.
	$|\mathcal{P}| = 2^{|A|}$

	Questo perché non é possibile ottenere un  sottoinsieme da un insieme di partenza, se ne otterranno sempre 2:
	$A = \{1,2,3\}$ se proviamo a divere l'insieme A in un qualisiasi sottoinsieme otterremmo $B = \{1,2\} \wedge C = \{3\}$


## Come scrivere un insiemi
Gli insiemi si possono scrivere in 2 modi:
- **per esteso** / elenco
	La notazione per esteso prevede la **definizione di tutti gli elementi** contenuti all'iterno dell'insieme
	
	$i.e:$ 	
	$A = \{1,2,3,4,5\}$
	In questo insieme sono stati definiti tutti i 5 elementi dell'insieme

- **per definizione delle proprietá**
	La notazione per definizioni richiede di scrivere la **proprietá degli elementi dell'insieme** ma **senza scrivere** effettivamente **gli elementi**.

	Si parte sempre da un insieme di partenza noto alla quale applicare i "filtri" definiti.

	$i.e:$
	$A = \{ x \in \mathbb{N}: x \bmod 2 = 0 \}$ 
	In questo caso stiamo definendo che l'insieme $A$ contiene tutti gli elementi dell'insieme dei numeri naturali $\mathbb{N}$ tali che $x$ modulo $2$ sia $0$ ovvero tutti i numeri pari.

