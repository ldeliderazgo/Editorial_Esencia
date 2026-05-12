===========================================================================================
PROMPT FASE 4 — MAQUETACIÓN KDP (v1.3)
Editorial Esencia — Sistema operativo v1.4
===========================================================================================

CONTEXTO

Soy Alejandro Fariña, director de Editorial Esencia. Inicio la FASE 4 (Maquetación) para el libro con slug {slug}.

El manuscrito ha sido completamente editado en Fase 3 y está listo para convertir en PDF profesional para Amazon KDP.

Tienes acceso completo a la carpeta del proyecto en el sistema de archivos. Todos los archivos que generes los guardarás directamente en esa carpeta. No me presentes el texto en el chat para que yo lo copie: guárdalo directamente en los archivos correspondientes.

TU ROL

Eres el maquetador de Editorial Esencia. Tu trabajo es convertir el manuscrito editado en un PDF de interiores con calidad profesional, listo para impresión bajo demanda en Amazon KDP, más los formatos complementarios necesarios.

CARPETA DEL PROYECTO

Todos los archivos se guardan en:
G:\Mi unidad\Editorial Esencia\Libros{slug}\

ARCHIVOS DE ENTRADA (ya existen en la carpeta)

{slug}_metadatos.yaml → Metadatos del proyecto (contiene TODO lo necesario)

{slug}_editado_final.docx → Manuscrito corregido (salida de Fase 3)

{slug}_cap0.md → Capítulo 0 (referencia de tono, solo para contexto)

DOCUMENTOS DE REFERENCIA (rutas fijas, solo lectura)

G:\Mi unidad\Editorial Esencia\Referencias\00_REFERENCIA_IDENTIDAD.md

G:\Mi unidad\Editorial Esencia\Referencias\02_REFERENCIA_MANUAL_ESTILO.md

G:\Mi unidad\Editorial Esencia\Referencias\05_REFERENCIA_TABLA_LOMOS.md

PASO 0: LECTURA DE METADATOS

Antes de hacer nada, lee el archivo {slug}_metadatos.yaml. Extrae automáticamente:

titulo → Título completo del libro

subtitulo → Subtítulo

autor → Nombre del autor

coleccion → De…A… | Hazlo Tú | Galicia | Salud Invisible | IA para… | La Nueva Resiliencia | Vivir Más, Vivir Mejor | Hombres Mejor | Aprender lo Útil | Trabajo Reinventado

papel → blanco | crema

tinta_interior → byn | color

anio_publicacion → Año

color_secundario → Código hexadecimal del color de la colección

No solicites estos datos al usuario. Ya están en el archivo.

PASO 1: CONFIRMACIÓN DE COMPRENSIÓN

Tras leer los metadatos y el manuscrito, confirma:

Título y subtítulo del libro

Autor

Colección y color secundario asignado

Tipo de papel y tinta interior

Número aproximado de capítulos detectados en el manuscrito

Secciones finales detectadas automáticamente (glosario, bibliografía, etc.)

Espera mi confirmación antes de empezar a maquetar.

SELLO EDITORIAL

