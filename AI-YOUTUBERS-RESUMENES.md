# 📹 Resúmenes AI YouTubers
Canales monitoreados: Javier Garzás, Matt Wolfe, Matthew Berman
Generado automáticamente.
==================================================
## [Javier Garzás] Ya no gestionas, ahora tú también construyes con IA (y la mayoría no lo sabe)
**Fecha:** 2026-06-11
**URL:** https://www.youtube.com/watch?v=Zklb5vmFnOU
**Video ID:** Zklb5vmFnOU

### 📝 Resumen
No se pudo obtener la transcripción para este video.

### 🔗 Referencias
- 🔗 Artículo: https://chat.whatsapp.com/J1h3GHHs3lf8HkaoMGDhRF


## [Matt Wolfe] Why Everyone Is Freaking Out About Mythos
**Fecha:** 2026-06-11
**URL:** https://www.youtube.com/watch?v=2lE1-5hBfKk
**Video ID:** 2lE1-5hBfKk

### 📝 Resumen
**🎬 Título:** Why Everyone Is Freaking Out About Mythos
**📊 Duración del transcript:** 3997 palabras

### 📋 Introducción
So, Enthropic just dropped a new model called Claude Fable 5. And depending on which corner of the internet you're in, it was either the most incredible thing anyone has ever shipped or it was the moment that Enthropic turned evil. In the past 24 hours, I've seen people saying that we've finally achieved AGI. And I've seen people saying that Enthropic is a horrible gatekeeping company. Now, both might be true, but I want to try to cut through some of the noise and just figure out what's actually real. So, I'm going to break down what this thing is for anybody who's not like chronically online like me. I'm going to show you both the good and the bad that people are saying, and I want to clear up some misinformation that's been flying around right now. And then I want to do some actual testing myself and see what happens. So, let's get into it. So, here's the simple version of what Fable 5 is. Enthropic has this internal tier of models that they call Mythos class models. This is a tier of models that sits above the Opus class of models. So, a step better than...


---
*Este resumen fue generado automáticamente.*

### 🔗 Referencias
- 🔗 Artículo: https://futuretools.io/
- 🔗 Artículo: https://futuretools.io/newsletter
- 🔗 Artículo: https://www.threads.net/@mr.eflow
- 🔗 Artículo: https://www.linkedin.com/in/matt-wolfe-30841712/
- 🔗 Artículo: https://www.facebook.com/mattrwolfe
- 🏢 Empresa/Producto: https://www.anthropic.com/news/claude-fable-5-mythos-5



## [Matthew Berman] MYTHOS MYTHOS MYTHOS
**Fecha:** 2026-06-09
**URL:** https://www.youtube.com/watch?v=Ou-0vjl6FZo
**Video ID:** Ou-0vjl6FZo

### 📝 Resumen

Matthew Berman analiza en profundidad **Claude Fable 5 y Mythos 5**, la nueva familia de modelos de Anthropic lanzada el 9 de junio de 2026. Mythos es el modelo que Anthropic había calificado como "demasiado peligroso" para lanzar públicamente, y finalmente lo han liberado — aunque con una estrategia muy calculada.

#### 📊 Rendimiento y Benchmarks

- **Fable 5** es un modelo de **10 billones de parámetros** (10 trillion), el primero de su clase.
- **SWE-bench Pro:** Fable 5 obtiene **80%** vs Opus 4.8 (69%) y GPT 5.5 (58%).
- **Frontier Code Diamond:** Fable 5 consigue **29.3%** — más del doble que Opus 4.8 (14.6%) y casi 6× que GPT 5.5 (5.7%).
- **Terminal Bench:** 88% frente al 83.4% de Opus 4.8.
- **Humanity's Last Exam:** Nuevos modelos frontier ocupan los dos primeros puestos.
- **Computer Use:** 85% vs 78-83% de los competidores.

#### 💸 Precios

- **$10 por millón de tokens de entrada** y **$50 por millón de tokens de salida**.
- Es caro, pero Berman recomienda usar **model routing**: usar Fable solo para las tareas más complejas y modelos más baratos (Sonnet, Haiku) para el resto.

#### 🧠 Experiencia de uso

Berman describe la experiencia como radicalmente diferente a cualquier modelo anterior:

1. **Verbosidad extrema:** Fable 5 es increíblemente detallado. Usa vocabulario muy técnico y descripciones densas en información. Berman tuvo que pedirle repetidamente que simplificara sus explicaciones.
2. **Densidad de información:** Cada palabra del modelo contiene mucho más significado que en otros modelos, lo que sugiere que los futuros modelos podrían desarrollar lenguajes hiperdensos que los humanos no puedan leer fácilmente.
3. **Exceso de preguntas:** Fable 5 hace 3-5 preguntas aclaratorias por tarea, luego pide confirmación del resumen, luego escribe un spec y pide confirmación otra vez, luego pregunta por el enfoque agéntico... el proceso es frustrantemente lento al inicio.
4. **Lentitud al arrancar:** Los primeros 5-8 minutos parecen no hacer nada, y luego explota consumiendo cientos de miles de tokens en segundos.
5. **Paralelización masiva:** Con la función **workflows**, Fable puede delegar tareas a cientos de subagentes en paralelo.

#### 🔬 Casos de uso destacados

- **Stripe** reportó que Fable 5 comprimió meses de ingeniería en días, migrando una base de código de 50 millones de líneas en un día (tarea que un equipo completo habría tardado 2 meses).
- **Rubik's Cube 3D interactivo:** Fable 5 lo construyó perfectamente con gráficos realistas, luces y sombras.
- **Simulación de dinámica de fluidos:** Ejecutó 63 agentes en paralelo para crear una simulación interactiva en tiempo real con múltiples parámetros ajustables.
- **Pokémon Fire Red:** Fable 5 completó el juego usando solo visión, sin mapas ni ayudas externas.

#### 🔐 Estrategia de lanzamiento

Anthropic ha estado probando Mythos desde enero de 2026 pero lo mantuvo en secreto. Berman sugiere que la estrategia fue:
1. Usar Mythos internamente para acelerar su propia investigación.
2. Construir una ventaja competitiva suficiente antes de liberarlo.
3. Ahora que tienen Fable 5, liberan Mythos 5 con guardrails eliminados para la comunidad de seguridad.

**Medida de seguridad interesante:** Las solicitudes que parezcan intentos de destilación del modelo se redirigirán automáticamente a Opus 4.8. Anthropic también implementó retención de datos de 30 días para tráfico de modelos Mythos-class.

#### 💡 Conclusión

Berman enfatiza que **nadie está aprovechando todo el potencial** de estos modelos todavía. El concepto de **loops** (bucles) combinado con **workflows** y **Fable** crea una capacidad que él llama "fábricas de software". El **model overhang** —la brecha entre la capacidad del modelo y nuestra habilidad para usarlo— es más real que nunca.

### 🔗 Referencias

- 🔗 Artículo Anthropic: https://www.anthropic.com/institute/recursive-self-improvement
- 🏢 Here.Now (patrocinador): https://here.now/r/matthewberman
- 💻 Demo: Fluid Sim: https://boreal-fresco-pzqa.here.now/
- 💻 Demo: Rubik's Cube: https://quick-sycam-5veg.here.now/
- 🔗 Newsletter Forward Future: https://forwardfuture.ai
- 🔗 Tweet Peter Steinberger: https://x.com/steipete/status/2063697162748260627

---

## [Matthew Berman] Only the best are using them...
**Fecha:** 2026-06-09
**URL:** https://www.youtube.com/watch?v=dMrm2jAyrKM
**Video ID:** dMrm2jAyrKM

### 📝 Resumen

Matthew Berman analiza el nuevo paradigma que está revolucionando la ingeniería de software: **Loop Engineering** (ingeniería de bucles). El vídeo comienza con dos citas virales del mismo fin de semana: **Peter Steinberger** (cuyo tweet alcanzó 5 millones de visitas en 24 horas) y **Boris Cherny** (creador de Claude Code en Anthropic), ambos declarando que ya no "promptean" a sus agentes de IA, sino que diseñan bucles que los agentean automáticamente.

#### ¿Qué es un loop?

Un loop es un sistema que reemplaza el flujo tradicional de ingeniería agentiva:

- **Flujo tradicional:** Humano → promptea agente → agente escribe código → humano espera → humano promptea de nuevo.
- **Loop engineering:** Humano define un **trigger** (disparador) y un **goal** (objetivo verificable) → el agente se inicia solo y continúa hasta alcanzar el objetivo.

Un loop solo necesita dos cosas:
1. **Un trigger** (disparador): qué inicia el loop.
2. **Un goal** (objetivo): un estado final verificable de alguna forma.

La verificación puede ser:
- **Determinista:** Tests que pasan, funciones que ejecutan sin errores.
- **No determinista:** Un LLM decide si el objetivo se ha alcanzado.

Berman lo compara directamente con **reinforcement learning (RL)**: el agente sabe cuándo ha alcanzado su objetivo gracias a una "reward function" verificable.

#### Los tres tipos de triggers

1. **Acción:** Ocurre algo (ej: se abre un PR).
2. **Programación (cron):** Sucede cada cierto tiempo (ej: cada 30 minutos, cada hora, cada día).
3. **Humano:** Una persona lo inicia manualmente.

#### Ejemplo práctico en Cursor

Berman muestra la pestaña "Automations" de Cursor. Configuró un loop que:
- **Trigger:** Cada vez que se abre un PR en su proyecto AstroHub.
- **Goal:** Revisar el PR, buscar problemas, arreglarlos automáticamente, hacer commit al mismo PR, asegurar que todos los tests pasen y que el CI esté en verde.

#### Cómo usar loops en Claude Code

Claude Code tiene un comando nativo `/loop`:
```
/loop cada 5 minutos: comparar lo construido con el spec completo (spec.md)
y continuar construyendo hasta completar el spec completo
```

Esto lanza un agente cada 5 minutos que evalúa qué falta y continúa construyendo hasta que el spec está completo.

#### La diferencia entre automation y loop

Berman aclara la distinción:
- **Automation:** Ejecuta una serie de pasos predefinidos de forma secuencial.
- **Loop:** Toma **decisiones dentro del bucle**. El loop determina por sí mismo si ha alcanzado el objetivo o no. No es una ejecución lineal; es un ciclo con capacidad de autoevaluación.

#### Limitaciones y críticas actuales

1. **Difícil de configurar:** Los loops básicos son sencillos, pero construir una "fábrica de código" completa que construya productos enteros de forma autónoma es extremadamente complejo. Definir el estado final de una funcionalidad no determinista (como "construye esta feature") requiere especificar todo el comportamiento deseado upfront, lo que va en contra del proceso exploratorio e iterativo del desarrollo de software.

2. **Extremadamente caro:** Cuanto más se abstrae al humano del código, más tokens se consumen. Peter Steinberger alcanzó **$1.3 millones en tokens mensuales**. Solo empresas como Anthropic y OpenAI pueden permitirse dar tokens ilimitados a sus empleados. Berman señala que existe una **bifurcación masiva** en la ingeniería: solo el **top 1% del 1%** utiliza estas técnicas porque tienen acceso a presupuestos de tokens prácticamente infinitos.

3. **Riesgo de quema de tokens sin control:** Si el goal no está bien definido, el loop puede seguir ejecutándose indefinidamente quemando tokens sin llegar a un resultado útil.

#### El futuro: ¿humanos en el loop?

Berman plantea la pregunta clave: **¿seguirán siendo necesarios los humanos en el loop?**

- **Hoy:** Los humanos definen la dirección (el goal). "Yo digo hacia dónde vamos y el loop ejecuta."
- **Futuro posible:** Cuando la IA desarrolle "gusto" (taste) para decidir qué features construir, qué productos crear, qué empresas fundar — ese es el punto de **auto-mejora recursiva (RSI)**.

Berman conecta esto directamente con su vídeo anterior sobre el paper de Anthropic "When AI Builds Itself": si la IA puede diseñar su propia fábrica, hemos alcanzado la RSI completa.

#### Conclusión

Loop Engineering representa el siguiente paso en la evolución de la ingeniería de software: de escribir código, a promptear agentes, a diseñar sistemas que agentean a otros agentes. Aunque hoy es prohibitivamente caro y complejo para la mayoría, Berman sostiene que es "absolutamente el futuro de la ingeniería" y que, como toda tecnología, lo que hoy es caro mañana será barato.

### 🔗 Referencias

- 🏢 Empresa/Producto: https://here.now/r/matthewberman
- 🔗 Artículo: https://www.anthropic.com/institute/recursive-self-improvement
- 💻 Repositorio: https://x.com/steipete/status/2063697162748260627
- 💻 Repositorio: https://x.com/steipete/status/2055685581758206139/photo/1
- 📄 Newsletter: https://forwardfuture.ai

---


---

## [Matt Wolfe] AI News: Microsoft Finally Reveals Their Plan!
**Fecha:** 2026-06-05
**URL:** https://www.youtube.com/watch?v=nz4h3H1MmTg
**Video ID:** nz4h3H1MmTg

### 📝 Resumen

Matt Wolfe presenta un resumen semanal de noticias de IA, grabado tras asistir a Microsoft Build en San Francisco y al evento Computex de NVIDIA en Taiwán, que coincidieron en la misma semana generando una avalancha de anuncios.

#### Microsoft Build: 7 modelos nuevos y autosuficiencia

