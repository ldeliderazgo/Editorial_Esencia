
TABLA DE DIMENSIONES DE PORTADA — Editorial Esencia
Referencia exacta para calcular ancho de portada según número de páginas.

FÓRMULA DEL LOMO
Papel blanco:
Lomo (pulgadas) = Páginas × 0.002252"
Lomo (mm) = Lomo (pulgadas) × 25.4

Papel crema:
Lomo (pulgadas) = Páginas × 0.002500"
Lomo (mm) = Lomo (pulgadas) × 25.4

Ancho total de portada:
Ancho = (3600 px contraportada + lomo en px + 3600 px portada frontal)

TABLA COMPLETA — 300 DPI
Formato: 6×9" | Sangrado: 0.125" | Resolución: 300 DPI

PAPEL BLANCO
Páginas	Lomo (pulgadas)	Lomo (mm)	Ancho imagen (px)	Alto (px)	Ratio
100	0.225"	5.7 mm	3694	2775	1.33:1
110	0.248"	6.3 mm	3700	2775	1.33:1
120	0.270"	6.9 mm	3707	2775	1.34:1
128	0.288"	7.3 mm	3712	2775	1.34:1
130	0.293"	7.4 mm	3713	2775	1.34:1
140	0.315"	8.0 mm	3719	2775	1.34:1
150	0.338"	8.6 mm	3727	2775	1.34:1
160	0.360"	9.1 mm	3734	2775	1.35:1
170	0.383"	9.7 mm	3741	2775	1.35:1
180	0.405"	10.3 mm	3747	2775	1.35:1
190	0.428"	10.9 mm	3754	2775	1.35:1
200	0.450"	11.4 mm	3761	2775	1.36:1
210	0.473"	12.0 mm	3768	2775	1.36:1
220	0.496"	12.6 mm	3774	2775	1.36:1
230	0.518"	13.1 mm	3781	2775	1.36:1
240	0.540"	13.7 mm	3787	2775	1.37:1
250	0.563"	14.3 mm	3794	2775	1.37:1
260	0.585"	14.9 mm	3800	2775	1.37:1
270	0.608"	15.4 mm	3807	2775	1.37:1
280	0.631"	16.0 mm	3814	2775	1.37:1
290	0.653"	16.6 mm	3820	2775	1.38:1
300	0.676"	17.2 mm	3828	2775	1.38:1
320	0.721"	18.3 mm	3841	2775	1.38:1
340	0.765"	19.4 mm	3854	2775	1.39:1
350	0.788"	20.0 mm	3861	2775	1.39:1
370	0.833"	21.1 mm	3874	2775	1.39:1
400	0.901"	22.9 mm	3895	2775	1.40:1
450	1.013"	25.7 mm	3929	2775	1.42:1
PAPEL CREMA
Páginas	Lomo (pulgadas)	Lomo (mm)	Ancho imagen (px)	Alto (px)	Ratio
100	0.250"	6.4 mm	3700	2775	1.33:1
120	0.300"	7.6 mm	3713	2775	1.34:1
128	0.320"	8.1 mm	3720	2775	1.34:1
150	0.375"	9.5 mm	3735	2775	1.34:1
180	0.450"	11.4 mm	3761	2775	1.36:1
200	0.500"	12.7 mm	3774	2775	1.36:1
220	0.550"	14.0 mm	3787	2775	1.36:1
250	0.625"	15.9 mm	3814	2775	1.37:1
280	0.700"	17.8 mm	3841	2775	1.39:1
300	0.750"	19.1 mm	3854	2775	1.39:1
350	0.875"	22.2 mm	3881	2775	1.40:1
400	1.000"	25.4 mm	3908	2775	1.41:1
450	1.125"	28.6 mm	3935	2775	1.42:1
CÓMO USAR ESTA TABLA
Paso 1: Identifica el número exacto de páginas del PDF (de INFORME_PRODUCCION).
Ejemplo: 128 páginas.

Paso 2: Elige si papel es blanco o crema.
Ejemplo: Papel blanco.

Paso 3: Busca en la tabla.
Papel blanco, 128 páginas:
├─ Lomo: 7.3 mm
└─ Ancho imagen: 3712 px

Paso 4: El alto siempre es 2775 px.
Por lo tanto:
├─ Ancho: 3712 px
├─ Alto: 2775 px
└─ Ratio: 1.34:1

Paso 5: Usa estos números en el prompt de la Fase 5 (Portada).
[ANCHO_PX] = 3712
[ALTO_PX] = 2775
[RATIO] = 1.34:1

VERIFICACIÓN RÁPIDA
Si tu número de páginas no está exacto en la tabla:

Busca el rango más cercano (arriba y abajo).

Interpola linealmente:
Lomo interpolado = Lomo_anterior + (Páginas_diferencia × incremento_por_página)

Ejemplo: 125 páginas (papel blanco)
Rango: 120pp (6.9mm) — 130pp (7.4mm)
Diferencia: 5 páginas = 0.5 mm
Por página: 0.1 mm
Para 125pp: 6.9 + (0.1 × 5) = 7.4 mm

Ancho en px: 128pp tiene 3712px
Para 125pp: aproximadamente 3710px

NOTA IMPORTANTE: RESOLUCIÓN MÍNIMA
Independientemente de la tabla:

✓ Mínimo absoluto: 3800 px de ancho (para evitar borrosas en impresión)
✓ Ideal: 4000+ px de ancho
✓ Altura: siempre 2775 px a 300 DPI

Si el generador de imágenes entrega menos de 3800 px de ancho, RECHAZAR la imagen y solicitar upscaling (con herramientas como Topaz Gigapixel o Magnific AI).

Tabla de Dimensiones de Lomos — Editorial Esencia
Versión 2.0 — Abril 2026