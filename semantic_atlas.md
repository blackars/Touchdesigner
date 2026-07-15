# 1. Qué podría ser el proyecto

Podrías plantearlo como:

## Título posible

**Atlas Latente: visualizador semántico de IA, arte y nuevos medios**

Otras opciones:

-   **Cartografía de Referentes**
-   **Máquina de Afinidades**
-   **Archivo Vectorial de Nuevos Medios**
-   **Constelación IA-Arte**
-   **Theoretical Particle Atlas**
-   **Mapa Vivo de Autores y Obras**
-   **Biblioteca Latente**
-   **Visualizador de Pensamiento Interdisciplinar**
-   **Atlas de Procesos Humanos-Máquina**

----------

# 2. Qué datos consumiría

Tu tabla ya tiene una estructura muy rica. Cada fila puede convertirse en un “objeto visual” con múltiples capas.

Tus columnas actuales podrían transformarse así:

Columna de la tabla

Traducción visual posible

Autor / artista

Nodo principal, partícula, retrato, avatar, punto en constelación

Año

Eje temporal, anillo orbital, profundidad, color por época

Obra / fuente principal

Tarjeta expandible con imagen, cita, resumen o miniatura

Tipo de fuente

Forma del nodo: libro, paper, obra, exposición, conferencia

Disciplina / campo

Color, región del mapa, capa temática

Tesis central

Texto breve generado o resumido por LLM

Metodología

Patrón de movimiento, textura, línea, geometría

Aporte

Intensidad, tamaño, brillo, halo

Límites

Sombra, ruido, glitch, borde discontinuo

Utilidad para tu proyecto

Sistema de filtros o rutas curatoriales

Observaciones

Capa de notas personales

Enlace

Ficha externa, botón, QR, apertura web

Imagen del autor

Retrato o silueta

Imagen de obra

Miniatura, textura, collage o imagen generada a partir de metadatos

Quote

Fragmento flotante

Resumen de ideas

Panel lateral, voz sintética, tooltip, ficha expandida

----------

# 3. Formas visuales posibles

## 3.1. Mapa de constelaciones

Cada autor sería una estrella. Las relaciones se dibujan como líneas:

-   Manovich cerca de cultural analytics, estética artificial, base de datos.
-   Burbano cerca de arqueología medial, Sur Global, historia de medios.
-   Anadol cerca de datos, naturaleza, inmersión.
-   Fuller cerca de software studies, ecologías mediales.
-   Berry cerca de capitalismo computacional, medios sintéticos.
-   Crawford cerca de infraestructura, extracción, trabajo, materialidad.
-   Zylinska cerca de posthumanismo, fotografía, ética.
-   Paglen cerca de machine vision, vigilancia, imágenes invisibles.
-   Ridler cerca de datasets manuales, archivo, botánica.
-   Herndon/Dryhurst cerca de voz, consentimiento, data trusts.

### Interacción

-   Zoom in/out.
-   Hover sobre nodo: aparece frase clave.
-   Click: abre ficha completa.
-   Doble click: pregunta al LLM “¿cómo se conecta este autor con mi proyecto?”
-   Filtros por campo: pedagogía, curaduría, humanidades digitales, ética, práctica artística.
-   Slider temporal 2024–2026.
-   Botón “mostrar tensiones”: ética vs estética, herramienta vs medio, autonomía vs dependencia, datos abiertos vs explotación.

### Estética

Minimalista, fondo oscuro o blanco hueso, nodos pequeños, líneas finas, tipografía limpia. Algo entre **mapa astronómico**, **diagrama de redes** y **archivo museográfico**.

----------

## 3.2. Mapa vectorial / embedding map

Este sería el más potente conceptualmente.

Tomas los textos de cada fila:

-   tesis central;
-   metodología;
-   aporte;
-   límites;
-   observaciones;
-   resumen del autor;
-   keywords.

Luego generas **embeddings** —vectores semánticos— y los proyectas en 2D con UMAP o t-SNE.

El resultado: los autores aparecen en un espacio visual según **afinidad conceptual**, no según categorías manuales.

Ejemplo:

-   Ridler, Crawford, Herndon/Dryhurst y Buick podrían aparecer cerca por datos, derechos y datasets.
-   Anadol, Crespo, Yi y Akten podrían agruparse por naturaleza, vida artificial, ecología e inmersión.
-   Black, Blair, Heaton, Sims y Campbell podrían formar una región pedagógica.
-   Wasielewski, Iervolino, Hamm y Man Lai formarían la zona de museos y curaduría.
-   Berry, Galloway, Fuller, Manovich y Klein et al. quedarían en la zona teórica/crítica.