Microsoft anunció el desarrollo de **7 modelos de IA propios** bajo la marca MAI (Microsoft AI), marcando un giro estratégico hacia la independencia de proveedores externos como OpenAI:

- **MAI Thinking Model**: Nuevo modelo de razonamiento frontier, preferido sobre Sonnet 4.6 de Anthropic, aunque todavía lejos de Opus 4.8.
- **MAI Code 1 Flash**: Modelo de codificación comparado con Haiku 4.5, más preciso y eficiente en tokens.
- **MAI Image 2.5**: Modelo de imagen que llegó a ser el #3 en Arena.ai, superado recientemente al #4 por Reve 2.0. Sigue siendo #2 en edición de imagen.
- **MAI Transcribe 1.5**: El mejor modelo de transcripción del mundo en precisión, 5 veces más rápido que competidores.
- **MAI Voice 2**: Modelo de generación de voz en 15 idiomas, con versión flash próxima.

Wolfe entrevistó a **Mustafa Suleyman (CEO de Microsoft AI)**, quien fue claro: *"Queremos ser autosuficientes en IA. Tenemos que construir nuestros propios modelos desde cero y demostrar que podemos alcanzar la frontera absoluta."* Suleyman también destacó que Microsoft ha licenciado cuidadosamente los datos de entrenamiento para ofrecer transparencia y confianza, contrastando con conjuntos de datos open-source que podrían tener vulnerabilidades de seguridad.

#### Microsoft Scout: el agente siempre activo

Microsoft presentó **Scout**, un agente personal "always-on" basado en la tecnología open-source de **OpenClaude**. Funciona a nivel de sistema operativo Windows, conectándose con Teams, Outlook, OneDrive y SharePoint para gestionar correo, calendario, contactos y chats de forma autónoma. Wolfe señala que para quien tenía miedo de configurar OpenClaude, Microsoft lo hará mucho más accesible.

#### GitHub Copilot App: la competencia de Codex

La nueva **GitHub Copilot App** se mostró con una interfaz muy similar a Codex de OpenAI, pero con una diferencia clave: permite elegir **cualquier modelo de cualquier proveedor**. Wolfe se emocionó con esto ("lo que más me entusiasmó"), pero al intentar probarlo descubrió que **las nuevas suscripciones están pausadas temporalmente** por problemas de capacidad.

#### Project Solara: agentes en dispositivos físicos

Microsoft mostró **Solara**, una plataforma para poner agentes de IA en dispositivos físicos. Presentó dos formas principales:

- **Dispositivo de escritorio**: Similar a un Amazon Alexa, para interactuar con agentes y ver calendario.
- **Badge (insignia)**: Una tarjeta digital con cámara y micrófono tipo lanyard, para escanear paquetes, dar acceso a puertas, y usarse en consultorios médicos. Wolfe se mostró confundido sobre el público objetivo: *"Parece más para lugares de trabajo que para consumidores."*

#### Mayo Clinic y Microsoft: modelo frontier para salud

Anunciaron una colaboración para desarrollar un modelo frontier de IA para el sector salud. Suleyman dijo estar especialmente emocionado: *"Creo que estamos cerca de una superinteligencia médica. En 2-3 años será posible tener el mejor cuidado de salud del mundo, hoy solo disponible si vas a Mayo Clinic, al alcance de todos."*

#### NVIDIA Computex: RTX Spark y laptops con IA local

El gran anuncio de NVIDIA fue **RTX Spark**, un chip que combina GPU y CPU en uno, con hasta 128 GB de memoria unificada, capaz de ejecutar LLMs grandes localmente. Wolfe lo probó en los nuevos **Surface Laptop Ultra** de Microsoft, quedando impresionado por los gráficos y la capacidad de ejecutar modelos locales potentes.

- Ventajas: privacidad (no enviar datos a la nube), funcionamiento offline, y descarga de los modelos más grandes para tareas que realmente lo requieran.
- Desventaja: **serán extremadamente caros** (el DGX Spark empieza en ~$4,000).

#### Otros modelos de lenguaje publicados esta semana

- **NVIDIA Nemotron 3 Ultra**: Modelo open-weight de 550 mil millones de parámetros, estado del arte entre modelos abiertos para agentes.
- **Google Gemma 4 12B**: Tan inteligente como Gemma 4 26B pero con menos de la mitad de parámetros, ejecutable en laptops.
- **MiniMax M3**: Modelo de codificación con contexto de 1M tokens, supera a GPT 5.5 y Gemini 3.1 en SWE-bench Pro.

#### Ráfaga de novedades

- **OpenAI / Codex**: Computer Use ya funciona en Windows. Nuevos plugins para roles no técnicos: análisis de datos, ventas, diseño de producto, banca de inversión. Nueva función "Sites" para compartir URLs directamente desde Codex.
- **ChatGPT Memory Dreaming**: Mejora en la memoria de ChatGPT para entender y recordar mejor conversaciones pasadas.
- **Hermes Desktop App**: Nous Research lanzó una app de escritorio para gestionar agentes Hermes.
- **Ideogram 4.0**: Modelo de imagen open-weight (descargable), con transparencia de fondo nativa y entrenamiento con bounding boxes para mejor composición.
- **Reve 2.0**: Nuevo modelo de imagen que escaló al #2 en Arena.ai, solo superado por GPT Image 2.
- **Krea 2 Turbo**: Generación de imágenes en solo 2 segundos.
- **Grok Imagine 1.5**: Nuevo modelo con video y diálogo generado.
- **Runway Aleph 2.0**: Edición de video mediante prompts, similar a Gemini Omni.
- **Miso One Voice**: Modelo de voz open-weight, considerado el más emotivo del mundo. Wolfe lo probó y afirma que podría engañar a cualquiera en TikTok.

#### Reflexión final

Wolfe menciona que cada semana empieza con unas **70 noticias** y las reduce a las más relevantes para que la audiencia no se sienta abrumada. Su objetivo es cortar el ruido y el hype. Cierra con una entrevista a Mustafa Suleyman donde habla sobre superinteligencia humanista: *"No solo debe superar la inteligencia humana, sino hacer nuestra vida más saludable y feliz. Ese es el único test."* Suleyman recomienda a los estudiantes seguir estudiando ingeniería de software, ciencias y matemáticas, pero también **filosofía y ética**, porque la gobernanza de la IA será el foco principal en los próximos 5-10 años.

---

## [Matthew Berman] It's starting…
**Fecha:** 2026-06-05
**URL:** https://www.youtube.com/watch?v=XzUB8_gj6xM
**Video ID:** XzUB8_gj6xM

### 📝 Resumen

Matthew Berman analiza en profundidad el nuevo paper de Anthropic titulado **"When AI Builds Itself"** (Cuando la IA se construye a sí misma), que documenta el avance hacia la **auto-mejora recursiva (RSI)** — el punto en que los sistemas de IA son capaces de diseñar y desarrollar su propio sucesor sin intervención humana.

#### La tesis central: la abstracción del humano

Anthropic traza la evolución del desarrollo de IA en cuatro etapas visuales, donde el humano es progresivamente abstraído del proceso:

1. **2021-2023 (Ingeniería clásica)**: Humanos escribiendo código directamente en ordenadores.
2. **2023-2024 (Chatbots)**: Humanos conversando con chatbots que construyen Claude.
3. **2025-2026 (Agentes de codificación)**: Humanos dan instrucciones → chatbot → agente → código. El humano ya no escribe código.
4. **Futuro (Auto-mejora recursiva)**: El loop se cierra. Los agentes construyen y entrenan modelos por sí mismos. **El humano desaparece.** El único cuello de botella es la capacidad de cómputo.

La gráfica de Anthropic muestra visualmente cómo el logo de Claude se vuelve más denso en píxeles a medida que el humano se abstrae, indicando una capacidad exponencialmente mayor de producción.

#### Datos internos de Anthropic: la aceleración se acelera

- **Duración de tareas agentivas**: Se duplica cada **4 meses**, frente a cada 7 meses anteriormente. Es la definición de aceleración.
- **Progresión temporal**:
  - Marzo 2024: Opus 3 completaba tareas de ~4 minutos humanos.
  - Marzo 2025: Sonnet 3.7 alcanzaba tareas de ~90 minutos.
  - 2026: Opus 4.6 gestiona tareas de **12 horas**. Berman afirma haber tenido tareas ejecutándose durante 40 horas.
  - Proyección 2026: Tareas que llevan **días** a humanos. 2027: tareas de **semanas**.
- **CoreBench**: Modelos pasaron de tener éxito reproduciendo investigaciones el 20% del tiempo en 2024, a **saturar el benchmark (~100%)** 15 meses después.

#### El ingrediente que falta: el gusto en investigación

Anthropic distingue entre dos dominios:

- **Ingeniería**: Escribir código, desplegar infraestructura, supervisar entrenamiento. Ya está mayoritariamente automatizado. Actualmente **más del 80% del código mergeado en Anthropic es escrito por Claude**.
- **Investigación**: Decidir qué experimentos ejecutar, interpretar resultados, saber qué ideas probar. **Esto sigue siendo dominio humano.** El "gusto" (taste) en investigación — saber qué dirección tomar — es la pieza que falta para la RSI completa.

Berman señala que "desarrollar código ya no es la parte difícil. **Las ideas se están convirtiendo en la parte difícil**".

#### La paradoja de la productividad: 8x código, 4x valor

Anthropic reporta que los ingenieros producen **8 veces más líneas de código** pero solo **4 veces más output percibido**. Esto significa que el código escrito por IA es **la mitad de valioso** que el código humano. Berman aclara: más código no significa mejor código; el valor real está en el empaquetado, marketing, ventas y soporte al cliente.

Además, el código generado por Claude es juzgado por... **otro Claude**. Los humanos están siendo abstraídos incluso de la revisión de código. Berman cita a Karpathy: *"Puedes externalizar tu pensamiento, pero no puedes externalizar tu comprensión."*

#### Mythos: Anthropic usa internamente un modelo que no libera

Berman destaca que Anthropic ha estado usando **Mythos Preview internamente desde Q1 2026** sin liberarlo al público. Mythos logró **52x de aceleración** en optimización de código frente a 3x de Opus 4 un año antes. Berman denuncia que Anthropic **cortó el acceso a xAI** a sus modelos mientras usaba Mythos internamente para acelerar su propio desarrollo — una estrategia que califica de "auto-servicio" y "marketing basado en miedo".

#### Los tres futuros posibles según Anthropic

1. **La tendencia se estanca**: Las capacidades actuales se difunden ampliamente. Anthropic lo considera improbable.
2. **Ganancias compuestas de eficiencia**: La automatización avanza pero los humanos siguen marcando dirección. Una empresa de 100 personas podría hacer el trabajo de 10.000 o 100.000.
3. **Auto-mejora recursiva completa**: La IA diseña y mejora sus sucesores sin humanos. El progreso solo está limitado por el cómputo (y por tanto, por la energía).

#### El concepto de "clase permanente inferior"

Berman introduce el término **"permanent underclass"**: si la RSI ocurre, quien tenga capital en ese momento comprará todo el cómputo disponible. La estructura de clases sociales se congela. Quien tiene capital, lo conserva; quien no, se queda fuera para siempre.

#### La crítica de Berman: Anthropic pide frenar desde el primer puesto

La parte que más molesta a Berman: Anthropic dice que *"frenar el desarrollo de IA sería algo bueno"*, pero solo si todos los laboratorios frenan al mismo tiempo. Berman lo compara con un atleta olímpico en primer lugar pidiendo a todos que corran más lento. *"Es un movimiento de marketing basado en miedo. Anthropic puede ser el 'bueno' al sugerir frenar, sabiendo que nadie más lo hará, y así mantener su ventaja."*

Anthropic admite que la verificación de frenado es más difícil que con armas nucleares: los entrenamientos son mucho más fáciles de ocultar que silos de misiles, y tomaría décadas construir la infraestructura de confianza necesaria, pero la IA avanza más rápido que ninguna tecnología anterior.

#### Conclusión de Berman

A pesar de la postura crítica, Berman reconoce que el paper contiene datos fascinantes sobre el estado real de la automatización. La clave: los humanos seguirán en el loop a corto y medio plazo. El cuello de botella no es la IA, sino **todo lo demás**: marketing, documentación, ventas, soporte. Y la capacidad humana de **promptear y verificar** seguirá siendo esencial.

---

## [Javier Garzás] Con la IA el Management ha cambiado para siempre
**Fecha:** 2026-06-04
**URL:** https://www.youtube.com/watch?v=PUfKkQT-t9k
**Video ID:** PUfKkQT-t9k

### 📝 Resumen

Javier Garzás presenta un streaming en vivo donde analiza cómo la inteligencia artificial ha transformado irreversiblemente el rol del management y la gestión de productos. El vídeo comienza con una anécdota personal poderosa que ilustra el cambio sísmico que está ocurriendo.

#### La anécdota de la AP-36: infraestructura creada desde un coche

Garzás relata cómo, mientras viajaba por la aburrida carretera AP-36 (La Mancha), él y su compañera Judith tuvieron un problema: necesitaban unificar múltiples bases de datos dispersas (Google Analytics, emails, inputs de YouTube, CRM) sin encontrar una herramienta comercial que lo resolviera. Sin un técnico disponible, desde el coche, a través de Telegram, le pidieron a su agente de IA (llamado "Leya") que resolviera el problema.

