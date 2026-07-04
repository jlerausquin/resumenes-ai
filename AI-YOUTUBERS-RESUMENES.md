# 📹 Resúmenes Diarios — IA YouTubers

---

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

## [Javier Garzás] Most people use ChatGPT/Claude to chat and NOT to manage. 15 tricks to change that
**Fecha:** 2026-07-01
**URL:** https://www.youtube.com/watch?v=XW-gFpXTVpM
**Video ID:** XW-gFpXTVpM

### 📝 Resumen

Javier Garzás aborda una realidad que observa en 2026: profesionales con años de experiencia usan ChatGPT o Claude como si fueran meros buscadores con superpoderes, para redactar correos o hacer resúmenes. El vídeo presenta **15 trucos progresivos** (de menor a mayor complejidad) para transformar la IA de un chat conversacional a una **máquina de gestión autónoma**. Garzás utiliza Claude como referencia, pero señala que todos los conceptos aplican a cualquier chatbot de IA, incluyendo ChatGPT.

#### Memoria y contexto: el primer escalón

El primer consejo es el más básico pero fundamental: la IA debe conocer los **mínimos del proyecto, producto u organización**. Para ello existe la funcionalidad de **memoria** en todos los chatbots. Garzás explica que el contexto es aquello que la IA desconoce porque ocurrió después de su entrenamiento, y que el usuario debe proporcionarle: nombre del equipo, organización, años de experiencia, tipo de cliente, etc. Configurar esto permite que cada respuesta esté automáticamente contextualizada.

- **Acción**: escribir en la memoria cómo se llama el equipo, la organización, el tipo de cliente y otros datos permanentes.
- **Beneficio**: la IA contextualiza cada respuesta sin necesidad de repetir la información en cada prompt.

#### Selector de modelos: economía de tokens

Garzás compara los distintos modelos (LLMs) dentro de un chatbot con los perfiles profesionales de una organización: hay gente más preparada (consume más recursos) y gente junior (más barata, para tareas simples). En Claude los niveles son **Opus** (más potente, caro), **Sonnet** (intermedio) y **Haiku** (básico, barato). La clave es usarlos según la complejidad de la tarea:

- **Opus**: para tareas estratégicas como priorización de backlog con OKRs vía MCP.
- **Sonnet**: para tareas intermedias.
- **Haiku**: para tareas sencillas como redactar correos triviales.
- Esto no solo optimiza velocidad, sino que **economiza tokens**, cuyo coste equipara a la gasolina o el Bitcoin en importancia.

#### MCPs: conectar la IA con las herramientas del día a día

Los puntos 3 y 4 se centran en los **MCPs (Model Context Protocol)**, que permiten al chatbot leer y escribir datos de otras aplicaciones.

- **Punto 3**: conectar el chatbot al **gestor de correo electrónico y calendario** (Gmail, Google Calendar). Garzás recomienda que la interfaz de entrada del gestor sea el propio chatbot, no el cliente de correo. El chatbot puede leer correos, gestionar la agenda y crear eventos recurrentes mucho más rápido que haciéndolo manualmente.
- **Punto 4**: conectar el chatbot a las **herramientas de gestión de tareas** (Jira, Notion, etc.) vía MCP. El gestor de productos puede así gestionar tickets, priorizar y leer historias de usuario directamente desde el chatbot, sin entrar en la herramienta.

#### Artefactos y visuales interactivos

Garzás dedica los puntos 5 y 6 a la **visualización**. La mayoría de chatbots tienen una funcionalidad de **artefactos** que crea pequeñas aplicaciones integradas dentro del chat para visualizar datos:

- **Artefactos**: informes visuales, métricas, OKRs, datos financieros. Se pueden crear desde los datos extraídos vía MCP.
- **Visuales interactivos**: **user story maps**, **customer journeys**, y otras técnicas clásicas de product management que antes se hacían en pizarras físicas. Ahora se pueden crear, visualizar e interactuar con ellas mediante el LLM.

#### Proyectos: la organización del conocimiento

