---
published: true
---


# Relación Binaria

## Definición

Una relación binaria es un subconjunto del producto cartesiano entre dos conjuntos. 

Formalmente:

Si $A$ y $B$ son conjuntos, $R \subseteq A \times B$ es una relación binaria. $R$ es un conjunto formado por pares ordenados $(a,b)$ donde $a \in A$ y $b \in B$.

La expresión $a\,R\,b$ es equivalente a $(a,b) \in R$.

La relación binaria también puede estar definida sobre el mismo conjunto (los conjuntos $A$ y $B$ serían iguales: $A=B$), lo que se denomina como relación binaria sobre un conjunto $A$.

### Relación binaria inversa

Dado una relación binaria $R$ sobre los conjuntos $A$ y $B$, $R^{-1}$ es la relación binaria inversa de $R$. La relación binaria inversa verifica que: $a \, R^{-1} \, b \Leftrightarrow a \, R \, b$.

$R^{-1}$ puede ser calculada simplemente volteando el orden de los pares: $$R^{-1} = \{ (b,a) | (a,b) \in R \}$$.

## Ejemplo

$$A = \{1,2,3\}, B = \{x,y\}$$

Una posible relación binaria de $A$ y $B$ podría ser:
$$R = \{(1,x),(2,y)\}$$

{% include math.html %}