### Interacción

-   Buscar “autoría” y el mapa ilumina todos los nodos relacionados.
-   Buscar “Sur Global” y aparecen Burbano, Abdilla, Allahyari, Al-Badri, Roy & Deshbandhu.
-   Buscar “dataset” y aparecen Ridler, Crawford, Herndon/Dryhurst, Paglen, Buick, Lima et al.
-   Preguntar: “¿qué autores conectan pedagogía con ética de datos?”
-   El LLM responde y además traza una ruta visual entre nodos.

### Visual

Un paisaje abstracto de puntos, como polvo cósmico o células. No se ve como una tabla; se ve como un **espacio de pensamiento**.

----------

## 3.3. Sistema de partículas

Cada fila de tu base se convierte en una partícula. Las partículas tienen comportamiento según metadatos:

Dato

Comportamiento

Disciplina

Color

Año

Velocidad o posición temporal

Tipo de fuente

Forma

Afinidad semántica

Atracción entre partículas

Límites / tensiones

Repulsión

Aporte

Brillo

Utilidad para tu proyecto

Tamaño

Cantidad de conexiones

Número de órbitas

Podrías tener modos:

### Modo “constelación”

Relaciones estables.

### Modo “tormenta”

Las partículas se reorganizan según una pregunta.

Ejemplo:

> “Muéstrame autores que conecten IA, pedagogía y práctica artística.”

El sistema reordena el campo y agrupa las partículas relevantes.

### Modo “tensión”

Las partículas se separan por pares conceptuales:

-   arte / industria;
-   humano / máquina;
-   ética / espectáculo;
-   archivo / predicción;
-   pedagogía / automatización;
-   autoría / dataset;
-   Sur Global / Norte Global;
-   herramienta / medio;
-   imagen / infraestructura.

### Modo “respiración”

El mapa se mueve lentamente, como un organismo. Minimalista, contemplativo.

----------

## 3.4. Archivo de tarjetas expandibles

Una interfaz más clara para investigación.

Vista principal: mapa de nodos.

Al seleccionar un nodo, aparece una tarjeta:

Autor: Anna Ridler
Obra: Mosaic Virus / Every Single Iris on the Internet
Campo: IA, datasets, archivo, botánica
Tesis: El dataset es una construcción cultural y manual.
Aporte: Hace visible el trabajo humano detrás de los datos.
Límite: Su enfoque artesanal contrasta con modelos industriales.
Conexiones: Kate Crawford, Holly Herndon, Trevor Paglen, Sofia Crespo.
Pregunta sugerida: ¿Cómo puede un dataset convertirse en obra?

La tarjeta puede tener:

-   imagen del autor;
-   imagen de obra;
-   quote;
-   resumen de 50 palabras;
-   botón “expandir”;
-   botón “comparar con otro autor”;
-   botón “generar ruta de lectura”;
-   botón “ver relaciones”.

----------

## 3.5. Visualizador tipo “mapa de lectura”

En vez de explorar todos los nodos, el usuario elige una ruta:

### Ruta 1: IA y educación artística

Blair → Black & Chaput → Heaton → Sims → Campbell et al. → Manghani & Savage.

### Ruta 2: IA, ética y datasets

Crawford → Ridler → Paglen → Herndon/Dryhurst → Buick → Lima et al. → Chen & He.

### Ruta 3: IA, museos y curaduría

Wasielewski → Iervolino & Milne → Hamm → Man Lai → UNESCO → SIGGRAPH / ISEA.

### Ruta 4: IA y visualidad crítica

Steyerl → Paglen → Galloway → Berry → Laba → Zylinska.

### Ruta 5: IA, ecología y vida artificial

Anadol → Crespo → Anicka Yi → Akten → Kurant → Abdilla.

Cada ruta se vería como un **camino luminoso**, una navegación narrativa por el mapa.

----------

# 4. Proyectos similares que puedes estudiar

## 4.1. Open Knowledge Maps

Es una herramienta que crea mapas visuales de literatura académica. En vez de mostrar una lista de papers, agrupa documentos en burbujas temáticas. Es muy útil como referencia porque convierte búsqueda académica en una **visión panorámica por clusters**.