El punto 7 es uno de los que Garzás considera imprescindibles. Los **proyectos** (en Claude) son carpetas que agrupan conversaciones sobre un mismo tema (cliente, producto, actividad). Las ventajas son:

- Una **instrucción común** que da contexto adicional a todas las conversaciones del proyecto.
- **Ficheros compartidos** (PDFs, requerimientos) que todas las conversaciones pueden leer.
- **Memoria compartida** entre conversaciones del mismo proyecto, permitiendo que lo dicho en una conversación sea conocido por otra.

#### No escribas: usa la voz

El punto 8 es un cambio de hábito: **dejar de escribir y empezar a hablar**. Escribir es lento y anticuado. Garzás recomienda usar el micrófono integrado de los chatbots o herramientas externas como **Whisper Flow**, que transcribe la voz a texto no solo en el chatbot sino en cualquier campo de texto (correos, tickets en Notion, etc.).

#### Scraping vía extensión de Chrome

El punto 9 presenta una funcionalidad poco conocida: la **extensión de Chrome para Claude** que permite hacer **scraping** (simular que el usuario hace scroll y clics en cualquier web). Esto es especialmente útil para **discovery**: analizar webs de la competencia, tendencias del sector, etc. La IA recorre la web automáticamente mediante un prompt, ahorrando horas de navegación manual.

#### Claude Cowork: la aplicación de escritorio

El punto 10 introduce **Claude Cowork**, la aplicación de escritorio de Anthropic que ha cambiado la forma de trabajar de Garzás. Al estar instalada localmente, puede:

- Interactuar con **ficheros** (PDFs, facturas, documentos escaneados).
- Leer, sintetizar, abrir, mezclar y unir archivos.
- Hacerlo todo más rápido y consumiendo menos tokens que desde el navegador.

#### Tareas programadas y Dispatch

Los puntos 11 y 12 llevan la automatización al siguiente nivel:

- **Tareas programadas**: Claude Cowork puede ejecutar acciones recurrentes (revisar el backlog los lunes, comprobar incidencias de clientes cada noche) sin intervención manual.
- **Dispatch**: permite enviar instrucciones desde el móvil al entorno de escritorio local. Ideal para cuando se está de viaje, en un aeropuerto o en una gasolinera, y se recuerda algo importante que necesita ejecutarse en el equipo local.

#### Claude Code: el salto para no técnicos

El punto 13 aborda **Claude Code**, la herramienta de programación asistida por IA. Garzás anima a los no técnicos a perderle el miedo, porque permite:

- Convertir un requerimiento de Jira (vía MCP) en un **prototipo funcional** que se puede ver y enseñar al equipo, sin necesidad de que un desarrollador lo implemente.
- Gestionar repositorios en GitHub (guardar ficheros locales en servidores).
- Garzás afirma que "cuando empiezas con Claude Code es un antes y un después; no vuelves hacia atrás".

#### Skills: el estándar del futuro

El punto 14 es sobre las **skills**: prompts empaquetados en un formato estándar que pueden usarse en cualquier entorno (Claude, ChatGPT, etc.). Existen repositorios de skills con técnicas de product management como:

- Priorización de backlog
- Creación de historias de usuario
- Mapas de historia de usuario
- Customer journeys
- Técnicas de entrevista y personas

Garzás considera que dominar las skills es tan ineludible para un profesional digital como saber leer o hablar.

#### Claude Design: diseñar sin ser diseñador

El punto 15 cierra con **Claude Design**, una herramienta de diseño integrada con Claude Code. Permite:

- Crear diseños con estilos, tendencias y coherencia visual.
- Integrarse con Claude Code para que el diseño se convierta directamente en código.
- Que un gestor de producto pueda **enseñar diseños funcionales a su equipo** sin depender de un diseñador ni esperar sprints enteros. Ejemplo concreto: una **landing page básica** que antes requería un equipo técnico, ahora la puede hacer una sola persona.

#### Reflexión final / Conclusiones

