---
published: true
---

# Relación de orden

## Definición 

Una relación de orden es una [relación binaria](binary_relation.md) $R$ sobre un conjunto $M$ que verifica las propiedades de [reflexividad](#reflexividad), transitividad y antisimetría para cualquier combinación de elementos de $M$.

### Reflexividad

La propiedad de reflexividad indica que todo elemento de un conjunto $M$ está relacionado consigo mismo.

Formalmente, una relación $R$ es reflexiva si: $$ \forall x \in M:  x \, R \, x$$.


### Antisimetría

La propiedad de antisimetría indica que: para cualesquiera dos elementos $x,y$ de un conjunto $M$, si $x$ está relacionado con $y$ e $y$ está relacionado con $x$, necesariamente $x$ e $y$ tienen que ser iguales $x=y$. 

Formalmente, una relación $R$ es antisimétrica si: $$ \forall x,y \in M:  x \, R \, y \wedge x \neq y \to \neg (y \, R \, x) $$