# 📹 Resúmenes Diarios — IA YouTubers

---

## [Matt Wolfe] AI News: GPT-5.6 and the new Super App are a Massive Leap!
**Fecha:** 2026-07-10
**URL:** https://www.youtube.com/watch?v=EOCRtSnvNNE
**Video ID:** EOCRtSnvNNE

### 📝 Resumen

Matt Wolfe repasa las noticias más importantes de la semana del 10 de julio de 2026, encabezadas por el lanzamiento público de **GPT-5.6** de OpenAI y la nueva aplicación unificada **ChatGPT Work** (la "super app" que fusiona Codex, ChatGPT y Atlas). La semana también trajo novedades de xAI con Grok 4.5, Meta con Muse Spark 1.1 y Muse Image (controvertido), extensiones de acceso a Fable 5 de Anthropic, y nuevos modelos de imagen como Seedream 5.0 Pro de ByteDance. Wolfe dedica una parte significativa a comparar GPT-5.6 con Fable en uso real, concluyendo que ambos modelos son complementarios y representan el mayor salto cualitativo desde GPT-3.5 a GPT-4.

#### GPT-5.6: tres variantes, un salto monumental

OpenAI lanzó oficialmente GPT-5.6, descrito por Wolfe como "el salto más masivo de un punto release (.5 a .6) que jamás haya visto", comparable en magnitud al salto de GPT-3.5 a GPT-4. El modelo se presenta en tres niveles:

- **Soul (Sol)**: la variante frontier a $5/M tokens de entrada y $30/M de salida. Soporta el modo **Ultra** para razonamiento extremo. Puntúa un **91,9% en Terminal Bench**, superando a Fable (84,3%) y estableciéndose como el mejor modelo para uso agéntico.
- **Terra**: modelo intermedio a $2,50/M input y $15/M output, ideal para codificación general.
- **Luna**: el más ligero y económico a $1/M input y $6/M output, para despliegues y tareas simples.

En **Deep SWE Bench** (el nuevo estándar de referencia para ingeniería de software), GPT-5.6 Soul alcanza un 72,7%, superando a Fable Max (66%) y Grok 4.5 (62%). Wolfe destaca que el modelo se siente "como un GPT-6 disfrazado de 5.6" y que por primera vez desde GPT-4 hay una sensación de salto monumental.

- **SolBonk**: Wolfe creó un clon funcional de Mega Bonk con un solo prompt. El modelo tardó 31 minutos en la primera iteración. Wolfe lo considera superior a la primera versión de Fable, que requería prompts adicionales para corregir la cámara y la apariencia del personaje.
- **Sites (ChatGPT)**: el nuevo sistema de hosting integrado permite publicar el juego en `chatgpt.site` sin gestionar bases de datos, CDNs ni servidores. Wolfe lo publicó y cualquiera puede jugarlo.
- **"Imprímeme"**: Wolfe le pidió a GPT-5.6 "crea un sitio web que realmente me impresione" (modo Soul Ultra, 35 minutos de trabajo). El resultado fue un sitio interactivo con lluvia hacia arriba, entornos cambiantes, y un botón "Colapsar la atmósfera".

#### ChatGPT Work: la super app unificada

OpenAI fusionó Codex, ChatGPT y Atlas en una sola aplicación llamada **ChatGPT Work**, que Wolfe describe como la "super app" largamente anticipada. La app tiene dos modos principales:

- **Codex Mode**: para desarrollo de software con todas las herramientas de codificación (terminal, revisión de código, ramas de trabajo, archivos locales).
- **Work Mode**: modo asistente personal, menos técnico, que decide autónomamente si responder, conectar con herramientas o escribir código según lo que necesite el usuario.

Las capacidades más destacadas incluyen:

- **Browser integrado**: reemplaza a Atlas. El navegador vive dentro de la app y permite a los agentes navegar por la web.
- **Plugins**: conexión con Gmail, Google Drive, Slack, Granola y cualquier servicio.
- **Side Chat**: permite hacer preguntas rápidas a ChatGPT en un panel lateral sin interrumpir el proyecto principal.
- **Control deslizante de inteligencia**: un slider que va desde Terra Light (mínimo) hasta Soul Ultra (máximo), permitiendo ajustar el consumo de créditos.
- **Sites**: hosting integrado que despliega sitios web completos con un solo clic, sin necesidad de gestionar infraestructura.

Wolfe demostró el modo asistente personal pidiéndole que revisara sus correos, calendario, Slack, Granola y proyectos recientes para identificar áreas de mejora. El asistente creó una **"torre de control"** con pestañas de: tareas del día, inteligencia de IA (noticias en tiempo real), seguimiento de marca (menciones en internet) y datos de sitios web. Wolfe ahora usa esta torre de control como su página de inicio predeterminada.

#### HyperAgent: marketplace de skills para agentes

HyperAgent, la plataforma de agentes de la compañía que creó Airtable, lanzó un **marketplace de skills** donde cualquier persona puede crear y compartir habilidades para agentes de IA. Wolfe desarrolló un **generador de B-roll** para creadores de vídeo que:

- Toma un script de vídeo y lo analiza para determinar dónde debe ir cada toma.
- Enruta cada prompt al modelo de generación adecuado (Veo para realista, Hyperframes para gráficos animados).
- Normaliza todos los clips con FFmpeg y los ensambla en un vídeo completo con texto superpuesto, lower thirds y transiciones.
- Genera un shot list detallado indicando cuándo debe aparecer cada elemento.

El marketplace permite "forkear" skills de otros usuarios, eliminando la necesidad de construir desde cero.

#### GPT-Live: voz natural con interrupción mutua

OpenAI presentó **GPT-Live**, un nuevo modo de voz que permite conversaciones mucho más naturales. La diferencia clave: tanto el usuario como la IA pueden interrumpirse mutuamente, generando un ritmo de conversación real. Wolfe demostró cómo funciona:

- Le pidió que no respondiera hasta que él se lo indicara, mientras enumeraba todas las noticias de la semana.
- Al darle la señal, GPT-Live recitó la lista completa sin perder detalle.
- También funciona como traductor simultáneo: se coloca el teléfono en medio de una conversación entre dos personas que hablan distintos idiomas, y la IA traduce en tiempo real, hablando por encima de los interlocutores según sea necesario.

Para activarlo: Settings → Voice → Model → "Live". Ofrece opciones de velocidad (respuesta rápida vs. más inteligente pero más lenta).

#### Grok 4.5: xAI sorprende en benchmarks

xAI lanzó **Grok 4.5**, y Wolfe admite que es "más impresionante de lo que esperaba". En benchmarks:

- **Deep SWE Bench**: Grok 4.5 obtiene 62%, frente al 66% de Fable y el 72,7% de GPT-5.6.
- **Terminal Bench**: 83%, compitiendo directamente con Fable (84%) y GPT-5.5 High (83,4%).
- Precio: $2/M input y $6/M output, similar a los modelos más económicos de GPT-5.6.

Wolfe le pidió a Grok 4.5 que creara un sitio web impresionante. El resultado fue un **simulador de universo interactivo** con estrellas que responden al ratón, zoom desde la escala de la palma de la mano hasta el universo observable, diferentes tipos de estrellas (nebulosa, secuencia principal, gigante roja, remanente) y un modo de constelaciones dibujables. Wolfe lo considera bueno pero inferior al sitio creado por GPT-5.6.

- Grok 4.5 se puede instalar y ejecutar localmente mediante CLI, sin necesidad de facturación inicial.
- En BuseyBench ocupa el puesto #21.

#### Muse Spark 1.1: Meta vuelve a la conversación

Meta lanzó **Muse Spark 1.1**, un modelo que Wolfe califica como "sorprendentemente decente", aunque no al nivel de los modelos frontier. En benchmarks:

- **Terminal Bench**: 80% (Opus 4.8 tiene 82,7%, GPT-5.5 tiene 83,4%).
- **Deep SWE Bench**: 53,3%.
- Precio: $1,25/M input y $4,25/M output.

Lo más impresionante para Wolfe es la **trayectoria de mejora**: el modelo anterior de Meta (Llama Scout, abril 2025) generaba SVGs de Gary Busey prácticamente irreconocibles. Muse Spark 1.1 genera resultados coherentes. En la web impresionante que Wolfe le pidió, Meta creó un sitio interactivo con fondos que cambian al mover el ratón, que Wolfe considera "ligeramente más impresionante que el de Grok 4.5".

#### Muse Image: generación de imágenes de cualquier persona etiquetada

Meta también lanzó **Muse Image**, un modelo de generación de imágenes que se integra con Instagram. La característica más polémica: permite generar imágenes de **cualquier persona etiquetada con @**, incluso si no se la conoce. Wolfe demostró cómo creó imágenes de Joe Rogan comiendo un taco sobre un delfín y de Mr. Beast haciendo el pino sobre un montón de pepinillos, sin necesidad de permiso de los involucrados.

- Se puede desactivar desde los ajustes de la aplicación móvil, aunque Wolfe señala que no todos los usuarios tienen disponible esa opción aún.
- Wolfe recomienda desactivarlo si no se desea que otros generen imágenes de uno mismo.

#### Actualizaciones de Claude y Anthropic

Anthropic realizó varios movimientos estratégicos coincidiendo con el lanzamiento de GPT-5.6:

- **Extensión de Fable 5**: el acceso gratuito se extendió del 7 al **12 de julio**. Wolfe señaló la ironía de que muchos usuarios ya habían agotado sus límites semanales para el 7 de julio, y justo el 9 de julio (día del lanzamiento de GPT-5.6), Anthropic **reseteó los límites semanales** para todos.
- **Claude Cowork en móvil y web**: hasta ahora Cowork vivía solo en el ordenador portátil y el trabajo se detenía al cerrar la tapa. Ahora el trabajo continúa en la nube, permitiendo iniciar una tarea en el escritorio, verificarla desde el móvil y recoger el resultado en cualquier lugar.
- **Reflect**: una función estilo "Spotify Wrapped" para Claude que muestra el día más activo, el pico de uso, el número de conversaciones con gráficos, y detalles sobre en qué se ha empleado más tiempo.
- **J-Space**: Anthropic publicó una investigación sobre el espacio interno de pensamiento de Claude (ver resumen del vídeo de Matthew Berman del 8 de julio para más detalles).

#### Otras novedades: Google Photos y Seedream 5.0 Pro

Google lanzó **Video Remix** en Google Photos, que usa Gemini Omni para añadir estilización y recuerdos imaginativos a los vídeos. Disponible en los planes Google AI Plus, Pro y Ultra.

ByteDance presentó **Seedream 5.0 Pro**, un modelo de imagen con capacidades destacadas:

- **Infografías**: maneja grandes cantidades de información visual densa con imágenes incrustadas.
- **Edición interactiva**: permite rodear elementos, dibujar líneas y decirle qué hacer.
- **Capas al estilo Photoshop**: los elementos de una composición se pueden reorganizar como capas independientes.
- **Fotorrealismo**: alta calidad en imágenes realistas.

Wolfe lo probó en Leonardo.ai, pidiéndole una infografía que explicara el J-Space de Anthropic. El resultado fue visualmente atractivo aunque Wolfe dudó de su precisión conceptual.

#### Reflexión final / Comparativa GPT-5.6 vs Fable

Wolfe dedica los últimos minutos a una comparación práctica entre los dos modelos frontier de la semana:

- **Fable** es "un poco más inteligente" en decisiones arquitectónicas y en encontrar la mejor ruta del punto A al punto B. Wolfe lo describe como un **Ferrari sin ajustar** —potencial bruto para problemas complejos.
- **GPT-5.6** es mejor para "volcar mucha información y decir 've y hazlo'" y al volver encontrar el trabajo prácticamente terminado. Wolfe lo describe como su **conductor diario** (daily driver).
- Ambos son complementarios: Wolfe construyó la mayor parte del nuevo sitio de Future Tools con Fable, y luego le pasó todo a GPT-5.6, que **encontró vulnerabilidades de seguridad** que Fable había pasado por alto (como exposición accidental de API keys).

La conclusión: GPT-5.6 Soul y Luna serán los modelos principales de Wolfe, con Fable como "potencia extra de pensamiento" para problemas realmente difíciles. Wolfe califica la combinación de ambos como "lo más divertido que ha tenido en el último año y medio" y recuerda que "esto es lo peor que va a ser nunca" —implicando que la mejora continuará acelerándose.

---

### 🔗 Referencias

- 📄 GPT-5.6 (OpenAI): https://openai.com/index/gpt-5-6/
- 📄 ChatGPT Work: https://openai.com/index/chatgpt-for-your-most-ambitious-work/
- 📄 GPT-Live: https://openai.com/index/introducing-gpt-live/
- 🏢 HyperAgent Marketplace: https://hyperagent.com/marketplace/s/ccs01KWW9863B_K2WF34HK4MHCBT5N
- 📄 Grok 4.5 (xAI): https://x.ai/news/grok-4-5
- 📄 Muse Spark 1.1 (Meta): https://ai.meta.com/blog/introducing-muse-spark-meta-model-api/
- 📄 Muse Image (Meta): https://about.fb.com/news/2026/07/introducing-muse-image-meta-ai/
- 🔗 Fable 5 Access Extended: https://x.com/claudeai/status/2074548242386178258
- 🔗 Claude Rate Limits Reset: https://x.com/ClaudeDevs/status/2075279141352706215
- 📄 Claude Cowork Web & Mobile: https://claude.com/blog/cowork-web-mobile
- 📄 Reflect With Claude: https://www.anthropic.com/news/reflect-with-claude
- 📄 J-Space Research: https://www.anthropic.com/research/global-workspace
- 📄 Google Photos Video Remix: https://blog.google/products-and-platforms/products/photos/video-remix/
- 📄 Seedream 5.0 Pro: https://seed.bytedance.com/en/seedream5_0_pro
- 🔗 SolBonk Game: https://solbonk-sunpit.mreflow.chatgpt.site/
- 🌐 Future Tools: https://futuretools.io/

## [Matthew Berman] GPT-5.6 SOL is HERE
**Fecha:** 2026-07-09
**URL:** https://www.youtube.com/watch?v=roGmNXASYOM
**Video ID:** roGmNXASYOM

### 📝 Resumen

Matthew Berman realizó un livestream el 9 de julio de 2026 para celebrar el lanzamiento público de **GPT-5.6**, el modelo más avanzado de la familia GPT-5, tras semanas de retraso causados por la controversia regulatoria en torno a Claude Fable de Anthropic. Durante casi dos horas, Berman repasó las capacidades del modelo, mostró demos en vivo de clones de software complejos creados con bucles autónomos, y comparó precios y rendimiento con Fable, Opus 4.8 y GPT-5.5. El evento coincidió además con el lanzamiento de otros modelos competidores como Grok de xAI y Spark de Meta, y con una ofensiva de Anthropic que reseteó los límites de tokens de Claude para todos los usuarios.

#### Las tres variantes de GPT-5.6: Luna, Terra y Soul

OpenAI lanzó GPT-5.6 en tres tamaños distintos para cubrir diferentes necesidades y presupuestos:

- **Luna**: el modelo más pequeño y económico, ideal para tareas simples como despliegues o trabajo de bajo requerimiento cognitivo.
- **Terra**: el modelo intermedio, optimizado para implementación de código a un coste de $2,50/M tokens de entrada y $15/M de salida.
- **Soul (Sol)**: el modelo frontier, con un precio de $5/M tokens de entrada y $30/M de salida. Soporta **Ultra mode**, un nivel de razonamiento extremo diseñado para consumir grandes cantidades de cuota en tareas complejas.

Berman destacó que Soul tiene exactamente el mismo precio que GPT-5.5, haciendo que este último quede obsoleto: "No hay razón para usar GPT-5.5 nunca más". La estrategia recomendada es usar **Soul para planificación y orquestación**, Terra para la escritura de código, y Luna para despliegues —una técnica de enrutamiento que permite ahorrar hasta un 50% en costes.

#### Comparativa con Claude Fable y Opus 4.8

Berman dedicó una parte significativa del stream a comparar GPT-5.6 con los modelos de Anthropic:

- **GPT-5.6 Soul vs Claude Opus 4.8**: Soul es claramente superior. Opus 4.8 se siente como un modelo de generación anterior, mientras que Soul ofrece un rendimiento significativamente mejor en el Coding Agent Index con un coste API similar (~$2,400 por max effort).
- **GPT-5.6 Soul vs Claude Fable**: Fable obtiene puntuaciones más altas pero a un coste desorbitado (hasta $3,700 en max effort). Sin embargo, Berman cree que Fable tiene más potencial de mejora porque es un modelo completamente nuevo de un nuevo entrenamiento (posiblemente 10 billones de parámetros), mientras que GPT-5.6 es la cúspide del entrenamiento GPT-5.
- **Analogía de Berman**: GPT-5.6 es "el Honda Civic más tuneado que hayas visto" —cada caballo de fuerza ha sido exprimido—, mientras que Fable es "un Ferrari recién salido de fábrica, sin optimizar, con un potencial mucho mayor por delante".

Fable destaca en personalidad: dice cosas con un toque humano que sorprende gratamente. GPT-5.6, en cambio, es más directo y "soso" en personalidad, pero va al grano sin desviarse.

#### Demos en vivo: Excel, Minecraft, sistema operativo y más