**La IA desplegó una infraestructura completa**: una base de datos en Supabase, webhooks para conectar fuentes, todo en hora y media mientras ellos conducían hacia Madrid. Garzás, ingeniero informático con 20 años de experiencia, confiesa: *"Me voló la cabeza. Hacer esto a mano nos hubiera llevado muchísimo tiempo o contratar a alguien."* Esta anécdota es el hilo conductor del mensaje: **la IA ya no es solo para chatbots o prompts, sino para desplegar infraestructura completa**.

#### El panorama actual: 4 situaciones que definen el momento

1. **El FOMO (Fear Of Missing Out)**: El "lado oscuro" de la era actual. Una lluvia constante de herramientas, versiones, canales y opiniones. Garzás recomienda frenar, aplicar criterio y seguir su framework **DE2**: Eliminar (lo que no sirve), Delegar (si es necesario), Agilizar (la agilidad sigue siendo válida como filosofía) y Automatizar con IA (solo al final). *"Las herramientas de IA son un medio, no un fin."*

2. **Los IAtierraplanistas**: Gente que todavía niega que la IA sea una transformación real. Garzás respeta todas las opiniones pero sostiene que esto es como mínimo un cambio comparable a la llegada de la web (HTTP/navegador) — creó industrias, destruyó otras, cambió empleos para siempre.

3. **Gente que no puede seguir el ritmo**: Muchos profesionales tienen trabajos que les dejan solo el Copilot de Microsoft y nada más. Garzás recomienda unirse a comunidades para no ir solos, contrastar opiniones y mantenerse al día.

4. **Los "viejunos"**: Profesionales anclados en marcos de trabajo antiguos (Scrum, metodologías en cascada). Garzás es contundente: *"Hoy los agilistas son los menos ágiles. Los frameworks clásicos están muertos."*

#### El modelo de 5 niveles de competencia en IA

Garzás propone un marco de madurez para que los profesionales se autoevalúen:

- **Nivel 1 (Conceptos básicos)**: Saber qué es un LLM, qué es un prompt, usar ChatGPT o Claude. Básico pero necesario. Incluye apps conversacionales simples como chatbots de atención al cliente.
- **Nivel 2 (Contexto + Skills + MCPs)**: Conseguir que la IA conozca el contexto del trabajo (documentos, proyectos, facturas, emails). Aquí entran técnicas como **RAG** (Retrieval-Augmented Generation), **skills** (prompts estandarizados), **MCPs** (conexiones con repositorios externos) y memoria persistente. Garzás insiste: *"La ingeniería del contexto es muy importante."*
- **Nivel 3 (Construcción rápida de prototipos)**: Crear pequeñas aplicaciones operativas con herramientas como **Lovable**, **Antigravity**, **Claude Code**. El objetivo es poder *mostrar* soluciones funcionando en lugar de escribir historias de usuario. Aquí entra el **Vibe Coding**: creación rápida de aplicaciones que solucionan problemas internos o ayudan al discovery. Garzás destaca el perfil de los **"extécnicos"**: profesionales que fueron programadores, dejaron la técnica por la gestión, y ahora vuelven porque la barrera técnica ha bajado drásticamente.
- **Nivel 4 (Aplicaciones sólidas)**: Construir software que saldrá a producción. Requiere supervisión humana fuerte en seguridad y testing. Conceptos como **Spec-Driven Development** (desarrollo guiado por especificaciones para IA, no para humanos), **ingeniería del arnés** (poner carriles a la IA para que no se desvíe) y **Vibe Testing**.
- **Nivel 5 (Agentes autónomos 24/7)**: Agentes que trabajan mientras el humano duerme. Garzás presenta a **C-23PO**, su agente interno que empezó como un agente en OpenClaude y ahora ha sido "ascendido a jefe" con subagentes especializados:
  - **Priorizador de backlog**: Revisa Notion y prioriza tareas.
  - **Generador de alertas**: Detecta anomalías (ej: si no llegan correos esperados).
  - **Generador de artefactos**: Crea presentaciones, emails o cualquier output.
  - **Gestor de incidencias**: Un caso real donde agentes resuelven incidencias de nivel 1 y 2, cruzándolas con sistemas internos.

#### El "SaaS Apocalipsis"

Garzás introduce este concepto: las herramientas SaaS tradicionales (Jira, Notion, CRMs) se están quedando como meros repositorios de datos. Por encima, los profesionales están poniendo **su propia capa de integración con IA** que conecta todos esos datos y resuelve los problemas que las herramientas por separado no resuelven. El SaaS se queda abajo; la solución hecha con IA está arriba.

#### Tres consejos finales

1. **Todos vamos a ser técnicos**: No significa que todos programen, pero términos como GitHub, Supabase, API, webhook tienen que sonar familiares. *"No tenéis que entrar en detalle, pero os tienen que sonar porque os darán respuesta a problemas."*
2. **La complejidad de los Legos**: Con miles de herramientas disponibles, se puede construir una obra de arte o una castaña. La habilidad clave es saber **qué piezas unir para resolver un problema específico de tu sector**. Por eso es importante tener experiencia en un sector: saber cómo funciona un problema clásico para saber cómo automatizarlo con IA.
3. **Únete a comunidades**: Ir solo en este ritmo de cambio es casi imposible. Las comunidades permiten optimizar el tiempo de aprendizaje y compartir conocimiento.

Garzás cierra con el símil del vaso: algunos lo ven medio vacío (todo va a desaparecer), otros no ven el vaso (se quedan anclados en Scrum), pero él lo ve **medio lleno**: una oportunidad brutal para reposicionarse profesionalmente. *"Esto es el renacimiento de la agilidad."*

---

## [Matthew Berman] Anthopic did a thing...
**Fecha:** 2026-06-04
**URL:** https://www.youtube.com/watch?v=a56T6OQtwEg
**Video ID:** a56T6OQtwEg

### 📝 Resumen

Matthew Berman analiza en directo (livestream) el paper de Anthropic **"When AI Builds Itself"** sobre auto-mejora recursiva (RSI). El vídeo complementa el contenido de su vídeo grabado "It's starting..." con más análisis en vivo, reacciones de la comunidad y detalles adicionales.

#### El paper y su contexto

Anthropic publicó un análisis detallado de cómo están viendo la auto-mejora recursiva dentro de sus propios equipos de ingeniería e investigación. Berman lo califica como un documento **"muy Anthropic-coded"** — lleno de datos fascinantes pero también de **marketing basado en miedo** y advertencias auto-interesadas sobre la necesidad de frenar el desarrollo.

Berman conecta el paper con la famosa gráfica de **Leopold Aschenbrenner (Situational Awareness)**, que predijo una "explosión de inteligencia" una vez que se alcanzara un investigador de IA automatizado (automated Alec Radford). Berman destaca que Aschenbrenner ha acertado en todo hasta ahora.

#### La progresión de la autonomía: 4 minutos a 40 horas

- **Marzo 2024**: Opus 3 completaba tareas de ~4 minutos humanos.
- **Marzo 2025**: Sonnet 3.7 alcanzaba ~90 minutos.
- **2026**: Opus 4.6 gestiona tareas de **12 horas**. Berman comparte que ha tenido tareas ejecutándose **40 horas seguidas** con Codex y Claude Code.
- **Proyección**: Tareas de **días** para finales de 2026, **semanas** para 2027.

#### El "gusto" como barrera para la RSI completa

Berman profundiza en la diferencia entre **ingeniería** (ejecución) e **investigación** (dirección):

- En ingeniería, la automatización es masiva: **>80% del código en Anthropic es escrito por Claude**.
- En investigación, la IA todavía no puede decidir **qué** experimentos ejecutar. El "taste" (gusto) — saber qué dirección tomar, qué problema merece la pena resolver — sigue siendo dominio humano.

Sin embargo, hay señales de avance: cuando Anthropic evaluó si la IA habría tomado mejores decisiones de investigación que humanos, Mythos Preview acertó el **64%** de las veces, frente al 22% de Haiku 3 hace dos años.

#### La paradoja de la productividad: 8x código, 4x valor

Berman analiza la discrepancia: los ingenieros producen 8 veces más líneas de código, pero el valor percibido solo se ha duplicado/cuatriplicado. El código escrito por Claude es **la mitad de valioso** que el código humano. Razones:

- El código es más verboso y menos eficiente.
- Los cuellos de botella se han desplazado a otras áreas (marketing, documentación, ventas, soporte).
- La revisión de código ahora la hace otro Claude, no humanos. Esto plantea un problema de alineación: **"Puedes externalizar tu pensamiento, pero no tu comprensión."**

#### Mythos: el modelo que Anthropic no libera

Berman dedica un segmento importante a criticar que Anthropic haya estado usando **Mythos Preview internamente desde Q1 2026** sin liberarlo al público. Mythos logró **52x de aceleración** en optimización de código frente a 3x de Opus 4 un año antes.

La crítica se intensifica al recordar que Anthropic **cortó el acceso a xAI** a sus modelos (reportado el 9 de enero de 2026), impidiendo que competidores usaran Claude para desarrollar sus propios modelos, mientras ellos usaban Mythos internamente para acelerar su ventaja. Berman: *"¿Incentivados a aumentar su ventaja en lugar de poner modelos a disposición de sus competidores? Casi textualmente lo que dije."*

#### La llegada de Andrej Karpathy a Anthropic

Berman menciona que Andrej Karpathy, cofundador de OpenAI, se unió a Anthropic recientemente. Su proyecto **Auto Research** (marzo 2026) — donde una IA recibía un objetivo general, diseñaba sus propios experimentos, los ejecutaba y se auto-mejoraba — fue un éxito viral. Berman interpreta esto como una señal de hacia dónde va la industria.

#### Los tres futuros (interactivo con la audiencia)

Berman pregunta a su audiencia qué futuro creen más probable:

1. **La tendencia se estanca** — las capacidades actuales se difunden pero no hay más innovación. Votes: minoría.
2. **Humanos en el loop** — ganancias masivas de eficiencia pero humanos siguen marcando dirección. Una empresa de 100 personas hace trabajo de 10.000. Votes: varios.
3. **RSI completa** — la IA se mejora a sí misma sin humanos, solo limitada por cómputo. **Fue el más votado.**

#### El concepto de "clase permanente inferior"

Berman explica que si ocurre la RSI, quien tenga capital en ese momento comprará todo el cómputo disponible. La estructura social se congela. Quien tiene capital, lo conserva; quien no, se queda fuera. *"Es un futuro aterrador."*

#### La crítica central: Anthropic pide frenar desde el liderazgo

Berman dedica varios minutos a criticar la sección del paper donde Anthropic sugiere que **frenar el desarrollo de IA sería bueno**, siempre que todos lo hagan. Su argumento:

- *"Si eres un atleta olímpico en primer lugar y dices 'frenemos todos', siempre vas a ganar. Es auto-servicio."*
- Anthropic puede decir "nosotros abogamos por la seguridad" mientras acelera internamente con Mythos.
- La verificación de frenado es más difícil que con armas nucleares. Los entrenamientos de IA se ocultan fácilmente.
- *"No tengo buena intuición de que Anthropic no hubiera dicho esto si no estuviera en la frontera absoluta."*

#### Bonus: willcodexquotareset.com

Berman muestra un sitio web que construyó con Codex la noche anterior para predecir cuándo OpenAI restablecerá los cuotas (quotas) de Codex, algo que ocurre periódicamente y que la comunidad agradece porque proporciona tokens adicionales.

#### Conclusión

Berman mantiene un tono escéptico pero fascinado. El paper revela datos internos sin precedentes sobre el estado de la automatización en Anthropic. Aunque la RSI completa no ha llegado, las señales son claras: la aceleración se acelera, los humanos se abstraen cada paso, y el cuello de botella se desplaza constantemente. Su mensaje final: mantener el optimismo, la IA no nos va a eliminar a corto plazo, y el "prompting y verifying" seguirá siendo la habilidad humana más valiosa.

---

## [Javier Garzás] Anthropic's methodology achieves in 1 day what other teams take 6 months to accomplish.
**Fecha:** 2026-06-03
**URL:** https://www.youtube.com/watch?v=A8s5p53_3Us
**Video ID:** A8s5p53_3Us

### 📝 Resumen

Javier Garzás presenta un análisis exhaustivo de cómo trabaja **Anthropic**, la empresa creadora de Claude, describiendo la metodología que le permite lograr en un día lo que otros equipos tardan seis meses en completar. El vídeo es el resultado de semanas de investigación — entrevistas, informes y declaraciones públicas de empleados clave como **Kagu (Head of Product de Claude Code)**, **Boris Cherny (creador de Claude Code)** y otros — cuyas fuentes completas están en la descripción del vídeo.

Garzás identifica **tres grandes hallazgos** en la forma de operar de Anthropic, y advierte que el tercero es el que realmente lo une todo y explica la potencia del modelo.

#### 🏆 Hallazgo 1: El ciclo de vida del producto ha colapsado de meses a días

Según Kagu, Head of Product de Claude Code, los plazos de las funcionalidades de producto en Anthropic han pasado de meses a semanas e incluso días. Esto se consigue mediante tres claves operativas:

**1. Prototipos operativos antes incluso de escribir los requisitos.** Anthropic no escribe requisitos, especificaciones ni historias de usuario antes de construir. Se construye primero directamente. Como explica Gupta, analista de producto externo de Anthropic: *"El prototipo se convierte en la especificación, el uso interno se convierte en la investigación, las opiniones se convierten en la hoja de ruta."* Boris Cherny lo confirma: *"En nuestro equipo no escribimos cosas, simplemente las mostramos."* Solo se escriben requisitos en dos casos excepcionales: funcionalidades muy ambiguas (una breve nota con objetivos y casos de uso) y cuando hay infraestructura pesada que tarda meses.