### Qué tomar de ahí

-   burbujas temáticas;
-   agrupación por conceptos;
-   vista general rápida;
-   documentos dentro de cada cluster;
-   navegación desde tema hacia fuente.

### Cómo adaptarlo

Tu sistema podría crear burbujas como:

-   educación artística;
-   datasets y autoría;
-   nuevos medios;
-   curaduría;
-   humanidades digitales;
-   arte ecológico con IA;
-   visión maquínica;
-   Sur Global.

Web: [https://openknowledgemaps.org](https://openknowledgemaps.org)

----------

## 4.2. Connected Papers

Connected Papers genera grafos visuales a partir de un paper semilla. Los nodos son papers relacionados por co-citación o acoplamiento bibliográfico.

### Qué tomar

-   grafo limpio;
-   nodos relacionados;
-   lectura de influencias;
-   idea de “paper semilla”;
-   exploración desde una fuente central.

### Cómo adaptarlo

Tú podrías seleccionar un autor semilla:

> “Lev Manovich”

Y el mapa muestra autores cercanos:

-   Arielli;
-   Fuller;
-   Berry;
-   Galloway;
-   Wardrip-Fruin;
-   Bogost;
-   Wasielewski.

O seleccionar:

> “Anna Ridler”

Y aparecen:

-   Crawford;
-   Herndon/Dryhurst;
-   Paglen;
-   Sofia Crespo;
-   Buick;
-   Lima et al.

Web: [https://www.connectedpapers.com](https://www.connectedpapers.com)

----------

## 4.3. ResearchRabbit

ResearchRabbit permite crear colecciones de papers y explorar relaciones entre autores, trabajos anteriores, trabajos posteriores y coautorías.

### Qué tomar

-   colecciones;
-   autores sugeridos;
-   papers anteriores/posteriores;
-   grafo dinámico;
-   modo exploratorio para revisión bibliográfica.

### Cómo adaptarlo

Podrías tener colecciones propias:

-   “mi corpus de pedagogía”;
-   “mi corpus de curaduría”;
-   “mi corpus de ética de datos”;
-   “mis artistas referentes”;
-   “mis autores teóricos”.

Web: [https://www.researchrabbit.ai](https://www.researchrabbit.ai)

----------

## 4.4. Litmaps

Litmaps visualiza papers en relación con el tiempo. Es útil para ver genealogías y evolución de campos.

### Qué tomar

-   eje temporal;
-   conexiones entre fuentes;
-   actualización de literatura;
-   rutas históricas.

### Cómo adaptarlo

Podrías mostrar:

-   genealogía de nuevos medios;
-   transición de software studies a IA generativa;
-   evolución de arte generativo a IA;
-   aparición de debates 2024–2026.

Web: [https://www.litmaps.com](https://www.litmaps.com)

----------

## 4.5. Cultural Analytics Lab

Los proyectos de Lev Manovich y el Cultural Analytics Lab son fundamentales para lo que estás imaginando. Trabajan con grandes colecciones visuales y las convierten en mapas, grids, líneas temporales y visualizaciones exploratorias.

Proyectos relevantes:

-   **Selfiecity**
-   **Phototrails**
-   **On Broadway**
-   **MoMA Photography Collection**
-   **One Million Manga Pages**
-   **Visualizing Vertov**

### Qué tomar

-   análisis cultural como visualización;
-   imágenes como puntos de datos;
-   visualización de grandes colecciones;
-   mapas de color, estilo, tiempo y composición;
-   estética entre investigación y obra.

Web: [https://lab.culturalanalytics.info/p/projects.html](https://lab.culturalanalytics.info/p/projects.html)

----------

## 4.6. Museum Semantic Search

Proyecto muy cercano técnicamente a lo que necesitas. Usa embeddings, descripciones generadas por IA y visualización de colecciones museales. Permite buscar obras mediante lenguaje natural y explorar un mapa donde cada punto representa una obra.

### Qué tomar

-   búsqueda semántica;
-   embeddings de texto e imagen;
-   mapa 2D;
-   puntos como obras;
-   búsqueda natural;
-   visualización de clusters;
-   uso de descripciones generadas por IA.

Esto se parece muchísimo a tu idea, solo que en vez de obras de museo tendrías autores, papers, obras, citas y conceptos.

Demo / repo:  
[https://github.com/derekphilipau/museum-semantic-search](https://github.com/derekphilipau/museum-semantic-search)

----------

## 4.7. Collection Space Navigator

Herramienta para explorar colecciones multidimensionales mediante navegación espacial.

### Qué tomar

-   exploración de colecciones como espacio;
-   filtros;
-   navegación visual;
-   uso para investigación;
-   posibilidad de trabajar con imágenes.

Repo: [https://github.com/Collection-Space-Navigator/CSN](https://github.com/Collection-Space-Navigator/CSN)

----------

## 4.8. ArtGraph

ArtGraph es un proyecto de knowledge graph artístico basado en WikiArt y DBpedia. Su estructura central son autores y obras.

### Qué tomar

-   autores y obras como nodos;
-   relaciones semánticas;
-   grafo consultable;
-   estructura tipo Neo4j;
-   interfaz web para exploración.

Idea aplicable:
Autor → escribió → Obra
Autor → trabaja en → Disciplina
Obra → aborda → Concepto
Concepto → se relaciona con → Otro concepto
Autor → dialoga con → Autor
Obra → útil para → Tu proyecto

## 4.9. E.A.T. Knowledge Graph Project

Proyecto que convierte archivos de Experiments in Art and Technology en un grafo de conocimiento. Es muy relevante porque cruza arte, tecnología, archivo, entidades, relaciones y visualización.

### Qué tomar

-   archivo artístico como grafo;
-   entidades: artistas, ingenieros, documentos, eventos;
-   generación de triples;
-   vínculo entre dato y fuente;
-   posibilidad de visualización y consulta.

Muy útil si quieres que tu proyecto sea más académico y museográfico.

----------

## 4.10. VOSviewer / CitNetExplorer

Herramientas clásicas de bibliometría visual.

### Qué tomar

-   clusters bibliométricos;
-   co-ocurrencia de palabras clave;
-   redes de citación;
-   mapas de densidad;
-   análisis de campos.

Podrías usarlas como inspiración para vistas:

-   “mapa de conceptos frecuentes”;
-   “red de autores”;
-   “mapa de disciplinas”;
-   “mapa de obras”.

Web: [https://www.vosviewer.com](https://www.vosviewer.com)

----------

# 5. Tipologías de visualizador que podrías crear

## Opción A: Atlas semántico minimalista

Una interfaz limpia donde cada autor es un punto en un plano semántico.

### Componentes

-   mapa de puntos;
-   panel lateral;
-   buscador;
-   filtros;
-   miniaturas;
-   quotes;
-   resumen generado;
-   rutas temáticas.

### Ideal si quieres

Un proyecto elegante, académico y usable.

### Tecnología posible

-   CSV / Google Sheets / Airtable;
-   Python para embeddings;
-   UMAP para coordenadas;
-   React + D3 / Three.js / PixiJS;
-   pequeño LLM local o API;
-   base vectorial ligera.

----------

## Opción B: Instalación audiovisual de partículas

La tabla se convierte en una nube viva. Los autores son partículas que se atraen o repelen según sus ideas.

### Componentes

-   partículas flotantes;
-   sonido generativo;
-   textos mínimos;
-   citas que aparecen y desaparecen;
-   imágenes de obras como texturas;
-   modo contemplativo;
-   interacción por mouse, voz o teclado.

### Ideal si quieres

Una pieza de nuevos medios más poética y abstracta.

### Tecnología posible

-   TouchDesigner;
-   p5.js;
-   Three.js;
-   Unity;
-   Unreal Engine;
-   Max/MSP;
-   WebGL;
-   shaders.

----------

## Opción C: Explorador curatorial con IA

Una interfaz donde preguntas cosas al sistema y este reorganiza visualmente el mapa.

Ejemplos de preguntas:

¿Qué autores conectan pedagogía y datasets?
¿Qué ruta de lectura me recomiendas para entender IA y curaduría?
Muéstrame autores críticos con la idea de IA como herramienta neutral.
¿Qué artistas trabajan con naturaleza e IA?
¿Qué tensiones aparecen entre Refik Anadol y Kate Crawford?
¿Qué autores sirven para fundamentar un curso de IA y arte?

El sistema responde con:

-   texto breve;
-   ruta visual;
-   nodos resaltados;
-   comparaciones;
-   citas;
-   mini bibliografía.

### Ideal si quieres

Una herramienta de investigación real.

----------

## Opción D: Mapa de tensiones

No organizas por autores, sino por tensiones conceptuales.

Ejes posibles:

Humano ---------------- Máquina
Arte ------------------ Industria
Ética ----------------- Espectáculo
Archivo --------------- Predicción
Pedagogía ------------- Automatización
Cuerpo ---------------- Dato
Sur Global ------------ Norte Global
Herramienta ----------- Medio
Imagen ---------------- Infraestructura
Autoría --------------- Dataset

Cada autor cae en algún punto del espacio.

### Ejemplo

-   Crawford: infraestructura / ética / extracción.
-   Anadol: espectáculo / datos / inmersión / naturaleza.
-   Ridler: dataset / archivo / manualidad.
-   Chung: cuerpo / máquina / co-creación.
-   Burbano: Sur Global / historia / materialidad.
-   Manovich: medio / cultura visual / base de datos.
-   Galloway: simulación / crítica / interfaz.
-   Wasielewski: curaduría / museo / IA.
-   Heaton: pedagogía / diálogo / alfabetización.

### Ideal si quieres

Un visualizador conceptual y crítico, no solo bibliográfico.

----------

## Opción E: Biblioteca viva / archivo generativo

Cada vez que abres el sistema, el mapa cambia ligeramente. El LLM genera:

-   una pregunta del día;
-   una ruta de lectura;
-   un quote;
-   una conexión inesperada;
-   una tensión;
-   una mini-curaduría.

Ejemplo:

Conexión inesperada:
Anna Ridler y Holly Herndon comparten una preocupación por convertir el dataset en un espacio de negociación ética.

Ruta sugerida:
Ridler → Crawford → Herndon/Dryhurst → Buick → Lima et al.

### Ideal si quieres

Una pieza que se sienta viva, no como base de datos estática.

----------

# 6. Arquitectura técnica posible

## Versión simple

### Entrada

Tu tabla en CSV o Google Sheets.

### Proceso

1.  Cargar filas.
2.  Concatenar campos relevantes:
Autor + obra + disciplina + tesis central + metodología + aporte + límites + observaciones

3.  Generar embeddings.
4.  Reducir a 2D con UMAP.
5.  Dibujar puntos.
6.  Usar LLM para resúmenes y preguntas.

### Salida

Interfaz web con mapa y fichas.

### Stack

-   Google Sheets / CSV
-   Python
-   sentence-transformers
-   UMAP
-   JSON
-   React
-   D3.js / PixiJS
-   Ollama o LM Studio para LLM local
-   SQLite o ChromaDB

----------

## Versión intermedia

### Componentes

Base de datos:
CSV / Airtable / Notion / SQLite

Procesamiento:
Python + Pandas + embeddings

Vector database:
ChromaDB / LanceDB / FAISS

Frontend:
React + Three.js o PixiJS

LLM:
Ollama con Phi, Mistral, Llama 3.2 o Gemma

Imágenes:
URLs manuales + miniaturas de obras + retratos

Interacción:
Búsqueda semántica + filtros + comparación

## Versión avanzada

### Componentes

Knowledge graph:
Neo4j / RDF / Wikibase

Embeddings:
Text embeddings + image embeddings

Frontend:
Three.js / WebGPU / custom shaders

LLM:
RAG sobre tu corpus

Interacción:
Chat visual + rutas generativas + timeline + mapas de tensión

Modo instalación:
TouchDesigner / Unreal / WebGL fullscreen

# 7. Modelo de datos recomendado

Tu tabla podría convertirse en JSON así:

{
  "id": "anna_ridler",
  "autor": "Anna Ridler",
  "anio": "2024-2025",
  "obra": ["Slowly Fading Quietly", "Time Blooms", "Every Single Iris on the Internet"],
  "tipo_fuente": "Obra artística / instalación / dataset artístico",
  "disciplina": ["IA", "datasets", "archivo", "botánica", "arte generativo"],
  "tesis": "Los datasets no son neutros: son construcciones culturales, manuales, afectivas y políticas.",
  "metodologia": "Creación manual de datasets, fotografía, clasificación, entrenamiento de modelos, instalación.",
  "aporte": "Hace visible el trabajo humano detrás de los datos y convierte el dataset en material artístico.",
  "limites": "Muchas obras clave comienzan antes de 2024.",
  "utilidad": "Muy útil para hablar de dataset-making como metodología artística.",
  "observaciones": "Ideal para contrastar con modelos masivos opacos.",
  "url": "https://annaridler.com",
  "imagen_autor": "url",
  "imagen_obra": "url",
  "quotes": [
    "The dataset is its own work of art."
  ],
  "keywords": ["dataset", "botánica", "archivo", "clasificación", "IA"]
}
# 8. Funciones con LLM pequeño

No necesitas un modelo enorme. Un modelo pequeño puede hacer tareas útiles si trabaja con tu tabla.

## Funciones posibles

### 8.1. Resumen de nodo

Resume en 40 palabras la postura de este autor.

### 8.2. Comparación

Compara a Anna Ridler con Kate Crawford en relación con datasets.

### 8.3. Ruta de lectura

Crea una ruta de 6 autores para entender IA y pedagogía artística.

### 8.4. Preguntas generativas

Genera 3 preguntas de investigación a partir de este cluster.

### 8.5. Curaduría automática

Crea una mini-exposición con 5 obras sobre IA, archivo y colonialidad.

### 8.6. Conexiones inesperadas

Encuentra una conexión poco obvia entre Refik Anadol y Andrés Burbano.

### 8.7. Crítica

# 9. Modos de visualización concretos

## Modo 1: Red de autores

Nodos:

-   autores;
-   artistas;
-   papers;
-   obras;
-   instituciones.

Relaciones:

-   comparte concepto;
-   cita/influye;
-   misma disciplina;
-   misma metodología;
-   tensión conceptual;
-   útil para el mismo eje.

----------

## Modo 2: Mapa de conceptos

Los nodos no son autores sino conceptos:

-   dataset;
-   autoría;
-   pedagogía;
-   curaduría;
-   machine vision;
-   co-creación;
-   Sur Global;
-   infraestructura;
-   posthumanismo;
-   archivo;
-   museo;
-   copyright;
-   inmersión;
-   visualización;
-   bioarte.

Al hacer click en “dataset”, aparecen:

-   Ridler;
-   Crawford;
-   Herndon/Dryhurst;
-   Paglen;
-   Buick;
-   Lima et al.;
-   Chen & He.

----------

## Modo 3: Timeline

Una línea temporal con capas:
2021: Atlas of AI
2023: The Perception Machine
2024: Artificial Aesthetics / ISEA / SIGGRAPH Asia
2025: The Call / Curating AI-driven Art / AI and Curation
2026: Ethical Dilemmas in AI-generated Art

Podrías mostrar cómo las ideas se condensan en el periodo 2024–2026.

----------

## Modo 4: Galería de retratos

Una cuadrícula minimalista con retratos de autores/artistas.

Al pasar el mouse:

-   aparece su obra principal;
-   una frase;
-   tres keywords;
-   una línea de conexión hacia autores relacionados.

Esto sería útil para presentación o clase.

----------

## Modo 5: Paisaje semántico

Un plano abstracto con regiones:

Norte: Teoría crítica
Sur: Pedagogía
Este: Museos / curaduría
Oeste: Práctica artística
Centro: IA generativa / nuevos medios

Cada nodo se ubica según embeddings y categorías.

----------

## Modo 6: Matriz visual

La tabla se mantiene, pero cada fila tiene una traducción visual.

Ejemplo:
Autor: Manovich
Color: azul
Forma: círculo
Movimiento: orbital
Campo: teoría de medios
Intensidad: alta
Relación: base de datos / estética / imagen

Esto permite alternar entre:

-   vista tabla;
-   vista mapa;
-   vista partículas;
-   vista timeline;
-   vista tarjetas.

----------

# 10. Propuesta de interfaz concreta

## Pantalla principal
## Panel lateral
Anna Ridler
Obra: Every Single Iris on the Internet
Campo: IA, datasets, archivo, botánica

Tesis:
Los datasets no son neutros; son construcciones culturales y materiales.

Aporte:
Convierte el dataset en obra y visibiliza el trabajo humano de clasificación.

Conexiones:
Kate Crawford · Holly Herndon · Trevor Paglen · Sofia Crespo

Botones:
[Comparar] [Ruta de lectura] [Citas] [Ver obra] [Preguntar al modelo]

# 11. Tres prototipos posibles

## Prototipo 1: “Mapa Semántico”

### Qué hace

-   carga CSV;
-   genera embeddings;
-   crea mapa 2D;
-   permite click en autores;
-   muestra ficha;
-   búsqueda semántica.

### Dificultad

Media-baja.

### Herramientas

-   Python;
-   UMAP;
-   React;
-   D3 o PixiJS;
-   OpenAI embeddings o sentence-transformers;
-   Ollama opcional.

----------

## Prototipo 2: “Constelación Viva”

### Qué hace

-   visualización de partículas;
-   relaciones por afinidad;
-   movimiento lento;
-   quotes flotantes;
-   imágenes como texturas;
-   modo instalación.

### Dificultad

Media.

### Herramientas

-   p5.js o Three.js;
-   JSON;
-   shaders simples;
-   LLM para textos;
-   audio generativo opcional.

----------

## Prototipo 3: “Curador IA”

### Qué hace

-   chat con tu base;
-   responde con autores relevantes;
-   reorganiza mapa;
-   crea rutas;
-   genera mini-exposiciones;
-   compara posturas.

### Dificultad

Media-alta.

### Herramientas

-   ChromaDB;
-   LangChain o LlamaIndex;
-   Ollama;
-   React;
-   RAG sobre tu tabla.

----------

# 12. Prompt interno del modelo

El modelo podría tener una instrucción así:
Eres un asistente curatorial especializado en IA, nuevos medios, educación artística, humanidades digitales y teoría crítica. 
Solo puedes responder usando la base de datos de autores, obras, tesis, metodologías, aportes, límites y observaciones.
Cuando el usuario pregunte por conexiones, debes:
1. identificar autores relevantes;
2. explicar la relación;
3. proponer una ruta visual;
4. sugerir una pregunta de investigación;
5. indicar tensiones o límites.
Responde de forma breve, crítica y útil para investigación-creación.
# 13. Preguntas que el visualizador podría permitir
¿Qué autores trabajan con datasets como material artístico?
¿Qué autores sirven para pensar IA y pedagogía?
¿Qué tensiones hay entre espectáculo inmersivo y crítica de infraestructura?
¿Qué relación hay entre Refik Anadol y Kate Crawford?
¿Qué autores conectan archivo, colonialidad e IA?
¿Qué ruta debo leer para diseñar un curso de IA y arte?
¿Qué artistas trabajan con IA, naturaleza y vida artificial?
¿Qué papers discuten autoría distribuida?
¿Qué obras podrían formar una exposición sobre IA y nuevos medios?
¿Qué autores son más útiles para mi marco metodológico?

# 14. Una idea más poética: “El oráculo de la tabla”

Tu visualizador podría tener un modo experimental:

El usuario no busca directamente. Escribe una palabra:
archivo

El sistema responde visualmente:

-   aparecen nodos lentamente;
-   se conectan por líneas;
-   emergen quotes;
-   el LLM genera una frase;
-   una imagen abstracta se compone con miniaturas de obras.

Ejemplo:
Archivo no es memoria pasiva: es una máquina de clasificación, poder y posibilidad.
Ruta sugerida:
Ridler → Paglen → Crawford → Allahyari → Burbano → Wasielewski

Esto puede convertir la investigación en una **experiencia estética**.

----------

# 15. Recomendación final

Yo lo construiría en tres capas:

## Capa 1: Base académica

Tu tabla limpia, con todos los campos completos.

## Capa 2: Mapa semántico

Embeddings + UMAP + visualización de nodos.

## Capa 3: LLM curatorial

Un modelo pequeño que pueda:

-   resumir;
-   comparar;
-   sugerir rutas;
-   generar preguntas;
-   reorganizar el mapa.

----------

# 16. MVP recomendado

Para empezar sin complicarte demasiado:

### MVP: “Atlas de Referentes IA-Arte”

Funciones mínimas:

1.  Importar CSV.
2.  Mostrar autores como nodos.
3.  Colorear por disciplina.
4.  Buscar por palabra o concepto.
5.  Click en nodo para ver ficha.
6.  Botón “conectar con autores similares”.
7.  Botón “preguntar al modelo”.
8.  Mostrar imagen del autor/obra si existe URL.
9.  Exportar ruta seleccionada como lista de lectura.

### Visual

-   fondo negro o blanco;
-   nodos pequeños;
-   líneas finas;
-   tarjetas flotantes;
-   tipografía sans-serif;
-   colores suaves;
-   movimiento lento.

### Resultado

Una herramienta útil para tesis, clase, proyecto artístico y exposición.