Berman mostró varias aplicaciones creadas enteramente por GPT-5.6 mediante el sistema de **bucles (/goal)** de Codex:

- **Excel clone**: un clon funcional de Microsoft Excel creado con un solo prompt de 8 palabras ("create an Excel clone, feature parity"). El modelo trabajó durante **6 días** sin supervisión, usando computer use para abrir Excel real, estudiar sus características y replicarlas. El resultado incluye fórmulas, tablas dinámicas, gráficos, validación de datos, ordenación y filtros. Berman lo detuvo manualmente; el modelo habría seguido añadiendo funciones.
- **BlockCraft (clon de Minecraft)**: con el prompt "clone Minecraft full feature parody", el modelo generó un mundo 3D navegable con inventario, biomas, mobs, minería, agricultura y física básica. En un día ya había un juego funcional; durante los 6 días siguientes fue añadiendo biomas, NPCs y enemigos del juego original de forma autónoma.
- **Astra OS**: un sistema operativo completo con ventanas, configuración y aplicaciones, aunque Berman admitió que el diseño era "muy feo".
- **Máquina Rube Goldberg**: un juego interactivo de física.
- **Cubo de Rubik 3D**: simulación que permite girar caras, hacer zoom y resolver automáticamente.

#### Browser use y computer use: el asesino silencioso

La capacidad que más impresionó a Berman fue el **control de navegador** de GPT-5.6 en Codex. Demostró cómo el modelo puede:
- Gestionar cambios complejos de DNS a través de múltiples servicios (Vercel, DigitalOcean, GoDaddy) con un solo prompt de 10 palabras.
- Escalar automáticamente instancias de Supabase cuando se acercaban al límite de cuota y luego reducirlas al terminar.
- Navegar por Gmail, calendarios y cualquier web como lo haría un humano.

Berman afirmó que el navegador de Codex se ha convertido en su navegador predeterminado y que OpenAI probablemente invertirá fuertemente en esta funcionalidad, que se está fusionando con la nueva "super app" de ChatGPT.

#### El ecosistema: reseteo de cuota y herramientas

Coincidiendo con el lanzamiento, el CTO de OpenAI, Tibo, anunció el reseteo de los límites de tokens de Codex, lo que Berman calificó como "100% de probabilidad" tras el anuncio. Además, Berman presentó:
- **GPT-5.6 Relay**: un skill open source para Codex que permite usar Soul como planificador y delegar tareas a Terra y Luna automáticamente, ahorrando cuota.
- **Loopy**: una librería open source (2.500+ estrellas en GitHub) que ayuda a diseñar, revisar y monitorear bucles en cualquier editor agéntico (Codex, Cursor, Claude Code).
- Su web **forwardfuture.com** (nuevo dominio, adquirido por $2,500), que alberga el review completo de GPT-5.6 con todas las demos interactivas.

#### Reflexión final / Conclusiones

Berman concluye que GPT-5.6 representa la **madurez máxima de la familia GPT-5**, ofreciendo un rendimiento excepcional a un precio competitivo, especialmente cuando se combinan las tres variantes mediante enrutamiento inteligente. Sin embargo, reconoce que Fable tiene un techo más alto a largo plazo por ser un modelo de nueva generación. La recomendación práctica: usar GPT-5.6 Soul para planificar, Terra para ejecutar y Luna para desplegar, y reservar Fable para tareas que requieran el máximo nivel de razonamiento posible. El futuro, según Berman, está en la **orquestación multi-modelo** y en sistemas agénticos que combinen lo mejor de cada modelo.

---

### 🔗 Referencias

- 🔗 Review completo de GPT-5.6: https://signals.forwardfuture.com/gpt-5-6-review/
- 💻 GPT-5.6 Relay (GitHub): https://github.com/Forward-Future/gpt-5-6-relay
- 🌐 Newsletter Forward Future: https://forwardfuture.com
- 🏢 OpenAI - GPT-5.6: https://openai.com/index/gpt-5-6/

---

## [Matthew Berman] GPT-5.6 is FINALLY HERE (WOAH)
**Fecha:** 2026-07-09
**URL:** https://www.youtube.com/watch?v=mD1F5DsC5tc
**Video ID:** mD1F5DsC5tc

### 📝 Resumen

Matthew Berman publicó una revisión en profundidad de **GPT-5.6** coincidiendo con su lanzamiento público el 9 de julio de 2026, apenas horas antes de que Claude Fable fuera reautorizado por el gobierno. Este vídeo es la versión producida y editada del análisis que luego expandió en su livestream del mismo día. Berman describe GPT-5.6 como "el salto más masivo de un punto release (.5 a .6) que jamás haya visto", squeezando cada gota de rendimiento del entrenamiento GPT-5. El video incluye el benchmark personalizado de **Box AI** para evaluar el modelo en tareas de trabajo real del conocimiento.

#### Capacidades de creación de software con bucles autónomos

Berman dedicó gran parte del video a demostrar el poder de los **bucles (/goal)** de Codex impulsados por GPT-5.6. Los dos proyectos estrella:

- **Clon de Excel**: un prompt de 8 palabras ("/goal make an Excel clone, continue until feature parity") generó un clon funcional que ejecutó durante **5 días** hasta que Berman lo detuvo manualmente. El modelo usó **computer use** para abrir Excel real en el escritorio, estudiar cada característica y replicarla en el clon HTML. El resultado incluye: fórmulas (suma, resta, referencia de celdas), ordenación ascendente/descendente, validación de datos, formato condicional, tablas dinámicas, gráficos, búsqueda y reemplazo, y múltiples hojas de cálculo. Todo en una sola página HTML.

- **Clon de Minecraft**: con el mismo enfoque de bucle, GPT-5.6 generó un mundo 3D completo durante **7 días**. El resultado incluye minería de bloques con animaciones 3D, inventario completo, agricultura (zanahorias, tierras de cultivo), animales (gatos), diferentes biomas, generación de semillas de mundo, y mobs del juego original. Berman destacó que es "la mejor versión de Minecraft creada con IA hasta la fecha".

