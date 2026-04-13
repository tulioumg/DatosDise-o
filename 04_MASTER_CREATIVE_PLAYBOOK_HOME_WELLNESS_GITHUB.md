import os

content = """# MANUAL DE INSTRUCCIONES ESTRICTAS: GENERACIÓN DE DISEÑO DE ALTO IMPACTO
## Objetivo: Replicar el estilo visual de "Minimalismo de Autor" (Jerarquía, Contraste y Metáfora)

Este documento contiene las reglas de oro para que el GPT genere imágenes que sigan exactamente el estilo de las referencias adjuntas: fondos limpios, tipografía masiva y metáforas visuales potentes.

---

## 1. REGLAS DE ORO DE COMPOSICIÓN (STRICT RULES)
* **Formato:** Siempre cuadrado (1:1), 1050 x 1050 px.
* **Espacio Negativo:** El 60-70% de la imagen debe estar vacío (aire). El contenido debe estar estrictamente centrado.
* **Velocidad de Lectura:** El usuario debe entender el mensaje en 2 segundos.
* **Fondo:** Sólido absoluto. Blanco puro (`#FFFFFF`), Negro puro (`#000000`) o Gris Neutro. Sin texturas, sin ruido, sin degradados.

---

## 2. SISTEMA TIPOGRÁFICO Y RESALTE
* **Fuente Principal:** Sans-Serif masiva, Extra Bold, geométrica (estilo Montserrat o Inter).
* **El Bloque de Resalte (The Highlight Box):** * Una palabra clave o la frase final DEBE estar encerrada en un rectángulo sólido de color vibrante (Verde Neón, Amarillo, Rojo o Azul).
    * El texto dentro del bloque debe ser Negro sobre fondo de color, o Blanco sobre fondo oscuro.
* **Jerarquía:** El titular es lo más grande. El subtexto o firma debe ser significativamente más pequeño y minimalista.

---

## 3. ESTILOS VISUALES PERMITIDOS (MÉTODOS)

### MÉTODO A: El Icono Lineal (Flat Line Art)
* Uso de un icono vectorial 2D en la parte superior.
* Trazos limpios, sin relleno o con relleno sólido simple.
* Ejemplo: Un corazón con una mano, un caracol, una diana.


---

## 4. PROHIBICIONES TOTALES (RED FLAGS)
* **NO** usar fotos de personas reales.
* **NO** usar más de 3 colores en total por imagen.
* **NO** usar fuentes con serifa (decorativas) para el cuerpo principal.
* **NO** añadir elementos decorativos (estrellitas, marcos, garabatos) que no tengan una función comunicativa.
* **NO** usar degradados en el fondo.

---

## 5. PROMPT TÉCNICO MAESTRO PARA DALL-E
Para generar estas imágenes, el GPT debe usar esta estructura de prompt:

> "A square social media graphic, 1050x1050. Solid [Color] background. Center-aligned composition. In the center, a [Metaphor: 3D matte object or 2D vector icon]. Above/Below it, bold sans-serif typography. One specific word or phrase must be inside a solid [Accent Color] rectangular box. High contrast, high-end professional graphic design, minimalist aesthetic, extreme negative space, maximum readability, no clutter."

---

## 6. CHECKLIST DE CALIDAD PRE-SALIDA
1. ¿El fondo es un color sólido único?
2. ¿Hay una palabra resaltada en un bloque de color?
3. ¿La tipografía es Bold y Sans-Serif?
4. ¿Hay mucho espacio libre alrededor de los elementos?
5. ¿La imagen se ve "cara" y profesional (minimalista)?
"""

file_path = "manual-diseno-instrucciones-estrictas.md"
with open(file_path, "w", encoding="utf-8") as f:
    f.write(content)

print(file_path)
