# 📹 Resúmenes — Matt Wolfe

---

## [Matt Wolfe] AI News: Fable's Back But This New Model is Better?
**Fecha:** 2026-07-03
**URL:** https://www.youtube.com/watch?v=NVP_paJarG4
**Video ID:** NVP_paJarG4

### 📝 Resumen

Matt Wolfe repasa las noticias más relevantes de la semana en inteligencia artificial, encabezadas por el regreso de **Fable 5** (el modelo estrella de Anthropic que había sido retirado por seguridad el 12 de junio) y el anuncio de **GPT 5.6** de OpenAI, que llega en tres variantes pero con acceso severamente restringido. El vídeo también cubre el lanzamiento de Claude Sonnet 5, varias novedades de Google (Nano Banana 2 Light, Gemini Omni Flash, Gemini Spark en macOS), una oferta polémica de OpenAI al gobierno de Trump, y el nuevo benchmark humorístico de Wolfe: **BuseyBench**.

#### Fable 5 vuelve… con más restricciones

El 1 de julio, Anthropic redeployó Fable 5 tras 2,5 semanas de ausencia forzada por seguridad. La nueva versión mantiene las mismas capacidades pero incorpora guardrails adicionales. Según Anthropic, el nuevo clasificador es más sensible, lo que resulta en que solicitudes benignas sean bloqueadas con mayor frecuencia durante tareas rutinarias de codificación y depuración.

- **Bridgemind** (cuenta de benchmarks en X) reportó caídas significativas en rendimiento: debugging pasó de 86,2 a 25,9; refactoring de 73,6 a 38,4; alucinaciones de 75,9 a 61,7.
- Sin embargo, Wolfe indica que en su experiencia personal el modelo **se siente igual que antes**. No ha recibido ningún bloqueo inesperado en sus pruebas, incluyendo proyectos complejos como un dashboard de creación de vídeos cortos, un generador de B-roll para artículos, y el propio BuseyBench.
- **Limitación temporal**: el acceso a Fable 5 incluido en los planes de pago solo está garantizado hasta el **7 de julio**. Después, requerirá créditos de uso adicionales. Wolfe recomienda aprovechar estos días para que Fable realice el trabajo pesado de proyectos grandes, y luego continuar con Opus o GPT-5.5 para los ajustes incrementales.

#### BuseyBench: el benchmark más absurdo (y revelador)

Wolfe presenta **BuseyBench** (buseybench.com), un benchmark que mide la capacidad de los modelos de IA para generar imágenes SVG del rostro de **Gary Busey**. Construido íntegramente con Fable 5, el sitio permite:

- Ver la evolución de modelos desde **GPT-3.5 Turbo (marzo 2023)** hasta los modelos más recientes.
- Ordenar resultados por **coste** (GPT-5.5 Pro: $4 por SVG; O1 Pro: $3), **tokens usados** (Grok 420: 106.000 tokens) o **duración de ejecución** (GLM 5.1: 6 min 50 s).
- Filtrar por **proveedor** para ver la evolución temporal de cada familia de modelos.
- La progresión es clara: los modelos mejoran visiblemente con el tiempo en su capacidad de generar código SVG que se asemeje a un rostro humano.
- También incluye un apartado para generadores de imágenes (MidJourney V1 → Nano Banana 2 Light / GPT Image 2), aunque menos desarrollado.

#### GPT 5.6: Sol, Terra y Luna

OpenAI anunció oficialmente **GPT 5.6**, su nueva generación de modelos, en tres variantes: **Sol** (la más potente, comparable a Fable/Mythos), **Terra** (intermedia, similar a Sonnet) y **Luna** (la más ligera, similar a Haiku). Sin embargo, el acceso está **extremadamente restringido**:

