# 8. ANÁLISIS DIMENSIONAL

---

## 8.1 ¿Qué es el análisis dimensional?

El análisis dimensional es una herramienta que permite estudiar las dimensiones de las magnitudes físicas.

Se utiliza para:

- verificar si una fórmula es correcta  
- analizar relaciones entre magnitudes  
- evitar errores en cálculos  

---

## 8.2 Dimensiones fundamentales

Son las magnitudes básicas de la física.

| Magnitud | Símbolo |
|---------|--------|
| Longitud | L |
| Masa     | M |
| Tiempo   | T |

---

## 8.3 Significado de letras en fórmulas

Cada letra representa una magnitud física.

---

### Velocidad

v = d / t  

- v: velocidad  
- d: distancia  
- t: tiempo  

---

### Aceleración

a = v / t  

- a: aceleración  
- v: velocidad  
- t: tiempo  

---

### Fuerza

F = m · a  

- F: fuerza  
- m: masa  
- a: aceleración  

---

### Densidad

ρ = m / V  

- ρ: densidad  
- m: masa  
- V: volumen  

---

### Trabajo

W = F · d  

- W: trabajo  
- F: fuerza  
- d: distancia  

---

### Potencia

P = W / t  

- P: potencia  
- W: trabajo  
- t: tiempo  

---

## 8.4 Formación de dimensiones

Se reemplazan las magnitudes por sus dimensiones.

---

### Velocidad

v = d / t  

d → L  
t → T  

v = L / T = L T⁻¹  

---

### Aceleración

a = v / t  

v → L T⁻¹  

a = (L T⁻¹) / T = L T⁻²  

---

### Fuerza

F = m · a  

m → M  
a → L T⁻²  

F = M L T⁻²  

---

### Densidad

ρ = m / V  

m → M  
V → L³  

ρ = M / L³ = M L⁻³  

---

### Trabajo

W = F · d  

F → M L T⁻²  
d → L  

W = (M L T⁻²) · L  

W = M L² T⁻²  

---

### Potencia

P = W / t  

W → M L² T⁻²  

P = (M L² T⁻²) / T  

P = M L² T⁻³  

---

## 8.5 Reglas del análisis dimensional

---

### A) Suma y resta

Solo se pueden sumar o restar magnitudes con la misma dimensión.

Correcto:

5 m + 3 m = 8 m  

Incorrecto:

5 m + 3 s  

---

### B) Homogeneidad dimensional

En una ecuación física correcta, ambos lados deben tener la misma dimensión.

Ejemplo correcto:

v = d / t  

Lado izquierdo:

v → L T⁻¹  

Lado derecho:

d / t → L / T = L T⁻¹  

Resultado:

L T⁻¹ = L T⁻¹  

---

Ejemplo incorrecto:

v = d · t  

Lado izquierdo:

L T⁻¹  

Lado derecho:

L T  

Resultado:

L T⁻¹ ≠ L T  

---

### C) Constantes

Los números y constantes no tienen dimensión.

Ejemplos:

2, 5, 10, π  

Ejemplo:

V = π · r² · h  

π no afecta la dimensión  

---

### D) Exponentes

Los exponentes son números sin dimensión.

Ejemplos:

L² → área  
L³ → volumen  
T⁻¹ → indica que está en el denominador  

Ejemplo:

v = d / t  

L / T = L T⁻¹  

---

## 8.6 Forma de resolver

Pasos:

1. Escribir la fórmula  
2. Reemplazar cada magnitud por su dimensión  
3. Convertir divisiones en exponentes negativos  
4. Comparar ambos lados  

---

## 8.7 Ejemplos completos

---

### Ejemplo 1

F = m · a  

Lado izquierdo:

F → M L T⁻²  

Lado derecho:

m · a → M · (L T⁻²) = M L T⁻²  

Resultado:

Correcto  

---

### Ejemplo 2

v = d · t  

Lado izquierdo:

v → L T⁻¹  

Lado derecho:

d · t → L T  

Resultado:

Incorrecto  

---

### Ejemplo 3

ρ = m / V  

Lado izquierdo:

ρ → M L⁻³  

Lado derecho:

m / V → M / L³ = M L⁻³  

Resultado:

Correcto  

---

### Ejemplo 4

W = F · d  

Lado izquierdo:

W → M L² T⁻²  

Lado derecho:

F · d → (M L T⁻²) · L = M L² T⁻²  

Resultado:

Correcto  

---

## 8.8 Dimensiones importantes

| Magnitud | Dimensión |
|---------|----------|
| Velocidad | L T⁻¹ |
| Aceleración | L T⁻² |
| Fuerza | M L T⁻² |
| Densidad | M L⁻³ |
| Trabajo | M L² T⁻² |
| Potencia | M L² T⁻³ |
| Presión | M L⁻¹ T⁻² |

---

## 8.9 Conclusión

El análisis dimensional permite:

- verificar ecuaciones  
- detectar errores  
- comprender relaciones físicas  

Es una herramienta fundamental en física.