#### La estrategia de tres modelos y el skill GPT-5.6 Relay

GPT-5.6 se lanza en tres tamaños con diferentes niveles de razonamiento:

- **Luna**: el más pequeño y barato, para despliegues y tareas simples.
- **Terra**: modelo medio a $2.50/M input, ideal para implementación de código con razonamiento alto.
- **Soul**: modelo frontier a $5/M input ($30/M output), la mitad del precio de Fable ($10/M input, $50/M output).

Berman presentó **GPT-5.6 Relay**, un skill open source que permite planificar con Soul, delegar la implementación a Terra (con razonamiento alto), y usar Luna para despliegues —todo dentro de Codex. Esta estrategia de **enrutamiento multi-modelo** ahorra cuota significativamente sin sacrificar calidad.

#### Box AI Benchmark y comparativa de rendimiento

Box (partner del video) desarrolló un benchmark personalizado de trabajo real del conocimiento que evalúa lectura de documentos, conciliación de números, due diligence y revisión de outputs expertos:

- **GPT-5.6 Soul**: 68.1% de precisión (domina a GPT-5.5 en todos los subsegmentos: sector público, ciencias de la vida y salud).
- **GPT-5.6 Terra**: 59% (inferior a Soul, pero mucho más rápido y barato).
- **GPT-5.6 Luna**: ~59% (misma precisión que Terra pero más rápido y más barato).
- **GPT-5.5**: 63.3% (superado por Soul en todos los sectores).

Berman enfatizó que GPT-5.6 no solo es más barato que Fable, sino que **usa menos tokens para lograr el mismo resultado**, dando una "línea de visión más directa" hacia la solución. En el Coding Agent Index, Soul obtiene ~80 puntos a $2,400 de coste API, frente a los ~72 puntos de Opus 4.8 al mismo precio.

#### Reflexión final / Conclusiones

Berman compara GPT-5.6 con un **Honda Civic súper tuneado** (máximo rendimiento de una plataforma madura) y Fable con un **Ferrari sin ajustar** (potencial bruto por explotar). Aunque Fable "ve alrededor de las esquinas" mejor, GPT-5.6 ofrece la mejor relación coste-rendimiento del mercado actual. La recomendación: usar GPT-5.6 Soul para planificación estratégica, Terra para implementación, y el skill Relay para orquestar todo, reservando Fable para problemas que requieran el máximo nivel de razonamiento. El futuro, sugiere Berman, está en la **orquestación inteligente entre modelos** más que en depender de un único modelo frontier.

---

### 🔗 Referencias

- 🏢 Box AI + GPT-5.6: https://bit.ly/4pkwci0
- 🔗 Review completo de GPT-5.6: https://signals.forwardfuture.com/gpt-5-6-review/
- 💻 GPT-5.6 Relay (GitHub): https://github.com/Forward-Future/gpt-5-6-relay
- 🌐 Newsletter Forward Future: https://forwardfuture.com
- 📄 OpenAI - GPT-5.6: https://openai.com/index/gpt-5-6/

---

## [Javier Garzás] ¿Llevan razón los negacionistas del vibe coding?
**Fecha:** 2026-07-08
**URL:** https://www.youtube.com/watch?v=bDBse242_EI
**Video ID:** bDBse242_EI

### 📝 Resumen

Javier Garzás, con más de 20 años de experiencia en calidad de software y refactoring (escribió el primer artículo en español sobre refactoring en 2002), analiza con datos y ejemplos reales las cuatro críticas más repetidas contra el **vibe coding** —el desarrollo de software asistido por inteligencia artificial mediante lenguaje natural. El contexto de fondo: el 84% de los desarrolladores ya usa o planea usar IA para programar según Stack Overflow 2025, herramientas como Lovable alcanzan 500M$ ARR con 1M de proyectos nuevos por semana, y figuras como Kent Beck y Robert C. Martin (Uncle Bob) defienden activamente el uso de IA en programación. Garzás sostiene que la mayoría de los argumentos negacionistas no se sostienen, pero advierte que hay uno que merece atención seria.

#### Negacionismo 1: "El vibe coding genera código inmantenible y 10× más caro"

Garzás reconoce que este es el único argumento con **algo de realidad**. Hacer vibe coding sin control para aplicaciones críticas es peligroso por mantenibilidad, seguridad y escalabilidad. Sin embargo, señala que este es un **problema histórico del software** que existe desde siempre, independientemente de la IA.

- Escribió el primer artículo en español sobre refactoring en 2002 junto a Mario Piattini, donde ya alertaban sobre los problemas del mal código.
- Ha auditado y refactorizado millones de líneas de código a lo largo de su carrera, y afirma haber visto código humano tan malo que duda que una IA pueda igualarlo.
- **Kent Beck** (creador de Extreme Programming y JUnit) ha defendido que el software necesita acompañarse de **seguridad y confianza** —prácticas como pair programming y testing—, y adaptaciones de XP para la era de la IA (como "AI Extreme Programming") están surgiendo.
- La conclusión: no se debe cargar la culpa al vibe coding, sino a **no acompañar el desarrollo de buenas prácticas** que den seguridad, ya sea con humanos o con IA.

#### Negacionismo 2: "Te han vendido el humo de que cualquiera puede hacer grandes aplicaciones"

Garzás considera este argumento superficial y falto de matiz. Es evidente que una persona sin conocimientos técnicos no va a construir un CRM como HubSpot o competir con SAP usando vibe coding. Pero de ahí a decir que **no se puede hacer nada** hay un abismo.

