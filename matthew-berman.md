# 📹 Resúmenes — Matthew Berman

---


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