Garzás sintetiza su mensaje: **no te puedes quedar en usar un chatbot para escribir correos o corregir ortografía**. Hay que convertir la IA en una máquina que dé superpoderes para salir del rol del "gestor tradicional" (que solo leía tickets, escribía historias de usuario y coordinaba reuniones) y convertirse en un **builder, un creador**. Los 15 trucos permiten visualizar, mezclar datos, crear prototipos, diseñar y programar sin ser técnico. El salto es de "chatear" a "gestionar con IA", y separa al profesional que va 10x del que se queda atrás. Invita a unirse a su comunidad de WhatsApp para seguir aprendiendo.

---

### 🔗 Referencias

- 🏢 Comunidad WhatsApp de Javier Garzás: enlace en la descripción del vídeo
- 🔗 Whisper Flow: herramienta de transcripción por voz
- 🔗 Extensión de Chrome para Claude (scraping)
- 🔗 Claude Cowork (aplicación de escritorio de Anthropic)
- 🔗 Claude Code (herramienta de programación asistida por IA)
- 🔗 Claude Design (herramienta de diseño de Anthropic)
- 🏢 Anthropic: https://www.anthropic.com

## [Matthew Berman] "The best thing since OpenClaw" (Hermes Tutorial)
**Fecha:** 2026-06-28
**URL:** https://www.youtube.com/watch?v=TML-0HmxWCE
**Video ID:** TML-0HmxWCE

### 📝 Resumen

Matthew Berman presenta una tutorial práctico sobre **Hermes Agent**, la plataforma de agentes de IA creada por Nous Research, patrocinado por Hostinger. Berman lo califica como "lo mejor desde OpenClaw" y demuestra su instalación en menos de dos minutos, destacando las diferencias clave frente a alternativas como OpenClaw. El vídeo recorre todas las capacidades principales del sistema: desde la configuración inicial hasta la integración con Telegram, pasando por skills, plugins, memoria, perfiles y automatizaciones programadas.

#### Instalación ultrarrápida con Hostinger

Berman muestra el proceso completo de instalación. Usando el plan de Hostinger (con un 73% de descuento mediante enlace patrocinado), el proceso es completamente automatizado:

- Selección del plan y configuración del proveedor (OpenAI en este caso).
- Creación de una API key en platform.openai.com y pegarla en el panel de Hostinger.
- Hostinger configura Hermes automáticamente en menos de 2 minutos.
- Tras la instalación, Berman configura su modelo por defecto como GPT 5.4 Mini y verifica que el agente responde correctamente.

- **Diferencia clave**: a diferencia de instalar localmente en un Mac Mini o servidor propio, Hostinger provee un entorno aislado y gestionado, eliminando la necesidad de mantenimiento de infraestructura.

#### Skills preinstalados y personalización

Hermes viene con una amplia colección de **skills** activados por defecto, algo que lo diferencia significativamente de OpenClaw. Berman recorre el panel de skills:

- Skills incluidos de serie: Claude Code, Codex, Hermes Agent (auto-referencia), Manim (animaciones matemáticas), Manim Video, Excalidraw (diagramas), entre muchos otros.
- Cada skill se puede leer, activar o desactivar con un simple clic.
- **Instalación de nuevos skills**: Berman demuestra instalando el skill "Last 30 Days" desde GitHub. El proceso consiste en copiar el archivo `SKILL.md` del repositorio, pegarlo en el panel de skills de Hermes y nombrarlo. Tras crearlo, se invoca escribiendo `/` en el chat y seleccionando el skill.
- **Auto-reparación (self-healing)**: durante la demostración, el skill requería un archivo adicional que no estaba presente. Hermes detectó el problema automáticamente, descargó el repositorio en un directorio temporal y continuó la ejecución sin intervención del usuario.

#### Automatizaciones con Tasks

El sistema de **Tasks** permite crear automatizaciones programadas, similares a los loops de OpenClaw pero más accesibles:

- Creación mediante una interfaz gráfica: nombre, programación (ej. cada 24 horas), prompt descriptivo.
- Berman crea un "Daily Brief" que revisa su calendario y resume las reuniones del día.
- Los tasks pueden incluir skills específicos y entregar la salida directamente al chat.
- Todos los trabajos programados se listan y gestionan desde un panel central.