- Solo disponible mediante API para un grupo selecto de socios y organizaciones de confianza.
- **Sol Ultra** puntúa un **91,9% en Terminal Bench** frente al 84,3% de Fable.
- Terra iguala a Fable en Terminal Bench.
- Precios: Sol a **$5 input / $30 output** — aproximadamente la mitad que Fable ($10/$50).
- Wolfe especula que OpenAI podría activar el acceso general justo el **7 de julio**, cuando expire el periodo gratuito de Fable 5.

#### OpenAI ofrece un 5% al gobierno de Trump

Wolfe cubre una noticia que le genera sentimientos encontrados: OpenAI habría ofrecido al gobierno de Trump una **participación del 5% en la compañía** (valorado en ~$42.600 millones) como medida para aliviar tensiones regulatorias y compartir el beneficio económico de la IA con el público. Wolfe señala el conflicto de intereses: si el gobierno tiene participación en la empresa que debe regular, se incentiva una regulación más laxa para maximizar el valor de esa participación.

#### Claude Sonnet 5: nuevo pero no frontera

Anthropic lanzó **Claude Sonnet 5**, un modelo de gama media que mejora respecto a Sonnet 4.6 en trabajo de conocimiento y reduce comportamientos indeseables, pero **no alcanza el nivel de Opus, Mythos o Fable**. La propia Anthropic lo reconoce explícitamente en su system card. Su principal ventaja es el precio: **$2 input / $10 output** (hasta el 31 de agosto, luego $3/$15). Wolfe lo probó en BuseyBench: Sonnet 5 genera un SVG de Gary Busey decente, pero inferior a Fugu Ultra, Quinn 3.7 y Gemini 3.5 Flash.

#### Novedades de Google: Nano Banana 2 Light, Omni Flash y más

Google lanzó varias actualizaciones:

- **Nano Banana 2 Light**: genera imágenes en **4 segundos** a un coste de ~3,5 centavos por 1.000 imágenes. Wolfe lo probó en Gemini (Ultra plan): resultados rápidos y sólidos.
- **Gemini Omni Flash**: versión más rápida y barata de Gemini Omni para generación y edición de vídeo. Disponible vía API a 10 centavos/segundo. Wolfe lo probó en Gemini con un vídeo de Google IO: añadió Godzilla a la escena, aunque tuvo problemas con el API (errores internos del servidor).
- **NotebookLM**: ahora permite crear **vídeos cortos verticales de 60 segundos** a partir de notebooks. Wolfe lo probó: el resultado tardó ~30 minutos y la calidad fue básica (imágenes simples y voz narrada).
- **Gemini Meet Notes**: toma notas automáticas en reuniones de Google Meet, con resúmenes y action items guardados en Google Docs.
- **Gemini Spark para macOS**: la respuesta de Google a OpenClaw ya disponible en macOS para suscriptores Ultra. Wolfe demostró cómo Spark organizó su carpeta de descargas automáticamente.

#### Ronda rápida

- **Claude Science**: Anthropic lanzó un workbench de IA para científicos, disponible en Mac/Linux para suscriptores de pago.
- **Cursor iOS**: aplicación móvil que permite lanzar y controlar agentes en la nube desde el teléfono.
- **X MCP Server**: X (Twitter) lanzó un servidor MCP para facilitar la integración de agentes con su plataforma.
- **OpenAI Codex Hardware**: teaser de un macro pad físico diseñado específicamente para Codex, con lanzamiento previsto para el **15 de julio**.

#### Reflexión final / Conclusiones

Wolfe cierra reconociendo que la semana ha sido abrumadora en cantidad y profundidad de noticias: el regreso de Fable 5 con restricciones, la llegada de GPT 5.6 con acceso limitado, y los movimientos estratégicos de OpenAI con el gobierno marcan una nueva era de **regulación y restricción** en el acceso a modelos de frontera. El creador reafirma su compromiso de publicar resúmenes semanales cada viernes para que su audiencia no tenga que seguir todas las fuentes por su cuenta.

---

### 🔗 Referencias