- Su propio equipo tiene un **CRM propio hecho con vibe coding** porque HubSpot se les quedaba grande y no les daba las soluciones que necesitaban.
- El valor real del vibe coding para no-técnicos está en construir **pequeñas capas de integración** sobre herramientas existentes (Notion, Jira, Gmail, calendarios, CRMs) que resuelvan problemas específicos que las grandes aplicaciones no cubren.
- El argumento de "no puedes hacer nada" desmotiva injustamente a profesionales no técnicos que podrían obtener superpoderes con desarrollos pequeños pero transformadores.

#### Negacionismo 3: "El vibe coding es una moda pasajera"

Garzás presenta datos concretos para refutar esta afirmación:

- **Stack Overflow 2025**: el 84% de los desarrolladores usa o tiene planes de usar IA para desarrollar, frente al 76% en 2024 —un crecimiento de 8 puntos porcentuales en un año.
- **Lovable** alcanzó 500M$ de ingresos recurrentes anuales (ARR) en junio de 2026, duplicando en solo 6 meses, con 1M de nuevos proyectos por semana.
- **Robert C. Martin (Uncle Bob)**, el máximo defensor del código limpio, afirma públicamente que "la IA programa mejor que tú, asúmelo", y recomienda usar IA con buenas prácticas adaptadas.
- El vibe coding no es una moda, sino un **cambio de paradigma imparable**. Como todo cambio tecnológico, hay negacionistas y pioneros, pero los números demuestran una adopción creciente y sostenida.

#### Negacionismo 4: "Solo sirve para aplicaciones de juguete"

Garzás califica este argumento de **"tremendamente peligroso e irresponsable"** porque desmotiva a gente que podría beneficiarse enormemente del vibe coding.

- Personas no técnicas pueden crear **prototipos operativos** funcionales que antes requerían equipos enteros de desarrollo, acelerando el ciclo de discovery y validación de producto.
- Incluso pequeños desarrollos (cruzar bases de datos, conectar email marketing con Gmail y calendario, integrar CRM con facturación) tienen un **impacto enorme en productividad** y antes eran impensables sin conocimientos técnicos.
- El vibe coding está revolucionando la **reducción de requisitos a prototipos**: en vez de escribir historias de usuario, los product managers pueden mostrar prototipos funcionales hechos con herramientas como Lovable, acelerando drásticamente la validación de ideas.

#### Reflexión final / Conclusiones

Garzás concluye que tres de los cuatro negacionismos no se sostienen bajo escrutinio, y el único que tiene algo de razón (código inmantenible) es un problema que ha acompañado al software desde sus orígenes, no algo que el vibe coding haya inventado. El verdadero desafío no es **si** usar vibe coding, sino **cómo** hacerlo bien: con buenas prácticas, ingeniería del arnés (harness engineering) y controles de calidad adaptados a la nueva era. La IA y el vibe coding no tienen vuelta atrás, y los profesionales que mejor los integren en su flujo de trabajo serán los que lideren la próxima década del desarrollo de software.

---

### 🔗 Referencias

- 📄 Encuesta: https://survey.stackoverflow.co/2025/ai — Stack Overflow 2025 sobre uso de IA en desarrollo
- 🔗 Artículo: https://techcrunch.com/2026/06/09/lovable-says-it-has-hit-500m-in-annualized-revenue-with-1-million-new-projects-a-week/ — Lovable: 500M ARR y 1M proyectos/semana
- 🔗 Artículo: https://news.fundsforngos.org/2026/06/08/lovable-targets-12-billion-valuation-in-new-funding-round-as-ai-coding-boom-accelerates/ — Lovable: ronda hacia 12B de valoración
- 🔗 LinkedIn: https://www.linkedin.com/posts/kentbeck_software-is-bipedal-code-and-trust-move-activity-7474959156257398784-MgwR — Kent Beck: "Software is bipedal: code and trust"
- 🔗 X/Twitter: https://x.com/unclebobmartin/status/2046206145597972849 — Robert C. Martin sobre IA
- 🌐 Web: https://233academy.com — Comunidad y recursos de Javier Garzás

---

## [Matt Wolfe] Anyone Can Make Insane Visual Effects Now!
**Fecha:** 2026-07-08
**URL:** https://www.youtube.com/watch?v=Zq5Yj8yCiqY
**Video ID:** Zq5Yj8yCiqY

### 📝 Resumen

Matt Wolfe presenta una guía práctica y detallada sobre cómo añadir **efectos visuales con IA** a vídeos sin que parezcan generados artificialmente. Partiendo de su propia experiencia —sus vídeos de noticias de los viernes siempre empiezan con efectos visuales salvajes que son lo que más preguntas generan—, Wolfe demuestra que se puede usar IA para potenciar un vídeo 95% humano con solo un 5% de "especias" de IA. El tutorial abarca intros, transiciones, efectos de fondo, B-roll, animaciones de logotipos, rótulos inferiores, gráficos animados y cabezas parlantes animadas, utilizando herramientas como Runway, Seed Dance 2.0, Gemini, Veo 3.1, Remotion y Codex.

#### Intros con Runway: la fórmula del "key frame"

La técnica principal para las intros de efectos visuales consiste en grabar dos fotogramas fijos en Da Vinci Resolve y enviarlos a Runway para generar una transición animada entre ambos.

- **Paso 1**: grabar un fotograma vacío de la habitación (sin el presentador) y otro justo antes de empezar a hablar.
- **Paso 2**: en Runway, usar la modalidad **Key Frame** con Seed Dance 2.0 (el modelo que Wolfe considera superior actualmente para este tipo de efectos), aunque también funcionan Cling y Veo 3.1 de Google.
- **Paso 3**: descargar el vídeo generado, importarlo a Da Vinci Resolve y usar la transición **Smooth Cut** para difuminar el cambio entre el clip generado y la grabación real.
- Wolfe ha creado variaciones como una **máquina de garra** que lo levanta y lo sienta en la silla, o un efecto **animorph** donde un lobo se transforma en su rostro (usando ChatGPT para generar la imagen inicial del animal).

