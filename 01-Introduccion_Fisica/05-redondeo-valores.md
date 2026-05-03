# Tema 5: Redondeo de Valores

## Definición

Redondear consiste en aproximar un número decimal a una cantidad determinada de cifras decimales.

En estos apuntes se trabajará redondeando a **dos cifras decimales**.

---

## Importancia

El redondeo permite:

- Simplificar resultados numéricos.  
- Presentar respuestas claras.  
- Evitar exceso de decimales.  
- Expresar medidas correctamente.  

---

## Procedimiento General

Para redondear a dos decimales:

1. Se conserva hasta la segunda cifra decimal.  
2. Se observa la tercera cifra decimal.  
3. Según su valor, se modifica o conserva la segunda cifra decimal.

---

# Los 4 Casos de Redondeo

## Caso 1: La tercera cifra decimal es mayor que 5

La segunda cifra decimal aumenta en una unidad.

### Ejemplo

8.42931

La tercera cifra decimal es **9** (mayor que 5)

Resultado:

8.43

---

## Caso 2: La tercera cifra decimal es menor que 5

La segunda cifra decimal mantiene su valor.

### Ejemplo

9.43431

La tercera cifra decimal es **4** (menor que 5)

Resultado:

9.43

---

## Caso 3: La tercera cifra decimal es igual a 5 y la cifra anterior es par

La segunda cifra decimal se mantiene igual.

### Ejemplo

10.34591

La tercera cifra decimal es **5**  
La segunda cifra decimal es **4** (par)

Resultado:

10.34

---

## Caso 4: La tercera cifra decimal es igual a 5 y la cifra anterior es impar

La segunda cifra decimal aumenta en una unidad.

### Ejemplo

20.33591

La tercera cifra decimal es **5**  
La segunda cifra decimal es **3** (impar)

Resultado:

20.34

---

## Regla Especial Cuando Aparece 5

Si la tercera cifra decimal es exactamente **5**:

- Si la cifra anterior es **par**, se conserva.  
- Si la cifra anterior es **impar**, aumenta en uno.  

Esta regla reduce errores acumulados en muchos cálculos.

---

# Caso Especial: Cuando Hay Ceros Después del Punto Decimal

Cuando un número comienza con varios ceros después del punto decimal, como:

0.00341

los ceros no se toman como cifras significativas.  
Se busca la primera cifra diferente de cero y desde allí se aplica el redondeo.

### Ejemplo 1

0.00341

Resultado:

0.0034

### Ejemplo 2

0.00346

Resultado:

0.0035

### Ejemplo 3

0.000728

Resultado:

0.00073

---

## Más Ejemplos

| Número | Resultado |
|---|---|
| 6.728 | 6.73 |
| 4.321 | 4.32 |
| 7.455 | 7.46 |
| 9.445 | 9.44 |
| 3.995 | 4.00 |

---

## Aplicación en Física

Se recomienda mantener varios decimales durante el procedimiento y redondear al final.

Ejemplo:

v = 12.3467 m/s

Resultado:

v = 12.35 m/s

---

## Resumen

Para redondear a dos decimales se observa la tercera cifra decimal:

- Mayor que 5 → aumenta.  
- Menor que 5 → se conserva.  
- Igual a 5 → se aplica regla par o impar.  

Si hay varios ceros después del punto decimal, se trabaja desde la primera cifra significativa.

---

## Preguntas típicas de examen

1. ¿Qué es redondear?  
2. ¿Qué pasa si la tercera cifra decimal es menor que 5?  
3. ¿Qué pasa si es mayor que 5?  
4. ¿Qué ocurre si es exactamente 5?  
5. Redondee 10.345 a dos decimales.  
6. Redondee 0.00346 correctamente.