- 📄 Redeploying Fable 5 (Anthropic): https://www.anthropic.com/news/redeploying-fable-5
- 🔗 Fable 5 Nerfed (Bridgemind): https://x.com/bridgemindai/status/2072662214704533888
- 🏢 BuseyBench: https://buseybench.com/
- 📄 Previewing GPT-5.6 Sol (OpenAI): https://openai.com/index/previewing-gpt-5-6-sol/
- 📄 OpenAI Government Stake (The Verge): https://www.theverge.com/ai-artificial-intelligence/960588/openai-government-5-percent-stake-trump
- 📄 Claude Sonnet 5 (Anthropic): https://www.anthropic.com/news/claude-sonnet-5
- 📄 Gemini Omni Flash / Nano Banana 2 Lite (Google): https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-omni-flash-nano-banana-2-lite/
- 🔗 NotebookLM Video Overviews: https://x.com/NotebookLM/status/2071987494799716626
- 📄 Claude Science Workbench: https://www.anthropic.com/news/claude-science-ai-workbench
- 🏢 Cursor for iOS: https://cursor.com/blog/ios-mobile-app
- 📄 X MCP Server (TechCrunch): https://techcrunch.com/2026/06/30/x-now-offers-an-mcp-server-to-make-its-platform-easier-for-ai-tools-to-use/
- 📄 Gemini Meet Notes (Google): https://blog.google/products-and-platforms/products/workspace/take-notes-for-me/
- 📄 Gemini Spark Updates (Google): https://blog.google/innovation-and-ai/products/gemini-app/gemini-spark-updates-june-2026/
- 📄 OpenAI Codex Hardware (The Verge): https://www.theverge.com/ai-artificial-intelligence/959174/openai-codex-hardware-work-louder


## [Matt Wolfe] GLM-5.2 Proves Open-Source AI is Finally Good Now!
**Fecha:** 2026-07-01
**URL:** https://www.youtube.com/watch?v=XbHeJL45USQ
**Video ID:** XbHeJL45USQ

### 📝 Resumen

Matt Wolfe pone a prueba **GLM-5.2**, el nuevo modelo insignia de Z.AI (Zhipu AI), un modelo de pesos abiertos con licencia MIT que está generando un enorme revuelo en la comunidad de IA. Con un contexto de **1 millón de tokens**, capacidad de output de **128.000 tokens**, y un coste **5 veces menor** que modelos frontera como Opus 4.8, Wolfe explora qué puede hacer realmente este modelo y dónde se queda corto. El vídeo incluye pruebas en la web de ZAI, en el harness de Cursor, y demostraciones de creación de juegos, extensiones de Chrome, automatizaciones y animaciones.

#### ¿Qué es GLM-5.2 y por qué importa?

GLM-5.2 es un modelo de **753 mil millones de parámetros**, con pesos abiertos y licencia MIT. Sin embargo, Wolfe aclara un malentendido común: **pesos abiertos no significa ejecutable en casa**. El modelo ocupa más de **1,5 terabytes** descargado; incluso una versión cuantizada a 1 bit necesitaría unos 200 GB de memoria. No es un modelo para consumidores, sino para empresas y proveedores de infraestructura.

Las tres formas de acceder al modelo son:

- **Nivel 1 (web)**: usar z.ai directamente, gratuito y sin límite aparente.
- **Nivel 2 (API)**: conectar el modelo a aplicaciones propias o harness de agentes (Cursor, OpenCode, Claude Code).
- **Nivel 3 (self-hosted)**: alquilar GPUs en la nube o tener un superordenador propio.

Wolfe destaca que lo emocionante no es que cualquiera pueda ejecutarlo, sino que **el ecosistema puede construirse sobre él**: se puede alojar, optimizar, y compite en precio, reduciendo la dependencia de los grandes laboratorios cerrados.