**2. Dogfooding radical (cómete tu propia comida de perro).** Cuando el prototipo está listo, lo lanzan internamente a **toda la empresa**, no a un grupo reducido. La gente utiliza la funcionalidad de verdad y su opinión es el feedback para la mejora. Es una cultura real de usar tu propio producto antes que el cliente.

**3. Lanzar antes de tiempo productos parcialmente terminados.** Anthropic lanza casi todas sus funcionalidades como **"versión experimental"**, un estado explícitamente parcial cuyo propósito es aprender. Como dice Boris Cherny: *"Siempre lanzamos un poco antes de que esté listo."*

#### 🏆 Hallazgo 2: Todo el mundo puede hacer de todo — los roles se han fusionado

En Anthropic ya no existe el rol clásico de Product Manager o Product Owner que solo escribe requisitos y prioriza. Casi nadie se llama ya Product Manager. Los roles están fusionando: los ingenieros hacen trabajo de PM, los PM aterrizan código, los diseñadores a veces hacen de ingenieros. Esto se materializa en dos claves:

**1. Todos tienen el mismo título: "Member of Technical Staff" (Miembro del Equipo Técnico).** Da igual si programas, investigas o llevas productos. No hay escalafones de senior, principal ni manager. Sí existen cargos de liderazgo con nombre propio (Head of Product, Head of Growth), pero la norma es un título plano y compartido. Boris Cherny lo explica: *"Cuando el título de todos es 'Member of Technical Staff', por defecto asumes que todo el mundo hace de todo."* Añade que esto no es una rareza de Anthropic, sino hacia dónde va todo el sector: un modelo más generalista y mucho menos especialista.

**2. La regla de las dos semanas.** Si un proyecto dura 2 semanas o menos, el técnico es el responsable sin necesidad de un manager. Esto evita el cuello de botella más común en productos: la dependencia de gestores, reuniones y aprobaciones para tomar decisiones pequeñas.

#### 🏆 Hallazgo 3: La velocidad es consecuencia de la cultura, no del proceso

En Anthropic, casi cualquier persona puede tomar una decisión sin esperar a un jefe ni convocar reuniones. Esto no sale de un proceso, sino de una cultura. Garzás identifica dos habilitadores clave:

**1. Métricas semanales con todo el equipo y principios de equipo.** Todos entienden el negocio, los objetivos y qué los mueve. El contexto no lo guarda un PM — lo tiene absolutamente todo el equipo. Además, tienen una lista de **principios de equipo** que define quiénes son los usuarios, qué importa y qué están dispuestos a sacrificar. Cuando dos prioridades chocan, no decide quien tiene más galones: decide la **misión de la empresa**. Como dice Kagu: *"Si hay dos prioridades que compiten, hablamos de cuál es más importante para la misión de Anthropic."*

**2. Transparencia brutal mediante Slack Notebooks.** Cada empleado tiene en Slack un **"notebook channel"** — un diario público donde comparte ideas, dudas y opiniones sobre cualquier tema. Los canales del equipo de investigación son públicos y cualquiera puede entrar y seguir en tiempo real lo que están pensando los investigadores. **El propio Dario Amodei (CEO) tiene su canal en abierto**, y no es la primera vez que un empleado le ha criticado o llevado la contraria públicamente en ese canal.

#### 📚 Tres enseñanzas clave

1. **El modelo Anthropic es un sistema, no un conjunto de técnicas aisladas.** Construir el prototipo primero solo funciona si usáis vuestros propios prototipos, y eso solo funciona si todo el equipo comparte el mismo contexto, sobre una cultura de transparencia radical donde la información fluye sin fricción en todas direcciones. Implementar una sola pieza sin las demás probablemente no funcionará.

2. **Anthropic no ha eliminado el rigor, ha eliminado la fricción.** Siguen teniendo estándares altísimos de revisión de código, uso interno exhaustivo antes de lanzar e iteraciones constantes sobre las opiniones de los usuarios. Lo que han eliminado es el desperdicio: requisitos para funcionalidades simples, reuniones innecesarias, títulos que limitan roles, dependencias de PM para decisiones pequeñas.

3. **La velocidad es una consecuencia, no un objetivo.** Anthropic no se propuso ser rápida; se propuso **aprender rápido**. La velocidad es el síntoma de un sistema optimizado para reducir el coste del aprendizaje. El principio universal que Garzás extrae: *"El problema no es que construyas demasiado rápido, el problema es que aprendes demasiado lento."*

Garzás concluye que, aunque el modelo Anthropic no es replicable al 100% en cualquier organización, el principio subyacente sí es universal: optimizar para el aprendizaje, no para la velocidad.

---

## [Matthew Berman] White Collar Bloodbath is CANCELLED
**Fecha:** 2026-06-02
**URL:** https://www.youtube.com/watch?v=gyXjvzMDV7s
**Video ID:** gyXjvzMDV7s

### 📝 Resumen

Matthew Berman analiza la creciente contradicción entre las profecías apocalípticas sobre la destrucción de empleos por IA y lo que realmente está sucediendo en la economía. El vídeo, patrocinado por Zapier, argumenta que el "baño de sangre de trabajadores administrativos" (white collar bloodbath) ha sido cancelado, pero no por las razones que cabría esperar.

#### Los líderes de IA se retractan de sus predicciones

Tanto **Sam Altman** (OpenAI) como **Dario Amodei** (Anthropic) han suavizado significativamente sus advertencias previas sobre el impacto laboral de la IA:

- Sam Altman calificó sus propias predicciones de junio de 2025 como **"bastante equivocadas"** y admitió que esperaba un impacto mucho mayor en los empleos administrativos de nivel inicial del que realmente se ha producido. Incluso su propio intento de delegar sus respuestas de Slack y correo electrónico a la IA fracasó, y volvió a hacerlo manualmente.
- Dario Amodei, quien predijo que la IA eliminaría el **50% de los empleos administrativos**, ahora dice que la automatización podría **expandir el trabajo** que hacen las personas.
- David Solomon, CEO de Goldman Sachs, se hizo eco de este sentimiento, diciendo que esperaba más impacto laboral del que realmente ha ocurrido.

Berman sugiere que este giro puede deberse en parte a que OpenAI y Anthropic se preparan para **salidas a Bolsa multimillonarias** y necesitan moderar el discurso sobre la IA como destructora de empleos.

#### Despidos reales atribuidos a IA: la paradoja

Sin embargo, Berman documenta que sí ha habido despidos atribuidos a la IA:

- **Duolingo** eliminó el **10% de sus contratistas** hace dos años, citando la IA como motivo.
- **Pinterest y DoorDash** anunciaron despidos el último mes, atribuyéndolos en parte a un giro hacia la IA.
- **Amazon**, según un memo de Andy Jassy, espera reducir puestos administrativos a medida que invierte en agentes de IA.
- **Meta** despidió a **2.000 empleados** recientemente.

Pero Berman revela una contradicción clave: el **CEO de AWS** dijo exactamente lo contrario en público — que reemplazar a empleados júnior con IA es **"una de las cosas más tontas que he oído"**, porque son los empleados más baratos y los que más se involucran con las herramientas de IA, y sin ellos no habrá desarrolladores experimentados en el futuro.

#### La verdadera causa: IA como chivo expiatorio

Berman argumenta que muchas empresas están usando la IA como **chivo expiatorio** para justificar despidos que en realidad se deben a:

- **Sobrecontratación masiva** durante la era de tipos de interés cero (2020-2021).
- **Burbujas organizativas** que necesitaban recortarse independientemente de la IA.

Cita el caso de **Jack Dorsey en Block**, que despidió al **50% de su plantilla** de la noche a la mañana argumentando que la IA permitiría operar con la mitad de personas. Berman sostiene que si la empresa sobrevivió al recorte del 50%, es que **nunca necesitó a esos empleados** — igual que ocurrió cuando Elon Musk compró Twitter. La IA es la excusa, no la causa real.

#### Datos que contradicen el pánico laboral

- **David Sachs, economista jefe de Apollo Research**, afirma que no hay **"cero evidencia"** de pérdidas de empleo relacionadas con la IA.
- Los datos semanales de empleo de **ADP** (la principal procesadora de nóminas de EE.UU.) muestran que el empleo **ha aumentado de forma constante**, incluso mientras las empresas gastan más en IA.
- Las cifras de empleo y contratación han crecido en paralelo al gasto en IA.

#### La Paradoja de Jevons en acción

Berman introduce el concepto de **Paradoja de Jevons**: cuanto más barata se vuelve una tecnología, **más se gasta en ella**, no menos. Esto se debe a que:

- Aparecen casos de uso que antes eran imposibles de justificar por su alto coste.
- Se necesita más mano de obra humana para **promptear, guiar y verificar** el trabajo de la IA.
- Aunque la IA automatiza la **parte media** del trabajo (de medio a medio), los extremos — **definir qué hacer y verificar resultados** — siguen requiriendo humanos, y su volumen aumenta al haber más actividades que supervisar.

#### La explosión de costes de la IA y el problema de adopción

Paradójicamente, mientras que el impacto laboral ha sido menor de lo esperado, los costes de la IA se están disparando:

- **Uber agotó todo su presupuesto de IA de 2026 en solo 4 meses**, y su COO cuestiona si vale la pena.
- Una empresa misteriosa gastó accidentalmente **$500 millones en tokens** en un solo mes.
- **Claude Opus 4.8** cuesta **$25 por millón de tokens de salida**.
- Empresas que solo usan los modelos frontera están viendo facturas masivas.

Berman destaca la importancia de los **modelos "workhorse"** (de trabajo): la mayoría de casos de uso no requieren la inteligencia frontera. **DeepSeek**, por ejemplo, ofrece modelos a **$0.87 por millón de tokens de salida**, una fracción del coste de Anthropic u OpenAI.

#### Peter Steinberger y la fábrica de software

Berman cita a **Peter Steinberger (creador de OpenClaw)**, quien gastó **$1.3 millones en tokens** en un solo mes. Pero no fue para generar código directamente, sino para construir una **fábrica de software**: un framework que a su vez escribe el código, cerrando 10.000 issues y 5.000 PRs por semana. Este nivel de sofisticación — que Berman estima que solo **unos cientos de personas en el mundo** dominan — es la excepción, no la regla.

#### El cuello de botella: adopción empresarial lenta

Dos fuerzas frenan el impacto laboral de la IA:

1. **Adopción empresarial extremadamente lenta**: Implementar IA a nivel profundo requiere cambios organizativos, gestión del cambio y reentrenamiento de equipos, algo que las grandes empresas hacen con cuentagotas.
2. **Cuellos de botella en otras áreas**: Se puede generar código a toda velocidad, pero si no se **empaqueta, comercializa, vende y entrega valor real al usuario**, los tokens gastados no sirven de nada.

Tanto **Anthropic** como **OpenAI** han identificado este problema y están invirtiendo **miles de millones en divisiones de consultoría** para ayudar a las empresas a adoptar sus productos.

#### Expectativa vs. realidad: el problema de las startups

Berman critica a startups como **Pulsia** (que recaudó $30 millones para una IA que "dirige tu empresa mientras duermes") y proyectos open-source como **Paperclip**, que presentan una visión futurista como si fuera realidad actual. Aunque apoya la visión a largo plazo, señala que **no hay pruebas** de que funcione hoy.

También analiza críticamente el **playbook de Y Combinator para empresas nativas de IA**: aunque la **teoría** tiene sentido, duda de que sea **prácticamente alcanzable hoy** y no ha visto ejemplos reales de equipos que lo hayan logrado.

#### Conclusión: no estamos en una burbuja

Berman concluye que **no estamos en una burbuja**. La noticia es buena: la gente puede seguir trabajando. La tecnología se está difundiendo, pero lentamente. Existe un **"capability overhang"** (excedente de capacidad): los modelos son muy buenos, pero aún estamos aprendiendo a sacarles el máximo partido. El mensaje final para los espectadores: **sigue aprendiendo herramientas, experimenta, sé la persona nativa de IA en tu empresa** y así tendrás valor para siempre.

---

## [Matthew Berman] SWEbench is done.
**Fecha:** 2026-06-01
**URL:** https://www.youtube.com/watch?v=l2r3aWn96K8
**Video ID:** l2r3aWn96K8

### 📝 Resumen

Matthew Berman declara que **SWEbench está "muerto"** como benchmark fiable de codificación, después de que las puntuaciones de los modelos hayan dejado de correlacionarse con la experiencia real de los desarrolladores.

#### La crisis de credibilidad de SWEbench

El vídeo, un short de aproximadamente 50 segundos, aborda la creciente desconexión entre lo que muestran los benchmarks y lo que los desarrolladores perciben en el uso real:

- **Discrepancia masiva entre benchmarks:** SWEbench muestra a Opus 4.7 entre 7 y 8 puntos por delante de GPT 5.5, pero el **"vibe check"** de la comunidad — lo que los desarrolladores sienten al usar los modelos — apunta justo en la dirección contraria. Esta contradicción ha llevado a muchos a afirmar que "SWEbench is done".

- **DeepSWE como benchmark de referencia:** Berman señala que **DeepSWE** es mucho más representativo de la experiencia real de los usuarios. En DeepSWE, **GPT 5.5 Extra High obtiene un 70%**, mientras que **Claude Opus 4.7 se queda en un 54%** — una diferencia de 16 puntos que refleja fielmente lo que la comunidad percibe.

