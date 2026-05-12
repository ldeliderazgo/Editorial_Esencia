
METADATOS DEL PROYECTO — Editorial Esencia
Archivo: {slug}_metadatos.yaml
Ubicación: carpeta raíz del proyecto (G:\...\Libros\{slug}\)

Este documento describe la estructura y el propósito del fichero de metadatos que acompaña a cada libro.
Se genera automáticamente al finalizar la Fase 1 y es la única fuente de verdad para todas las fases posteriores.

1. PROPÓSITO
Centraliza información que hasta ahora se dispersaba entre el Documento de Definición, variables sueltas en prompts y tablas externas.
Cualquier fase (redacción, edición, maquetación, portada) leerá este archivo y obtendrá de él los datos necesarios sin intervención humana.

2. ESTRUCTURA YAML
yaml
proyecto:
  slug: "dinero-medio-no-fin"
  titulo: "De 'El dinero es lo más importante' a 'El dinero es un medio, no un fin'"
  subtitulo: "Cómo pensar sobre dinero en economía real"
  autor: "Alejandro Fariña"
  coleccion: "De…A…"
  segmento: 1
  papel: "blanco"
  tinta_interior: "byn"
  anio_publicacion: 2026
  color_secundario: "#8B1A2B"
  extension_por_capitulo:
    capitulo_0: 800
    capitulo_1: 5500
    capitulo_2: 5000
    capitulo_3: 6000
    capitulo_4: 3500
    ...
3. REGLAS DE GENERACIÓN
Slug: Se deriva del título provisional eliminando acentos, pasando todo a minúsculas y sustituyendo espacios por guiones. Los signos de puntuación se eliminan. Longitud máxima recomendada: 50 caracteres.
Ejemplo: título De "El dinero es lo más importante" a "El dinero es un medio, no un fin" → slug dinero-medio-no-fin.

Color secundario: Se asigna automáticamente según la colección utilizando la siguiente tabla:

Colección	Color secundario
De…A…	#8B1A2B (granate)
Hazlo Tú	#2C3E50 (azul medio)
Galicia	#A67B5B (tierra)
Salud Invisible	#4A7C59 (verde salvia)
IA para…	#1A56DB (azul eléctrico)
La Nueva Resiliencia	#6B705C (verde oliva)
Vivir Más, Vivir Mejor	#1C3D5A (azul oscuro)
Hombres Mejor	#2D2D2D (gris grafito)
Aprender lo Útil	#D4A373 (beige tostado)
Trabajo Reinventado	#E05A2D (naranja energético)
**Extensión por capítulo:** Se genera automáticamente a partir de la tabla de extensión por bloques definida en el Documento de Definición. Para cada capítulo, se suma la extensión objetivo de todos sus bloques (H2) y se asigna el valor medio de la horquilla. El director editorial puede ajustar estas cifras manualmente si lo considera necesario.
Papel y tinta interior: Los valores por defecto son blanco y byn. El director editorial puede modificarlos manualmente en el fichero .yaml si un proyecto lo requiere (por ejemplo, papel crema para la colección Galicia o tinta color si el libro contiene ilustraciones en color).

4. USO EN LAS FASES
Fase 2 (Redacción): El prompt de redacción lee {slug}_metadatos.yaml para obtener automáticamente el título, la colección y el segmento. El redactor ya no necesita copiar y pegar esos datos manualmente.

Fase 3 (Edición): El editor consulta los metadatos para conocer el tono esperado según la colección, el título exacto del libro y el público objetivo (segmento). Así alinea su trabajo con la identidad editorial.

Fase 4 (Maquetación): El maquetador extrae del archivo YAML los campos: título, subtítulo, autor, colección, tipo de papel, tinta interior y color secundario. No se requieren datos adicionales por parte del director.

Fase 5 (Portada): Las dimensiones de la portada se calculan a partir del número de páginas generado en Fase 4, y tanto el color secundario como la colección se toman de este mismo archivo de metadatos. El diseñador sabe exactamente qué estilo aplicar.

**NUEVO (v1.5):** En la Fase 2 (Redacción), el redactor leerá el campo `extension_por_capitulo` para conocer la extensión objetivo de cada capítulo antes de empezar a escribir. Esta información se complementa con el desglose por bloques que viaja en el Documento de Definición y en el Handoff.

5. MODIFICACIONES POSTERIORES
Si durante la producción se decide cambiar el papel, la tinta o cualquier otro campo, solo se modifica este fichero. Todas las fases que se ejecuten a continuación leerán la versión actualizada automáticamente, sin necesidad de repetir información en prompts ni en conversaciones.

6. ARCHIVO DE EJEMPLO
Se incluye en la carpeta del proyecto un archivo real {slug}_metadatos.yaml con los datos completos del libro. Este archivo de ejemplo sirve como plantilla y como referencia visual para todo el equipo.

Documento de referencia para todo el equipo editorial.