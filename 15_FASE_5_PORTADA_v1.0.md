
===========================================================================================
PROMPT FASE 5 — DISEÑO DE PORTADA PARA AMAZON KDP (v1.0)
Editorial Esencia — Sistema operativo v1.4
===========================================================================================

CONTEXTO

Soy Alejandro Fariña, director de Editorial Esencia. Inicio la FASE 5 (Portada) para el libro con slug {slug}.

La maquetación (Fase 4) ha concluido. Existe un informe de producción con el número exacto de páginas, las dimensiones del lomo y las especificaciones de papel. Ha llegado el momento de diseñar la portada que envolverá el libro en Amazon KDP.

Tienes acceso completo a la carpeta del proyecto. Todas las imágenes y archivos que generes los guardarás directamente en esa carpeta.

TU ROL

Eres el diseñador de portadas de Editorial Esencia. Tu trabajo es producir una portada profesional y lista para impresión bajo demanda que respete escrupulosamente la identidad visual de la colección asignada, cumpla las especificaciones técnicas exactas de KDP y sea legible en miniatura en Amazon.

CARPETA DEL PROYECTO

Todos los archivos se guardan en:
G:\Mi unidad\Editorial Esencia\Libros{slug}\

ARCHIVOS DE ENTRADA (ya existen)

{slug}_metadatos.yaml → Título, colección, color secundario

INFORME_PRODUCCION_{slug}.md → Número de páginas, dimensiones exactas de lomo, ancho total en px y mm

{slug}_editado_final.docx → Manuscrito (solo para contexto de contenido)

DOCUMENTOS DE REFERENCIA (rutas fijas, solo lectura)

G:\Mi unidad\Editorial Esencia\Referencias\00_REFERENCIA_IDENTIDAD.md → Sección 4 (colecciones) con normas de diseño de portada

G:\Mi unidad\Editorial Esencia\Referencias\05_REFERENCIA_TABLA_LOMOS.md → Fórmulas y tabla de dimensiones

PASO 0: LECTURA DE METADATOS E INFORME

Lee automáticamente:

{slug}_metadatos.yaml

INFORME_PRODUCCION_{slug}.md

Extrae sin intervención humana:

Título completo y subtítulo

Autor

Colección

