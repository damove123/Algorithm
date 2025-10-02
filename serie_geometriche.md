# Formulario Serie Geometriche Finite

## 1. Somma semplice
\[
\sum_{i=0}^{k-1} q^i = \frac{q^k - 1}{q - 1}, \quad q \neq 1
\]

Se \(q = 1\), la somma è semplicemente \(k\).

---

## 2. Somma con indice a partire da 1
\[
\sum_{i=1}^{k} q^i = \frac{q^{k+1} - q}{q - 1}, \quad q \neq 1
\]

---

## 3. Somma con fattore lineare sull’indice
\[
\sum_{i=0}^{k-1} i \, q^i = \frac{q - k q^k + (k-1)q^{k+1}}{(1-q)^2}, \quad q \neq 1
\]

---

## 4. Somma con indice quadratico
Formula più lunga, ma ordine di grandezza:
\[
\sum_{i=0}^{k-1} i^2 q^i = \Theta(k^2 q^k), \quad q > 1
\]

---

# Casi particolari

- Per \(q = 2\):  
\[
\sum_{i=0}^{k-1} 2^i = 2^k - 1
\]

- Per \(q = 3\):  
\[
\sum_{i=0}^{k-1} 3^i = \frac{3^k - 1}{2}
\]

- Per \(q = \tfrac{1}{2}\):  
\[
\sum_{i=0}^{k-1} \left(\tfrac{1}{2}\right)^i = 2\left(1 - \frac{1}{2^k}\right)
\]