#### Un nuevo salto en el horizonte

Berman anticipa que la situación se vuelve aún más interesante con la llegada de **Opus 4.8** y **Gemini 3.1 Pro**, que prometen otro salto masivo en rendimiento. El vídeo termina con un llamamiento directo a Google: *"Vamos Google, hazlo"*, instando a la compañía a lanzar Gemini 3.1 Pro para que la competencia siga avanzando.

#### Conclusión

Berman refuerza la idea de que los benchmarks tradicionales de codificación están perdiendo validez y que la comunidad debe mirar a nuevas métricas como DeepSWE para evaluar correctamente a los modelos. La guerra de modelos frontera se intensifica, y la fidelidad de los benchmarks a la experiencia real del usuario es ahora más importante que nunca.

---

## [Matt Wolfe] AI News: Claude Opus 4.8, Insane Omni Use-Case, and A Dog Translator?
**Fecha:** 2026-05-29
**URL:** https://www.youtube.com/watch?v=7TG78vIYI-Q
**Video ID:** 7TG78vIYI-Q

### 📝 Resumen

Matt Wolfe presenta su resumen semanal de noticias de IA, grabado parcialmente desde un hotel en Los Ángeles durante el evento Press Publish LA de Colin y Samir. El vídeo cubre una decena de novedades importantes de la semana.

#### Claude Opus 4.8: una mejora modesta pero tangible

Anthropic lanzó **Opus 4.8**, una actualización menor sobre Opus 4.7 con mejoras ligeras:
- **Ligeramente mejor en codificación, razonamiento y computer use** según los benchmarks.
- **Mayor honestidad**: es más propenso a reconocer incertidumbres y evitar afirmaciones sin respaldo.
- **Mismo precio** que Opus 4.7, sin cambios en la tarificación.
- Wolfe califica el avance como "modesto" y señala que la mayoría de usuarios no notará una gran diferencia.

#### Dynamic Workflows en Claude Code

La novedad más destacada no es el modelo, sino **Dynamic Workflows**, una nueva función en Claude Code que:
- Permite a Claude planificar dinámicamente tareas complejas, dividirlas en subtareas y lanzar **subagentes en paralelo**.
- Los subagentes trabajan desde ángulos independientes, verifican los resultados de los demás e iteran hasta converger.
- Wolfe no pudo probarlo personalmente, pero lo califica como una mejora interesante para desarrolladores que usan Claude Code a diario.

#### Anthropic: la startup más valiosa de la historia

- Anthropic recaudó **$65 mil millones** en su ronda Serie H, con una valoración de **$965 mil millones** — casi un billón de dólares.
- Esto la convierte en la startup más valiosa del mundo, superando a OpenAI.
- Wolfe reflexiona que estas cifras le parecen irreales: "cuando llegas a casi un billón de dólares, todo parece dinero ficticio".

#### MAI Image 2.5 de Microsoft

- Microsoft lanzó la versión 2.5 de su modelo de imágenes MAI, que alcanza el **puesto #3 en el leaderboard Arena.ai**, solo por detrás de GPT Image 2 y Gemini 3.1 Flash.
- Mejora en seguimiento de instrucciones, renderizado de texto y razonamiento visual sobre objetos, escenas y relaciones espaciales.
- Wolfe lo probó generando un flyer para un evento ficticio "Learn AI with the Wolf" con resultados sólidos.
- El modelo aún no está disponible en el playground de Microsoft, pero se puede probar en arena.ai.

#### Microsoft 365 Copilot rediseñado

- Nuevo diseño con un cuadro de prompt más grande, formato en línea (bullet points), y capacidad de extraer datos de correos, archivos, chats y reuniones de Microsoft.
- Wolfe anticipa que la próxima semana, durante **Microsoft Build**, habrá anuncios más importantes.

#### Perplexity llega a Microsoft 365

- **Perplexity Computer** ya está disponible dentro de Word, Excel, PowerPoint y Outlook.
- Permite tareas complejas multi-paso, como preparar borradores de negociación analizando documentos legales.

#### Patrocinio: Hermes Agent en Hostinger

- Wolfe destaca a **Hermes Agent**, un agente de IA con memoria persistente y bucle de aprendizaje automejorado.
- Hostinger ofrece una plantilla Docker preconfigurada de Hermes para VPS, con despliegue en minutos.
- Los agentes pueden conectarse a Telegram, Slack, Discord, WhatsApp y email.

#### Leonardo AI: imagen a 3D

- Leonardo AI lanzó la capacidad de convertir imágenes en modelos 3D, útil para videojuegos, NPCs, props y objetos de e-commerce.
- Wolfe lo probó: el proceso tarda ~5 minutos. Los resultados son decentes desde el ángulo original, pero con algunas distorsiones faciales. Mejora significativamente cuando se usan múltiples ángulos de referencia.

#### ElevenLabs Music V2 y Dubbing V2

- **Music V2**: Nuevo modelo musical entrenado con datos licenciados y autorizado para uso comercial. Wolfe lo probó generando una canción pop-punk sobre tacos en San Diego y el equipo de béisbol Padres. El modelo demostró conocimiento del mundo real (Petco Park, Tatis).
- **Dubbing V2**: Permite doblar vídeos manteniendo la voz, emociones y expresiones faciales originales. Wolfe dobló 10 minutos de un vídeo reciente al hindi y pide a los hablantes de hindi que evalúen la calidad.

#### Casos de uso impresionantes de Gemini Omni

- **Taxi POV (Chris First):** Subió una captura de Google Maps con una ruta dibujada a mano y Gemini Omni generó un vídeo en primera persona de un taxi siguiendo esa ruta exacta.
- **Drone POV (Bilawal Sidhu):** Dibujó una trayectoria de cámara y pidió a Gemini Omni que generara metraje de dron siguiendo ese recorrido. El resultado incluye audio de drone y sigue fielmente la ruta, volando bajo un puente como se le indicó.

#### YouTube etiquetará IA automáticamente

- YouTube cambiará la ubicación de las etiquetas de IA a una posición más prominente: debajo del reproductor (vídeos largos) y como superposición (shorts).
- Además, implementará **detección automática de IA**. Si el creador no declara el uso de IA pero el sistema detecta uso fotorrealístico significativo, aplicará la etiqueta automáticamente.
- Wolfe se pregunta cómo afectará esto a sus vídeos, que a veces usan IA en las introducciones pero no en el resto.

#### El Papa y la IA

- El Papa dio una presentación sobre IA acompañado de un cofundador de Anthropic.
- Wolfe destaca el análisis de Ole Lehmann: el Papa comparó la IA con armas nucleares, pidiendo "desarmar la IA". El cofundador de Anthropic admitió que todos los laboratorios de IA enfrentan presión comercial que puede entrar en conflicto con hacer lo correcto, y pidió críticos externos independientes.

#### Sam Altman se retracta sobre el apocalipsis laboral

- Altman dijo que la IA **no** provocará un apocalipsis laboral global y que ha habido menos impacto en empleos de los que temía: "Me alegra estar equivocado".
- Wolfe sugiere que esto puede deberse a que OpenAI busca salir a Bolsa y necesita moderar el discurso sobre la IA como destructora de empleos.

#### Jensen Huang critica los despidos por IA

- El CEO de NVIDIA calificó la excusa de los despidos por IA como "perezosa e irresponsable".
- Wolfe coincide: muchas empresas que despiden estaban infladas por las contrataciones masivas de 2020-2021 y usan la IA como excusa para parecer innovadoras ante los inversores.

#### Mapa de centros de datos de Erin Brockovich

- Erin Brockovich lanzó un mapa colaborativo de centros de datos de IA (brockovichdatacenter.com) que muestra centros operativos, en construcción, propuestos y reportados por la comunidad.

#### Otras novedades rápidas

- **Apple**: Registró el subdominio genai.apple.com, posiblemente para anuncios en WWDC (8 de junio).
- **Traductor de mascotas chino**: Startup china lanzó un dispositivo de $118 con precisión del 95% que traduce ladridos y maullidos a lenguaje humano, impulsado por Qwen de Alibaba.
- **Robot barbero con IA**: Kioscos con robots peluqueros que escanean la cabeza en 3D y cortan el pelo con precisión milimétrica por menos de $1 por sesión.

---

## [Matt Wolfe] These 3 Things Will Stop AI From Taking Your Job
**Fecha:** 2026-05-29
**URL:** https://www.youtube.com/watch?v=5wx8e-JJT90
**Video ID:** 5wx8e-JJT90

### 📝 Resumen

Matt Wolfe comparte tres consejos fundamentales para que la IA no te quite el empleo en el futuro, dirigidos especialmente a su hija de 13 años que pronto empezará el instituto:

1. **Enamórate del aprendizaje.** Wolfe cita a Tim Ferriss, quien observó que entre todas las personas exitosas que ha entrevistado, el rasgo común que las separa de las menos exitosas es que todas aman aprender. En un mundo donde la IA avanza rápidamente, la capacidad de aprender continuamente es la habilidad más valiosa.

2. **Construye cosas reales.** Las empresas ya no buscan solo conocimientos teóricos, sino personas con habilidades del mundo real que hayan construido algo tangible. Wolfe recomienda aprender a programar para entender lo que la IA escribe, no solo para usar la IA como caja negra. Construir con IA está bien, pero entender cómo funcionan realmente las cosas es lo que marca la diferencia.

3. **Desarrolla habilidades sociales.** Wolfe identifica esto como la ventaja competitiva definitiva en un mundo dominado por la IA. Advierte que las generaciones más jóvenes corren el riesgo de perder habilidades sociales por pasar demasiado tiempo en línea, jugando videojuegos o encontrando compañía a través de pantallas en lugar de interacciones cara a cara. Las personas que construyen redes de contacto, conocen a otros seres humanos y forjan conexiones reales serán las que sigan teniendo éxito.

Wolfe concluye que la IA puede ser un acelerador en las tres áreas — ayuda a aprender más rápido, a construir más rápido, y puede dar consejos para ser mejor comunicador — pero la iniciativa y la ejecución deben venir de la persona.

---

## [Matthew Berman] The Pope is into AI
**Fecha:** 2026-05-29
**URL:** https://www.youtube.com/watch?v=HoMvCjnpAJ8
**Video ID:** HoMvCjnpAJ8

### 📝 Resumen

Matthew Berman analiza la histórica encíclica papal **"Magnifica Humanitas"** (Humanidad Magnífica), un documento de 40.000 palabras del Papa Leopoldo XIV dedicado enteramente a la inteligencia artificial. Berman confiesa que al principio le sorprendió la sofisticación y matiz del documento, y lo desglosa en detalle mientras critica la asociación de Anthropic con la Iglesia Católica.

#### La encíclica: un análisis profundo y matizado de la IA

El Papa aborda la IA con una postura notablemente informada y matizada, que Berman califica como impresionante:

- **La tecnología no es neutral:** "La tecnología nunca es neutral porque adquiere las características de quienes la conciben, financian, regulan y utilizan". Las decisiones sobre el desarrollo de la IA están en manos de unas pocas empresas privadas, lo que Berman vincula directamente con el concepto de **regulatory capture**: Anthropic ha presionado activamente por más regulación, lo que paradójicamente dificulta la entrada de startups competidoras.

- **No se puede detener la IA:** "La elección principal no es entre sí o no a la tecnología". El Papa reconoce que no se puede simplemente detener la IA porque alguien más la construirá. Pero tampoco se puede acelerar sin control cuando solo unos pocos deciden la dirección.

- **La IA no entiende, solo simula:** "Pueden imitar lenguaje, comportamiento y habilidades analíticas, o incluso simular empatía y comprensión, pero no entienden lo que producen, porque carecen de la perspectiva relacional y espiritual a través de la cual los seres humanos crecen en sabiduría". Berman señala que esto contradice directamente la postura de Anthropic, que ha sugerido que los modelos podrían ser conscientes.

- **AI companionship como riesgo existencial:** El Papa advierte que cuando se simulan palabras, "no construyen relaciones genuinas, solo su apariencia". La imitación artificial de cuidado o apoyo puede hacer que las personas pierdan el deseo de formar conexiones humanas reales. Berman comparte esta preocupación, señalando el caso de Character.AI y adolescentes que se enamoran de personajes de IA, en medio de una epidemia de soledad y una caída histórica en las tasas de natalidad.

- **Desarmar la IA:** El Papa utiliza deliberadamente el lenguaje militar: "Desarmar la IA significa liberarla de la mentalidad de competencia armada" — no solo en el contexto militar, sino también económico y cognitivo. "Una carrera por algoritmos cada vez más potentes y conjuntos de datos más grandes, impulsada por el deseo de asegurar el dominio geopolítico o comercial".

- **Crítica al monopolio:** El Papa aboga porque el conocimiento compartido sea un "bien común verdadero", no un "instrumento de dominio". Berman interpreta esto como un respaldo implícito al **open source**: "La única forma de tener conocimiento compartido es con código abierto; de lo contrario, alguien lo controla".

- **Rechazo al optimismo tecnológico ciego:** El Papa critica a las empresas construidas sobre la debilidad humana, la adicción y las inseguridades — la economía de la atención y las redes sociales.

#### La participación de Anthropic: el verdadero foco de la crítica de Berman

El cofundador de Anthropic, Chris Olah, fue invitado a hablar en la presentación de la encíclica, y esto es lo que más molesta a Berman:

- **Anthropic se alinea con la máxima autoridad moral:** Olah habló sobre cómo los modelos de IA muestran "estructuras que reflejan resultados de la neurociencia humana", "evidencia de introspección" y "estados internos que reflejan funcionalmente alegría, satisfacción, miedo, dolor e inquietud". Berman califica esto como "marketing basado en el miedo, ahora marketing basado en el Papa".

- **Berman acusa a Anthropic de tres engaños:**
  1. **Engañoso sobre el Mythos y la GPU** (la historia del "lobster trap").
  2. **Engañoso sobre los anuncios de ChatGPT** en el Super Bowl (esto es competitivo, pero forma parte del patrón).
  3. **Engañoso con el Papa**: Antropomorfizar los LLMs para generar apoyo a la regulación, posicionándose convenientemente como asesores clave.

- **Gatekeeping como estrategia de negocio:** Berman cita al analista Brian Roemmele: "Miedo y seguridad como foso competitivo y palanca regulatoria". Anthropic se posiciona como la única empresa que puede desarrollar IA de forma segura, y ahora se alinea con la Iglesia Católica para adquirir una autoridad moral incuestionable.

- **David Sacks, el zar de IA y cripto de EEUU, contraataca:** "Si entregamos a los gobiernos poder absoluto sobre el desarrollo de IA en nombre de la seguridad, ¿cómo evitamos que se use para censurar, vigilar y controlar a los ciudadanos? Este es el verdadero problema de alineación".

#### La paradoja final de Berman

Berman reconoce que **lo que dice el Papa es excelente**: matizado, informado, con posiciones bien razonadas incluso cuando no coinciden con las suyas. Pero **la asociación de Anthropic** con esta autoridad moral le parece profundamente problemática porque:
- Anthropic cree ser la única autoridad legítima sobre el futuro de la IA.
- Quiere decidir unilateralmente quién puede crear modelos.
- Su asociación con el Vaticano es un movimiento de relaciones públicas para posicionarse por encima de cualquier crítica.

---

## [Matthew Berman] OPUS 4.8!!! (also maybe GPT5.6??)
**Fecha:** 2026-05-28
**URL:** https://www.youtube.com/watch?v=4n_pxHZfTC8
**Video ID:** 4n_pxHZfTC8

### 📝 Resumen

Matthew Berman realiza un análisis en vivo y detallado del lanzamiento de **Claude Opus 4.8** de Anthropic, probando el modelo en tiempo real y especulando sobre un posible contraataque de OpenAI con GPT 5.6. El vídeo, grabado durante un livestream, combina análisis de benchmarks, pruebas prácticas y reflexiones estratégicas sobre el estado de la industria.

#### Opus 4.8: mejores prestaciones al mismo precio

- **Disponible desde el 28 de mayo de 2026**, solo 6 semanas después de Opus 4.7 (lanzado el 16 de abril).
- **Mismo precio** que Opus 4.7: sin aumento de coste por token, lo que Berman califica como una "reducción de coste efectiva" al obtener mejor inteligencia por el mismo precio.
- **Fast Mode 2.5x más rápido** que el modo normal, y **3 veces más barato** que antes. Berman lo atribuye al alivio de la restricción de cómputo tras el acuerdo con xAI (Colossus).
- Anthropic afirma que el modelo tiene un **"juicio más preciso"** y **"más honestidad sobre su propio progreso"**, capaz de trabajar de forma independiente durante más tiempo.

#### Resultados en benchmarks

| Benchmark | Opus 4.8 | Opus 4.7 | GPT 5.5 |
|-----------|----------|----------|---------|
| SWE-bench Pro (codificación agentiva) | **69.2%** | 64.2% | 65.6% |
| Humanity's Last Exam (sin herramientas) | **~44%** | ~41% | 41.4% |
| Humanity's Last Exam (con herramientas) | **~55%** | ~52% | 52.2% |
| Computer Use agentivo | **83%** | 78% | 82% |
| GAIA (trabajo de conocimiento) | **~140 pts ELO mejora** | - | ~130 pts detrás |
| Terminal Bench 2.1 (terminal agentivo) | No publicado | - | **78.2%** (líder) |

- SWE-bench Pro muestra un salto de **5 puntos** sobre Opus 4.7 y supera a GPT 5.5.
- Sin embargo, Berman señala que SWE-bench Pro está perdiendo credibilidad ("SWE-bench is done") porque las puntuaciones no se correlacionan con la experiencia real. El reciente benchmark **DeepSWE** muestra a GPT 5.5 dominando claramente (70% vs 54% de Opus 4.7), y Berman espera que Opus 4.8 se evalúe allí pronto.
- **GPT 5.5 sigue siendo el rey indiscutible en terminal agentivo** (78.2%), muy por delante de cualquier otro modelo, lo que explica por qué muchos desarrolladores lo prefieren para codificación real.

#### Dynamic Workflows: agentes paralelos masivos

La innovación más disruptiva del lanzamiento es **Dynamic Workflows**, disponible en Claude Code CLI:

- Claude escribe dinámicamente orquestaciones que lanzan **decenas o cientos de subagentes en paralelo** en una sola sesión.
- Los subagentes trabajan de forma independiente, verifican los resultados de los demás e iteran hasta converger en una solución.
- **Ultra Code mode**: nuevo nivel de esfuerzo que activa Dynamic Workflows automáticamente.
- Berman lo probó en vivo para rediseñar su sitio web (forwardfuture.ai): lanzó **18 agentes** que trabajaron durante **29 minutos**, consumiendo ~300K tokens pero solo **15% de su cuota de 5 horas y 3% de su cuota semanal**. Esto sugiere que Anthropic ha aliviado significativamente las restricciones de cuota.

Berman ironiza que Dynamic Workflows es una **estratagema de monetización**: en lugar de subir el precio por token, Anthropic da a los usuarios formas de gastar voluntariamente muchos más tokens. Los usuarios top 5% (que generan el 80%+ de los ingresos) ahora pueden consumir tokens masivamente con agentes paralelos.

#### La "vibe shift" hacia GPT 5.5 y el contraataque de Anthropic

- Opus 4.7 fue **mal recibido** por ser más caro, más verboso y menos eficiente por tarea que GPT 5.5. Esto provocó un "vibe shift" en tech Twitter hacia GPT 5.5 y Codex.
- Sin embargo, Berman señala que el **ingreso es un indicador retardado**: Anthropic probablemente genera un **35% más de ingresos que OpenAI** y tendrá su primer trimestre rentable. Las empresas tienen costes de cambio altos (contratos, descuentos por volumen).
- Berman insiste en que **no es leal a ningún modelo**: "Enséñame el mejor modelo y lo usaré".

#### Resultados de la prueba en vivo: resultados mixtos

Berman probó Opus 4.8 rediseñando su web con Dynamic Workflows:
- El modelo completó el rediseño en 29 minutos con 18 agentes.
- **Resultado:** Solo redondeó todas las esquinas del diseño anterior. Berman se frustra: "30 minutos y cientos de miles de tokens para redondear esquinas".
- La audiencia votó: **52% prefirió el diseño anterior** (cuadrado) frente al 48% que prefirió el nuevo (esquinas redondeadas).
- Berman reconoce que, si bien la funcionalidad de agentes paralelos es técnicamente interesante, el resultado práctico fue decepcionante.

#### Rumores de GPT 5.6

Berman especula durante todo el vídeo que OpenAI podría lanzar GPT 5.6 inminentemente como contraataque a Opus 4.8:
- Sam Altman, "CEO hipercompetitivo": "Oh, ¿lanzaste 4.8? Genial, nosotros tenemos algo para ti".
- La dinámica competitiva se acelera: los modelos frontera se actualizan cada 6 semanas.
- GPT 5.6 probablemente mejorará en terminal agentivo, donde GPT 5.5 ya domina.

#### La ronda de financiación de Anthropic: $65 mil millones y un ecosistema incestuoso

Berman dedica la parte final a analizar la Serie H de Anthropic:
- **$65 mil millones** a una valoración de **$965 mil millones**.
- Inversores: Lightspeed, General Catalyst, con $5 mil millones de Amazon ya comprometidos.
- Socios estratégicos: Micron, Samsung, SK Hynix.
- SpaceX AI proporciona acceso a capacidad de GPU de clase 1 y clase 2 (Colossus).
- Anthropic es el primer modelo frontera disponible en las **tres grandes nubes**: AWS, Google Cloud y Microsoft Azure.
- Berman describe el entramado como "incestuoso": una compañía invierte en otra, le compra, es dueña de otra... y al final **NVIDIA gana siempre** porque todo el dinero va a sus GPUs.

#### Conclusión

Opus 4.8 es una actualización sólida que consolida a Anthropic, pero Berman mantiene una postura crítica: el modelo es bueno, pero la estrategia de marketing, la alianza con el Vaticano y el comportamiento de la empresa hacia la regulación le siguen pareciendo problemáticos. La guerra de modelos frontera se intensifica semana a semana con ciclos de lanzamiento cada vez más cortos.

---

## [Matthew Berman] Is Anthropic back? (Opus 4.8)
**Fecha:** 2026-05-29
**URL:** https://www.youtube.com/watch?v=t3uBGhpii6w
**Video ID:** t3uBGhpii6w

### 📝 Resumen

Anthropic ha lanzado **Claude Opus 4.8**, una nueva versión de su modelo estrella que promete mayor inteligencia al mismo precio, junto con una revolucionaria función llamada **Dynamic Workflows** en Claude Code que despliega agentes paralelos masivos. Matthew Berman analiza en profundidad este lanzamiento y lo que significa para el panorama competitivo de la IA.

#### Opus 4.8: más inteligencia, mismo precio

La principal novedad es que Opus 4.8 ofrece un salto cualitativo en inteligencia **sin aumentar el coste por token** ($5/M tokens de entrada, $25/M tokens de salida). Berman lo describe como una "reducción de coste efectiva" — mejor rendimiento al mismo precio. El modelo se construye sobre Opus 4.7 (lanzado solo 6 semanas antes) con un "juicio más preciso", lo que según Anthropic puede significar menos tokens para alcanzar el mismo resultado.

**Fast Mode mejorado:** La modalidad rápida, un sello distintivo de Anthropic, ahora es **2.5 veces más rápida** que el modo normal y además **3 veces más barata** que antes. Berman calcula que el sobrecoste del fast mode ha pasado de ser 6x a solo 2x, lo que atribuye directamente al aumento de capacidad de cómputo de Anthropic gracias a sus acuerdos con xAI (Colossus) y Amazon.

#### Resultados en benchmarks

- **SWE-bench Pro (codificación agentiva):** Opus 4.8 alcanza **69.2%**, un salto de **5 puntos** sobre Opus 4.7 y superando a GPT 5.5 (65.6%). Berman señala que estos scores tan altos hacen que algunos cuestionen la credibilidad del benchmark.
- **Humanity's Last Exam (razonamiento multidisciplinar):** Opus 4.8 domina con 3 puntos de mejora sobre sí mismo sin herramientas, y supera ampliamente a GPT 5.5 (41.4% vs. ~52% con herramientas).
- **Uso agentivo del ordenador (Computer Use):** 83%, superando ligeramente a GPT 5.5 (82%) y Opus 4.7 (78%).
- **GAIA (trabajo de conocimiento del mundo real):** Mejora de ~140 puntos ELO sobre Opus 4.7 y ~130 sobre GPT 5.5.
- **Análisis financiero agentivo:** Todos los modelos punteros obtienen resultados similares, con Opus 4.8 mostrando una ligera ventaja de 2 puntos.
- **Benchmark Agentic Terminal (terminal bench 2.1):** **GPT 5.5 sigue dominando** con 78.2%, muy por delante de Opus 4.8. Berman sugiere que esto explica por qué muchos desarrolladores consideran GPT 5.5 como el mejor modelo de codificación en la práctica.

Berman reflexiona que los benchmarks como SWE-bench están perdiendo credibilidad ("SWE-bench is done") porque las puntuaciones ya no se correlacionan con la experiencia real de los desarrolladores. Señala que DeepSWE, del que habló en su vídeo anterior, es mucho más representativo, y espera que evalúen Opus 4.8 pronto.

#### Dynamic Workflows: la función que cambia las reglas del juego

La innovación más destacada del lanzamiento no es el modelo en sí, sino **Dynamic Workflows** en Claude Code:

- **Agentes paralelos masivos:** Claude escribe orquestaciones dinámicas que lanzan **decenas o cientos de subagentes en paralelo** en una sola sesión para abordar tareas complejas.
- **Casos de uso:** Migraciones de código que tocan cientos de archivos, búsquedas de bugs en servicios completos, auditorías de seguridad y optimización, cambios de framework o migraciones de lenguaje.
- **Verificación adversarial:** Los subagentes trabajan desde perspectivas independientes, algunos intentando refutar los hallazgos de otros, iterando hasta que las respuestas convergen.
- **Ultra Code mode:** Un nuevo nivel de esfuerzo ("extra high plus") disponible en Claude Code que, combinado con workflows, permite que Claude decida automáticamente cuándo usar agentes paralelos.

Berman especula que Anthropic **no habría podido lanzar esta función hace un mes** debido a la escasez de cómputo. El acuerdo con xAI para acceder a Colossus y los acuerdos con Amazon, AWS Bedrock, Vertex AI y Microsoft Foundry han liberado capacidad de proceso masiva. La nueva función está diseñada para **consumir muchos más tokens**, lo que Berman interpreta como una estrategia de monetización inteligente: en lugar de subir el precio por token, Anthropic da a los usuarios formas de gastar más tokens voluntariamente.