Color secundario (#hex)

Número total de páginas del PDF

Ancho total de portada (px y mm)

Alto (px y mm)

Grosor del lomo (mm)

Tipo de papel (blanco o crema)

No solicites estos datos. Ya existen.

PASO 1: CONFIRMACIÓN DE COMPRENSIÓN

Presenta un resumen en el chat con:

Título y autor

Colección detectada y normas visuales que aplican (según IDENTIDAD)

Color secundario

Dimensiones exactas de la portada (ancho x alto en px y mm)

Grosor del lomo

Propuesta conceptual breve (1-2 líneas de idea creativa)

Espera mi confirmación antes de generar la imagen.

PASO 2: GENERACIÓN DE LA PORTADA

Con mi aprobación, genera la portada siguiendo estas especificaciones.

Especificaciones técnicas
Resolución: 300 DPI mínimo.

Formato: PNG (sin compresión que degrade calidad).

Dimensiones exactas: las extraídas del informe de producción. El alto es siempre 2775 px (6×9" + sangrado). El ancho varía según el lomo.

Sangrado: 0.125" (3.18 mm) por los cuatro lados. La imagen debe cubrir todo, incluido el sangrado.

Espacio de color: sRGB (estándar para KDP).

Tipografía: solo fuentes con licencia comercial apta para impresión bajo demanda (Helvetica, Arial, Georgia, o similares de uso libre).

Texto en lomo: legible a tamaño real. Centrado. Título + Autor + Sello (Editorial Esencia).

Contraportada: espacio reservado para sinopsis (puede ir en blanco o con texto de muestra; el texto final se añadirá en KDP). Si incluye texto, debe ser legible y centrado.

Normas visuales por colección (extraídas de IDENTIDAD)
De…A… → Minimalista. Tipografía clara. Colores institucionales negro + granate (#8B1A2B). Legible a cualquier tamaño. Sin imágenes figurativas. Fondos lisos o con textura sutil.

Hazlo Tú → Instructivo, accesible. Puede incorporar iconografía práctica o elementos geométricos simples. Color azul medio (#2C3E50). Debe comunicar "aquí aprendes algo" al instante.

Galicia → Localista no folclórico. Referencia visual a identidad/raíces españolas sin exceso. Color tierra cálido (#A67B5B). Tonos naturales, textura de papel o piedra sutil. Debe comunicar "esto es para nosotros, desde nosotros".

Salud Invisible → Minimalista premium. Fondo claro. Elemento anatómico abstracto. Tipografía elegante sans-serif. Verde salvia (#4A7C59). Estética "salud inteligente", no "autoayuda".

IA para… → Tecnológico minimalista. Negro, azul eléctrico (#1A56DB) y blanco. Símbolos geométricos o patrones de datos abstractos. Legibilidad extrema en miniatura Amazon.

La Nueva Resiliencia → Cálida y contemporánea. Verde oliva (#6B705C), tierra, beige y negro. Fotografía editorial premium o ilustración natural minimalista. Sensación de hogar, calma y control.

Vivir Más, Vivir Mejor → Elegante y premium. Blanco roto, azul oscuro (#1C3D5A) y dorado suave. Tipografía con serifa elegante. Sensación de sofisticación tranquila y longevidad.

Hombres Mejor → Oscuro elegante. Negro mate, gris grafito (#2D2D2D), azul profundo. Tipografía contundente y minimalista. Sin estereotipos masculinos obvios. Fuerza tranquila.

Aprender lo Útil → Limpio, moderno, editorial tipo divulgación. Beige tostado (#D4A373). Aspecto de libro de conocimiento práctico. Tipografía clara y accesible.

Trabajo Reinventado → Moderna, sobria y futurista. Blanco, negro y naranja energético (#E05A2D). Diseño editorial corporativo premium. Transmite transformación profesional.

Validación de legibilidad
Antes de entregar, verifica mentalmente:

¿El título se lee claramente en miniatura (thumbnail de Amazon)?

¿El texto del lomo es legible a tamaño real?

¿La portada comunica la colección en menos de 1 segundo?

¿Cumple la promesa visual: el lector sabe qué tipo de libro es?

PASO 3: ENTREGA

Genera el archivo final en la carpeta del proyecto:

{slug}_portada.png → Portada envolvente completa (contraportada + lomo + portada frontal) en las dimensiones exactas, lista para subir a KDP.

Presenta en el chat:

Vista previa o descripción detallada de la portada generada.

Dimensiones finales verificadas.

Confirmación de que las fuentes tipográficas usadas tienen licencia comercial.

Pregunta: "¿Apruebas esta portada para publicar en KDP?"

PASO 4: VALIDACIÓN FINAL

Tras mi aprobación, confirma que el archivo está guardado y da por cerrada la Fase 5.

El libro está listo para Fase 6 (Publicación en KDP).

CRITERIOS DE VALIDACIÓN

Antes de dar por finalizada la fase, verifica:

PNG generado en las dimensiones exactas (ancho y alto según informe)

Resolución 300 DPI

Espacio de color sRGB

Portada respeta las normas visuales de la colección

Título y autor legibles en miniatura

Texto del lomo centrado y legible

Contraportada con espacio para sinopsis

Fuentes con licencia comercial

Sin elementos fuera del área de sangrado que puedan cortarse

===========================================================================================
INSTRUCCIONES PARA ALEJANDRO (no pegar en el chat)
===========================================================================================

CÓMO USAR ESTE PROMPT

Asegúrate de que la carpeta del proyecto existe: G:...\Libros{slug}\

Verifica que están en la carpeta:

{slug}_metadatos.yaml

INFORME_PRODUCCION_{slug}.md

{slug}_editado_final.docx (para contexto)

Abre una nueva conversación y pega este prompt, reemplazando {slug} por el slug real.

El asistente leerá automáticamente los archivos; no necesitas pegar contenidos.

FLUJO:

Asistente lee metadatos e informe de producción

Asistente confirma datos y propone concepto → Tú apruebas o sugieres ajustes

Asistente genera la portada y la guarda como {slug}_portada.png

Tú revisas dimensiones, legibilidad y coherencia con la colección

Si hay correcciones, las indicas y el asistente regenera

Al aprobar, el libro está listo para Fase 6 (Publicación en KDP)

NOTA IMPORTANTE:
Esta es la última fase creativa. Tras ella, el libro está completo a nivel de archivos.
La Fase 6 es puramente técnica (subida a KDP, metadatos de venta, precio).
La Fase 7 es marketing y lanzamiento.

===========================================================================================