#### Memoria y Perfiles

Hermes incorpora un sistema de **memoria persistente** que se construye automáticamente con el uso:

- **Agent Soul**: documento central (equivalente a `identity.md`/`soul.md` de OpenClaw) que define la personalidad del agente. Berman edita el suyo para que hable como un pirata, demostrando el cambio de comportamiento en tiempo real.
- **Memoria explícita**: el usuario puede añadir información sobre sí mismo (nombre, empresa, newsletter) que el agente recordará en futuras interacciones.
- **Perfiles múltiples**: permite tener varios agentes especializados (marketing, desarrollo, etc.) cada uno con su propio conjunto de skills, memoria y configuración. Esto evita tener un agente "hinchado" con todas las capacidades mezcladas.

#### Panel de control e Insights

Hermes ofrece un panel analítico con datos de uso:

- Tokens consumidos diariamente (Berman muestra ~73,000 tokens).
- Número de mensajes y sesiones.
- Visibilidad granular del comportamiento del agente a lo largo del tiempo.

#### Configuración de proveedores y enrutamiento de modelos

Una de las fortalezas más destacadas de Hermes es su soporte extensivo de **proveedores de inferencia**:

- Proveedores compatibles: OpenAI, Anthropic, Copilot, DeepSeek, Gemini, Kimi, LM Studio (local), Mistral, Nexos, Nous Portal, Nvidia Nims.
- **Enrutamiento de modelos**: permite asignar modelos específicos para distintas tareas (visión, compresión, extracción web, búsqueda de sesiones, aprobación). Opción "auto" para delegar la decisión al sistema.
- **Plugins**: funcionalidades completas pre-integradas como Browser Use, FireCrawl (web scraping), Discord, Google Chat, Google Meet. También se pueden crear plugins propios.

#### Integración con Telegram

Berman demuestra la conexión de Hermes con **Telegram** como canal de comunicación:

- Desde el CLI de Hermes ejecuta `hermes gateway setup`.
- Selecciona Telegram de una lista extensa que incluye Slack, Matrix, Mattermost, WhatsApp, Signal, Email.
- Crea un bot en Telegram vía BotFather, copia el token y lo pega en Hermes.
- Configura los IDs de usuario permitidos para control de acceso.
- En menos de 5 minutos, Berman tiene su agente Hermes funcionando desde Telegram, manteniendo el contexto (incluyendo la personalidad pirata que configuró antes).

#### Demostración: generación de vídeo con Manim

Como demo final, Berman usa el skill **Manim Video** para crear un vídeo educativo animado:

- Prompt: "Crea un vídeo explicando cómo funcionan los exponenciales".
- En pocos minutos, Hermes genera un MP4 de 58 segundos con gráficos animados explicando el crecimiento exponencial mediante multiplicación repetida.
- El vídeo se reproduce directamente desde el chat, demostrando la capacidad multimodalde Hermes.

#### Reflexión final / Conclusiones

Berman concluye que Hermes Agent representa un salto significativo en accesibilidad para agentes de IA. La combinación de instalación en 2 minutos, skills preinstalados, auto-reparación, amplio soporte de proveedores, integración con canales de mensajería y perfiles múltiples lo convierten en una opción superior para usuarios técnicos y no técnicos por igual. El patrocinio de Hostinger elimina la barrera de la infraestructura, ofreciendo un entorno aislado y gestionado. Recomienda el enlace en la descripción para obtener descuentos y anima a los espectadores a probarlo.

---

### 🔗 Referencias

- 🏢 Hostinger (sponsor): https://hostinger.com/matthewhermes (código MATTHEWB para 10% descuento)
- 🏢 Hermes Agent: https://hermes-agent.nousresearch.com
- 🏢 Forward Future Newsletter: https://forwardfuture.ai

## [Matthew Berman] I can't believe this happened...

**Fecha:** 2026-06-26
**URL:** https://www.youtube.com/watch?v=eEdOqSmkZy0
**Video ID:** eEdOqSmkZy0

### 📝 Resumen