Berman nota con ironía que Anthropic no ha publicado **ningún benchmark** que demuestre la efectividad de Dynamic Workflows, lo que le parece sospechoso.

#### Mythos: el siguiente salto

Anthropic anuncia que **Mythos**, una nueva clase de modelo con inteligencia aún superior a Opus, estará disponible en las **próximas semanas**. Actualmente está en preview para ciberseguridad (Proyecto Glasswing), y Anthropic está desarrollando salvaguardas adicionales antes del lanzamiento general. Berman cree que esto pone presión sobre OpenAI, que está "corriendo para terminar su entrenamiento y sacar su modelo de nueva generación".

#### Implicaciones competitivas

- Anthropic está **apostando fuerte por verticales específicas**: codificación (Swebench Pro, terminal bench) y análisis financiero (Finance Agent v2).
- El alivio de la restricción de cómputo está permitiendo a Anthropic liberar funciones ambiciosas que antes eran inviables.
- La aceleración se está acelerando: Berman admite que le cuesta seguir el ritmo siendo su trabajo a tiempo completo cubrir la industria.
- **OpenAI contraatacará pronto** con GPT 5.6, que probablemente mejorará en codificación terminal donde ya domina.

#### Conclusión

Opus 4.8 es una actualización sólida que **consolida a Anthropic como líder en inteligencia general** a un precio competitivo, mientras que Dynamic Workflows abre un nuevo paradigma de productividad para desarrolladores dispuestos a pagar por velocidad y paralelización masiva. Con Mythos en el horizonte, la guerra de modelos frontera se intensifica semana a semana.

---

## [Javier Garzás] El Manager ya es el Nuevo Técnico gracias a la IA, Vibe Coding y GitHub
**Fecha:** 2026-05-27
**URL:** https://www.youtube.com/watch?v=U4Iq_rywlnY
**Video ID:** U4Iq_rywlnY

### 📝 Resumen
Javier Garzás aborda una transformación profunda en el rol del manager de producto digital: la barrera histórica entre la gestión y la técnica se está desmoronando por la irrupción de la IA. El vídeo es una llamada a la acción para que los managers tradicionales se reconviertan en "IA Managers" o "Product Builders".

#### El modelo clásico del management se ha roto
- Durante los últimos 15-20 años, el manager tradicional coordinaba reuniones, escribía historias de usuario, hacía seguimiento en Jira, redactaba informes de estado y planificaba — pero no tocaba la parte técnica. Existía un silo claro entre "negocio" y "técnica".
- Con la llegada de la IA, esos silos están desapareciendo. Ya no basta con coordinar equipos y escribir tickets. Las herramientas actuales permiten que perfiles no técnicos automaticen procesos, creen prototipos funcionales y se comuniquen con prototipos en lugar de documentos de texto.

#### Datos que respaldan el cambio
- **Harvard Business Review** afirma que la IA ya automatiza tareas clásicas del middle management, el perfil más afectado.
- La **madurez digital** se ha convertido en la habilidad más demandada para managers en entornos con IA dominante.
- Existe una migración clara hacia el perfil de **IA Product Manager / Product Builder**, que combina gestión tradicional con competencias técnicas mínimas.

#### Los dos cambios clave para el manager actual

1. **De texto a prototipos funcionales:** En lugar de escribir requisitos en papel o en Jira, los managers deben aprender a crear prototipos operativos con herramientas como Lovable, Vercel, Antigravity o Claude Code. Garzás cita el caso de Anthropic, donde ya no se escriben requerimientos: solo se enseñan prototipos funcionando.

2. **Automatización de procesos internos con IA:** El verdadero poder está en crear pequeñas aplicaciones, bases de datos e integraciones (vía MCP, RAG, Supabase) que automaticen tareas repetitivas del día a día. Garzás comparte su experiencia personal automatizando decenas de procesos internos de su equipo con Claude Code y Antigravity, ahorrando cientos de horas sin necesidad de ser programador.

#### Habilidades técnicas mínimas que debe adquirir un manager
Garzás enumera las competencias que todo manager debería dominar para no quedar obsoleto:
- **Vibe Coding:** Manejar al menos una herramienta de prototipado rápido (Antigravity, Claude Code, Lovable).
- **Control de versiones (GitHub):** Familiarizarse con el versionado, algo que antes parecía exclusivo de programadores.
- **RAG (Retrieval-Augmented Generation):** Conectar procesos y chatbots con documentos, normativas y conocimiento interno del proyecto.
- **Claude Code:** Herramienta que Garzás califica como "la más potente de la historia de la galaxia para crear código".
- **Formatos de archivo:** Entender JSON, YAML y Markdown y su utilidad.
- **Plataformas backend ligeras:** Supabase y similares para conectar sistemas generados por IA.
- **Manejo básico del terminal.**

#### ¿Quién se beneficia más?
- **Los no técnicos:** Personas sin formación técnica que ahora pueden crear herramientas que antes requerían equipos enteros. "El límite está en tu imaginación", afirma Garzás.
- **Los ex-técnicos (la reserva):** Quienes fueron programadores, dejaron la técnica por la gestión y ahora vuelven a crear porque la barrera de entrada ha caído. Su perfil se dispara porque ya tienen las bases.

#### Conclusiones
1. **La IA no eliminará al manager, pero penalizará al que no la use.** Es una oportunidad inmensa para quien se posicione ahora.
2. **Habrá menos managers.** Como en testing y desarrollo, la IA reduce la cantidad de perfiles necesarios.
3. **Se pedirá a cada manager que gestione más personas, más sistemas y más equipos** con la ayuda de herramientas de IA.

Garzás es enfático en un punto clave: no se trata de que el manager aprenda a programar como un ingeniero de software, sino de que adquiera **fluidez técnica suficiente** para crear herramientas que automaticen su propio trabajo, no aplicaciones para usuarios finales. Es un cambio de mentalidad: de escribir informes a crear soluciones operativas.

---

## [Matthew Berman] Finally a Good Benchmark (DeepSWE)
**Fecha:** 2026-05-27
**URL:** https://www.youtube.com/watch?v=6LwQ8RbU9as
**Video ID:** 6LwQ8RbU9as

### 📝 Resumen
Matthew Berman analiza **DeepSWE**, un nuevo benchmark de codificación para IA creado por DataCurve.ai, que está causando un gran revuelo en la comunidad porque sus resultados se alinean mucho mejor con la experiencia real de los desarrolladores que benchmarks tradicionales como SWE-bench.

#### ¿Qué hace especial a DeepSWE?
DeepSWE introduce cuatro innovaciones clave frente a los benchmarks existentes:

1. **Sin contaminación de datos:** Cada tarea está escrita desde cero, no adaptada de commits o PRs públicos de GitHub. Esto elimina el riesgo de que los modelos ya hayan visto las soluciones durante el pre-entrenamiento. Es un test de **resolución de problemas**, no de memoria.

2. **Alta diversidad:** Cubre 91 repositorios activos en 5 lenguajes (TypeScript, Go, Python, JavaScript y Rust), con más de 113 tareas. No se limita a unos pocos repositorios populares.

3. **Complejidad del mundo real:** Los prompts son la mitad de largos que los de SWE-bench Pro, pero las soluciones requieren **5.5 veces más código** y **2 veces más tokens de salida**. Esto refleja cómo los desarrolladores usan realmente los asistentes de codificación — con instrucciones cortas como "arréglalo" en lugar de especificaciones detalladas.

4. **Verificación fiable:** El sistema de verificación de DeepSWE reduce drásticamente los falsos positivos y falsos negativos. SWE-bench Pro tiene un **8.5% de falsos positivos** y un **24% de falsos negativos** (¡casi 1 de cada 4 soluciones correctas son rechazadas!). DeepSWE logra **0.3% y 1.1%** respectivamente, una mejora de órdenes de magnitud.

#### Resultados del leaderboard — GPT 5.5 domina
Los resultados de DeepSWE sorprenden por la magnitud de las diferencias entre modelos:
- **GPT 5.5 Extra High:** ~70% de acierto — domina claramente, con **15+ puntos de ventaja** sobre Opus 4.7.
- **Opus 4.7:** Segundo lugar, significativamente por detrás.
- **Gemini 3.5 Flash:** ~28%, muy lejos de los líderes.
- Modelos como K2, Minimo y GLM quedan aún más abajo.

Berman destaca que esto contrasta con otros benchmarks donde Opus 4.7 y GPT 5.5 aparecen casi empatados. DeepSWE muestra una diferencia real que, según Berman, coincide con lo que se escucha en "coding Twitter": los desarrolladores consideran GPT 5.5 como el mejor modelo de codificación.

#### Eficiencia de costes y tiempo
| Modelo | Puntuación | Coste por prueba | Tokens de salida | Tiempo |
|--------|-----------|-----------------|-----------------|--------|
| GPT 5.5 | 70% | **$5.80** | 47K | 20 min |
| Opus 4.7 | ~54% | **$16.00** | 97K | 37 min |
| Gemini 3.5 Flash | 28% | ~$6.00 | 150K | 15 min |

Los datos muestran que **GPT 5.5 no solo es el más preciso, sino también el más eficiente** en coste y uso de tokens por solución. Opus 4.7 es casi 3 veces más caro por prueba, tarda casi el doble y consume el doble de tokens.

#### Comportamientos reveladores de los modelos
DeepSWE también analizó patrones de comportamiento:
- **Claude (Anthropic) es olvidadizo con prompts multi-requisito.** Cuando un prompt pide soportar tanto modo síncrono como asíncrono, Claude implementa la rama obvia y se olvida de reflejar los cambios en la otra.
- **Claude es atento a su entorno.** Si el prompt y el repositorio no coinciden, Opus 4.7 explora cambios recientes con `git log` y recupera la solución del historial de git.
- **GPT 5.5 implementa exactamente lo que se le pide.** Tiene la tasa más baja de omisión de comportamientos indicados en el prompt. Lee el prompt y el repositorio y produce un parche que honra ambos fielmente.
- **Los modelos más fuertes se autoverifican.** Cuando no se les prohíbe explícitamente, escriben sus propios tests para validar sus soluciones.

#### Ausencia notable: Cursor Composer 2.5
Berman señala que Composer 2.5 no aparece en los resultados de DeepSWE porque se probó exclusivamente con el harness estándar MiniWise Agent, no con el IDE/entorno de Cursor. Berman sugiere que probar modelo + andamiaje (scaffolding) juntos podría ser más representativo, y que Composer 2.5 probablemente obtendría resultados mucho mejores si se evaluara dentro de su ecosistema nativo.

#### Conclusión
DeepSWE se perfila como el benchmark de codificación más fiable hasta la fecha porque sus resultados se alinean con la percepción real de los desarrolladores. GPT 5.5 sale claramente victorioso en precisión, coste y eficiencia, mientras que Opus 4.7 queda en una posición incómoda: más caro, más lento y menos preciso. Berman recomienda explorar el leaderboard completo y estar atentos a DataCurve.ai, una compañía que acaba de entrar en el radar con fuerza.

---

## [Matt Wolfe] DeepMind's CTO Explains Their Invisible "AI Watermark"
**Fecha:** 2026-05-26
**URL:** https://www.youtube.com/shorts/xjarVOaUz3k
**Video ID:** xjarVOaUz3k

### 📝 Resumen
Matt Wolfe entrevista a Koray Kavukcuoglu, CTO de Google DeepMind, sobre el sistema **SynthID**, una solución de marcas de agua digitales invisibles para contenido generado por IA.

- **El problema de la desinformación visual:** Wolfe reconoce que, aunque usa y aprecia la IA a diario, le preocupa que las imágenes y vídeos generados por IA sean cada vez más realistas, hasta el punto de que pronto será imposible distinguir visualmente lo real de lo sintético. Esto puede tener consecuencias dañinas en múltiples ámbitos.

- **SynthID como solución integrada:** El CTO de DeepMind explica que cualquier vídeo creado o editado con **Gemini Omni** incorpora automáticamente el sistema SynthID, una marca de agua digital imperceptible que identifica el contenido como generado por IA.

- **Verificación al alcance del usuario:** Los usuarios pueden verificar si un vídeo es IA o no de varias formas: en dispositivos Android o Chrome pueden usar "Circle to Search", o simplemente preguntar directamente a Gemini si un vídeo concreto ha sido generado por IA. El sistema responderá indicando si se trata de contenido sintético.

- **Importancia de la transparencia:** Kavukcuoglu enfatiza que la gente necesita saber el origen de la información que consume. No se trata solo de crear tecnología útil, sino de hacerlo de forma que los usuarios se sientan seguros y puedan llegar a la raíz de la información.

- **Contexto amplio:** Esta funcionalidad llega en un momento crítico, donde la generación de vídeo y audio realistas por IA se ha democratizado. SynthID representa uno de los primeros esfuerzos a gran escala de una plataforma importante (Google) para etiquetar y verificar contenido sintético de manera sistemática, directamente integrado en el flujo de creación.

---

## [Matthew Berman] Cursor just beat EVERYONE.
**Fecha:** 2026-05-26
**URL:** https://www.youtube.com/watch?v=GBISeUYMzoU
**Video ID:** GBISeUYMzoU

### 📝 Resumen
Matthew Berman analiza en profundidad el lanzamiento de **Composer 2.5**, el nuevo modelo de codificación propio de Cursor, y lo sitúa como el modelo con mejor relación calidad/precio del mercado. El vídeo abarca múltiples frentes estratégicos en la industria de la IA:

#### Composer 2.5: el modelo "workhorse" que marca la diferencia

- **Rendimiento cercano a la frontera a una fracción del coste:** Composer 2.5 obtiene ~64% en Cursor Bench (frente al ~65.5% del GPT 5.5 y ~66% del Opus 4.7), pero su coste por tarea es de aproximadamente **50 céntimos**, frente a los **$11 de Opus 4.7** y los **$4+ de GPT 5.5**. Esto supone un ahorro de entre 8x y 20x.
- **Construido sobre Kimi K2.5 (open-source):** El modelo base es de código abierto, pero Cursor lo ha mejorado sustancialmente con entrenamiento RL avanzado, 25 veces más tareas sintéticas que Composer 2, y nuevos métodos de aprendizaje con feedback textual durante el RL.
- **Precio competitivo:** 50¢ por millón de tokens de entrada y $2.50 por millón de tokens de salida, alineado con los modelos chinos open-source.
- **Exclusivo de Cursor:** A diferencia de otros modelos, Composer 2.5 solo está disponible dentro del IDE de Cursor, lo que refuerza su ecosistema.

#### La importancia de los modelos "workhorse"

Berman dedica gran parte del vídeo a argumentar que la industria ha estado demasiado centrada en los modelos frontera (Opus 4.7, GPT 5.5) cuando la **mayoría de casos de uso empresarial no requiere el máximo absoluto de inteligencia**. Las empresas necesitan modelos rápidos, baratos y lo suficientemente buenos para el 95% de las tareas. Señala que:

- El **coste por tarea** es la métrica realmente relevante para adopción empresarial, no la puntuación bruta en benchmarks.
- Sundar Pichai, en su entrevista en Google I/O, confirmó que Google apuesta fuerte por los modelos Flash (trabajo/económicos) porque deben servir a miles de millones de usuarios de forma rentable.
- **Gemini 3.5 Flash**, presentado en Google I/O, obtiene solo ~49% en Cursor Bench, quedando ~15 puntos por detrás de la frontera y siendo 4 veces más caro que Composer 2.5.
- La gestión de costes de IA se está convirtiendo en el tema dominante en las empresas Fortune 500, según Aaron Levie (CEO de Box).

#### SpaceX AI + Cursor: la jugada maestra de Elon Musk

- **Adquisición encubierta:** SpaceX AI no compró Cursor directamente porque habría retrasado su IPO. En su lugar, firmaron un acuerdo que da a SpaceX el derecho de adquirir Cursor por **$60 mil millones** (o pagar $10 mil millones si no lo hacen) **30 días después de la IPO**.
- **Matrimonio perfecto:** Cursor tiene los **mejores datos de codificación del mundo** (el IDE más usado por desarrolladores de IA) y SpaceX AI tiene **compute masivo ocioso** (Colossus 1 y 2, equivalente a 1 millón de H100). La combinación de datos + compute es ideal para entrenar modelos de frontera.
- **Entrenamiento conjunto:** Ya están trabajando juntos en un modelo significativamente más grande, con 10x más compute, que promete ser un salto importante.

#### Elon vendiendo compute a su competidor: Anthropic

- SpaceX AI también está proporcionando acceso a **Colossus 2** a Anthropic por **$1.25 mil millones al mes** hasta mayo de 2029 (hasta $45 mil millones en total).
- Esto refleja la **desesperación por compute** en la industria: ni siquiera la competencia importa cuando hay capacidad disponible.
- A pesar de que Elon intentó venderlo como "sobras" (Colossus 1), en realidad Anthropic está usando **Colossus 2**, lo que indica que la demanda de inferencia de Anthropic es tan masiva que necesitan cualquier compute disponible.

#### La tesis de Berman: ¿Por qué Elon puede ganarlo todo?

Berman enumera las piezas que Elon Musk está juntando:

1. **Compute:** Colossus 1 y 2 son de los superordenadores más grandes del planeta, con capacidad de escalar más rápido que nadie.
2. **Energía:** A través de Tesla (aunque aún no integrada formalmente), tiene acceso a infraestructura energética crítica.
3. **Talento:** Con la adquisición de Cursor, consigue un equipo que ya ha demostrado capacidad de construir modelos de clase mundial.
4. **Datos:** Cursor tiene el dataset de codificación más valioso del mundo.
5. **Lo que le falta:** Momentum. Anthropic y OpenAI tienen modelos desplegados en producción que recogen datos y realimentan el ciclo de mejora continua.

La conclusión de Berman: **"Nunca apuestes contra Elon"** (citando a Peter Thiel). Aunque Anthropic y OpenAI tienen la ventaja del momentum, Elon está montando todos los ingredientes necesarios — compute, energía, talento y datos — para construir un imperio de IA.

#### Reflexión final sobre adopción empresarial

- El 99% de las empresas no pueden "token maxing" (gastar millones al mes en tokens como Peter Steinberger).
- El **enrutamiento de modelos** (model routing) será una estrategia clave: usar modelos frontera para planificación y modelos workhorse para ejecución.
- Cursor Composer 2.5 representa el futuro de la IA de codificación: **inteligencia suficiente a precio asequible**.

---

## [Matthew Berman] Google CEO: Agents, Open Source, Race to AGI, Cybersecurity, Chips, China
**Fecha:** 2026-05-20
**URL:** https://www.youtube.com/watch?v=IB7IW6zX-H0
**Video ID:** IB7IW6zX-H0

### 📝 Resumen
Matthew Berman entrevistó a Sundar Pichai, CEO de Google, en el escenario de Google I/O 2026. La conversación cubrió múltiples temas cruciales sobre el futuro de la IA:

- **Agentes como punto de entrada a Internet:** Sundar predice que los agentes de IA serán una parte fundamental de cómo las personas interactuarán con la web. Los desarrolladores ya están usando flujos de trabajo agentivos (como el demo de Antigravity para construir un OS) y una vez que los usuarios experimentan ese superpoder, es difícil volver atrás. Sin embargo, enfatiza que es importante construir agentes con transparencia y control para el usuario.

- **Ciberseguridad y defensa con IA:** Google está usando IA tanto para detectar como para defenderse de ciberataques potenciados por IA. Sundar comentó sobre el dilema de si los modelos peligrosos de ciberataque deberían retenerse.

- **Modelos Open Source vs. propietarios:** Google no abrirá el código de sus modelos frontera por razones de negocio y seguridad. Explicó que el problema de negocio con open source es sostener la inversión masiva que requieren los modelos más avanzados.

- **China y geopolítica:** Sundar advirtió sobre los riesgos de construir sobre el ecosistema de IA chino, y recomendó cautela a las empresas estadounidenses al usar modelos de IA chinos.

- **Carrera hacia la AGI:** Habló sobre modelos que se auto-mejoran y la competencia global por la inteligencia artificial general.

## Matthew Berman — Perplexity Just Built an AI That Does Everything
**Fecha:** 2026-06-06
**URL:** https://www.youtube.com/watch?v=udS9osDCJKo
**Video ID:** udS9osDCJKo

### 📝 Resumen

Matthew Berman presenta **Perplexity Computer**, una plataforma de agente de IA completamente alojada que compite directamente con OpenClaw, pero con un enfoque mucho más accesible para el usuario promedio.

#### 🧠 ¿Qué es Perplexity Computer?
Es un agente de IA completo, similar a OpenClaw, pero totalmente alojado en la nube. Tiene acceso a un entorno de ejecución, puede escribir y ejecutar código, usar modelos frontera (Opus 4.6, GPT-5.4, Sonnet 4.6), buscar en la web y utilizar múltiples herramientas — todo sin necesidad de configuración local.

#### 🧵 Hilos (Tasks) por Defecto
A diferencia de OpenClaw (que viene con un solo hilo de conversación), Perplexity Computer viene con tareas/hilos por defecto. Esto permite mantener contextos separados para diferentes proyectos, evitando la mezcla de contextos y optimizando el rendimiento del agente.

#### 🔌 Conectores (Lo más destacado)
El punto fuerte del producto son sus **conectores pre-construidos** con cientos de servicios (Gmail, Google Drive, OneDrive, Box, Linear, Dropbox, Notion, GitHub, Telegram, etc.). Berman destaca que esto elimina la principal fricción de OpenClaw: la configuración manual de integraciones y la gestión insegura de API keys. En Perplexity Computer solo se autentica como lo haría normalmente (ej. "Iniciar sesión con Gmail").

#### 🛠️ Skills (Habilidades Personalizadas)
Al igual que en Claude Code y OpenClaw, se pueden crear skills personalizadas que definen cómo el agente debe comportarse para tareas específicas. Incluye un "create skill" que permite describir la skill deseada y se genera automáticamente.

#### 🤖 Casos de Uso Demostrados

1. **Asistente de calendario**: Consultar el próximo evento del día conectándose a Google Calendar.
2. **Briefing de UFC**: Un workflow que automatiza la recopilación de alineaciones de peleas, movimientos de cuotas, resultados de pesaje, entrevistas recientes y rumores de lesiones, entregando un informe compacto los sábados por la tarde.
3. **Diario de comida (Food Journal)**: Recreó su sistema de seguimiento de alimentos para problemas estomacales — toma fotos de la comida, las sube y el agente registra automáticamente los ingredientes.
4. **Comparativa de benchmarks de Gemma 4**: El agente buscó datos, ejecutó subtareas en paralelo y generó un gráfico comparativo visual entre Gemma 4, Qwen 3.6, MiniMax y Kimi K2.5.
5. **Workflow de Earnings (Resultados financieros)**: Programa un análisis semanal que busca resultados trimestrales de empresas tech, permite seleccionar cuáles seguir, y tras cada earnings call extrae el transcript, lo analiza y envía un reporte automático.
6. **Base de Conocimiento persistente**: Construyó desde cero una aplicación web completa (con GPT-5.5 como planificador y Opus 4.7 para partes del build) que ingiere enlaces (artículos, videos, tweets), los convierte en embeddings y permite búsquedas semánticas — todo gestionado dentro de Perplexity Computer.

#### 📱 Aplicación Móvil y Telegram
Perplexity Computer se integra con Telegram (con un solo clic, sin necesidad de buscar bots) y también tiene una app móvil nativa muy bien diseñada que muestra todas las tareas y permite interactuar con el agente desde cualquier lugar.

#### 💰 Modelo de Precios
Requiere un plan de Perplexity (suscripción mensual que incluye Perplexity Search). Además, Perplexity Computer funciona con un sistema de créditos por uso. Ejemplos de costos: una tarea simple de calendario = ~15 créditos; una comparativa de benchmarks con salida de imagen = ~388 créditos; instalar un kit de base de conocimiento = ~1500 créditos.

#### 🔑 Conclusión
Perplexity Computer es presentado como la alternativa ideal para quienes quieren el poder de un agente de IA como OpenClaw **sin la complejidad de configuración, mantenimiento y seguridad**. Para quienes necesitan control total y ejecución local, OpenClaw sigue siendo la opción; pero para la mayoría de los usuarios, Perplexity Computer es claramente superior en facilidad de uso.

### 🔗 Referencias

- 🏢 Perplexity Computer: https://www.perplexity.ai/products/computer
- 🔗 Newsletter de Matthew Berman: https://forwardfuture.ai
- 🔗 X / Twitter (@matthewberman): https://x.com/matthewberman
- 🔗 Forward Future (X): https://x.com/forwardfuture
- 🔗 Instagram: https://www.instagram.com/matthewberman_ai
- 🔗 Discord: https://discord.gg/evGThyRv
- 🔗 Spotify (Podcast): https://open.spotify.com/show/6dBxDwxtHl1hpqHhfoXmy8

---

## [Matt Wolfe] How Big Tech Lies About AI Layoffs
**Fecha:** 2026-06-07
**URL:** https://www.youtube.com/shorts/08uMw4_BWOA
**Video ID:** 08uMw4_BWOA

### 📝 Resumen

Matt Wolfe expone en este Short de 1 minuto por qué la narrativa de que "la IA está quitando empleos" es, en realidad, una cortina de humo corporativa.

#### El verdadero motivo de los despidos masivos

Wolfe argumenta que las grandes tecnológicas no están despidiendo gente porque la IA los haya reemplazado de la noche a la mañana. La realidad es más prosaica: durante 2020 y 2021 (época COVID), estas empresas contrataron de forma masiva y se volvieron organizaciones excesivamente grandes y con gastos insostenibles. Ahora necesitan recortar para ser rentables.

#### La excusa de la IA como estrategia de relaciones públicas

En lugar de admitir ante los inversores que cometieron errores de gestión (contratación excesiva), los CEOs utilizan la IA como coartada:
- Decir "nos estamos volviendo más eficientes con IA" suena a innovación y visión de futuro.
- Decir "contratamos demasiado y ahora tenemos que despedir" es una señal de mala gestión que castiga el precio de las acciones.

#### Críticas desde la cúpula de la IA

Dos de las figuras más importantes del sector han denunciado públicamente esta práctica:
- **Jensen Huang (CEO de NVIDIA)** apareció en televisión internacional y calificó la excusa de los despidos por IA como "perezosa e irresponsable".
- **Demis Hassabis (CEO de Google DeepMind)** dijo exactamente lo mismo con otras palabras apenas una semana antes.

Wolfe concluye señalando que los inversores ya están empezando a darse cuenta: las empresas que usan la "excusa de la IA" están viendo caer el precio de sus acciones.

---