- El modelo soporta **function calling, output estructurado, context caching y MCP**.
- Está claramente optimizado para **codificación y workflows agentivos**.
- **Empresas occidentales** como Lindy (DeepSeek V4), Cursor (Kimi 2.5) y Coinbase (GLM 5.2) ya están migrando cargas de trabajo a modelos chinos por ser más baratos y con menor riesgo regulatorio.

#### Pruebas en la web de ZAI: lógica, ética y creatividad

Wolfe realizó múltiples pruebas directamente en z.ai:

- **Página web**: el modelo creó una web HTML limpia y funcional con scroll automático, comparable a lo que harían Opus o GPT-5.5.
- **Pruebas de lógica**: acertó "cuántas R tiene strawberry" (3) y la pregunta del coche ("deberías conducir, necesitas llevar el coche al lavadero").
- **Prueba de contradicción**: detectó correctamente la incoherencia entre "rehabilitación de espalda" y "peso muerto de 300 libras".
- **Prueba ética (Ponzi scheme)**: accedió a detallar un esquema Ponzi cuando se enmarcó como parte de una novela, lo que Wolfe considera un comportamiento esperable.
- **Detección de IA**: al pedirle una introducción que "no sonara a IA", GPTZero la detectó como **100% generada por IA**, con frases hechas típicas.
- **Gráfico SVG**: creó un gráfico visual de la evolución de los LLMs chinos, comparable en calidad a GPT-5.5 pero a una fracción del coste.

#### BuseyBench: el primer test de SVGs de Gary Busey

Wolfe introduce un nuevo benchmark humorístico: **BuseyBench**, que mide la capacidad de los modelos para generar un SVG de la cara de Gary Busey. GLM-5.2 obtuvo un resultado "sorprendentemente bueno" para ser la primera entrada. También generó un SVG de un mono en patines, con resultado aceptable aunque con una radio a cuestas.

#### Usando GLM-5.2 en Cursor: juegos, extensiones y automatizaciones

La parte más potente del vídeo muestra GLM-5.2 dentro de **Cursor** como modelo de agente:

- **MegaBonk clone**: tras 6 prompts, Wolfe logró un clon funcional del juego 3D MegaBonk con controles, cámara y daño a enemigos. La calidad gráfica fue inferior a la lograda con Fable, pero considerando que el coste es **5 veces menor**, el resultado es impresionante para un modelo open-weight.
- **Chrome Extension (Page Brief)**: en 2 intentos, el modelo creó una extensión que resume páginas web, extrae action items y enlaces clave, y exporta a markdown. Funcionó correctamente tras una iteración de feedback.
- **Organización de descargas**: el modelo organizó la carpeta de descargas de Wolfe en subcarpetas (videos, imágenes, documentos, etc.) en 3 minutos y 16 segundos.
- **Mejora continua ("Improve Your Matt")**: Wolfe conectó GLM-5.2 con **Granola** (toma de notas de reuniones) para crear un skill que, cada viernes, analiza las reuniones de la semana, identifica problemas recurrentes y genera herramientas/skills como soluciones. El sistema encontró 7 problemas en reuniones del 22 de junio y creó 3 skills, incluyendo un **generador de hooks para vídeos cortos** (Hook Lab) que produce 5 variantes de hooks virales.

#### Animaciones con Remotion

GLM-5.2 también se probó con **Remotion** para crear animaciones. Generó un gráfico de barras animado comparando GLM-5.2 con GPT-5.5, Opus 4.6 y Gemini 3.5 en SWE-Bench Pro. Aunque la primera versión tenía texto solapado, tras una corrección el resultado fue funcional.

#### Inference.net: cambio de modelo sin riesgo

Wolfe destaca la herramienta **Inference.net** de Sam Hogan, que permite instalar un gateway para **reflejar tráfico en vivo** a GLM-5.2 mientras se sigue usando el proveedor actual. En 24 horas, un modelo de reinforcement learning genera evaluaciones, y si son positivas, se puede cambiar el modelo sin riesgo de caídas en producción.

