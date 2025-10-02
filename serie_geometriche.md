# Formulario Serie Geometriche Finite

In questo documento trovi ogni formula scritta **sia in LaTeX** (per chi usa GitHub da browser)
che in **plain text** (leggibile anche su app GitHub iOS).

---

## 1. Somma semplice

**LaTeX:**
$$
\sum_{i=0}^{k-1} q^i = \frac{q^k - 1}{q - 1}, \quad q \neq 1
$$

**Plain text:**
```
∑_{i=0}^{k-1} q^i = (q^k - 1) / (q - 1),   q ≠ 1
```
Se q = 1, la somma è semplicemente k.

---

## 2. Somma con indice a partire da 1

**LaTeX:**
$$
\sum_{i=1}^{k} q^i = \frac{q^{k+1} - q}{q - 1}, \quad q \neq 1
$$

**Plain text:**
```
∑_{i=1}^{k} q^i = (q^{k+1} - q) / (q - 1),   q ≠ 1
```

---

## 3. Somma con fattore lineare sull’indice

**LaTeX:**
$$
\sum_{i=0}^{k-1} i \, q^i = \frac{q - k q^k + (k-1)q^{k+1}}{(1-q)^2}, \quad q \neq 1
$$

**Plain text:**
```
∑_{i=0}^{k-1} i q^i = (q - k q^k + (k-1) q^{k+1}) / (1 - q)^2,   q ≠ 1
```

---

## 4. Somma con indice quadratico

**LaTeX (ordine di grandezza):**
$$
\sum_{i=0}^{k-1} i^2 q^i = \Theta(k^2 q^k), \quad q > 1
$$

**Plain text:**
```
∑_{i=0}^{k-1} i^2 q^i = Θ(k^2 q^k),   q > 1
```

---

# Casi particolari

### Per q = 2

**LaTeX:**
$$
\sum_{i=0}^{k-1} 2^i = 2^k - 1
$$

**Plain text:**
```
∑_{i=0}^{k-1} 2^i = 2^k - 1
```

---

### Per q = 3

**LaTeX:**
$$
\sum_{i=0}^{k-1} 3^i = \frac{3^k - 1}{2}
$$

**Plain text:**
```
∑_{i=0}^{k-1} 3^i = (3^k - 1) / 2
```

---

### Per q = 1/2

**LaTeX:**
$$
\sum_{i=0}^{k-1} \left(\tfrac{1}{2}\right)^i = 2\left(1 - \frac{1}{2^k}\right)
$$

**Plain text:**
```
∑_{i=0}^{k-1} (1/2)^i = 2 (1 - 1/2^k)
```
