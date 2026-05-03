
# Tema 09: Vectores

## Introducción

En física existen magnitudes que no solo requieren un valor numérico y una unidad, sino también una dirección y un sentido para quedar completamente definidas. Estas magnitudes reciben el nombre de **vectores**.

Los vectores permiten representar fenómenos donde importa hacia dónde actúa una cantidad física y cómo se comporta en el espacio.

Se utilizan frecuentemente en:

- fuerzas aplicadas sobre cuerpos  
- velocidad de un móvil  
- aceleración de una partícula  
- desplazamiento de objetos  
- campos eléctricos y magnéticos  

Por esta razón, el estudio de vectores es fundamental en física, matemáticas e ingeniería.

---

## Definición

Un vector es una magnitud que posee:

- módulo o magnitud  
- dirección  
- sentido  

Generalmente se representa mediante una flecha.

A = -------->

---

## Representación de un Vector

Un vector se representa gráficamente mediante un segmento orientado.

```svg
<svg width="900" height="420" viewBox="0 0 900 420" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <marker id="arrow" markerWidth="12" markerHeight="12" refX="10" refY="6" orient="auto">
      <path d="M0,0 L12,6 L0,12 Z" fill="#111"/>
    </marker>
    <marker id="arrowBlue" markerWidth="12" markerHeight="12" refX="10" refY="6" orient="auto">
      <path d="M0,0 L12,6 L0,12 Z" fill="#2563eb"/>
    </marker>
  </defs>

  <rect width="100%" height="100%" fill="white"/>

  <text x="285" y="35" font-size="28" font-family="Arial" font-weight="bold">
    Partes de un Vector
  </text>

  <line x1="100" y1="320" x2="800" y2="320" stroke="#888" stroke-width="2" marker-end="url(#arrow)"/>
  <line x1="100" y1="320" x2="100" y2="60" stroke="#888" stroke-width="2" marker-end="url(#arrow)"/>

  <text x="810" y="325" font-size="18" font-family="Arial">x</text>
  <text x="90" y="55" font-size="18" font-family="Arial">y</text>

  <line x1="100" y1="320" x2="620" y2="140"
        stroke="#111" stroke-width="4"
        marker-end="url(#arrow)"/>

  <circle cx="100" cy="320" r="5" fill="#111"/>

  <text x="55" y="345" font-size="18" font-family="Arial">Origen</text>
  <text x="630" y="145" font-size="18" font-family="Arial">Extremo</text>

  <line x1="180" y1="365" x2="580" y2="225"
        stroke="#2563eb" stroke-width="2"
        marker-start="url(#arrowBlue)"
        marker-end="url(#arrowBlue)"/>

  <text x="350" y="285" font-size="20" fill="#2563eb" font-family="Arial">Módulo</text>

  <text x="430" y="90" font-size="20" font-family="Arial">Dirección</text>
  <line x1="490" y1="100" x2="540" y2="125"
        stroke="#111" stroke-width="2"
        marker-end="url(#arrow)"/>

  <text x="645" y="105" font-size="20" font-family="Arial">Sentido</text>
  <line x1="705" y1="115" x2="645" y2="135"
        stroke="#111" stroke-width="2"
        marker-end="url(#arrow)"/>

  <path d="M180 320 A80 80 0 0 0 170 290"
        fill="none" stroke="#dc2626" stroke-width="3"/>

  <text x="185" y="295" font-size="22" fill="#dc2626" font-family="Arial">θ</text>

  <text x="215" y="375" font-size="20" fill="#dc2626" font-family="Arial">
    Dirección expresada mediante ángulo
  </text>
</svg>
````

---

## Partes del Vector

### Origen

Es el punto donde inicia el vector.

### Extremo

Es el punto final donde termina la flecha.

### Módulo

Es la longitud del vector y representa su tamaño.

### Dirección

Es la orientación del vector y normalmente se expresa mediante un ángulo medido respecto a un eje de referencia.

### Sentido

Indica hacia dónde apunta la flecha.

---

## Magnitud Escalar y Magnitud Vectorial

### Magnitud Escalar

Es aquella magnitud física que queda completamente determinada solo con un valor numérico y su unidad.

No necesita dirección ni sentido.

#### Ejemplos

* masa = 8 kg
* tiempo = 12 s
* temperatura = 25 °C
* energía = 300 J

---

### Magnitud Vectorial

Es aquella magnitud física que necesita:

* valor numérico
* unidad
* dirección
* sentido

#### Ejemplos

* fuerza = 20 N hacia la derecha
* velocidad = 15 m/s al norte
* aceleración = 3 m/s² hacia abajo
* desplazamiento = 10 m al este

---

## Diferencia Principal

Escalar   = valor + unidad

Vectorial = valor + unidad + dirección + sentido

---

## Resumen

Los vectores son magnitudes físicas con módulo, dirección y sentido. Se diferencian de las magnitudes escalares porque estas solo necesitan valor y unidad.