#### Reflexión final / Conclusiones

Wolfe concluye que GLM-5.2 **no es un modelo para usar ciegamente en todo**. No supera a Claude, GPT o Gemini en todas las métricas, pero es **uno de los modelos más interesantes para probar ahora mismo** por la combinación de: API barata, pesos abiertos, contexto masivo, fuerte capacidad de codificación, workflows agentivos, y la garantía de que **no será prohibido por el gobierno de EE.UU.** al ser open-weight. El mensaje clave: si tu tarea es larga, intensiva en código, con muchos documentos, agentiva o costosa en tokens, GLM-5.2 merece una prueba. La presión competitiva de modelos chinos baratos y abiertos está obligando a los grandes laboratorios a reaccionar.

---

### 🔗 Referencias

- 📄 Z.AI GLM-5.2: https://z.ai
- 💻 Repositorio GLM-5.2 (Hugging Face): enlace en descripción
- 🔗 GPTZero: https://gptzero.me
- 🏢 FutureTools.io (newsletter de Matt Wolfe): https://futuretools.io/newsletter
- 🏢 Inference.net: https://inference.net
- 🏢 Granola (toma de notas AI): https://granola.ai
- 🔗 Remotion: https://remotion.dev
- 🏢 BuseyBench: https://buseybench.com

---

## [Matt Wolfe] AI News: The New Model That's As Good As Fable
**Fecha:** 2026-06-26
**URL:** https://www.youtube.com/watch?v=zMVZvgCOr40
**Video ID:** zMVZvgCOr40

### 📝 Resumen

Matt Wolfe repasa las noticias más destacadas de la semana en inteligencia artificial. Aunque el volumen de novedades fue reducido, varias historias tuvieron un impacto significativo: el lanzamiento de Sakana Fugu (un orquestador de modelos que compite con Fable 5), la llegada de Claude Tag (la integración de Anthropic con Slack), y la noticia de que el gobierno de EE.UU. está interviniendo directamente en cómo OpenAI despliega sus nuevos modelos. Wolfe también cubre una ronda rápida con avances en video, pesos abiertos y chips de inferencia.

#### Sakana Fugu: un orquestador que compite con Fable 5

Sakana AI lanzó **Sakana Fugu**, un modelo que no es un LLM tradicional sino un **orquestador o gestor** que decide qué modelo(s) usar para cada prompt. Si un proveedor falla, enruta automáticamente a otro sin pérdida de progreso. Está disponible en dos variantes:

- **Fugu (estándar)**: equilibra rendimiento con baja latencia, ideal para tareas cotidianas.
- **Fugu Ultra**: optimizado para problemas complejos de múltiples pasos, priorizando la calidad máxima.

En benchmarks clave, Fugu Ultra supera a Fable 5 en **Live Code Bench** y **Google Proof Q&A**, y está a la par en **SciCode**. Solo cede en **Sweet Bench Pro**. Wolfe probó ambos modelos construyendo dos aplicaciones: un clon de Megabonk (que terminó pareciéndose más a Vampire Survivor) y un clon completo de FutureTools.io. El coste total fue de **30 dólares** (22M tokens de entrada, 210K de salida). La calidad visual del clon de Megabonk fue inferior a la lograda con Fable 5, pero el clon de FutureTools funcionó sorprendentemente bien con filtros, shortlists y páginas funcionales.

- **Acceso**: disponible vía console.sakana.ai con API key, integrable con Codex CLI.
- **Conclusión**: Fugu ofrece un enfoque novedoso de enrutamiento multi-modelo, pero no reemplaza la calidad de salida de Fable 5 en tareas creativas complejas.

#### Claude Tag: Anthropic entra en Slack como un colega más

Anthropic anunció **Claude Tag**, una integración que permite etiquetar a @Claude directamente en Slack como si fuera otro miembro del equipo. Las características principales incluyen:

- Claude puede descomponer proyectos en múltiples pasos, usar herramientas corporativas y trabajar en segundo plano.
- **Aprendizaje y memoria**: al estar presente en los canales, Claude aprende el contexto de la empresa de forma continua.
- **Iniciativa proactiva**: si está habilitado, Claude interviene voluntariamente cuando detecta que puede ayudar.
- **Seguridad corporativa**: los administradores deciden qué canales y datos puede ver.
- Anthropic afirma que el **65% de su propio código** se escribe ya usando esta función.

Andrej Karpathy calificó Claude Tag como el **tercer gran paradigma** en la interacción con IA: primero fueron los chats web (ChatGPT), luego las apps de escritorio (Claude Code), y ahora la IA integrada directamente en las herramientas que ya usas (Slack). El acceso está limitado a planes Teams y Enterprise.

#### GPT 5.6 y el control gubernamental sobre los lanzamientos

La noticia más polémica de la semana: el gobierno de Trump ha solicitado a OpenAI que **escalone la liberación de GPT 5.6** por motivos de seguridad. Según un memo interno citado por The Information, Sam Altman comunicó al equipo que el gobierno aprobaría el acceso **cliente por cliente** durante un periodo de previsualización. Se espera un lanzamiento general en 'unas semanas' si todo va bien.

Wolfe reflexiona sobre las implicaciones:

- Este modelo estaría al nivel de Fable 5, lo que explicaría la cautela gubernamental tras la polémica con Fable (que sigue sin estar disponible públicamente).
- OpenAI ha dejado claro que 'no es el modelo preferido a largo plazo' y trabajará con el gobierno para un marco sostenible.
- Podría significar el **fin de la era del 'salvaje oeste'** en IA, donde los modelos simplemente aparecían sin previo aviso.

#### Ronda rápida: Seed Dance 2.5, Krea 2, y más

- **Seed Dance 2.5**: ByteDance presentó un avance de su nuevo modelo de video que genera **30 segundos** (el doble que 2.0), soporta hasta **50 materiales de referencia** (texto, imagen, audio, video), y ofrece control más fino sobre movimiento y edición. Aún sin fecha de lanzamiento.
- **Krea 2 open weights**: Krea AI liberó los pesos de su modelo Krea 2, permitiendo descargarlo, afinarlo y ejecutarlo localmente al estilo Stable Diffusion o Flux.
- **The Atlantic AI Watchdog**: un buscador público que permite consultar qué música con copyright se usó para entrenar modelos como Suno y Udio. Incluye 150 canciones de Blink-182 e incluso **221 vídeos de YouTubers** como Moist Critical.
- **OpenAI + Broadcom**: anunciaron el desarrollo de un **chip de inferencia propio**, compitiendo indirectamente con Cerebras (con quien OpenAI también tiene acuerdo). Esto podría abaratar y acelerar el uso de ChatGPT.
- **Meta Ray-Ban**: 26 nuevos estilos y monturas, incluyendo colaboración con Kylie Jenner. Nuevos modelos Adventurer y Fury.

#### Reflexión final / Conclusiones

Wolfe cierra reconociendo que, aunque fue una semana con pocas noticias, las que hubo fueron de gran calado. La combinación de un orquestador como Sakana Fugu, la integración profunda de Claude en Slack, y la intervención gubernamental en los lanzamientos de modelos marcan un punto de inflexión en la industria. El creador recomienda seguir sus canales para mantenerse al día sin saturarse.

---

### 🔗 Referencias

- 🏢 Sakana AI console: https://console.sakana.ai
- 🏢 Nexos (sponsor): https://nexos.ai/wolf
- 📄 Claude Tag announcement: https://www.anthropic.com/news/claude-tag
- 📄 The Atlantic AI Watchdog: https://www.theatlantic.com/category/ai-watchdog
- 📄 GPT 5.6 staggered release (The Information)
- 🏢 Krea AI open weights: https://krea.ai