Matthew Berman ofrece un análisis profundamente crítico sobre la intervención del gobierno estadounidense en el lanzamiento de GPT 5.6 y las implicaciones para toda la industria de la IA. Por primera vez en tres años cubriendo el sector, Berman se muestra abiertamente pesimista. Señala directamente a Dario Amodei y Anthropic como los principales responsables de lo que considera una **captura regulatoria** que frenará la innovación, concentrará el poder en unas pocas empresas y perjudicará a desarrolladores, startups y usuarios finales.

#### La captura regulatoria de Anthropic

Berman argumenta que Anthropic ha llevado a cabo una campaña sistemática de **marketing del miedo** que culminó en la intervención gubernamental. Los pasos de esta estrategia incluyen:

- Anthropic lanzó Mythos (Fable 5) solo para un grupo selecto de empresas, generando un precedente de acceso restringido.
- La compañía difundió informes sobre cómo Alibaba estaba realizando **ataques de destilación** contra Claude, acusando a China de robar capacidades de sus modelos.
- Tras el lanzamiento público de Fable 5, el gobierno ordenó restringir el acceso a ciudadanos estadounidenses. Anthropic respondió retirando el modelo por completo.
- Este ciclo de 'modelo peligroso → lanzamiento restringido → gobierno interviene → retirada total' se ha convertido en el nuevo estándar.

Berman cita a **Bill Gurley**, el famoso VC, quien afirma que Anthropic podría haber demandado a los infractores chinos, pero optó por buscar **protección gubernamental contra la competencia**, algo que un tribunal no puede proporcionar. Gurley señala la inconsistencia: si los modelos están al borde de la AGI, ¿por qué no pueden detectar ataques de destilación en tiempo real?

#### GPT 5.6: lanzamiento escalonado

La noticia desencadenante: el gobierno de EE.UU. pidió a OpenAI que **escalone el lanzamiento de GPT 5.6**, siguiendo el modelo que Anthropic estableció con Mythos. Los detalles clave:

- Solo un grupo reducido de empresas seleccionadas tendrá acceso inicial.
- Sam Altman informó al equipo que el gobierno aprobaría **cliente por cliente** durante el periodo de previsualización.
- OpenAI declaró públicamente que 'no cree que este proceso deba convertirse en el estándar a largo plazo', pero acepta la medida como un paso temporal.
- **Noam Brown**, investigador de OpenAI, confirmó que GPT 5.6 es 'increíblemente fuerte y rápido para código'.
- El modelo tiene capacidades avanzadas de ciberseguridad (ataque y defensa), lo que motivó la cautela gubernamental.

#### Concentración de poder: el verdadero problema

Berman desarrolla las consecuencias sistémicas de la regulación asimétrica:

- **Ventaja para los incumbentes**: las grandes empresas que ya tienen relaciones con el gobierno y pueden saltar obstáculos regulatorios reciben los modelos primero. Startups y desarrolladores independientes se quedan con modelos de 6 meses de antigüedad.
- **Efecto compounding**: las empresas con acceso al modelo de frontera lo usan para construir la siguiente generación de software, acelerándose aún más frente a quienes no lo tienen.
- **OpenAI retrasa su IPO hasta 2027** según The New York Times. Berman sostiene que la verdadera razón no es la volatilidad del mercado, sino la **falta de visibilidad regulatoria**: OpenAI no sabe qué marco normativo tendrá que cumplir, lo que impide valorar la compañía.
- **Desincentivo a la competencia**: al no poder monetizar rápidamente los nuevos modelos, los laboratorios pierden el incentivo de lanzar iteraciones frecuentes. Esto ralentiza todo el ecosistema.

#### China no frena

Mientras EE.UU. ralentiza sus lanzamientos, Berman advierte que **China no está frenando su desarrollo de IA**:

- La ralentización, aunque sea de 'unas semanas', importa en una carrera global.
- Los modelos abiertos chinos podrían cerrar la brecha con los modelos de frontera estadounidenses si estos se retienen artificialmente.
- Otros países tendrán más incentivos para desarrollar **IA soberana**, reduciendo su dependencia de Estados Unidos.