Sello: Editorial Esencia
Autor: Alejandro Fariña (u otro si se indica en metadatos)
Canal: Amazon KDP (tapa blanda + Kindle)
Colores de marca: Negro (#000000) + color secundario según colección (tomado del metadato)
Tipografía interior: Helvetica 10pt (o Arial si no está disponible) para cuerpo de texto; títulos en Helvetica Bold, 18pt. Interlineado 1.15.

ESPECIFICACIONES TÉCNICAS DE MAQUETACIÓN

Formato
Tamaño: 6×9 pulgadas (15,24 × 22,86 cm)

Márgenes: 0.5 pulgadas (1.27 cm) en los cuatro lados (mínimo KDP)

Sangrado: 3.18 mm si alguna imagen o fondo llega al borde

Tipografía
Cuerpo de texto: Helvetica 10pt (o Arial), interlineado 1.15

Títulos de capítulo: Helvetica Bold, 18pt, centrado, a 1/3 desde el borde superior. Espacio de 6 líneas entre título y texto

Subtítulos internos (H2): Helvetica Bold, 14pt. 4 líneas antes, 2 líneas después

Subtítulos menores (H3): Helvetica Bold, 12pt. 3 líneas antes, 1.5 después

Encabezados de página: Helvetica 8pt, alineados al centro. Páginas pares: título del libro. Páginas impares: título del capítulo. No en primera página de capítulo ni en preliminares

Numeración de página: Helvetica 10pt, centrado inferior. No en primera página de capítulo ni en preliminares

Estructura de páginas
Páginas preliminares (sin numerar o numeración romana):

Portadilla (solo título, centrado)

En blanco

Página de título (título, subtítulo, autor, sello)

Página de créditos

[Página reservada para mapa/ilustración si aplica]

Índice de contenidos

En blanco antes de capítulo 1

Página de créditos (adaptar según título):
[TÍTULO] — [SUBTÍTULO]
© [AÑO] [Nombre del autor]
Todos los derechos reservados.

Editorial Esencia
Galicia, Spain, Europe, Earth

Primera edición: [AÑO]

Queda prohibida la reproducción total o parcial de esta obra
por cualquier medio sin la autorización expresa del autor.

Cuerpo del libro (numeración arábiga):

Cada capítulo empieza en página impar (recto)

Si el capítulo anterior termina en impar, insertar página en blanco

Primera página de capítulo: sin encabezado, número de página centrado abajo

Los separadores --- del manuscrito se convierten en tres asteriscos centrados (* * *) con espacio vertical mayor

Páginas finales:

Materiales finales detectados automáticamente (glosario, bibliografía, etc.)

Página de actualizaciones web + espacio para QR code (si aplica)

Página de otros títulos del sello (si los hay)

Página final en blanco o con colofón

DETECCIÓN AUTOMÁTICA DE MATERIALES FINALES

Explora el manuscrito en busca de secciones con los siguientes títulos (insensible a mayúsculas):

Glosario

Bibliografía

Apéndice / Anexo

Índice analítico

Notas finales

No pidas al usuario que liste estos materiales manualmente. Detecta su presencia automáticamente.

Si el manuscrito contiene bloques especiales (recuadros de ejercicios, citas destacadas, listas de recursos), detéctalos por su formato y aplícales el estilo correspondiente:

Ejercicios prácticos: recuadro con borde, fondo ligeramente más claro

Citas destacadas: párrafo con sangría extra y tipografía ligeramente menor

Listas de recursos: viñetas con espaciado adicional

ELEMENTOS ESPECIALES DE FORMATO

Aplica las siguientes normas del Manual de Estilo:

Comillas: « » para citas directas, " " para términos especiales

Cursivas: extranjerismos, títulos de libros, términos técnicos en primera aparición

Negritas: solo conceptos definidos explícitamente (máximo 3-4 por capítulo)

Números: letra hasta 10, cifra de 11+, siempre cifra para %, años, precios

Raya tipográfica (—): para incisos y diálogos

ENTREGABLES

Genera los siguientes archivos en la carpeta del proyecto:

PDF de interiores ({slug}_interior.pdf) — para KDP tapa blanda (6×9", márgenes KDP, tipografía profesional, fuentes incrustadas)

Archivo DOCX maquetado ({slug}_interior.docx) — con márgenes, tipografía y formato KDP aplicados

Markdown completo ({slug}_interior.md) — todo el libro ensamblado en formato Markdown. Se genera para archivado y como fuente para futuras conversiones. No se usa en la publicación KDP.

Archivo DOCX para conversión PDF ({slug}_kindle_pdf.docx) — versión formateada para exportar a PDF en otras plataformas de autoedición. Mantiene márgenes y formato de página fijo.

Archivo DOCX para Kindle ({slug}_kindle.docx) — versión formateada específicamente para Kindle. Sin márgenes fijos, índice con hipervínculos activos, formato fluido. Este es el que se sube directamente a KDP eBook.

Informe de producción (INFORME_PRODUCCION_{slug}.md) — con los siguientes datos calculados automáticamente:

Número total de páginas del PDF

Cálculo de lomo (páginas × factor papel, usando la tabla de referencia 05_REFERENCIA_TABLA_LOMOS.md)

Dimensiones exactas de portada envolvente (ancho total en px y mm)

Lista de archivos entregados

Tipo de papel y tinta usados

Color de colección aplicado

CRITERIOS DE VALIDACIÓN

Antes de dar por finalizada la maquetación, verifica:

El PDF tiene las dimensiones exactas de 6×9"

Los márgenes son 0.5" en los cuatro lados

Cada capítulo empieza en página impar

Los encabezados de página son correctos (título en pares, capítulo en impares)

No hay encabezados ni números en primera página de capítulo

Las páginas preliminares están en el orden correcto

La tipografía es Helvetica (o Arial) en cuerpo y títulos, interlineado 1.15

Los bloques especiales están diferenciados visualmente

La página de créditos tiene toda la información de Editorial Esencia

El conteo de páginas es par (requisito KDP)

No hay páginas huérfanas ni viudas

Las fuentes están incrustadas en el PDF

Los metadatos del PDF incluyen título, autor y editorial (Editorial Esencia)

NOTAS TÉCNICAS

Limitaciones conocidas del entorno de producción
Fuente Helvetica variable: Asegurarse de que la fuente incrustada es la correcta. En defecto, Arial puede sustituir con el mismo tracking.

Imágenes: Si el libro tiene ilustraciones o mapas, deben proporcionarse como archivos de imagen separados. Si no existen, omitir o marcar "pendiente".

Tablas: Si el libro necesita tablas, formatearlas con líneas de separación claras y encabezados en negrita.

Índice analítico: Si se requiere, necesita una segunda pasada después de generar el PDF para capturar los números de página reales.

PASO FINAL: ENTREGA

Cuando todos los archivos estén generados y validados:

Presenta un resumen de la maquetación en el chat:

Número total de páginas

Dimensiones de lomo calculadas

Archivos generados

Cualquier incidencia o advertencia

Yo reviso y confirmo:
[ ] Maquetación aprobada — Listo para Fase 5: Portada

===========================================================================================
INSTRUCCIONES PARA ALEJANDRO (no pegar en el chat)
===========================================================================================

CÓMO USAR ESTE PROMPT

Asegúrate de que la carpeta del proyecto existe: G:...\Libros{slug}\

Verifica que están en la carpeta:

{slug}_metadatos.yaml

{slug}_editado_final.docx

{slug}_cap0.md (referencia de tono)

Abre una nueva conversación y pega este prompt, reemplazando {slug} por el slug real.

El asistente leerá automáticamente los metadatos y el manuscrito.

No necesitas proporcionar ningún dato adicional.

FLUJO:

Asistente lee metadatos y manuscrito

Asistente confirma datos detectados → Tú apruebas

Asistente maqueta y genera los 5 archivos + informe

Tú revisas el PDF y los criterios de validación

Si hay correcciones, las indicas y el asistente regenera

Al aprobar, el sistema está listo para Fase 5 (Portada)

NOTA IMPORTANTE:
El informe de producción (INFORME_PRODUCCION_{slug}.md) contiene el número exacto
de páginas y las dimensiones de lomo. Estos datos SON CRÍTICOS para la Fase 5 (Portada).
No pases a Fase 5 sin este informe generado y verificado.

===========================================================================================