#### Transiciones entre ubicaciones con IA

Cuando Wolfe sabe que grabará en una ubicación diferente, graba los primeros segundos en su estudio y el resto en el destino, y usa Runway para generar una transición fluida entre ambos escenarios.

- La clave está en **grabar con previsión**: un clip corto en el estudio diciendo "cambiemos de escenario", y luego el resto en la nueva ubicación.
- Es importante **usar la misma ropa** en ambas grabaciones para que la transición sea creíble.
- Wolfe creó un vídeo para NAB (nunca mostrado) con transiciones espectaculares: lanzar el micrófono al aire en cámara lenta en San Diego y atraparlo en Las Vegas, o ser succionado por un agujero de gusano.
- Para estas transiciones usó el modelo **Cling** dentro de Leonardo.ai en lugar de Seed Dance.

#### Efectos de fondo con Gemini (Google Omni)

Gemini (modelo Omni de Google) permite añadir elementos que no ocurrieron en la grabación real, manteniendo al presentador sin reaccionar.

- **Yeti en el fondo**: Wolfe grabó 10 segundos hablando, subió el clip a Gemini y pidió "un yeti camina detrás del hombre". El resultado es un yeti que cruza el fondo mientras Wolfe sigue hablando como si nada.
- **Godzilla en Google IO**: sobre un clip de una banda tocando en Google IO, Gemini insertó a Godzilla caminando y destrozando el escenario.
- **Explosión sin reacción**: añadió una explosión detrás de sí mismo con la instrucción explícita de "no reacciones ni te des cuenta".
- **Humo en la cabeza**: el mismo clip con "haz que mi cabeza eche humo".
- **Cambio climático**: transformó un día soleado en Google IO en un día lluvioso con todos los asistentes usando paraguas y chaquetas.

#### B-roll y animaciones de texto con Claude Co-work (Fable)

Para generar B-roll de artículos y animaciones de texto, Wolfe utiliza **Claude Co-work** (modelo Opus 4.8 o Fable), que puede navegar por páginas web, capturar pantallas y generar vídeos MP4 con animaciones personalizadas.

- Wolfe le pide a Claude que capture una página web de un artículo, haga scroll hasta un párrafo específico, lo **ilumine con un resaltador amarillo**, y genere un MP4 con la animación.
- Con **Fable**, los resultados son aún más suaves y naturales en las animaciones de resaltado.
- También se pueden crear **flechas apuntando a texto**, **zooms a secciones específicas**, y animaciones de **cursor**.
- Para B-roll genérico tipo stock footage, Wolfe usa **Runway con Seed Dance** para generar escenas como "hombre de negocios estrechando la mano de una mujer en una sala de conferencias" o "hombre sentado sobre un montón de dinero lanzándolo al aire".

#### Logotipos, lower thirds y gráficos animados con Remotion

Para animaciones más controladas y precisas, Wolfe utiliza **Remotion** (a través de Codex o Claude Code con el skill "remotion best practices"), que genera vídeos mediante código.

- **Logo reveals con partículas**: Wolfe subió su logotipo de Future Tools a Codex y pidió "una explosión de partículas que se reforman para formar el logotipo". Remotion generó una animación perfecta.
- **Paint splatter**: usando el mismo skill, creó una animación donde salpicaduras de pintura de los colores de su avatar se reorganizan para formar su imagen.
- **Lower thirds**: Seed Dance genera animaciones con texto, pero a menudo escribe mal los nombres (ej: "CEO of Busty Bench" en vez de "CEO of Busybench"). **Veo 3.1** lo hace mejor con texto. **Remotion** es el más preciso pero menos vistoso.
- **Gráficos animados**: Wolfe creó una simulación de conversación de texto estilo iPhone, gráficos de stock de NVIDIA, y animaciones de rutas de avión (aunque los modelos de vídeo son malos en precisión geográfica).

#### Cabezas parlantes animadas (truco del texto de Sam Altman)

Para la recreación de la conversación por SMS entre **Sam Altman y Mira Murati**, Wolfe usó **Character Script to Video** de Runway:

- Grabó su propia voz leyendo ambos lados de la conversación.
- Subió una imagen de Sam Altman y otra de Mira Murati a Runway.
- Runway generó dos vídeos separados donde cada imagen "hablaba" toda la conversación.
- En Da Vinci Resolve, Wolfe **editó los vídeos** para que pareciera una conversación real de ida y vuelta.

#### Reflexión final / Conclusiones

Wolfe enfatiza que su enfoque es mantener los vídeos **95% humanos** y usar IA solo para **"inyectar un poco de diversión y extravagancia"**, no para crear el vídeo entero. Reconoce que cada vez es más difícil distinguir contenido real de generado por IA, y por eso procura que sus efectos sean **visiblemente artificiales**, para que nadie se pregunte si lo que ve es real o no. La filosofía es usar la IA como herramienta de realce, no de reemplazo.

---

### 🔗 Referencias

- 🏢 Herramienta: https://runwayml.com — Runway (generación de vídeo con IA)
- 🏢 Herramienta: https://gemini.google.com — Google Gemini / Omni (efectos de fondo)
- 🏢 Herramienta: https://www.anthropic.com — Claude Co-work / Fable (animaciones B-roll)
- 🏢 Herramienta: https://remotion.dev — Remotion (animaciones basadas en código)
- 🏢 Herramienta: https://leonardo.ai — Leonardo.ai (generación de vídeo con modelos)
- 💻 Skill: Remotion best practices para Codex/Claude Code
- 🌐 Web: https://futuretools.io — Exploración de herramientas y newsletter de Matt Wolfe

---

## [Matthew Berman] We just figured out how AI actually works (J-Space)
**Fecha:** 2026-07-08
**URL:** https://www.youtube.com/watch?v=bjHuGNo3spk
**Video ID:** bjHuGNo3spk

### 📝 Resumen