#### El open-source como única esperanza

Berman redirige su atención hacia los modelos de código abierto:

- La **democratización de la inteligencia de frontera** es más importante que nunca.
- Insta a la audiencia a **descargar y ejecutar modelos open-source localmente**, ofreciéndose a crear más tutoriales sobre cómo hacerlo.
- Advierte que si los modelos abiertos empiezan a acercarse a la frontera, Anthropic podría impulsar regulaciones también contra ellos, extendiendo el control a GPUs y cómputo.

Cita a **Aaron Levy** y **Peter Diamandis** para reforzar el mensaje: 'Alguien, en algún lugar, está decidiendo qué nivel de inteligencia tú y tu empresa pueden tener'.

#### Reacciones de la industria

Berman recopila opiniones de figuras clave:

- **Aaron Levy** describe la situación como 'regulación de facto de la IA' y anticipa que todos los modelos futuros con ciertos niveles de capacidad requerirán revisión gubernamental. Señala que los lanzamientos serán menos frecuentes pero con saltos mayores, lo que desde la perspectiva de seguridad es **peor** (cambios bruscos en lugar de iterativos).
- **Peter Diamandis** resume: 'alguien, en algún lugar, decide qué inteligencia puedes usar'.
- **Bill Gurley** acusa directamente a Anthropic de buscar protección contra la competencia en lugar de soluciones legales.
- El open-source sale ganando porque será la base sobre la que se construya la IA soberana de otros países.

#### Reflexión final / Conclusiones

Berman concluye con un mensaje de urgencia y llamada a la acción. La regulación de la IA no es inevitablemente mala, pero la forma en que se está implementando —empujada por un solo actor con intereses comerciales— crea una concentración de poder peligrosa. Insta a los espectadores a: (1) apoyar activamente el open-source descargando y probando modelos locales, y (2) contactar a sus representantes gubernamentales para expresar su desacuerdo. La ventana para mantener un ecosistema de IA abierto y competitivo se está cerrando rápidamente.

---

### 🔗 Referencias

- 📄 The Information — US government asked OpenAI to stagger GPT 5.6 release
- 📄 OpenAI GPT 5.6 blog post (limited preview announcement)
- 📄 New York Times — OpenAI leaning toward pushing IPO to 2027
- 📄 Anthropic accuses Alibaba of distillation attacks
- 📄 Bill Gurley on Anthropic regulatory capture


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


## [Matthew Berman] Anthropic is coming for EVERYTHING

**Fecha:** 2026-06-25
**URL:** https://www.youtube.com/watch?v=IwKuv4LrCVk
**Video ID:** IwKuv4LrCVk

### 📝 Resumen

Matthew Berman analiza el lanzamiento de **Claude Tag**, la nueva función de Anthropic que permite invocar a Claude directamente desde Slack. Lo que en un principio parece una simple integración de productividad se revela como una jugada estratégica de gran calado: Anthropic aspira a convertirse en la infraestructura subyacente de todo el trabajo de conocimiento a nivel global. El vídeo desgrana las implicaciones técnicas, económicas y sociales de este movimiento.

#### Claude Tag: un miembro más del equipo

Claude Tag no es un bot convencional en Slack. La integración permite etiquetar a @Claude como si fuera otro compañero de equipo, pero con diferencias fundamentales. Claude tiene acceso a todo el contexto de la empresa: documentos internos, conversaciones en canales, perfiles de colegas y herramientas conectadas. Funciona en **modo ambiente**, leyendo activamente todas las conversaciones sin necesidad de ser invocado explícitamente, construyendo un grafo de conocimiento completo de la organización.

- Anthropic afirma que el **65% del código de su equipo de producto** proviene ya de su versión interna de Claude Tag.
- La compañía describe el producto como una "evolución de Claude Code", más proactivo y diseñado para trabajar con equipos completos.
- No se trata de una herramienta aislada: Claude Tag puede ejecutar tareas reales (deployments, consultas, automatizaciones) directamente desde el chat.

#### El tercer paradigma del LLM según Andre Karpathy

