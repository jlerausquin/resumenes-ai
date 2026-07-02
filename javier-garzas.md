# 📹 Resúmenes — Javier Garzás

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