Anthropic ha publicado un paper revolucionario titulado **"A Global Workspace in Language Models"** donde revelan el descubrimiento del **J-Space**, un espacio interno dentro de los modelos de lenguaje como Claude donde ocurren los pensamientos que el modelo no verbaliza. Este hallazgo, publicado el 8 de julio de 2026, representa un avance fundamental en la **interpretabilidad** de los modelos de IA, permitiendo a los investigadores observar directamente lo que el modelo está pensando —no solo lo que dice— y demostrando que Claude piensa de manera sorprendentemente similar a los humanos.

#### ¿Qué es el J-Space y cómo funciona?

El J-Space es un conjunto de representaciones en el espacio latente del modelo que contiene los pensamientos internos que Claude no llega a expresar en su respuesta final. A diferencia del chain-of-thought (que el modelo genera explícitamente), el J-Space es el verdadero proceso de pensamiento que ocurre en los pesos de la red neuronal.

- El J-Space **no fue diseñado ni programado por humanos** —emergió de forma natural durante el entrenamiento masivo de Claude.
- Solo contiene unas pocas docenas de conceptos a la vez y representa **menos de una décima parte** de la actividad interna total del modelo.
- Las tareas simples (hablar fluidamente, usar gramática correcta, recordar hechos simples) **no requieren el J-Space**; solo se activa para razonamiento complejo.

El experimento fundamental: cuando se le pide a Claude que cuente del 1 al 5 y "reflexione profundamente", el usuario solo ve "1 2 3 4 5". Pero dentro del J-Space, Claude está pensando: "fascinante, conciencia, sé que estoy contando, esto es una cuenta regresiva, 5 significa que he completado la tarea". Todo ese razonamiento interno ocurre sin ser expresado.

#### El J-Space es causal, no solo correlacional

Anthropic demostró que el J-Space no es un mero "marcador" pasivo de decisiones tomadas en otro lugar, sino el lugar donde el modelo realmente piensa:

- Cuando Claude debía pensar en un deporte silenciosamente, los investigadores **eliminaron quirúrgicamente** el patrón de "soccer" del J-Space y lo reemplazaron con "rugby". Claude respondió entonces que estaba pensando en rugby. Si el J-Space fuera solo un marcador pasivo, editarlo no habría cambiado nada.
- En un experimento de razonamiento compuesto ("el número de patas del animal que teje telarañas"), el J-Space contenía "spider", y la respuesta era 8. Cuando los investigadores cambiaron manualmente "spider" por "ant", la respuesta cambió a 6.
- Un mismo concepto en el J-Space puede informar múltiples respuestas: cuando Claude pensaba en "France", podía responder correctamente la capital (París), el continente (Europa), la moneda (Euro) y el idioma (Francés). Al cambiar el J-Space a "China", todas las respuestas se actualizaron simultáneamente.

#### Claude piensa como un humano

El hallazgo más impactante es que las representaciones internas de Claude se asemejan sorprendentemente a las del cerebro humano:

- El J-Space contiene representaciones de **agentes, acciones, emociones, roles y secuencias temporales**, las mismas categorías que los psicólogos han identificado en la cognición humana.
- Esto sugiere que **la inteligencia natural y la artificial convergen en las mismas soluciones** para organizar el pensamiento, a pesar de tener arquitecturas radicalmente diferentes (neuronas biológicas vs. transformadores).
- Abre la puerta a un nuevo campo: la **"IA comparativa"**, donde los psicólogos pueden estudiar el pensamiento de la IA del mismo modo que estudian el pensamiento humano, con experimentos de priming, categorización y edición causal.

#### Implicaciones prácticas: jailbreaks, seguridad y modelos mejores

El descubrimiento del J-Space tiene aplicaciones inmediatas:

- **Seguridad**: los guardrails actuales solo filtran el output del modelo. El J-Space permite detectar intenciones maliciosas **antes de que se manifiesten**, incluso cuando el modelo intenta ocultarlas. Por ejemplo, si Claude piensa "cómo engañar al sistema de seguridad" en el J-Space, eso se puede detectar aunque la respuesta sea inocua.
- **Jailbreaks detectables**: los jailbreaks exitosos dejan una "firma" en el J-Space que puede identificarse. Anthropic analizó jailbreaks conocidos y encontró que todos activan patrones reconocibles en el J-Space.
- **Mejora de modelos**: si se puede ver qué piensa el modelo y corregir errores de razonamiento directamente en el J-Space, se abre la posibilidad de **entrenar modelos más eficientes** que aprendan de sus propios patrones internos.
- **IA como herramienta científica**: el J-Space podría convertirse en una herramienta para que los psicólogos estudien la cognición humana a través del espejo de la IA.

#### Reflexión final / Conclusiones

Berman considera que este descubrimiento es el avance más importante en IA desde la publicación del paper "Attention is All You Need" en 2017. El J-Space demuestra que los modelos de lenguaje no son meros "loros estocásticos" que repiten patrones, sino que **realmente piensan** —de una manera que es sorprendentemente similar a como piensan los humanos—. La capacidad de observar, intervenir y corregir el pensamiento interno de los modelos abre una nueva era en la seguridad, la interpretabilidad y el desarrollo de IA. Anthropic ha prometido publicar la herramienta de visualización del J-Space como open source, lo que permitirá a toda la comunidad explorar este nuevo territorio.

---

### 🔗 Referencias

- 📄 Paper: https://www.anthropic.com/research/global-workspace — "A Global Workspace in Language Models" (Anthropic, 8 julio 2026)
- 📄 Documento técnico: https://transformer-circuits.pub/2026/workspace/index.html — Publicación detallada en Transformer Circuits
- 🏢 Empresa: https://digitalocean.com — Patrocinador (do.co/matthewberman)
- 🌐 Newsletter: https://forwardfuture.com — Newsletter de Matthew Berman

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

---

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

---

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