Andre Karpathy, que recientemente se unió a Anthropic, describe Claude Tag como la **tercera gran rediseño de la UX de los LLMs**:

1. **Primer paradigma**: el LLM como sitio web — Claude.ai, ChatGPT.
2. **Segundo paradigma**: el LLM como aplicación de escritorio — Claude Code, Codex.
3. **Tercer paradigma**: una entidad persistente, asíncrona y autónoma con contexto y herramientas a nivel organizacional, trabajando junto a equipos humanos.

Karpathy afirma que "las interfaces están desapareciendo". En lugar de abrir una aplicación específica, el usuario interactúa con la IA desde donde ya está trabajando (Slack, en este caso). Berman anticipa que el siguiente paso lógico de Anthropic será construir un competidor directo de Slack.

#### Context lock-in: el verdadero riesgo

Berman introduce el concepto de **context lock-in** como la verdadera amenaza, distinto del tradicional vendor lock-in:

- El proveedor de IA se convierte en un **compañero de trabajo compartido** que interpreta, recuerda, enruta y ejecuta el trabajo.
- Las empresas no solo alquilan modelos, sino que entregan **todo el contexto de su organización** a Anthropic.
- El modelo de precios es especialmente peligroso: un trabajador humano tiene un salario limitado, pero Claude tiene **actividad tokenizada sin límite**. Una empresa podría pagar cantidades ilimitadas a Anthropic.
- Ankit Gupta, partner de Y Combinator, señala que en YC llevan meses construyendo versiones internas de exactamente estos productos, anticipándose 6-12 meses a los lanzamientos públicos.

#### El fin del software como lo conocemos

Berman plantea un escenario extremo pero lógico: si los agentes de IA operan el software de terceros directamente, los usuarios dejan de necesitar las interfaces de usuario de esos productos.

- Un agente de Anthropic puede operar una aplicación SaaS en nombre del cliente.
- El cliente nunca vuelve a abrir la interfaz de esa aplicación.
- Sin interfaz de usuario, la empresa SaaS se reduce a sus **workflows** (flujos de trabajo).
- Pero los agentes pueden escribir código para replicar esos workflows.
- Finalmente, la empresa SaaS es solo una **base de datos**, y los agentes pueden leer y escribir datos directamente.

- **Conclusión**: ningún software está a salvo. Los agentes están infiltrando todas las capas del ecosistema.

#### La necesidad de competencia y código abierto

Berman identifica dos líneas de defensa:

1. **Intervención gubernamental**: la sociedad no permitirá que una sola empresa concentre todo el poder sobre el trabajo de conocimiento.
2. **Modelos open-source y competencia**: las empresas deben poder elegir entre múltiples proveedores y poseer su propio contexto. Una estrategia multi-modelo y multi-proveedor es la única manera de no quedar atrapado en los precios y condiciones de un único proveedor.

#### Reflexión final / Conclusiones

Berman reconoce que el futuro del trabajo será inevitablemente una colaboración entre humanos y agentes de IA viviendo dentro de las empresas. La dirección que Anthropic está tomando con Claude Tag es, en sí misma, una visión poderosa y probablemente correcta de hacia dónde se dirige la industria. Sin embargo, advierte que concentrar esta capacidad en una sola empresa —por muy bienintencionada que sea— crea riesgos sistémicos enormes. La solución pasa por más competencia, más open-source y la capacidad de las empresas de poseer su propio contexto.

---

### 🔗 Referencias

- 📄 Anuncio Claude Tag: https://x.com/claudeai/status/2069468693017268244
- 📄 Andre Karpathy sobre Claude Tag: https://x.com/karpathy/status/2069547676849557725
- 📄 Y Combinator — Playbook for AI-native company: https://www.ycombinator.com/library/OX-the-playbook-for-building-an-ai-native-company
- 📄 Ankit Gupta: https://x.com/agupta/status/2069561285780623819
- 📄 Ashwin Goel sobre el "caballo de Troya": https://x.com/ashwingop/status/2069814177624121469
- 🏢 Sponsor — Recall 2.0: https://www.recall.it/?t=mb

