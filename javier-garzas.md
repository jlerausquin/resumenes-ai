# 📹 Resúmenes — Javier Garzás

## [Javier Garzás] Mientras gestionas con Jira o Notion, otros ya tienen un IA segundo cerebro con Claude Cowork

**Fecha:** 2026-05-20
**URL:** https://www.youtube.com/watch?v=yoHbh9eg6Ew
**Video ID:** yoHbh9eg6Ew

### 📝 Resumen

Javier Garzás plantea el problema de gestionar el conocimiento de un proyecto con herramientas que no están pensadas para la IA y propone un sistema de tres piezas que él y su equipo usan a diario y que ha compartido con los más de 500 profesionales de su comunidad. El sistema combina ficheros Markdown como memoria persistente, IA generativa instalada en local que los gestiona y Obsidian como capa de lectura, y su objetivo es que las conversaciones dejen de empezar de cero y que la IA recuerde el contexto del proyecto.

#### El límite de Word, Google Docs y los copilotos integrados

La forma tradicional de escribir un informe —abrir Word o Google Docs y ponerse a escribir— es hoy lenta e impensable. Los copilotos integrados, como Copilot en Word o Gemini en Google Docs, ayudan a redactar, pero el autor les atribuye dos limitaciones claras: son lentos al tocar los ficheros y son muy limitados para leer datos externos. Si se quiere usar un MCP que lea de una fuente externa, o aprovechar skills, la capacidad de los procesadores de texto tradicionales se queda corta; complementar el procesador de texto con una IA integrada, por tanto, no resuelve el problema de fondo.

#### Cuándo el chatbot se queda corto

Parece lógico entonces irse directamente a un chatbot potente —ChatGPT, Claude o Gemini— y construir el documento conversando: pedir secciones, buscar información, leer datos vía MCP. Eso funciona hasta que el documento es grande, del orden de 50 a 70 páginas. En ese punto aparecen dos problemas: la IA pierde contexto y empieza a olvidar el principio de la conversación, repitiendo cosas que se le pidió expresamente que no hiciera; y llega el momento de sacar una versión en papel o en un .docx, que no tiene una salida sencilla.

#### El copy-paste como trampa: dos repositorios y la versión buena perdida

La salida más obvia, copiar y pegar el resultado en un Word o un Google Doc, genera dos repositorios: la conversación del chatbot con sus MCP y skills, y la versión pegada en el fichero. Cada cambio obliga a volver al chatbot y repetir el copy-paste en ambos sentidos, un flujo muy tedioso. Además, por el no determinismo de la IA, al pedir una nueva versión puede devolver algo muy distinto a lo ya cerrado en el documento, y se pierde el control de dónde está la versión buena. La conversación sirve para generar, no para mantener.

#### La fuente de verdad: ficheros Markdown

La solución pasa por una fuente de verdad persistente y ligera, y el formato que encaja es Markdown, los ficheros .md, con una antigüedad que el autor sitúa en 2004. Destaca cuatro propiedades poco evidentes: son ficheros y por tanto memoria persistente fuera de la ventana de contexto; ocupan muy poco, son texto plano y se modifican en segundos; conservan el formato (negritas, cursivas, tachado, títulos H1 y H2) de forma que un Google Doc sabe interpretarlo al importarlos; y las IA los entienden y manipulan de manera muy eficiente, al no ser un HTML complejo, un PDF o un .docx. El inconveniente es que gestionarlos a mano —versionarlos, unirlos, separarlos— resulta tedioso para cualquier persona.

#### Las IA que trabajan en local: Claude Cowork y OpenClaw

Ese inconveniente lo resuelven las IA que trabajan directamente con los ficheros del ordenador, como Claude Cowork u OpenClaw, que crean, modifican, unen y separan los Markdown en local sin exigir conocimientos técnicos. Eso permite que el chatbot potente se use para generar y no para mantener: se aprovecha su potencia conectada a MCP de CRM, Gmail o Calendar, pero el resultado se vuelca a ficheros ligeros en lugar de a un repositorio pesado tipo .docx, lo que reduce el miedo a la pérdida de contexto.

#### Obsidian: el visualizador que cierra el triángulo

Para la IA un .md es oro puro, pero para una persona es un formato feo y tedioso de leer. Ese hueco lo cubre Obsidian, herramienta gratuita que ya existía antes de la aparición de ChatGPT (el autor la sitúa hacia 2020) y que visualiza de forma amigable y muy visual los ficheros Markdown guardados en las carpetas del ordenador, con una experiencia cercana a un editor de texto enriquecido. El sistema queda así como un triángulo: Markdown como fuente de verdad, IA generativa instalada en local que lo gestiona y Obsidian como visor que conecta lo que la IA necesita con lo que el humano necesita ver.

#### El origen del método: de Zettelkasten al flujo Karpathy

El autor sitúa el origen de este flujo de trabajo en Andréj Karpathy, uno de los fundadores de OpenAI, que contó cómo trabajaba y de ahí el nombre de «flujo Karpathy». La raíz es mucho más antigua: el Zettelkasten, el método de fichas del sociólogo alemán Niklas Luhmann, que escribió más de 70 libros con él. Garzás cuenta que ya lo utilizó en la elaboración de su tesis doctoral, mucho antes de la era de la IA, y que llevarlo al trabajo con inteligencia artificial sigue siendo la base profunda de la que derivan las familias de métodos que hoy se observan.

### 🔗 Referencias

| Recurso | Enlace |
| --- | --- |
| Grupo gratuito de WhatsApp de la comunidad «los rebeldes y ágiles» | — |
| Obsidian | — |
| Claude Cowork (Anthropic) | — |
| OpenClaw | — |
| Jira | — |
| Notion | — |
| Zettelkasten (método de Niklas Luhmann) | — |
| Andréj Karpathy | — |

---
## [Javier Garzás] El PM que aún Escribe Requisitos está Antiguo gracias a IAs como Claude Design

**Fecha:** 2026-05-10
**URL:** https://www.youtube.com/watch?v=yfp9e8SvhGE
**Video ID:** yfp9e8SvhGE

### 📝 Resumen

El vídeo parte de una idea central de Javier Garzás: escribir requisitos es ya una práctica del pasado para una parte creciente del sector, y lo que de verdad importa no es la herramienta de moda, sino hacia dónde se está desplazando el ciclo de vida del producto. Su tesis es que Claude Design, más allá de si es más o menos potente que Figma, es la señal de un movimiento estratégico que probablemente copiarán el resto de grandes actores de la IA.

#### Las dos maneras clásicas de especificar requisitos

Las dos formas «viejunas» son la herencia de un mundo con poco cambio. La primera es la cascada: entregas en ciclos de meses, producto que acababa en un medio físico como una cinta o un CD y se distribuía desde el CPD, con cambios posteriores carísimos. Las especificaciones en papel se convertían a menudo en contratos inamovibles, bajo la lógica del «proyecto llave en mano», y el objetivo último era reducir la interacción humana durante la creación. La segunda son las historias de usuario, que llegan con la corriente ágil y con la cultura de la colaboración por encima de la negociación: textos mínimos, definidas como «promesas de conversación», pensadas para la interacción entre humanos. Garzás aclara que ese primer mundo sigue existiendo, pero con un hueco pequeño.

#### La nube cambia el ritmo y aparece la incertidumbre

Cuando el software pasa a la nube y se accede por navegador o aplicación móvil, los cambios se vuelven fáciles y el negocio deja de entender que se tarde mucho en corregir un bug o en añadir una funcionalidad. Al mismo tiempo se agota la etapa de automatizar procedimientos manuales bien definidos y entra una época de mucha más incertidumbre, en la que predecir lo que quiere el usuario es más difícil. De ahí la receta: prototipar muy rápido y escribir muy poco requisito para liberar antes y captar necesidades directamente del negocio. En este punto menciona variantes y formatos posteriores, como Gherkin para describir con pruebas de aceptación.

#### La tercera vía: especificaciones en Markdown

Con la IA generativa capaz de crear algoritmos y prototipos a una velocidad impensable, aparecen las especificaciones (specs) en texto plano, típicamente en ficheros Markdown, un formato que recuerda que data de 2004 o 2006. Su función es acotar al máximo lo que debe hacer la máquina y disponer de una única fuente de la verdad, porque la IA es no determinista y, ante la misma especificación, puede dar resultados distintos; también ayuda a manejar la pérdida de contexto. Garzás lo considera un tema polémico: si se acota en exceso se vuelve al lado oscuro de la cascada, de modo que la disciplina consiste en hacer specs lo más pequeñas posible aunque sean detalladas.

#### La cuarta vía: prototipos funcionales creados desde negocio

La IA permitió crear prototipos operativos sin saber programar, con la advertencia habitual del autor: prototipos, no grandes aplicaciones en producción con millones de usuarios, que siempre exigen un bucle humano-IA. Con esto, el responsable de negocio o product manager ya no enseña textos ni imágenes muertas de un Figma, sino algo que funciona con sus botones, desplegables y campos, y puede validarlo con usuarios beta del círculo «friends and family» sin pasar por ciclos, perfiles y reuniones largas. Herramientas como Lovable elevaron el nivel y son uno de los exponentes de esta vía, que difumina las fronteras profesionales y hace equipos más pequeños, sin que ello signifique prescindir del UX cuando el producto lo requiere.

#### Claude Design: la noticia y la caída del 7% de Figma

Claude Design aparece en abril de 2026 y, según la noticia que origina el vídeo, las acciones de Figma —su competidor histórico más fuerte y la herramienta hiperpopular de diseñadores y UX— caen un 7%. La herramienta ha sido muy criticada por simple y alejada de Figma, y la primera impresión al probarla es la de un «Canva con superpoderes», con una función de exportación directa a Canva; Garzás la usó, por ejemplo, para diseñar la convocatoria de un encuentro presencial de su comunidad para ver el estreno de Mandalorian. Su insistencia es que quedarse en la comparación de potencia y en el FOMO de herramientas impide ver el trasfondo.

#### El botón clave: la integración con Claude Code

El detalle que pasa desapercibido es un pequeño botón de integración con Claude Code, en opinión del autor la herramienta más potente de creación y programación hasta la fecha. Lo que propone Anthropic es que, una vez validado el prototipo, este pase de forma integrada y sin fisuras mediante un handoff a Claude Code, que lo implementa, quedando muy cerca de una release si lo permiten los requisitos funcionales, de negocio y de seguridad. Eso va más allá de Lovable y competidores, que se quedaban en prototipos más o menos muertos: aquí hay control total sobre infraestructura y arquitectura, con validación por perfiles humanos acompañada de agentes que validan resultados.

#### Un ciclo de vida completo en manos de la IA

El ciclo que dibuja el vídeo es: la persona de negocio diseña en Claude Design, se valida el prototipo y se entrega a Claude Code, que implementa; las especificaciones en texto quedan en un segundo plano, sin desaparecer. El resultado es más velocidad y menos separación entre negocio, diseño y técnico. Garzás señala las consecuencias: para aplicaciones con gran exigencia de diseño harán falta perfiles muy senior, lo que deja a los junior en una posición delicada; pero también subraya que muchas de las cosas que se hacen son automatizaciones menores o de uso interno, antes impensables por presupuesto, perfiles y tiempos, que ahora asume directamente un perfil de negocio.

### 🔗 Referencias

| Recurso | Enlace |
| --- | --- |
| Grupo gratuito de WhatsApp de la comunidad «los rebeldes y ágiles» | — |
| Claude Design (Anthropic) | — |
| Claude Code (Anthropic) | — |
| Lovable | — |
| Figma | — |
| Canva | — |
| Gherkin (formato de pruebas de aceptación) | — |

---
## [Javier Garzás] He creado un agente de IA que hace de mi Product Owner: esto es lo que aprendí

**Fecha:** 2026-05-03
**URL:** https://www.youtube.com/watch?v=9yERjr1P6X8
**Video ID:** 9yERjr1P6X8

### 📝 Resumen

Garzás ha entregado su backlog a un agente de IA propio al que ha bautizado como C233PO, que lleva semanas trabajando para él como coproduct owner y le ha enseñado tanto la parte brillante como la parte oscura de delegar la gestión rutinaria en una IA. El vídeo cuenta cómo funciona por dentro, qué ha cambiado en su equipo y qué riesgos conviene gestionar antes de replicarlo.

#### C233PO: un agente, no un chatbot

La distinción es el eje del experimento: no es un LLM, ni un prompt, ni un chatbot, ni una skill, sino un agente autónomo que está operativo 7x24 en un entorno propio, lee el backlog en Notion y escribe por Telegram al teléfono de Javier. Por la mañana le llegan mensajes como que llevan tres días sin tocar tareas marcadas con F (las de futuro, separadas de lo urgente y lo importante), avisos de que solo se está centrando en el día a día mientras lo que aporta valor no entra en el backlog, o listas de los cinco items que debería revisar hoy con el aviso de que alguno no aporta valor y debería eliminarse. En su equipo hay además otro agente llamado Leia.

#### Qué hace cada noche y qué cambia en el equipo

C233PO mantiene el backlog, lo reordena, lo prioriza y lo limpia, y por la noche, con una tarea planificada a las 3 de la mañana aprovechando que hay menos demanda de tokens, prepara el daily y avisa de los cambios por Telegram. Antes, la rutina consistía en abrir el backlog en el proyector media hora antes del daily para ordenar, quitar y añadir items, algo que muchas veces no se hacía por falta de tiempo y que dejaba backlogs caóticos. La mayor sorpresa ha sido que el agente empezó a recordar por iniciativa propia buenas prácticas que él mismo le había inculcado, y que mantiene la disciplina sin cansarse ni ceder a la presión del día a día.

#### Una arquitectura de tres capas

El agente no se construye solo con un prompt. La primera capa es el alma: los ficheros Soul.md e Identity.md, en texto plano y lenguaje natural, donde están los criterios de trabajo, la obsesión por el valor, la guerra contra el desperdicio como enemigo del valor y la brújula interna para decidir qué importa más. Sin ella, sería un ejecutor sin juicio. La segunda capa es la memoria: Memory.md y User.md describen el negocio, la ética, los principios y cómo trabaja la organización, y es lo que le permite saber en qué punto se quedó ayer y diferenciarse de un chatbot que empieza de cero. La tercera capa es la acción: Agents.md y Tools.md definen cómo actúa, qué puede tocar, cómo lee el calendario y a qué herramientas accede.

#### Open Clow sobre un VPS como plataforma

La base es Open Clow, que define como un repositorio o workspace de agentes de IA de código abierto, no un LLM ni un chatbot, que él ejecuta en un VPS por tener menos riesgos que en local. La plataforma permite hablar con el agente desde herramientas conocidas como Telegram o WhatsApp, conectarlo a Google Calendar y a Notion, y programar tareas planificadas. Sobre esa base, el agente hereda buenas prácticas acumuladas en más de 20 años de trabajo y en la asesoría a más de 800 equipos: tareas F de futuro, items pequeños, backlogs reducidos, técnicas de priorización, clasificación por valor y revisiones periódicas de elementos olvidados. El matiz de nomenclatura es importante: es un coproduct owner, se queda con lo rutinario y mecánico, y no alcanza lo que hace un product manager de verdad, que es discovery, visión de futuro y decisión sobre qué problemas resolver.

#### La parte oscura: tres riesgos a gestionar

El primero es que la IA siempre dice que sí; y en un equipo humano, que todo el mundo asienta es mala señal, porque las mejores ideas surgen de la diversidad y de discusiones sanas. El segundo es el acceso a los datos: para funcionar necesita calendar, correo, backlog en Notion y la capacidad de escribir por Telegram a él y a su equipo, así que recomienda conceder solo lo imprescindible y separar tajantemente lo confidencial. El tercero es el tiempo: cuidado con que las automatizaciones se conviertan en aficiones. Su regla es eliminar antes los procesos que no deberían existir, comprobar si el proceso se puede agilizar, valorar si aporta valor, si se repite, si consume mucho tiempo y si el mantenimiento será caro, e ir siempre a MVPs de automatización.

#### El humano no desaparece

La parte mecánica, viejuna y tediosa probablemente acabará en manos de la IA, pero lo diferenciador es lo mental, humano y emocional: el olfato, el pensar, el decidir, ver qué problemas hay fuera y el alma de la organización, algo que la IA no tiene y que el agente le devuelve en forma de tiempo. C233PO no ocupa su puesto, ocupa su agenda. Su consejo para quien esté en estas disciplinas es que aprenda a montar este tipo de agentes, porque la barrera no es técnica sino de paciencia y de olfato para decidir dónde merece la pena invertir tiempo, y quien lo haga ahora tendrá ventaja mientras otros siguen discutiendo sobre el Scrum de los años ochenta. Cierra con una pregunta al público: cuántas horas semanales dedica cada uno a tareas que un agente bien configurado podría hacer a las 3 de la mañana mientras duerme.

### 🔗 Referencias

| Recurso | Enlace |
| --- | --- |
| Grupo gratuito de WhatsApp del canal | — |
| Open Clow (workspace de agentes de IA de código abierto) | — |
| Notion (backlog del equipo) | — |
| Google Calendar | — |
| Telegram | — |
| VPS (servidor virtual donde corre el agente) | — |
| Vídeos del canal sobre prompts, skills y agentes | — |

---
## [Javier Garzás] Los creadores de Agile lo admiten: la IA ha cambiado tu profesión para siempre

**Fecha:** 2026-04-26
**URL:** https://www.youtube.com/watch?v=9QHrMeIGL7U
**Video ID:** 9QHrMeIGL7U

### 📝 Resumen

El vídeo parte de un hecho reciente: los firmantes del manifiesto ágil y una cuarentena larga de profesionales volvieron a Utah, en febrero, 25 años después de la firma, para constatar que la IA ha cambiado la profesión de crear software. Garzás, que lleva desde 2001 en esto y ha acompañado a más de 800 equipos, resume en cinco pilares qué ha cambiado y qué papel queda para las personas.

#### Un cambio de época admitido por los propios firmantes

Fowler sostiene que el salto actual está al nivel del que supuso pasar a los lenguajes de alto nivel. Uncle Bob va más allá y pide dejar de programar: la IA lo hace más rápido y mejor, así que conviene dedicarse a lo que aporta valor real y asumir que no hay marcha atrás. Kent Beck reconoce que el 90% de sus habilidades ha pasado a valer cero, mientras que el 10% restante se ha multiplicado de forma exponencial. Incluso autores de la época cascada hablan ya de una tercera época dorada en la evolución del software.

#### Pilar 1 — Cualquiera puede construir software hablándole en español

Karpathy tiene fijado un mensaje en su cuenta que define el lenguaje de programación más potente hoy como el español (o el inglés). En un taller con Lovable, gente del propio sector se sorprendía de que con un prompt sencillo se genere en segundos un prototipo operativo, no necesariamente liberable a producción pero muy por encima de una pantalla muerta o un PowerPoint. Otras herramientas citadas son Antigravity y Claude Code. El impacto real está en el software pequeño: Javier y su equipo acumulan centenares de aplicaciones internas de vibe coding que antes no se habrían hecho por falta de presupuesto o de un técnico dedicado. La consecuencia es que empresas pequeñas entran en sectores antes vedados y que el mercado se llena de desarrollos que no existían.

#### Pilar 2 — Si la IA asume parte del trabajo, los equipos se reducen

Equipos más pequeños implican menos ceremonias, menos reuniones y menos coordinación, algo que se diseñó para plantillas grandes. Garzás lo ve como una oportunidad de saneamiento frente a los dailies de 40 personas y 45 minutos que llamó «oscuridad». Además, las fronteras entre roles se difuminan: el product manager hace algo de UX con ayuda de IA y el UX crea prototipos operativos en lugar de pantallas en Figma; en algunas empresas aparece incluso un rol que aglutina todo y que se está llamando «product». El efecto colateral es exigente: quien no sea técnico tendrá que manejarse con GitHub, entender qué es un fichero markdown o leer código generado sin asustarse. El perfil puramente no técnico, igual que el estrictamente antiguo, está en extinción.

#### Pilar 3 — Del documento de requisitos al prototipo operativo

Si se puede tener un prototipo funcionando en minutos, el documento de requisitos pierde su papel central: historias de usuario, especificaciones funcionales y todo el material pensado para la interacción humana pasan a un segundo plano. La razón es simple: un prototipo operativo vale mucho más que una imagen y que mil palabras. Al mismo tiempo, gran parte de los requisitos deben empezar a pensarse para la máquina, con ficheros de especificación que actúan como fuente única de la verdad frente al comportamiento no determinista de la IA. De aquí sale la conclusión más importante: el Discovery, descubrir qué problemas merece la pena resolver, deja de ser una fase previa y ocurre en paralelo, construyendo. El Discovery es la estrella del momento y una gran ventana profesional, porque el delivery se automatiza cada vez más.

#### Pilar 4 — El legacy, el código nuevo y quién mantiene qué

Durante años disciplinas como la deuda técnica, el clean code o herramientas como Sonar existieron para que los humanos entendieran el código. Cuando el código lo genera y lo mantiene la IA bajo supervisión humana, esas prácticas siguen siendo importantes pero su papel es menos crítico, y aparecen voces que proponen volver al código máquina o al ensamblador en puntos críticos, porque la IA lo interpreta bien aunque sea ilegible para nosotros. El caso que más le sorprende es el del legacy: sistemas de 20 años, empezados en C y luego Java, con sus programadores originales jubilados y rincones que casi nadie entiende, donde se conecta un chatbot con un LLM mediante técnicas de RAG para que pueda estudiarlo e interpretarlo. Ha visto ya tres o cuatro casos así, y eso rompe la dependencia del guardián único del conocimiento.

#### Pilar 5 — El testing, cuello de botella y gran oportunidad

Si el equipo genera código diez veces más rápido, las pruebas manuales se convierten en el cuello de botella, y ya no queda nada por supuesto: siguen haciendo falta garantías de seguridad, de contención y de que la IA no se salga de los raíles marcados. Por eso habla del tercer carril y de IA juez o LLM juez, con agentes que controlan a otros agentes, validación continua y verificación basada en agentes, siempre dentro de un bucle humano que seguirá existiendo. Para quien se dedique al QA o al testing, históricamente una disciplina poco valorada, es una época dorada con decenas de técnicas y herramientas nuevas apareciendo.

#### ¿Nos reemplazará la IA? La paradoja de Jevons

Kent Beck respondía a esta pregunta en un podcast con la paradoja de Jevons: cuando una innovación aumenta la eficiencia con la que se usa un recurso, el consumo tiende a crecer en lugar de reducirse. El ejemplo es la fotografía: del carrete a lo digital, hoy hacemos muchísimas más fotos que nunca porque sacar una foto es casi gratis. Con el software pasará lo mismo: se producirá más software que en toda la historia junta. Por eso la pregunta relevante no es si la IA sustituye a las personas, sino qué papel ocupará cada profesional en un mundo con diez veces más software, que probablemente exigirá más gente pensando, diseñando, validando y controlando, y menos gente atada a la rutina mecánica. La decisión, insiste, hay que tomarla hoy y no mañana.

### 🔗 Referencias

| Recurso | Enlace |
| --- | --- |
| Grupo gratuito de WhatsApp del canal | — |
| Lovable (herramienta de vibe coding) | — |
| Antigravity (herramienta de generación de código con IA) | — |
| Claude Code (agente de código de Anthropic) | — |
| Sonar (calidad de código) | — |
| Vídeo del canal sobre RAG | — |

---
## [Javier Garzás] OpenClaw IA: si gestionas productos así, ya vas tarde

**Fecha:** 2026-04-19
**URL:** https://www.youtube.com/watch?v=1ZTjZ-IKu8k
**Video ID:** 1ZTjZ-IKu8k

### 📝 Resumen

Javier Garzás abre el vídeo distinguiendo dos tipos de gestores: los que usan la IA como un buscador ampliado y los que ya tienen un agente autónomo trabajando 24×7 para sus equipos y productos. La mayoría sigue en el primer grupo sin saberlo. En su comunidad de más de 500 profesionales, la incorporación de OpenClaw marcó un antes y un después. El vídeo cubre qué es la herramienta, sus casos de uso en gestión de producto y proyectos, y cómo la instaló él, con la advertencia de que no es trivial hacerlo bien y de que una instalación descuidada no es segura.

#### Qué es OpenClaw

OpenClaw es un agente de código abierto y software libre, autoalojado: se ejecuta en el PC del usuario o en un servidor propio y automatiza tareas en esa máquina, puede leer ficheros y estar funcionando 24 horas haciendo lo que se le encomiende. No es un LLM: se conecta vía API al modelo que el usuario configure, sea un GPT o cualquier otro del mercado. La diferencia clave con un chatbot como ChatGPT o Copilot es que no vive en la nube de un tercero ni espera a que se le pregunte: está siempre dispuesto, siempre procesando, en una máquina que el usuario controla.

#### El lío de nombres y su origen

Garzás dedica un apartado a aclarar el naming, porque el proyecto ha tenido varios nombres y en algún momento se llamó Clawbot y antes Moltbot. Anthropic, propietaria de Claude, pidió de manera amistosa al proyecto que cambiara el nombre de Clawbot por su parecido con el suyo, y para evitar problemas se adoptó el nombre actual, OpenClaw. El proyecto lo creó un desarrollador independiente, Peter Steinberger, que se hizo tan famoso con él que acabó fichado por OpenAI. Como dato de tracción, el autor destaca que superó las 220.000 estrellas en GitHub en menos de tres meses, un récord absoluto en la plataforma, y que ha sido citado varias veces por el CEO de Nvidia como una revolución al nivel de la aparición de ChatGPT.

#### Las cinco claves que lo hacen disruptivo

El primer punto es que es un agente y no un LLM: se conecta por API a cualquier modelo y trabaja con prompts y skills. El segundo es su proactividad: cuando no puede resolver un problema se busca la vida, busca una skill, descarga lo que necesita y lo soluciona, algo que un ChatGPT no hace. El tercero es que su interfaz de chatbot son herramientas que todo el mundo ya conoce —Telegram, WhatsApp o Slack—, lo que además permite aprovechar funciones como el micrófono por audio. El cuarto es que es software libre, gratis entre comillas, porque hay que pagar los tokens del LLM y el PC o VPS donde se instala. El quinto, que Garzás considera el más llamativo, es que se autoconfigura: si no puede ejecutar algo, se va a la web o a GitHub, busca la manera de lograrlo y propone soluciones, un comportamiento que compara con Jarvis o Her.

#### Cómo instalarlo: VPS frente a local

La recomendación del autor es instalarlo en un VPS, un servidor virtual privado, y no en local, por dos razones: seguridad, ya que en local tiene acceso a todo, y disponibilidad, porque así funciona 24×7 sin depender de tener el ordenador dedicado y encendido. Él lo tiene en Hostinger, que ahora patrocina el canal aunque él ya lo usaba antes. El proceso resumido: entrar en la web de Hostinger, elegir el plan básico de VPS —no hace falta mucha potencia para arrancar—, configurar la duración del plan y el descuento, aplicar el cupón "Javier Garzas", desmarcar la opción de "IA lista para usar" para no consumir créditos de Hostinger y usar en su lugar la cuenta propia de OpenAI, y esperar al despliegue automático. Después se accede al panel con el token y la contraseña y se chatea con el agente de instalación, cuya primera tarea recomendada es configurar una pasarela o chatbot, normalmente Telegram porque WhatsApp resulta más complicado y tiene más restricciones. Avisa de que con Anthropic hay más fricción y problemas de compatibilidad, así que la mayoría usa modelos de OpenAI.

#### Casos de uso en gestión de producto

El primero son los backlogs inteligentes y proactivos: por la noche, cuando hay menos tráfico y menos consumo de tokens, el agente analiza Slack, los tickets y las plataformas de feedback de usuario, y genera un backlog de ítems priorizados con criterios de aceptación propuestos, que el product manager revisa después. El segundo es el reporting: cada lunes a las 8 el agente recopila las métricas de producto, las contrasta con los OKRs aplicando una skill, y entrega por Telegram un resumen ejecutivo listo para enviar sin abrir ninguna herramienta. El tercero es la vigilancia de competidores: se le da la instrucción de monitorizar los lanzamientos de un competidor y avisar, siguiendo repositorios, notas, artículos publicados, redes sociales y tendencias, en lugar de hacer scroll manual. El cuarto es la detección de oportunidades: rastrea patrones de uso en analítica, reseñas y sesiones, detecta necesidades emergentes y sugiere hipótesis. El quinto es la preparación de roadmaps: antes de las revisiones trimestrales resume el progreso de las iniciativas y lo convierte en narrativas y borradores de argumentario según la skill y los prompts configurados, algo que describe como un copiloto muy potente, un "co-PM".

#### Riesgos, seguridad y control de costes

El agente tiene acceso total a los archivos, y todavía más si se instala en local, de ahí la insistencia en llevarlo a un VPS, lo que minimiza pero no elimina el riesgo. Como todo LLM, no es determinista y puede alucinar, así que hay que comprobar lo que hace. Recomienda vigilar la seguridad de los puertos, exigir que pida confirmación antes de acciones raras y no instalar MCPs o skills de terceros sin revisarlos. En costes distingue el alojamiento, que considera ridículo —menos que una pizza o una hamburguesa—, del consumo de tokens del LLM, que es lo que hay que controlar: él tiene fijado un presupuesto máximo en OpenAI, de modo que cuando se agota el agente avisa y deja de consumir. Advierte del riesgo de dejar la tarjeta sin límite, porque un agente muy proactivo puede gastar de madrugada resolviendo problemas por iniciativa propia.

### 🔗 Referencias

| Recurso | Enlace |
| --- | --- |
| OpenClaw (proyecto de agente de código abierto, más de 220.000 estrellas en GitHub) | — |
| Hostinger (planes VPS y despliegue automático de OpenClaw) | — |
| Cupón de descuento "Javier Garzas" para Hostinger | — |
| Guía en PDF sobre configuración e instalación de OpenClaw | — |
| Grupo de WhatsApp gratuito del canal | — |
| Vídeo del canal sobre skills aplicadas a gestión de producto | — |
| Vídeo del canal sobre skills de OKR | — |

---
## [Javier Garzás] 5 libros que cambiarán cómo gestionas con IA (y que el 90% nunca leerá)

**Fecha:** 2026-04-05
**URL:** https://www.youtube.com/watch?v=URznOJ5Ex1g
**Video ID:** URznOJ5Ex1g

### 📝 Resumen

Javier Garzás parte de una crítica al ruido informativo: el 90% de los profesionales que conoce se informa solo con newsletters y LinkedIn, y sigue gestionando igual que hace cinco o seis años. Frente a los posts que duran minutos, propone cinco libros que, en su experiencia, explican el presente y el futuro de la gestión. Ninguno promete un método mágico ni ofrece listas de herramientas; todos exigen cambiar la forma de pensar.

#### 1. La ola que viene — Mustafa Suleyman

El primer libro es "La ola que viene", de Mustafa Suleyman, cofundador de DeepMind y actual CEO de la división de IA en Microsoft, al que Garzás presenta como alguien que lleva décadas construyendo la tecnología y no un divulgador cualquiera. No es un libro de productividad ni de herramientas: es un libro incómodo sobre la magnitud real de lo que está pasando. Su tesis es que la ola que viene es a la vez la mayor oportunidad y el mayor riesgo que ha tenido la civilización, y que la mayoría de las organizaciones no está entendiendo ninguna de las dos. Para un gestor la consecuencia es directa: quien trate la IA como una moda pasajera o una herramienta más que añadir al stack llegará tarde, no un poco tarde, sino estructuralmente tarde. El objetivo del libro es obligar a salir del detalle del prompt y del chatbot para ver el mapa completo.

#### 2. The Atomic Human — Neil Lawrence

El segundo título es "The Atomic Human", de Neil Lawrence, catedrático de machine learning en la Universidad de Cambridge, al que Garzás escuchó en persona en una AI Summit en Londres. Su pregunta no es cómo usamos la IA, sino qué queda de nosotros cuando la IA hace lo que antes hacíamos. Para el autor esto ya no es filosofía sino operativa: si un manager no sabe qué aporta él que una IA no puede replicar, no puede construir un equipo de futuro, ni delegar, ni liderar, y se queda en la mera supervisión de tareas, algo que no escala. Lawrence sostiene que lo que nos define es precisamente lo más difícil de automatizar: el juicio en contextos de incertidumbre, la confianza, la comunicación implícita y el olfato para reconocer patrones y tendencias.

#### 3. Frictionless: la fricción invisible que frena a los equipos

El tercer libro aborda por qué se bloquean los gestores, y la respuesta no es la falta de herramientas sino el exceso de fricción. Su tesis es que en la mayoría de los equipos una parte enorme del tiempo se va en coordinación, esperas y retrabajo en lugar de trabajo real, en un ruido organizativo que nadie ha decidido eliminar. La advertencia central es que la IA amplifica lo que ya existe: si el proceso es lento y antiguo, la IA lo hará ir aún más lento, y si el equipo tiene fricciones, los agentes generarán más fricción. De ahí su regla repetida: antes de automatizar hay que limpiar, y no se debe optimizar lo que no debería existir. Frente a los títulos más abstractos, este es el más operativo y ayuda a visualizar metodológicamente qué está frenando al equipo para eliminarlo antes de disparar el uso de IA.

#### 4. Pensar con prompts: cognición híbrida y razón generativa

El cuarto libro es "Pensar con prompts", un ensayo sobre cómo cambia nuestra forma de pensar cuando se usa IA generativa a diario: ya no pensamos solos, sino en conversaciones constantes con modelos como ChatGPT o Claude. Introduce el concepto de cognición híbrida y defiende que un prompt no es solo una orden, sino un acto de pensamiento, una pregunta o hipótesis que abre un espacio mental compartido entre humanos y máquinas; el autor lo llama razón generativa y laboratorio de pensamiento. La IA funciona a la vez como espejo de nuestros sesgos y como amplificador de capacidades, y aprender a gestionar esa colaboración se plantea casi como un acto de responsabilidad. Un detalle llamativo: el libro firma como una entidad híbrida humano-máquina, idea que nace de la colaboración entre un filósofo italiano, Andrea Colamedici, y una IA, defendiendo que las ideas ya no nacen de una mente individual sino del diálogo entre inteligencia humana y artificial. Para el gestor, la lectura es útil para usar la IA como copiloto en discovery, estrategia y delivery, y para decidir qué tareas automatizar y cuáles no.

#### 5. Extreme Programming de Kent Beck: el clásico del 99 que vuelve

El quinto libro es el más paradójico: "Extreme Programming" de Kent Beck, en una edición de 2001 sobre un original de 1999, el mismo Beck que formalizó el TDD y que hoy asesora a empresas sobre desarrollo aumentado con IA. Garzás lo reivindica precisamente porque el framework de Extreme Programming nació para resolver un problema que la IA ha vuelto a poner sobre la mesa multiplicado: cómo mantener el control de productos que crecen a toda velocidad. En 1999 el problema estaba en el desarrollo humano; hoy está en la velocidad con la que crean los agentes. De aquel corpus destaca el test driven development como técnica de control, entendida de forma conceptual y no solo técnica: escribir pruebas que describan lo que se quiere antes de crear, en ciclos de generar y validar. Encaja con el spec driven development: mantener en ficheros de texto plano las especificaciones funcionales, de negocio y de aceptación que guían la generación, evitando que esas specs degeneren en un nuevo cascada. No todo el detalle del libro sirve hoy, pero sí su filosofía y el motivo por el que nacieron esas prácticas.

#### Hilo común: cinco incomodidades y ninguna receta

Garzás cierra describiendo los cinco libros como cinco incomodidades de distinto nivel: una macro sobre el sistema, una de identidad, una operativa y una táctica, más un regreso al pasado que ayuda a explicar el futuro. Ninguno da una lista de herramientas ni promete felicidad a quien siga un método mágico, pero todos piden algo: cambiar la forma de pensar, ir más allá del Copilot o ChatGPT, entender el sistema, eliminar fricción antes de automatizar y mantener el control de lo que se construye. Avisa de que eso difícilmente se aprende perdiendo horas en LinkedIn, aunque también reconoce que hoy se publican muchos libros generados a gran velocidad que no valen nada.

### 🔗 Referencias

| Recurso | Enlace |
| --- | --- |
| "La ola que viene", de Mustafa Suleyman | — |
| "The Atomic Human", de Neil Lawrence | — |
| "Frictionless" (libro sobre la fricción en los equipos) | — |
| "Pensar con prompts" (firmado por entidad híbrida; Andrea Colamedici) | — |
| "Extreme Programming", de Kent Beck (edición 2001, original 1999) | — |
| Grupo de WhatsApp gratuito del canal | — |
| Vídeo relacionado del canal sobre los temas tratados | — |

---
## [Javier Garzás] El clásico Sprint hoy es demasiado lento: las 3 velocidades de los equipos con IA

**Fecha:** 2026-03-29
**URL:** https://www.youtube.com/watch?v=nOtaMh2yRfI
**Video ID:** nOtaMh2yRfI

### 📝 Resumen

Javier Garzás, con más de 800 equipos transformados en más de 20 años, sostiene que el sprint tal y como nació hace tres décadas ya no encaja con la velocidad de creación que permite la IA. Frente a los equipos que siguen aplicándolo sin cuestionárselo, plantea un ciclo de vida en el que humanos e inteligencias artificiales conviven de forma explícita dentro de carriles de velocidad diferenciados.

#### Los tres supuestos de Scrum que la IA ha hecho saltar por los aires

El punto de partida del vídeo es que los sprints originales se diseñaron sobre tres supuestos que la IA ha destruido. El primero era que crear productos era un proceso mucho más lento; se trata de un marco de los años 80, de una época en la que ni existían los smartphones. El segundo asumía que solo los perfiles técnicos, y en concreto los desarrolladores, creaban producto. El tercero daba por hecho que los equipos estaban formados exclusivamente por personas. Con la IA esos tres pilares caen: la velocidad de creación se ha disparado, los perfiles no técnicos ya construyen y los agentes forman parte del equipo. De ahí la necesidad de definir ciclos de vida que integren de forma explícita el trabajo de personas y de IAs, sin renunciar a la velocidad pero también sin liberar versiones que acaben explotando.

#### Del IA human loop a los carriles de velocidad

Antes de organizar el trabajo, Garzás distingue tres niveles de participación humano-IA dentro del llamado human in the loop: autonomía total de la IA con supervisión humana muy baja, supervisión parcial del humano sobre lo que hace la IA, y supervisión total o máxima. Esos tres niveles se corresponden con la metáfora central del vídeo: una autovía con carriles separados por velocidad, donde los vehículos lentos no frenan a los rápidos. La idea de organizar el trabajo por carriles no es nueva: sitúa su primera referencia conocida en Microsoft a finales de la década de 2010, cuando empezó a separar un carril de impacto interno y otro de impacto externo durante las migraciones a la nube. La novedad es que la IA añade un tercer carril que ahora mismo se está definiendo en foros y comunidades.

#### El carril interno: velocidad de la luz y vibe coding

El primer carril es el carril interno o inner loop, el de mayor velocidad, dedicado a la creación y construcción. Es el carril donde hoy manda el vibe coding: la IA hace algorítmica, prototipado y generación a gran velocidad, con autonomía casi total y supervisión humana mínima. El ciclo se mide en minutos, y en él participan tanto perfiles técnicos como no técnicos, incluido un product manager que prototipa sin pasar por un equipo de desarrollo, algo impensable hace unos años. Su función es explorar, probar alternativas y validar cuanto antes con usuarios cercanos, beta o friends and family, en lugar de discutir sobre pantallazos y PowerPoint. Garzás insiste en que este carril no es para producción y en que no puede frenarse con planificaciones, reviews de fin de sprint, ceremonias ni multitud de perfiles opinando.

#### El carril medio: supervisión con agentes, no con personas

El segundo carril es el más novedoso, el middle loop, una capa de control y robustez que comprueba lo que la IA ha producido a toda velocidad. Su objetivo no es solo que algo funcione, sino que no genere un desastre. El autor ilustra el riesgo con el caso de Amazon: dejó demasiada autonomía a la IA en el carril rápido, se reportaron hasta cuatro fallos críticos y hubo hasta seis horas de incidencias con millones de pedidos afectados. El error contrario es igual de grave: trasladar al carril intermedio las revisiones humanas manuales de siempre, porque así las personas se convierten en cuello de botella y frenan los vehículos rápidos. La supervisión debe hacerse con agentes de IA y técnicas de IA que controlen a la IA. Aquí aparecen disciplinas emergentes que aún están buscando nombre, como la ingeniería del arnés (harness engineering), entendida como todo lo que rodea a la IA para que trabaje dentro de límites seguros, fiables y controlados, y el vibe engineering, orientado a hacer robusto lo que salió del primer carril y diferenciado de los "vibers" cuyo foco es la validación.

#### El carril externo: liberar y aprender de usuarios reales

El tercer carril es el externo, u outer loop, el más lento y el más supervisado, reservado para poner cosas en manos de usuarios reales: compradores de un e-commerce, alumnos de una formación, etc. Aquí ya no importa crear rápido, sino observar cómo se comporta lo construido: si aporta valor, si resuelve el problema correcto, si encaja en el negocio y si merece la pena seguir evolucionándolo. La participación humana es estratégica y prácticamente total, con el discovery como pieza determinante: decidir qué validar, interpretar el feedback, priorizar y determinar si el producto sigue, pivota o se descarta.

#### Etiquetar el backlog y qué queda del sprint clásico

La recomendación operativa es etiquetar cada elemento del backlog con el carril por el que va a circular, porque eso condiciona las subtareas y la definición de terminado de cada tarjeta. Un mismo ítem puede nacer en cualquier carril y saltar de uno a otro según el momento: hay ideas que mueren en el carril interno, lo cual es sano, y validaciones del carril externo que devuelven trabajo al interno para volver a explorar. Los tres carriles pueden funcionar en paralelo. Sobre el sprint, Garzás considera que la terminología se mantendrá por cultura organizativa, pero que en la práctica se relaja: contrastada con la Guía de Scrum, resulta dudoso que lo que se hace hoy fuera pueda seguir llamándose así. El carril interno vive mejor en un modelo tipo kanban de ciclo continuo, sin plannings, reviews ni dailies eternos, mientras que los carriles medio y externo pueden seguir cerca de un scrum más planificado.

### 🔗 Referencias

| Recurso | Enlace |
| --- | --- |
| Guía de Scrum (Scrum Guide) | — |
| Grupo de WhatsApp gratuito del canal | — |
| Vídeo del canal sobre nuevos ciclos de vida con IA | — |
| Vídeo del canal sobre vibe coding | — |

---
## [Javier Garzás] Si gestionas productos sin la técnica IA-Skills eres lento

**Fecha:** 2026-03-22
**URL:** https://www.youtube.com/watch?v=v95f4EL8_nQ
**Video ID:** v95f4EL8_nQ

### 📝 Resumen

Javier Garzás explica qué son las IA-Skills, por qué se han vuelto una técnica ineludible para quien gestiona productos y cómo arrancar con ellas. Compara a quien sigue trabajando con copy-paste de prompts con aquellos que en su día seguían pegando pósits cuando ya existían herramientas de gestión mucho más potentes: se quedan lentos y se quedan atrás.

#### Del trabajo a mano al pegado de prompts

Repasa la evolución de la técnica. Primero se escribía todo a mano; después llegaron las IA generativas y las librerías de prompts, con buenas prácticas en lenguaje natural para escribir una historia de usuario, priorizar o redactar una prueba de aceptación. El avance fue enorme, pero el problema actual es que copiar y pegar prompts es lento y difícil de distribuir en equipo, obliga a tenerlos en un Notion o un Google Doc y sobrecarga la ventana de contexto con tokens, lo que hace que la IA empiece a perder el hilo en problemas complejos.

#### GPTs, proyectos y Gems: el conocimiento quedaba encerrado

Un paso intermedio fueron los custom GPTs, que encapsulaban los prompts y facilitaban distribuirlos, un patrón que después replicaron los proyectos de Claude y las Gems de Google. La limitación es que ese conocimiento quedaba encerrado en cada ecosistema concreto: llevarse lo que se había creado en un custom GPT o en un proyecto de Claude a otro entorno como Google Antigravity era realmente complejo.

#### Qué es una IA-Skill y cuándo se convirtió en estándar

Una skill es, técnicamente, una carpeta que contiene un fichero skill.md —Markdown, texto plano y fácil de formatear— con las instrucciones, el contexto y el comportamiento deseado, que puede ir acompañada de otros ficheros de contexto y distribuirse en formato .zip. Aclara que el nombre confunde: no se trata de que la persona tenga una destreza con la IA, sino de darle una destreza a la IA. Anthropic lanzó las skills hacia el 16 de octubre de 2025 y en diciembre de ese mismo año las abrió y estandarizó, igual que había ocurrido antes con los MCP. Al ser estándar, funcionan en Claude, en Antigravity, en ChatGPT y en prácticamente cualquier chatbot.

#### Ventajas: distribución, reutilización y contexto más limpio

Las skills permiten onboardings mucho más rápidos, reutilizar el conocimiento de expertos y distribuir las mejores prácticas entre el equipo, además de hacer a la organización independiente de una herramienta o ecosistema concreto. Añade una ventaja técnica importante: al invocar una skill, esta no inunda la ventana de contexto, con lo que se puede mantener una conversación larga sin el problema de sobrecarga de tokens que degrada las respuestas.

#### Demo práctica en Claude con un user story mapping

Muestra el camino más sencillo. En Claude se entra en personalización, se va a la sección de skills y se pulsa el botón de añadir, donde hay varias opciones: crear con Claude, que abre una conversación en la que la herramienta pregunta qué se quiere construir y al final guarda la skill, o bien escribir las instrucciones directamente y cargar la habilidad. Hace la demostración descargando una skill de mapa de historia de usuario del repositorio de Dean Peters en GitHub y muestra cómo Claude se apoya en las buenas prácticas embebidas por el autor para generar el mapa, la persona y el recorrido del usuario. Comenta de pasada que trabajó el ejemplo con Whisper en lugar de escribir y que merece la pena.

#### Combinar skills con MCP: Miro y Gamma

Cuenta que Miro es su herramienta de trabajo para volcar ideas, donde hace su brainstorming personal, y que las skills vía MCP leen ese tablero y aplican las instrucciones que él ha definido para sintetizar y condensar la información. Con un MCP de salida hacia Gamma consigue generar informes, carruseles o presentaciones a partir de esa síntesis, como sustituto potente del PowerPoint clásico. Su recomendación es enganchar siempre las skills a un MCP, porque ahí se multiplica y se dispara su potencial.

#### Repositorios y marketplaces de skills

Recomienda el repositorio de Dean Peters en GitHub, centrado en product management, con material muy variado: hipótesis, discovery, customer journey, métricas financieras o jobs to be done, entre otras. Explica que basta con entrar en una skill, descargarla, copiar el texto del skill.md o adaptarlo, y subirla al chatbot. Además de ese repositorio, menciona otros recursos donde buscar skills ya hechas: el marketplace skillsmp.com, mcp market y skills.sh. Cualquiera puede usar las skills de otros o crear las suyas propias.

#### Migrar de GPTs a skills: lo que hace su equipo

Su equipo ha migrado prácticamente todo lo que tenía en los antiguos custom GPTs a skills, porque son mucho más rápidas, no atan a una plataforma y se pueden invocar desde cualquier sitio. Mantiene sus GPTs públicos de OKRs y de product management porque los usa mucha gente, pero para uso interno la apuesta son las skills. Cierra insistiendo en no quedarse en el mundo del pegaprom y en combinar skills con MCP, y remite a su comunidad gratuita de WhatsApp para seguir el tema en un formato más ágil.

### 🔗 Referencias

| Recurso | Enlace |
| --- | --- |
| Repositorio de skills de Dean Peters (Product Management, GitHub) | — |
| skillsmp.com (marketplace de skills) | skillsmp.com |
| mcp market (marketplace de skills) | — |
| skills.sh | skills.sh |
| MCP (protocolo de Anthropic) | — |
| Grupo de WhatsApp gratuito de Javier Garzás | — |

---
## [Javier Garzás] Así han evolucionado los roles de Producto cuando el equipo trabaja con IA

**Fecha:** 2026-03-15
**URL:** https://www.youtube.com/watch?v=6EHLuD_9bTI
**Video ID:** 6EHLuD_9bTI

### 📝 Resumen

Javier Garzás analiza qué partes del rol de product manager, product owner o gestor conviene potenciar y cuáles abandonar para seguir siendo imprescindible en equipos que trabajan con IA. Parte de dos datos que resume al arrancar: la IA ya genera el 4 % de todos los commits de GitHub y, al ritmo actual, podría superar el 20 % antes de terminar el año, y en Spotify los mejores ingenieros llevan meses sin escribir una línea de código y solo supervisan lo que genera la IA.

#### La barrera técnica ha caído para siempre

El mensaje central es que hoy cualquier perfil, sea técnico o no, no solo tiene la capacidad de crear productos tecnológicos: tiene la obligación. La IA ha tirado la barrera de entrada que reservaba la creación de prototipos, integraciones y automatizaciones a perfiles con conocimientos profundos, y para ello no hace falta un conocimiento enorme, sino paciencia y criterio. Un mundo con roles claros, carreras definidas y certificaciones está desapareciendo, y no por la caída de Scrum ni por una nueva moda metodológica, sino porque esa barrera exclusiva ha dejado de existir.

#### De escribir código a dirigir a la IA

El trabajo humano se ha desplazado de teclear líneas de código a verificar, poner límites y dirigir. Herramientas como Claude Code escriben código a un nivel muy alto, proponen cambios y empujan commits complejos a producción, de modo que el humano pasa a definir objetivos, revisar, acotar y fijar arquitectura. El mismo patrón se repite en cualquier trabajo de conocimiento con un ordenador delante: leer, analizar, resumir, preparar documentos y reuniones o coordinar es terreno de la IA, mientras criterio, decisiones e impacto quedan para las personas.

#### Se diluyen las fronteras entre perfiles profesionales

De ahí que los roles dejen de definirse por lo que se sabía hacer técnicamente y pasen a definirse por cómo se use la IA. Los silos entre departamentos ya se rompieron; ahora se rompen los silos entre perfiles: un PM que genera un prototipo funcional y valida su idea sin una cadena de especialistas, un diseñador que sustituye un diseño muerto en Figma por algo operativo, o un desarrollador que asume tareas antes exclusivas de testing. El profesional multifuncional, la máxima expresión de las competencias en T, pasa de ser raro a ser obligatorio. Menciona herramientas de vibe coding como Lovable o Antigravity, esta última usada por su propio equipo para automatizar tareas cotidianas y pequeñas aplicaciones de uso interno.

#### El auge del perfil builder

El título del rol importa cada vez menos; importa si la persona es capaz de tomar un problema concreto de su alrededor, imaginar una solución y llevarla a cabo ella misma. Insiste en no llevarlo al terreno de las grandes aplicaciones: la clave está en lo cotidiano y en soluciones operativas de uso interno, sin necesidad de llegar a producción con millones de usuarios. De ahí la etiqueta de roles builders o IA builders, y ejemplos como crear una skill en lugar de revisar a mano la herramienta de gestión, tirar de MCP para acelerar el seguimiento o automatizar la revisión de informes y tendencias con IA.

#### Se transforman las prácticas clásicas: fuera PRDs, dentro prototipos y specs

Cuando crear se democratiza, cambian las prácticas de ingeniería y de gestión, y los ciclos pasan a ser bucles rápidos de IA y humano. Los requisitos dejan de volcarse en documentos eternos y se sustituyen por prototipos hechos en poco tiempo por perfiles no técnicos que muestran el comportamiento esperado desde el primer día. Señala que el responsable de Claude Code ha contado que no habrían llegado a esa herramienta si no hubieran eliminado por completo los PRDs. Las historias de usuario conviven ahora con specs en ficheros que condicionan a la IA, y el testing cambia: la IA genera tests unitarios, de interacción y de APIs directamente desde las specs, y el equipo revisa la cobertura. La documentación no desaparece, pero el centro de gravedad deja de ser el Word, el ticket, Jira o Confluence.

#### Todo el mundo se ha vuelto más técnico, sin ser programador

No se trata de que todos aprendan a programar, sino de que las herramientas técnicas antes exclusivas de perfiles muy especializados se han vuelto necesarias y mucho más fáciles de usar. Es normal ver a gestores de proyectos tocando Git, lanzando tests o participando en revisiones de código, algo impensable hace poco. Con Claude Code, un PM puede lanzar una revisión con un botón y que los agentes generen la pull request automáticamente, sin tener que abrir un IDE.

#### El fin del gestor administrativo

Las tareas repetitivas de informes, reporting, coordinación y reuniones se reducen drásticamente con equipos más pequeños y menos gente. Quien se quede solo en alinear perfiles, convocar reuniones y hacer reporting tiene poco recorrido: el PM del futuro toma decisiones, crea y se involucra activamente con las disciplinas que le rodean para acelerar el negocio. Las habilidades humanas —criterio, empatía, capacidad de influir, leer una sala, generar confianza— dejan de ser un extra y pasan a ser el núcleo de lo que queda cuando la parte mecánica la asume la máquina.

#### La lección de Gutenberg

Cierra con la historia de la imprenta: hacia 1440 Gutenberg construyó un ingenio que hizo irrelevante la parte mecánica del trabajo de miles de copistas, que no eran malos profesionales, y que provocó pánico real, resistencia y pérdida de empleos. Con perspectiva histórica, el número total de personas que trabajó alrededor de la industria del libro se disparó con impresores, editores y distribuidores, y se multiplicaron los libros y las obras. Su lectura es la misma para la IA: desaparecen oportunidades, pero se abren muchas más.

### 🔗 Referencias

| Recurso | Enlace |
| --- | --- |
| Claude Code (Anthropic) | — |
| Antigravity (Google) | — |
| Lovable | — |
| MCP (protocolo de Anthropic) | — |
| Grupo de WhatsApp gratuito de Javier Garzás | — |

---
## [Javier Garzás] Sin Scrum: así se organizan los equipos que usan IA

**Fecha:** 2026-03-08
**URL:** https://www.youtube.com/watch?v=eOju3Z0VnHg
**Video ID:** eOju3Z0VnHg

### 📝 Resumen

Javier Garzás sostiene que Scrum responde a un paradigma ya superado y describe los métodos y flujos de trabajo que están adoptando los equipos que trabajan con IA como herramienta principal. La consecuencia más incómoda de ese cambio no es metodológica, sino estructural: afecta al tamaño y a la composición de los equipos de producto.

#### Discovery y delivery: los dos grandes bloques de siempre

Recuerda que la creación de producto de base tecnológica se ha organizado históricamente en torno a dos responsabilidades: el discovery, centrado en descubrir necesidades y problemas de los usuarios y validar si se ha acertado, y el delivery, centrado en optimizar tiempos, procesos, coordinación, releases e incrementos. Cada cambio de paradigma tecnológico ha ido adaptando ambos bloques. Los frameworks clásicos, y Scrum en particular, fueron muy valiosos sobre todo para el delivery, pero se pensaron para el trabajo entre personas y para iteraciones mucho más lentas que las actuales.

#### Los nuevos flujos nativos de IA: GitHub Kit, Claude Code y AWS Kiro

Señala que empresas y colectivos han ido publicando flujos de trabajo para la convivencia de equipos humanos con IA y destaca tres. El primero, GitHub Kit, con GitHub y Microsoft detrás. El segundo, el flujo casi metodológico que propone Anthropic alrededor de Claude Code, una de las herramientas más punteras para creación de producto. El tercero, Kiro, de Amazon Web Services. Añade que la productividad del delivery se ha disparado y que la capacidad de desplegar y testear a velocidades desconocidas era inimaginable tiempo atrás.

#### El spec-driven development (SDD) como denominador común

Todas esas propuestas comparten un patrón: dejar crear a la IA, pero acotándola. Se acota el qué debe crear (decisiones de negocio) y el cómo, en la parte técnica y de arquitectura. Ese conjunto de aproximaciones se agrupa bajo el nombre de SDD, spec-driven development, y se apoya en especificaciones claras en ficheros, típicamente en Markdown. El flujo típico es: los humanos definen las specs, con historias de usuario y pruebas de aceptación incluidas; la IA propone un plan técnico y una arquitectura; los humanos revisan, acotan y aprueban; la IA implementa y el ciclo se cierra con validación y testeo humano. Es un bucle continuo humano-IA-humano, con iteraciones mucho más cortas que las de los frameworks clásicos. Avisa del riesgo de irse al lado oscuro de la cascada: pocas historias de usuario y bien delimitadas.

#### Cómo lo aplica su propio equipo: specs.md, Gherkin y versionado

Cuenta que en su equipo usan una versión muy simplificada del SDD para desarrollos internos. Crean ficheros specs.md con pocas historias de usuario, cada una con sus criterios de aceptación escritos en Gherkin. Guardan y versionan esos ficheros, y de ahí salen pequeñas aplicaciones de uso cotidiano que les ahorran bastante tiempo. Insiste en repetir que la clave es mantener el número de historias bajo control para no acabar haciendo cascada con otro nombre.

#### Menos personas en el delivery, pero no cero personas

Responde con un "sí y no" a la pregunta de si desaparece la necesidad de humanos en el delivery. Hoy es imposible prescindir de supervisión: hacen falta técnicos que condicionen planes y arquitectura, que supervisen despliegues y detecten derivas, y especialistas de negocio que comprueben que lo liberado satisface necesidades reales. La parte negativa, que confiesa que no le gusta, es que las personas necesarias para el delivery son bastantes menos que antes y que la tendencia va a más.

#### El renacer del discovery como espacio diferenciador

El foco creativo se desplaza al discovery, que se convierte en el nuevo espacio de valor. Subraya que la IA no sustituye las técnicas clásicas de descubrimiento —cita el value proposition canvas, que él usa continuamente, y otras muchas— sino que las potencia: investigaciones profundas para descubrir tendencias y estudios, análisis de artículos y observatorios, scraping de webs de la competencia y de mercado, comprensión mucho más rápida y profunda de clientes y usuarios, y prototipado ultrarrápido. Distingue el vibe coding, orientado a prototipar y a validar necesidades con perfiles no técnicos, del vibe engineering, orientado a producto robusto. Aun así, defiende que el juicio estratégico del product manager, la empatía del diseñador y la visión técnica del ingeniero siguen siendo imprescindibles.

#### Equipos de tres o cuatro personas donde antes había siete u ocho

Los roles no desaparecen, se transforman: cambian de nombre, se potencian y también se reducen en número, concentrándose en lo que la IA no puede replicar. Aparecen perfiles como el IA product manager, el product designer, un IA tester o validador de calidad, y el ingeniero de software que garantiza la viabilidad técnica. La tendencia a dos o tres años es pasar de equipos de unas siete u ocho personas a equipos de tres o cuatro, con menos gente pero más impacto. Como cara positiva, señala que caen las barreras de entrada y surgen muchas más startups y empresas que antes no podían plantearse crear producto tecnológico, lo que podría generar una demanda agregada de talento mayor.

#### Conclusión: ventaja para quien se forma rápido

Reconoce la doble cara de la moneda: ahorros significativos de coste y tiempo para las empresas, pero impactos dolorosos para los profesionales que no se reciclen, y competidores nuevos donde antes había barreras infranqueables. Su consejo es formarse rápido, escuchar vídeos, leer libros y papers, seguir tendencias y filtrar la paja de la realidad. Cierra invitando a comentar en el vídeo y a unirse a su grupo de WhatsApp gratuito.

### 🔗 Referencias

| Recurso | Enlace |
| --- | --- |
| GitHub Kit (flujo de GitHub y Microsoft) | — |
| Flujo de trabajo de Claude Code (Anthropic) | — |
| Kiro (Amazon Web Services) | — |
| Grupo de WhatsApp gratuito de Javier Garzás | — |

---
## [Javier Garzás] La IA ha Matado a Scrum (esto es lo que viene Ahora)

**Fecha:** 2026-03-01
**URL:** https://www.youtube.com/watch?v=jrTrihcZZlc
**Video ID:** jrTrihcZZlc

### 📝 Resumen

Javier Garzás, que ha formado y mentorizado a cientos de equipos en Scrum, sostiene que ese framework fue imprescindible pero hoy empieza a ser parte del pasado: quien sigue gestionando equipos como antes de la IA trabaja con un modelo pensado para otros tiempos. El vídeo explica por qué los pilares clásicos chocan con la forma actual de crear producto, qué está apareciendo en su lugar y en qué cuatro líneas conviene posicionarse.

#### De dónde viene Scrum y por qué su contexto ya no es el nuestro
La primera mención de Scrum en el desarrollo de software aparece en un libro de 1990, una joya poco conocida que forma parte de su colección, y sus padres lo popularizan a mediados de los 90. En aquel contexto no existían los smartphones, WhatsApp ni YouTube. La última guía oficial de Scrum es de 2020, cuando ChatGPT todavía no había llegado (aparece en noviembre de 2022); en junio de 2025 uno de sus creadores publicó un pack de expansión no del todo oficial que integra la IA, pero es solo un suplemento que no toca el núcleo duro, que sigue siendo el de 2020: sprint, product backlog, sprint backlog y roles como el product owner y el scrum master. Muchos equipos están abandonando Scrum por la puerta de atrás sin atreverse a decirlo, o deformándolo hasta que resulta irreconocible.

#### La IA cambia la forma de crear y eso condiciona el modelo de gestión
El autor repite una idea central: cuando cambia la tecnología con la que se crea el producto, cambian los modelos de gestión. Un framework nacido para software distribuido en CDs y cintas alcanzó su máxima popularidad con el software como servicio en la nube, y ahora se intenta retorcer para gestionar una tecnología totalmente distinta. La IA generativa genera código de forma brutal, acerca la creación de tecnología a perfiles no técnicos y hace volver a perfiles técnicos que la habían abandonado; primero aparece el vibe coding, después el vibe engineering y empiezan a surgir maneras de trabajar pensadas para convivir con la IA.

#### Velocidad: el sprint de dos semanas se debilita
Estábamos acostumbrados a unos ritmos concretos entre la ideación, el paso por negocio y la conversión en incremento, MVP o release, y eso ya se había acelerado con el no code antes de sumarle la capa de IA generativa. El concepto tradicional de sprint, con la referencia de las dos semanas, se tambalea cuando un equipo es capaz de incrementar el producto con funcionalidades listas para producción en días o incluso en un día. La cadencia de iteración deja de tener el mismo sentido y el vocabulario clásico empieza a no encajar con la realidad de los equipos modernos.

#### Equipos más pequeños y menos ceremonias
Scrum concienció a las organizaciones, en parte por influencia de Putnam, de que los equipos debían ser pequeños, con aquel 7 más menos 2 y menos de diez personas; pero ese "pequeño" hoy resulta grande. Los equipos actuales son mucho más pequeños y especializados, en parte porque son más productivos, y con ellos pierden sentido ceremonias como los dailies, las retrospectivas o los plannings con la frecuencia anterior. Antes, para convertir una funcionalidad en prototipo intervenían negocio, diseño y técnica; hoy con vibe coding un único perfil de negocio puede sacar un prototipo no liberable pero sí enseñable a friends and family.

#### Artefactos que mutan: de las historias de usuario a las specs
Las historias de usuario no son nativas de Scrum, vienen más del extreme programming, y nacieron para la interacción entre personas; hoy hay que decirle a una IA lo que queremos y no se le habla igual que a una persona. Ese artefacto empieza a cambiar y no sirve igual, y lo mismo ocurre con el sprint backlog cuando los sprints se diluyen. La línea emergente es el SDD (spec-driven development) o desarrollo guiado por especificaciones, donde todavía no está claro cómo hacerlo: las specs detalladas parecen la vía más interesante, pero si crecen demasiado recuerdan al viejo cascada. Por ahora conviven dos maneras de transmitir requisitos, las historias de usuario para personas y las specs para las IA.

#### Roles: del product owner al IA Product Manager
Los roles clásicos se van quedando solos: el product owner fue evolucionando hacia el product manager, figura con más responsabilidades y visión, y ese product manager está mutando de nuevo hacia el IA Product Manager, que potencia a sus equipos con inteligencia artificial. El scrum master, figura vital que enseñó a andar a muchas organizaciones, prácticamente desaparece cuando hay menos sprints y menos ceremonias, y cuando sobrevive es como un facilitador de naturaleza distinta. Aparecen además roles nuevos ligados a la convivencia con el no code y la IA, como perfiles de tipo builder que ayudan con la arquitectura de esas soluciones.

#### Nuevos ciclos de vida de dos carriles y el nuevo testing
Frente al sprint clásico emergen ciclos de vida de dos carriles: uno ultrarrápido de vibe coding para validar prototipos con personas conocidas, y otro algo más lento de vibe engineering que asegura mínimos de ingeniería, robustez, seguridad y calidad antes de producir. El legacy y los ciclos antiguos seguirán conviviendo durante años con estos modelos. En paralelo, el testing y el QA viven un cambio radical: hacen falta técnicas y buenas prácticas para controlar lo que hace la IA, para que una IA controle a otra, para poner semáforos de lo que puede y no puede hacer y para revisar de forma automatizada las tripas de lo que genera.

#### Cuatro líneas de trabajo para no quedarse atrás
El autor resume su recomendación en cuatro grandes líneas: la evolución de los roles (los que mutan y los que aparecen, como el IA Product Manager); los ciclos de vida donde conviven legacy, vibe coding y vibe engineering; los artefactos, con los repositorios tradicionales conviviendo con el spec-driven development y su familia de tendencias; y el control de calidad, el testing y el QA sobre lo que produce la IA. Cierra describiendo la etapa como una disrupción total y un reto profesional apasionante, invita a comentar en YouTube qué prácticas tradicionales se han cambiado en cada equipo y recuerda el enlace a su grupo de WhatsApp gratuito en la descripción.

### 🔗 Referencias

| Recurso | Enlace |
| --- | --- |
| Guía oficial de Scrum (última versión, 2020) | — |
| Pack de expansión de Scrum con IA (junio de 2025) | — |
| Libro de 1990 donde se menciona Scrum por primera vez | — |
| ChatGPT (noviembre de 2022) | — |
| Grupo de WhatsApp gratuito de Javier Garzás | — |

---
## [Javier Garzás] NO seas el cuello de botella de tu proyecto (Deja de LEER PDFs y Usa NotebookLM)

**Fecha:** 2026-02-22
**URL:** https://www.youtube.com/watch?v=n0f2d-QmiJY
**Video ID:** n0f2d-QmiJY

### 📝 Resumen

Javier Garzás vuelve sobre NotebookLM, la herramienta gratuita de Google que utiliza desde pocas semanas después de su lanzamiento, para explicar por qué sigue sorprendiéndole que tantísima gente que gestiona proyectos no la use. Su tesis es directa: quien sigue leyendo decenas de PDFs, Excel, papers, webs y pliegos de prescripciones técnicas a la antigua o buscando por palabra clave se convierte en un cuello de botella, en el "manager embudo", y pierde horas de vida en tareas que una IA resuelve en segundos.

#### Qué es NotebookLM y por qué se ha convertido en el rey
NotebookLM se plantea como una especie de gestor documental con IA: cada cuaderno es un repositorio de información al que se le añaden fuentes y sobre el que se pregunta en lenguaje natural, con búsqueda semántica en lugar de búsqueda por palabra clave. Su gran ventaja es que no sale de la información aportada, de modo que las respuestas se apoyan en las fuentes cargadas y no en el conocimiento general del modelo. El autor distingue con claridad entre lo que es la entrada de información y lo que es la salida: en la entrada considera que no tiene competidor en su nicho (gestión de proyectos y productos con mucha información heterogénea), mientras que para salidas más elaboradas prefiere otras herramientas. Si se necesita algo más potente ya hay que ir a un RAG, que son palabras mayores.

#### Cómo se cargan las fuentes y cómo se mantienen actualizadas
El botón de añadir fuentes admite subir archivos, pegar webs, incorporar texto copiado y, desde versiones recientes, conectar con Drive, algo que el autor considera muy importante. Esa conexión permite trabajar con un Google Doc que se va editando: si se modifica el documento, la fuente se actualiza y el cuaderno toma la última versión, lo que evita subir y bajar documentación y resulta ideal para preparar informes en los que la IA propone mejoras y el documento evoluciona. Admite PDFs, Excel, webs, vídeos de YouTube y textos pegados, mezclándolo todo en un mismo cuaderno, y además incorpora búsqueda profunda o investigación para descubrir nuevas fuentes, función que el autor combina con Perplexity para localizar papers de última generación que luego introduce en el cuaderno.

#### Citas, control de alucinaciones y uso en temas sensibles
Cada respuesta indica de qué fuente sale y enlaza al punto exacto del documento, lo que permite verificar la información y controlar el riesgo de alucinaciones. Esto resulta determinante en asuntos delicados como contratos, cláusulas o normativa, donde no se puede afirmar nada que no sea cierto. La herramienta también sugiere preguntas que al usuario no se le habrían ocurrido, aprovechando que tiene delante toda la información cargada. El autor lo resume como un cuaderno de estudio con IA que sirve tanto para consultar como para formarse dentro de la propia organización.

#### Casos de uso en gestión de producto y proyectos
Enumera varios casos de uso muy típicos en su sector: agrupar normas ISO, certificaciones y toda la documentación necesaria para preparar una auditoría; hacer discovery de tendencias y estudios de mercado, por ejemplo para saber qué está haciendo la competencia en product management; centralizar la información dispersa de un proyecto (licitación, pliego, documentos y correos del cliente) para obtener respuestas rápidas; crear cuadernos para gente junior o recién incorporada que necesita resolver dudas sin abrir documento por documento; y usos personales como finanzas o facturas. Sus propios cuadernos incluyen uno de prompt engineering con papers y el blog de Martin Fowler, otro sobre vibe coding y estudios sobre diferencias generacionales en equipos o el impacto de la IA en las profesiones.

#### Cuadernos en abierto, compartición y privacidad
Los cuadernos destacados son cuadernos abiertos que otras personas han dejado accesibles, como el que The Economist publicó con fuentes sobre el mundo en 2026, y permiten estudiar un tema preguntando por IA sobre las fuentes que alguien ha dejado preparadas. Trasladado a una organización, el autor propone dejar en abierto o compartir cuadernos con normativas, cláusulas y buenas prácticas para que juniors o cualquier persona del equipo se resuelvan dudas solas, sin montar un RAG ni infraestructura complicada. Sobre el miedo a subir información, recuerda que es una interfaz de Google: los documentos se comportan como si estuvieran en Drive y no salen de Google.

#### Leer imágenes y formatos de salida
Una capacidad que el autor destaca es la lectura de imágenes: está volcando apuntes, dibujos hechos a mano en formaciones, anotaciones y pizarras (procedentes en su caso de Google Photos) para extraer de ahí conocimiento acumulado durante años. En cuanto a las salidas, admite que no es lo más potente de la herramienta, aunque permite generar resumen en audio, diapositivas, infografías, tablas, tarjetas y mapas mentales. Para llevar todo ese material a un entregable presentable prefiere herramientas más específicas y visuales como gamma.app. Cierra insistiendo en que es gratuita y que no usarla mantiene al gestor de proyectos atrapado en tareas lentas, y enlaza en la descripción su grupo de WhatsApp y un vídeo anterior más tutorial.

### 🔗 Referencias

| Recurso | Enlace |
| --- | --- |
| NotebookLM (Google) | — |
| Google Drive | — |
| Google Photos | — |
| Perplexity | — |
| gamma.app | https://gamma.app |
| Cuaderno en abierto de The Economist sobre el mundo en 2026 | — |
| Blog de Martin Fowler | — |
| Vídeo anterior del canal sobre NotebookLM en formato tutorial | — |
| Grupo de WhatsApp gratuito de Javier Garzás | — |

---
## [Javier Garzás] Experta Nº1 en Product Management con IA: “Te vas a quedar ATRÁS si no cambias YA” con Judith Sáez

**Fecha:** 2026-02-15
**URL:** https://www.youtube.com/watch?v=Zh1FgyoywCw
**Video ID:** Zh1FgyoywCw

### 📝 Resumen

Javier Garzás entrevista a Judith Sáez, profesional con más de 15 años en productos digitales, para repasar cómo cambia el oficio de product management cuando la IA entra de lleno en el día a día. La conversación gira en torno a qué técnicas siguen vigentes, qué prácticas conviene abandonar y cómo se organiza un equipo pequeño que sostiene un e-commerce de farmacia con miles de pedidos diarios.

#### Perfil y contexto: del código al IA Product Manager
Judith Sáez empezó como programadora en aplicaciones móviles y backend y fue migrando hacia producto, gestión de proyectos y procesos; hoy se define como IA Product Manager más que como product manager a secas. Trabaja en el sector farmacéutico liderando la parte tecnológica de tres países, con un e-commerce en torno a 5.000 pedidos al día y unos 100 millones de euros de facturación anual, con unas 30 personas en producto y tecnología y trabajo diario en inglés. Su equipo protagonizó la migración de un desarrollo completamente a medida a Magento 2, resuelta en menos de seis meses y con equipos más pequeños que en etapas anteriores. Avisa de que la IA no se puede aplicar al 100% en un negocio de ese volumen: la clave está en decidir dónde entra y dónde no.

#### Lo que sigue valiendo: MVP, priorización y "hacer de poli malo"
Para ella las técnicas clásicas de gestión no han muerto: MVP, priorización y gestión de alcance siguen siendo válidas, y lo que cambia radicalmente es el tiempo y la forma de llegar a ellas. Definir el alcance de un MVP que antes exigía días de análisis, discovery de mercado y de competencia ahora se resuelve en horas con apoyo de IA. Su receta es "hacer de poli malo": saber decir no a negocio, pero con métricas y razones que lo justifiquen. Un ejemplo concreto fue el análisis de riesgo de una tarjeta regalo: aunque la funcionalidad parecía sencilla, los postmortems y postreleases anteriores mostraban impacto en los equipos de data, logística y facturación, de modo que la IA ayuda a anticipar que una petición aparentemente pequeña arrastra a otros equipos.

#### Cuadernos de conocimiento como base del discovery
Una de sus bases diarias es construir cuadernos de conocimiento que recogen no solo su información, sino también la de todo el equipo y la de años anteriores; la herramienta concreta da igual, porque se puede llevar a NotebookLM, a un Gem de Géminis o a un proyecto o custom GPT. Esto transforma el discovery: muchas funcionalidades que se analizan ya se intentaron en el pasado y la IA permite saber qué se hizo y por qué sin depender de buscar documentación antigua ni de preguntar a personas que ya no están en el equipo o que están de vacaciones. En un negocio donde diez minutos de caída de las tiendas de tres países cuestan miles de euros, contar con esa memoria consultable es crítico.

#### Migraciones y releases grandes: workstream leads y showstoppers
En releases grandes como las migraciones, su equipo se apoya en leads por cada workstream implicado (pricing, catálogo, CRM, PIM, SEO, facturación, logística, data): cada persona responde en exclusiva de su ámbito, porque si la responsabilidad se diluye nadie acaba estando realmente a cargo. Para saber si un e-commerce está listo manejan el concepto de showstopper, los pasos que no pueden fallar: el funnel completo, el pago, la página de gracias y que el pedido llegue al almacén, con un runbook que evita dejarse nada. Rechaza la documentación exhaustiva en general, pero defiende una documentación básica de configuraciones (por ejemplo los manuales de los métodos de pago) a la que recurrir o preguntar directamente a un agente cuando hay un punto crítico.

#### IA con criterio: automatizaciones, soporte y microfuncionalidades
Advierte de que intentar automatizar cualquier cosa es un error: en su equipo han probado N8N y han visto cómo se generan cuadros de mando que nadie mira o alertas que nadie necesita, creando un "monstruo" a seis meses vista. Su método es hacer una tabla con lo que consume más tiempo, lo que realmente aporta valor y lo que es repetible, y solo entonces decidir qué se automatiza. Uno de los filones que exploran es el soporte, las incidencias y el QA, tareas repetitivas que desmotivan al equipo y donde sí tiene sentido desplegar agentes de IA. En empresas con legacy, su recomendación es aislar microfuncionalidades fuera del núcleo (validaciones de precios, catálogo, herramientas de marketing o soporte) y llevarlas a desarrollo puro, en lugar de intentar meter la IA dentro del core.

#### Menos reuniones y más esencialismo: cómo organiza al equipo
Su equipo no tiene dailies, decisión por la que ha recibido críticas, y sustituye esas ceremonias por reuniones semanales más las que se convocan a demanda cuando aparece un blocker o hay que cerrar acuerdos. Trabajan con franjas de una semana en lugar de un sprint clásico de dos semanas, con una lista de tareas muy básica por equipo y sin actualizar historias de usuario, horas o tareas. Su principio es el esencialismo puro: un escáner rápido de los cientos de correos diarios para descartar lo no crítico, distinguiendo lo urgente de lo importante, y una herramienta tipo Roda como gestor de tareas y documentación. Además recomienda medir lo que casi nadie mide, como las horas de reuniones por equipo o la creación de franjas de horas fértiles protegidas para concentrarse con pomodoros.

#### Requisitos con IA, prototipado y LLM como juez
Para redactar requisitos usa IA con su propio contexto y skills, y va un paso más allá con prototipado: en la mayoría de los casos no hace falta un diseño de Figma, basta una herramienta como V0 que genere un prototipo por lenguaje natural y permite validarlo con un usuario, algo impensable cuando un prototipo exigía un diseñador. Para evitar dejar escenarios sin cubrir trabaja con un LLM como juez: una IA valida a la otra y avisa de detalles según el país, como que en Portugal hay que mostrar una línea legal concreta en los descuentos del carrito o que la fidelización solo está activa en algunos mercados. También señala que la agilidad corrompida dejó de medirse: hoy se lanzan funcionalidades sin saber si se usan y sin tests A/B ni insights de usuario.

#### Carrera, expertise y reciclaje profesional
Judith cree que la IA no elimina la profesión, sino que revaloriza el expertise: la IA pone escenarios sobre la mesa, pero no los que se aprenden tras muchas migraciones, caídas de sitios y WordPress migrados. Le diría a su yo de hace quince años que los límites se los pone uno mismo, porque ella misma tenía un enorme síndrome del impostor y hoy trabaja íntegramente en inglés. Su consejo para quien empieza o se recicla es preguntarse en qué es bueno y en qué no, apoyarse en quien es mejor en lo que uno flojea, perder el miedo a disciplinas nuevas (marketing, diseño, prototipado) sin pretender ser experto, y elegir mentores y formadores rigurosos, porque la IA también ha traído mucho postureo y perfiles que dan ponencias sin conocimiento real del sector.

### 🔗 Referencias

| Recurso | Enlace |
| --- | --- |
| NotebookLM | — |
| Gem de Géminis (Google) | — |
| N8N | — |
| Magento 2 | — |
| Figma | — |
| V0 (prototipado por lenguaje natural) | — |
| Roda (gestor de tareas y documentación) | — |

---
## [Javier Garzás] AI makes Project Management obsolete: this is what's coming next

**Fecha:** 2026-09-09
**URL:** https://www.youtube.com/watch?v=WAfTZLE9cso
**Video ID:** WAfTZLE9cso

### 📝 Resumen

Javier Garzás, con más de veinte años de experiencia en el sector digital, sostiene que la gestión de proyectos tradicional no está muriendo, pero sí está dejando de ser una rama con crecimiento y glamour profesional. A partir de tres señales medibles —el comportamiento de las herramientas, el desplome del interés por el término y la retirada de los grandes referentes— traza una fotografía del sector y argumenta que lo relevante no es la decadencia de lo antiguo, sino el nacimiento de una nueva disciplina de gestión moldeada por la IA.

#### Las herramientas: Jira pierde el futuro mientras Atlassian factura más que nunca

Jira, nacida en 2002 —cinco años antes que el iPhone—, es la herramienta emblemática de la gestión tradicional, y hoy pierde un 32% de sus clientes nuevos en un año. En contraste, Linear, nacida en 2019, crece por encima del 67% y se ha posicionado como la herramienta de la nueva gestión, muy acoplada a la creación de producto y bien integrada con herramientas de generación de código como Cursor. Garzás subraya la aparente paradoja de que Atlassian, la empresa propietaria de Jira, factura más que nunca: lo hace sobre su base instalada, es decir, sobre los clientes de toda la vida. Donde se desangra es en la captación de nuevos clientes, en el crecimiento. Con un símil televisivo, Jira sería la televisión que sigue viendo la gente mayor, mientras que Linear y similares se han convertido en el YouTube que consume la gente joven. En términos fríos, lo que pierde Jira es el futuro: emprendedores, nuevas startups y empresas que prefieren herramientas más ligeras.

#### El desplome del interés y la retirada de los grandes nombres

El segundo síntoma es la demanda: las búsquedas del término "gestión de proyectos" caen un 55% en un año, hasta niveles de práctica irrelevancia mediática. El tercero es la deserción de figuras de referencia. Jürgen Appelo, creador de Management 3.0 y uno de los nombres más influyentes del management digital, ha anunciado el cierre de su newsletter y de su actividad en redes para trabajar por cuenta ajena en la gestión de un hospital. La marca Management 3.0 continúa, pero con un atractivo muy alejado de sus mejores tiempos. En la misma línea, la Scrum Alliance cerró su último ejercicio publicado en pérdidas por primera vez, con casi dos millones de dólares, y la mayoría de las conferencias del sector han desaparecido o arrastran una asistencia poco significativa.

#### Por qué la gestión no desaparece: las modas sólidas no mueren

Garzás rechaza la lectura catastrofista. Tras ver llegar y caer varias modas tecnológicas, su experiencia indica que las disciplinas robustas nunca desaparecen del todo: la ciberseguridad estuvo muy de moda y sigue vigente aunque ya no sea tendencia; el software libre tuvo su burbuja y sigue existiendo; incluso la orientación a objetos, mucho más antigua, continúa ahí. La gestión de proyectos, con todas sus ramas, es una disciplina sólida de muchos años que seguirá existiendo, pero ya no será una rama potente de crecimiento ni de moda profesional. Cuando algo pierde ese impulso, normalmente aparece una rama nueva empujada por una disrupción tecnológica: en este caso, la IA como motor principal de la creación algorítmica y de la programación, sin que ello signifique que la IA pueda entregar software a producción por sí sola.

#### El nacimiento de una nueva forma de gestionar

Lo interesante, según el autor, es que se está asistiendo al nacimiento de otro modo de afrontar los retos que antes cubría la gestión tradicional. Esta disciplina incipiente —product management, product builder, product maker, o el nombre que acabe recibiendo— responde a problemas que antes no existían: equipos mucho más pequeños, un delivery simplificado, reducido y muy automatizado, la mejora del discovery para detectar qué necesidades merecen resolverse, el trabajo en iteraciones y mini-sprints muy cortos, la necesidad de especificar a una máquina cómo debe hacer las cosas y la convivencia con un "ser no humano" que debe ser supervisado por personas.

#### Tres mundos que convivirán durante años

Garzás distingue tres capas simultáneas en el ámbito digital. La primera es la gestión en cascada tradicional, la más antigua, que sigue existiendo. La segunda es la agilidad clásica y sus aledaños, que se mantendrá durante años en administraciones públicas, grandes bancos y corporaciones donde la seguridad y la inercia tecnológica dificultan incorporar la IA con rapidez. La tercera, y la verdaderamente importante ahora, es la nueva gestión que está naciendo al calor de la IA. Su consecuencia estructural es clara: habrá muchos menos roles dedicados en exclusiva a la gestión, porque habrá menos tareas burocráticas y equipos más reducidos.

#### El rol del manager frente a la necesidad de management

El paralelismo que usa el autor es el de tester y testing: una cosa es la persona que ocupa el rol y otra la actividad que debe realizarse. Con la gestión ocurre algo similar: la necesidad de management no desaparecerá, aunque se reduzca la demanda de roles exclusivos. Además, perfiles técnicos que tradicionalmente no gestionaban —programadores, perfiles de QA, diseñadores e incluso product managers— tendrán que aprender a supervisar lo que produce la IA, orientarse más al negocio, a la priorización y al descubrimiento de problemas que vale la pena resolver.

#### Consejos según el momento profesional

La recomendación de Garzás se segmenta por situación. Quien está empezando y quiere dedicarse a esto debería moverse rápido hacia la nueva gestión, que aún se está formando y prácticamente no tiene nombre, antes de que llegue todo el mundo. Quien ya acumula años de experiencia en gestión tradicional en una organización consolidada debería capitalizar esa experiencia durante los años profesionales que le queden. Y quien quiera cambiar de rumbo, sea cual sea su edad, encontrará en esta nueva gestión un renacimiento atractivo de la disciplina, con la advertencia de que conviene formarse, aceptar el ciclo de prueba y error y sumarse a comunidades, porque el ritmo es demasiado rápido para avanzarlo en solitario. Cierra el vídeo recordando una idea que atribuye a Marty Cagan, referente del product management: las tareas burocráticas de la gestión tradicional pueden acabar totalmente automatizadas.

### 🔗 Referencias

| Recurso | Enlace |
|---|---|
| Jira (Atlassian) | https://www.atlassian.com/software/jira |
| Linear | https://linear.app |
| Cursor | https://cursor.com |
| Management 3.0 (Jürgen Appelo) | https://management30.com |
| Scrum Alliance | https://www.scrumalliance.org |
| Marty Cagan / Silicon Valley Product Group | https://www.svpg.com |
| Comunidad Rebeldes y Ágiles (233 Academy) | https://233academy.com |

---
## [Javier Garzás] Qué hacer con tu carrera después de los 40 en la era de la IA: las 4 leyes
**Fecha:** 2026-09-02
**URL:** https://www.youtube.com/watch?v=eO6MRBgwGuU
**Video ID:** eO6MRBgwGuU

### 📝 Resumen

Javier Garzás aborda un fenómeno que observa cada vez con más frecuencia: profesionales del sector tecnológico de alrededor de 50 años siendo prejubilados, y la inquietud de quienes rondan los 40, a quienes les quedarían apenas diez años de margen para reaccionar. Aunque reconoce el debate sobre si los despidos masivos son realmente culpa de la IA o si esta solo los enmascara, su objetivo no es analizar las causas sino ayudar al espectador a posicionarse como profesional difícil de reemplazar. Para ello presenta cuatro "leyes" que dice haber seguido durante años para surfear los sucesivos cambios de paradigma del sector —el paso a SaaS, las metodologías ágiles y ahora la IA— y las adapta específicamente a quienes ya tienen experiencia acumulada, porque cambiar de sector es más difícil y queda menos tiempo: la metáfora del punto V1 del despegue de un avión, a partir del cual ya no hay marcha atrás.

#### Ley 1: cuando algo se construye más fácil y barato, se crea mucho más
Garzás parte de la paradoja de Jevons: abaratar la creación de un bien aumenta su producción total. En software ocurre desde hace décadas —lenguajes de alto nivel, SaaS, plataformas, no-code— y la IA multiplica el fenómeno: perfiles sin formación técnica (marketing, medicina, fisioterapia...) ya prototipan negocios o automatizan procesos. Recuerda que ya en 2013 predijo en su blog esta democratización de la programación, y cita que GitHub llegó a caer en agosto de 2026 por el aluvión de código subido. Su conclusión: habrá más software y más profesiones nuevas, así que no hay que huir del sector digital, sino buscar necesidades emergentes derivadas del propio conocimiento en nichos aún no masificados —integraciones de IA, implantación de RAG, seguridad y arneses para creación con IA, arquitectura de IA o discovery de productos—, aunque eso exija "desenamorarse" de soluciones pasadas.

#### Ley 2: las maneras mueren, los problemas perduran
Los grandes problemas que resuelve una profesión cambian poco; lo que caduca es la forma de resolverlos. Garzás lo ejemplifica con su propia trayectoria: la revisión manual de calidad de código que le pagaban por hacer quedó obsoleta cuando llegaron herramientas automáticas como Sonar, pero el problema de la mala calidad seguía existiendo; algo similar ocurrió con los modelos de mejora de procesos tipo CMMI, contra los que escribió un libro muy criticado y que hoy quedan testimoniales. Advierte además contra el falso consuelo de que el problema perdure: los cocheros de caballos no se convirtieron en taxistas. Y desmonta la famosa frase de que "el cliente no quiere un taladro, quiere un agujero": lo que quiere es colgar un cuadro. La recomendación es analizar con honestidad si se está enamorado de la solución antigua o del problema real, y saltar a la nueva manera de resolverlo.

#### Ley 3: cada salto tecnológico empuja hacia la multifuncionalidad
El mundo industrial dejó departamentos estancos (negocio, diseño, técnico, testing) que evolucionaron primero hacia equipos multifuncionales con competencias en T —especialización propia y conocimiento ligero del resto—. Con la IA se avanza hacia competencias en M: la barrera de entrada a disciplinas colindantes se ha roto (un perfil de negocio ahora puede crear prototipos técnicos pidiéndoselo a la IA en lenguaje natural), por lo que hay que conocer en profundidad las profesiones vecinas, no solo por encima. Garzás lo ve reflejado en las ofertas de empleo actuales, llenas de roles nuevos y multifuncionales. La buena noticia: la IA elimina la parte ardua de aprender esas disciplinas.

#### Ley 4: el conocimiento se regala; el criterio es lo que se paga
Antes el conocimiento era escaso y caro (libros difíciles de conseguir, másters); hoy se regala en podcasts, vídeos y redes, y además caduca cada vez más rápido. Por la ley de oferta y demanda, su valor cae y lo que realmente se paga es el criterio: saber priorizar en qué formarse, porque el tiempo es el recurso escaso. Por eso la formación puntual tradicional pierde peso frente a la formación continua, y el juego se gana encontrando "agujas de conocimiento en pajares enormes". Para afinar ese criterio recomienda unirse a comunidades de profesionales con problemas similares y crear un "sistema de escaneado" continuo (con la metáfora del escáner de Terminator) que permita procesar mucha información superficial para detectar dónde profundizar.

#### Conclusión: cuatro recomendaciones prácticas
Garzás sintetiza las cuatro leyes en un decálogo práctico: buscar las necesidades nuevas que están apareciendo sin aferrarse a las soluciones antiguas; analizar el gran problema que resuelve la propia profesión y adoptar cuanto antes su nueva forma de solucionarlo; empezar ya a hacer parte del trabajo de las profesiones colindantes; y rodearse de comunidades que agudicen el olfato para priorizar bien el tiempo, ya que todos disponen de las mismas 24 horas, pero no todos saben optimizarlas. Define el momento actual como "el renacimiento" de las profesiones y anima a los espectadores a compartir sus propios consejos en los comentarios.

### 🔗 Referencias

| Qué es | Referencia |
|---|---|
| Vídeo analizado | [Qué hacer con tu carrera después de los 40 en la era de la IA](https://www.youtube.com/watch?v=eO6MRBgwGuU) |
| Blog personal y diccionario de IA de Javier Garzás | [javiergarzas.com](https://javiergarzas.com) |
| Comunidad profesional mencionada | [233academy.com](https://233academy.com) |
| Herramienta de análisis de calidad de código citada | [Sonar](https://www.sonarsource.com) |
| Repositorio citado por el aumento de código subido | [GitHub](https://github.com) |
| Concepto económico citado (paradoja de Jevons) | [Paradoja de Jevons](https://es.wikipedia.org/wiki/Paradoja_de_Jevons) |

---
## [Javier Garzás] La IA escribe el software, PERO arreglarlo será el trabajo mejor pagado (sin volver a programar)
**Fecha:** 2026-08-26
**URL:** https://www.youtube.com/watch?v=Q34r7Zt8KXw
**Video ID:** Q34r7Zt8KXw

### 📝 Resumen

El vídeo analiza la contradicción central del desarrollo de software actual: la IA ya genera la mayor parte del código nuevo, pero nadie se fía del todo de él, y de esa brecha nace una nueva profesión muy bien pagada. El autor compara la situación con el efecto 2000, cuando el mundo pagó fortunas a programadores veteranos para revisar código mal hecho, y advierte de que la historia se repite ahora con mucho más software y sin una fecha límite.

#### La radiografía del sector: datos y contradicciones

La IA ya escribe el 42% del código que se sube hoy, con una previsión de alcanzar el 65% en 2027, y no hay vuelta atrás. Sin embargo, las empresas más punteras muestran una doble cara: Oracle presume de que la IA genera su código pero prohíbe su uso en las partes críticas de sus productos, y la comunidad Linux permite código con IA solo si una persona humana lo firma y se hace responsable. Además, el 96% de quienes suben código generado con IA afirma no fiarse de él, pero solo el 48% lo verifica realmente. El autor recuerda que el software mal hecho no lo ha inventado la IA: ya antes de su auge se estimaban pérdidas de billones de dólares anuales por su mala calidad, solo que ahora hay mucho más volumen y más creadores sin conocimientos técnicos.

#### El verification gap y la nueva profesión

La combinación de más volumen de código, menos expertos capaces de juzgarlo y la necesidad de criterio humano crea el llamado "verification gap", un hueco que ya está dando lugar a una profesión con nombre y ofertas publicadas, como la de "vibe coding cleanup specialist": el especialista que limpia, hace mantenible, seguro y escalable el código generado por IA o por personas no técnicas. Se trata de un perfil de entrada puntual más que continua, contratado cuando una idea validada con prototipos IA necesita rigor, y que en Estados Unidos ya alcanza sueldos de entre 120.000 y 200.000 dólares al año, con tarifas de hasta 200 dólares la hora y demanda al alza en los portales de empleo.

#### Qué se le pide al nuevo perfil: criterio, abstracción y control

El profesional ideal no compite con la IA ni la rechaza, sino que la controla; no es un programador tradicional, sino alguien que trabaja a un nivel de abstracción superior al detalle del lenguaje o del IDE; y usa la propia IA para controlar a la IA, mediante técnicas como LLM como juez, guardarraíles y semáforos. El autor recuerda que por miedo muchas empresas bloquean la IA por completo, lo que las deja lentas frente a la competencia: el criterio está en el punto justo, ni prohibición total ni anarquía.

#### Dónde la IA debe ir a toda velocidad

Hay dos áreas donde el software generado por IA por no técnicos debe fluir sin freno: la automatización de procesos internos de profesionales de marketing, derecho o analítica, que pueden consultar bases de datos en lenguaje natural o integrar sistemas vía MCP; y el prototipado, donde gente de negocio valida ideas con herramientas low-code antes de invertir en producción. En cambio, los puntos críticos (seguridad, escalabilidad, mantenibilidad, uso masivo) exigen supervisión humana experta.

#### Consejos según el rol

Para los managers, el mensaje es no eliminar la IA (irían lentos) ni dejarla libre (hipotecarían el futuro), y plantearse cuanto antes un asesor o auditor externo de criterio técnico. Para los técnicos, es el renacimiento de la profesión: subir el nivel de abstracción, posicionarse sobre la IA y aprender a controlarla. Y para los ex técnicos que dejaron la programación por la gestión, es el perfil mejor posicionado: entienden las raíces técnicas, pero ya no necesitan perderse en el detalle.

#### La lección del efecto 2000

El mundo gastó entre 300.000 y 600.000 millones de dólares en revisar código sin control ante el cambio de milenio, y hubo que reclutar a veteranos jubilados, los únicos con criterio, pagándoles fortunas. Gracias a ellos casi no pasó nada, aunque hubo incidentes reales: horas sin procesar datos de un satélite espía en EE.UU. y 150 diagnósticos erróneos de test de Down en un hospital inglés. La conclusión del vídeo es que esa historia se repite hoy con mucho más software, sin fecha límite, y que los profesionales con criterio para resolverlo serán los más revalorizados.

### 🔗 Referencias

| Referencia | Tipo | Enlace |
|---|---|---|
| Oracle | Empresa | https://www.oracle.com |
| Comunidad Linux (kernel) | Comunidad / proyecto | https://www.kernel.org |
| Splicer (caso: ingenieros que cobran por borrar código IA) | Empresa / caso mencionado | — |
| Forbes | Medio | https://www.forbes.com |
| Robert C. Martin (Uncle Bob) | Referencia profesional | https://blog.cleancoder.com |
| Kent Beck | Referencia profesional | https://www.kentbeck.com |
| Diccionario de IA (recurso del canal) | Recurso mencionado | — |

---
## [Javier Garzás] Las 7 Nuevas Profesiones con más futuro en la era de la IA (y las mejores no piden saber programar)
**Fecha:** 2026-08-19
**URL:** https://www.youtube.com/watch?v=rEnB7_QHj0E
**Video ID:** rEnB7_QHj0E

### 📝 Resumen

Javier Garzás analiza las siete profesiones emergentes que la IA está creando, ordenadas de mayor a menor exigencia técnica. Parte de una idea central: la IA ya genera la parte algorítmica que antes escribía un programador, lo que permite a personas sin conocimientos técnicos crear software pequeño, automatizaciones e integraciones mediante lenguaje natural. Eso sí, matiza que liberar software en producción para muchos usuarios sigue exigiendo conocimientos de escalabilidad y seguridad. El vídeo subraya que estas profesiones aún no están masificadas, por lo que existe una ventana para posicionarse, y que las tres últimas son especialmente accesibles para perfiles no técnicos.

#### El puente hacia los desarrolladores tradicionales

La primera profesión es la de quien enseña a los desarrolladores clásicos la nueva forma de crear software con IA, un ámbito con familias emergentes como el desarrollo dirigido por especificaciones (SDD) o la "codificación aumentada", término que atribuye a Kent Beck. También menciona el ecosistema de frameworks e infraestructura que acompaña a esta transición, con referencias como GitHub y AWS Kiro, y lo presenta como un rol muy demandado para modernizar equipos.

#### La ingeniería del arnés

La segunda profesión, bautizada por OpenAI, es la ingeniería del arnés: el profesional que controla lo que crea la IA y pone los "guardarraíles" para que no se salga de los límites. Incluye técnicas como usar LLMs como jueces de otros LLMs o los semáforos de control. Garzás la describe como la evolución natural del testing tradicional en la era de la IA, con un enorme campo por explorar.

#### Llevar a producción el software de los no técnicos

La tercera es el especialista que lleva a producción el software creado por personas sin conocimientos técnicos: emprendedores y profesionales independientes que validan una idea y superan el MVP, pero no saben escalarla. Este rol, ejercido a menudo por consultores independientes, se encarga de hacer ese software escalable, seguro, mantenible y robusto, a modo de auditoría o consultoría periódica.

#### IA aplicada al software legacy

La cuarta profesión fusiona el mundo legacy con la IA: un ingeniero capaz de entender, refactorizar, migrar y mejorar software antiguo (C, C++, Fortran) que históricamente solo conocía quien lo creó. La IA, con un humano que la dirija, elimina la enorme barrera de entrada de estos sistemas, y Garzás remite a un artículo de Martin Fowler sobre esta posibilidad.

#### El arquitecto empresarial de IA

La quinta, el "arquitecto empresarial de IA", pone orden en el caos de herramientas que invade las organizaciones: skills, GPTs, agentes, RAG, fuentes de verdad, versiones de LLM, tokenización y las distintas familias de Anthropic, Google Gemini, OpenAI o las IA chinas. Es el perfil, de abstracción alta y sin necesidad de detalle técnico, que decide qué adoptar y qué descartar en cada organización.

#### El líder de producto en la era de la IA

La sexta es el líder de producto con IA, bajo nombres como AI Product Manager, Product Builder o Product Maker. Supone la evolución del product manager y product owner tradicionales, con roles cada vez más fusionados (producto, diseño y técnica). Este perfil potencia el discovery con IA: leer reseñas de la web, chatbots que analizan la opinión de los clientes, detectar pains y gains, o búsquedas profundas por sector para decidir qué incorporar al producto.

#### La séptima profesión: IA en tu propio sector

La última no es un puesto en sí, sino una recomendación para todo profesional, técnico o no: incorporar la IA a su sector. Quien tiene años de experiencia en marketing, derecho, medicina o cualquier campo, puede disparar su valor automatizando procesos burocráticos, fusionando datos de Excel, CRM, ticketing o correo, y creando pequeñas automatizaciones antes impensables. Garzás insiste en que la clave no está en crear aplicaciones para millones de usuarios, sino en aplicar el superpoder de la IA a los procesos internos que cada uno conoce mejor.

### 🔗 Referencias

| Referencia | Tipo | Enlace |
|---|---|---|
| Martin Fowler — artículo sobre IA y software legacy | Artículo | https://martinfowler.com/ |
| Kent Beck — codificación aumentada | Autor | https://www.kentbeck.com/ |
| Spec-Driven Development (SDD) | Metodología | https://sdd.dev/ |
| GitHub Copilot | Producto | https://github.com/features/copilot |
| AWS Kiro | Producto | https://aws.amazon.com/kiro/ |
| OpenAI — origen del término "ingeniería del arnés" | Empresa | https://openai.com/ |
| Anthropic (Claude, skills, agentes) | Empresa | https://www.anthropic.com/ |
| Google Gemini | Producto | https://gemini.google.com/ |
| Diccionario de la IA (PDF gratuito, enlace en la descripción del vídeo) | Recurso | https://www.youtube.com/watch?v=rEnB7_QHj0E |

---
## [Javier Garzás] El dashboard de mi proyecto en 3 min con Claude Code (deja de perder tardes en informes)
**Fecha:** 2026-08-12
**URL:** https://www.youtube.com/watch?v=N5HpfPhp13k
**Video ID:** N5HpfPhp13k

### 📝 Resumen

El vídeo muestra cómo construir cuadros de mando de proyectos con IA en minutos, siguiendo un camino de tres niveles de complejidad creciente: desde un chat en el navegador con ficheros adjuntos hasta una IA instalada en local que se actualiza sola de forma periódica. La propuesta central es que la elaboración manual de informes de seguimiento (sintetizar datos de correos, Jira, Notion o Excel y maquetarlos en PowerPoint) ha quedado obsoleta frente a los asistentes de IA.

#### El problema: informes que consumen tardes enteras
Garzás parte del dolor habitual de cualquier responsable de proyecto: reunir incidencias, correos, ficheros locales y métricas de herramientas diversas, cruzarlos, sintetizarlos y maquetar la salida (PowerPoint, PDF o Excel). Ese proceso, que tradicionalmente llevaba horas o tardes, es precisamente el que la IA elimina: el método manual se sustituye por prompts y skills que encapsulan el criterio de selección y síntesis.

#### Nivel 1: dashboard en el navegador arrastrando ficheros
La primera demo es inmediata y gratuita: se arrastra un Excel con costes y avance del proyecto a un chatbot (Claude, ChatGPT o Gemini) y, con un prompt sencillo, el asistente analiza los datos, extrae conclusiones y genera un artefacto interactivo con KPIs clásicos —coste, plazo, alcance y calidad—, desviaciones, CPIs, composición del gasto mes a mes y gráficos como el diagrama de Kiviat. El resultado es descargable y publicable, y se puede refinar ajustando el prompt a la casuística de cada proyecto.

#### Nivel 2: conexión en vivo a las herramientas con MCP
El segundo nivel conecta el chat a las herramientas reales del proyecto mediante conectores MCP (Model Context Protocol), como el de Notion, activable desde el propio Claude. Con lenguaje natural se consultan bases de datos, sprints e incidencias y se cruzan varias fuentes a la vez (Jira, Gmail, calendario o CRM). En la demo, el asistente genera una versión 2 del cuadro de mando leyendo directamente los datos de un proyecto Notion, sin exportaciones ni subidas de ficheros.

#### Nivel 3: IA local con acceso a carpetas y ficheros
El escalón más potente instala la IA en local —Claude Desktop con Claude Code integrado, o el equivalente Codex de OpenAI— y le concede acceso controlado a la carpeta del proyecto. Así el asistente lee actas, PDFs, OKRs y Excel locales, combina esa información con los conectores MCP y produce un dashboard HTML interactivo, visible en un navegador integrado, con velocidad por sprint, valor de negocio, incidencias por módulo o severidad. Garzás insiste en las precauciones de seguridad: no subir nada confidencial y hacer copias de seguridad.

#### Rutinas: el cuadro de mando que se actualiza solo
El cierre del vídeo presenta las rutinas de Claude Code: tareas programadas que se ejecutan periódicamente. Con una rutina configurada para cada viernes a las 8:00, el asistente relee la carpeta del proyecto, consulta Notion vía MCP y regenera el dashboard HTML automáticamente, dejando un resumen de cinco líneas con los cambios. A las 8:05 el responsable ya tiene el informe listo sin intervención.

#### Conclusión
Garzás resume que cada usuario puede quedarse en el nivel que necesite, pero subraya que la combinación de acceso a herramientas (MCP), acceso a ficheros locales y automatización por rutinas supera con creces al chatbot tradicional, ahorrando horas y mejorando la calidad visual de los informes. Invita a la comunidad a compartir sus propias experiencias y flujos.

### 🔗 Referencias

| Referencia | Enlace |
|---|---|
| Model Context Protocol (MCP) | https://modelcontextprotocol.io |
| Claude Code (Anthropic) | https://www.anthropic.com/claude-code |
| Claude Desktop (Anthropic) | https://www.anthropic.com |
| OpenAI Codex | https://openai.com |
| Notion | https://www.notion.com |
| Jira (Atlassian) | https://www.atlassian.com/software/jira |
| Supabase | https://supabase.com |

---
## [Javier Garzás] ¿Fin de los programadores? Tu oportunidad de posicionarte, aunque no sepas programar
**Fecha:** 2026-08-05
**URL:** https://www.youtube.com/watch?v=niwfPxiTrlM
**Video ID:** niwfPxiTrlM

### 📝 Resumen

El vídeo aborda la pregunta que sobrevuela la profesión: si la IA ya programa, ¿sobran los programadores? Javier Garzás sostiene que lo que viene no es el final, sino el renacimiento de la profesión, tanto para los técnicos como para quienes nunca han escrito una línea de código.

#### La IA ya programa: ¿fin o renacimiento?
El vídeo arranca con un hecho: la IA ya es capaz de crear software, lo que permite a cualquier persona construir aplicaciones sin saber programar. Para fundamentar el "antes y después" se citan referentes del sector. Boris Cherney, creador de Claude Code, ha dejado de usar su editor de código clásico y trabaja con lenguaje natural vía prompts. Robert C. Martin (Uncle Bob), autor de Clean Code, afirma que programar a mano "a la antigua" es prácticamente un suicidio y hoy se limita a rodear a la IA de tests y controles sin necesidad de leer el código. Kent Beck, creador de Extreme Programming, resumió el cambio con su célebre frase: el valor del 90% de sus habilidades acababa de caer a cero, y el 10% restante valía ahora 1000 veces más.

#### Los datos de la adopción
Se presentan cifras que respaldan la tendencia. El informe DORA de Google Cloud señala que el 90% de los profesionales del desarrollo ya usa IA en su trabajo diario, y los CEOs de Microsoft y Google reconocen que la IA escribe en torno al 30% de su código, cifra que sube cada trimestre. Lovable, herramienta de vibe coding, registra un millón de proyectos nuevos cada semana, y el 80% de quienes construyen con ella no son perfiles técnicos. El propio equipo de Garzás ya crea con IA sus CRMs, dashboards de seguimiento económico, generadores de certificados para su comunidad y todas sus webs corporativas.

#### Implicaciones para los no técnicos
La conclusión práctica es directa: cualquier profesional —fisioterapeuta, abogado, gestor de proyectos, product owner— debe empezar a crear software ya mediante lenguaje natural, sin tocar una línea de código. La disrupción real no está en las grandes aplicaciones, sino en pequeñas soluciones que mejoran el día a día: dashboards que visualizan datos de gestión y económicos, consultas conversacionales a bases de datos que antes exigían SQL, prototipos e integraciones que antes requerían un equipo informático o un presupuesto inalcanzable.

#### La paradoja de Jevons y la explosión del software
Al abaratarse la producción de software se disparará su consumo (paradoja de Jevons), igual que ocurrió con la fotografía digital. Habrá mucho más software de "usar y tirar", automatización de tareas cotidianas y, sobre todo, nuevos negocios: emprendedores y startups que antes necesitaban inversión para contratar un equipo técnico ahora podrán validar sus ideas por sí solos. Parte de ese software quedará en prototipo, pero cuando una idea validada empiece a escalar y a acumular usuarios reales, necesitará pasar a un estado profesional.

#### La nueva demanda de perfiles técnicos
Ahí reside la gran oportunidad para los técnicos: se demandará cada vez más a profesionales capaces de tomar el software creado por no técnicos y llevarlo a un nivel productivo serio, con seguridad, accesibilidad, escalabilidad y guardarraíles, lo que se conoce como ingeniería del arnés o vibe engineering. La vieja escuela, la de programar a mano, queda obsoleta: entre la comunidad corre la frase de que escribir código a mano empieza a ser "una irresponsabilidad", porque te hace lento y te saca del sistema.

#### La lección histórica de Fortran
Para responder si la IA acabará con la profesión, el vídeo recurre a la historia. Cuando apareció Fortran en los años 50, el "sacerdocio" de programadores veteranos criticó a John Backus por haber hecho la programación tan fácil que cualquiera pudiera usarla, tachándolo de revolucionario loco. Lejos de acabar con la profesión, los lenguajes de alto nivel multiplicaron el número de personas que entraron en la programación. La misma lógica se aplica a la IA: no eliminará la profesión, la disparará. A quien se esté planteando formarse en programación, Garzás le recomienda hacerlo sí, pero en la "nueva informática": entender qué hay detrás del código para saber dirigir a la IA y hacer robusto y escalable el software que otros crean con ella.

### 🔗 Referencias

| Referencia | Tipo | Enlace |
|---|---|---|
| Claude Code (Anthropic) | Producto | https://claude.com/claude-code |
| Robert C. Martin (Uncle Bob) — Clean Code | Autor / Libro | https://blog.cleancoder.com |
| Kent Beck — Extreme Programming | Metodología | https://www.extremeprogramming.org |
| Informe DORA (Google Cloud) | Informe | https://dora.dev |
| Lovable | Producto | https://lovable.dev |
| javiergarzas.com | Web del canal | https://javiergarzas.com |
| 23academy.com | Formación | https://23academy.com |
| FORTRAN / John Backus | Referencia histórica | https://en.wikipedia.org/wiki/Fortran |

---
## [Javier Garzás] Claude Code for project management without coding knowledge
**Fecha:** 2026-07-30
**URL:** https://www.youtube.com/watch?v=-QKnfdAjgjY
**Video ID:** -QKnfdAjgjY

### 📝 Resumen

Javier Garzás presenta Claude Code como una herramienta de inteligencia artificial capaz de transformar la gestión de proyectos sin necesidad de conocimientos de programación. El autor desmonta la percepción de que Claude Code es exclusivamente para desarrolladores y demuestra cómo cualquier profesional puede aprovecharlo para tareas cotidianas de gestión.

#### La diferencia fundamental con los chatbots tradicionales

A diferencia de ChatGPT o Claude en el navegador, Claude Code se instala localmente en el PC y tiene acceso directo a los archivos del usuario. Esto elimina la necesidad de ir subiendo documentos uno a uno, permitiendo trabajar con carpetas enteras de forma simultánea. La herramienta puede leer PDFs, CSVs, Excel, PowerPoint y cualquier otro formato, procesándolos como un conjunto unificado.

#### Cinco casos de uso reales para la gestión

El vídeo detalla cinco aplicaciones prácticas. El primero es leer y resumir grandes volúmenes de datos: contratos, normativas, informes de clientes almacenados en una misma carpeta. El segundo consiste en clasificar y transformar archivos heterogéneos — por ejemplo, fusionar facturas en PDF con datos de Excel para generar un único informe estructurado. El tercer caso permite crear visualizaciones y cuadros de mando interactivos directamente desde los datos, generando dashboards financieros sin escribir una línea de código. El cuarto caso aborda la priorización de tareas cruzando archivos locales con herramientas externas como Gmail o Jira mediante MCP. El quinto explora el concepto del "segundo cerebro": almacenar documentación y notas en formato Markdown, que la IA procesa con fluidez, y visualizarlas posteriormente con herramientas como Obsidian.

#### Arquitectura y modos de acceso

Claude Code puede usarse de cuatro formas: terminal (modo avanzado), IDE (para programadores), aplicación de escritorio (la recomendada para no técnicos) y navegador (versión limitada). La versión de escritorio permite gestionar carpetas de trabajo de manera intuitiva, mientras que mediante MCP (Model Context Protocol) se puede conectar con fuentes de datos externas como sistemas de incidencias o correo electrónico, ampliando significativamente el alcance de la herramienta.

#### Implicaciones para la productividad profesional

El autor enfatiza que la herramienta no solo automatiza tareas tediosas sino que cambia fundamentalmente la relación del gestor con los datos. Lo que antes requería horas de trabajo manual — síntesis de documentos, extracción de información, cruce de datos — ahora se resuelve con instrucciones en lenguaje natural. La barrera técnica desaparece, permitiendo que cualquier profesional pueda crear informes, dashboards y análisis que antes requerían equipos especializados.

#### Origen y contexto del proyecto

Claude Code nació de una anécdota: su creador, Boris Cherry, desarrolló una pequeña aplicación local para entender cómo funcionaba la API de Anthropic. Al conectarle IA, le preguntó qué música estaba escuchando y la herramienta, usando utilidades del sistema operativo, fue capaz de responder. Este momento fundacional ilustra la filosofía del producto: una IA que opera directamente sobre el entorno del usuario, comprendiendo y manipulando su contexto local.

### 🔗 Referencias
- 📄 Paper: https://www.anthropic.com/research/claude-code-expertise
- 📄 Paper: https://arxiv.org/abs/2507.09089
- 🔗 Artículo/Web: https://metr.org/blog/2026-02-24-uplift-update
- 🔗 Artículo/Web: https://javiergarzas.com/diccionario-de-la-ia-javier-garzas

---

## [Javier Garzás] La Agilidad se está quedando sin empleos: primero el Scrum Master, ¿luego tú?
**Fecha:** 2026-07-22
**URL:** https://www.youtube.com/watch?v=BLTWGaI5HgY
**Video ID:** BLTWGaI5HgY

### 📝 Resumen

Javier Garzás analiza la progresiva desaparición del rol de Scrum Master como puesto dedicado en las organizaciones, respaldado con datos del mercado laboral, y ofrece consejos para quienes trabajan en gestión de productos y proyectos digitales.

#### Los 5 datos que confirman la tendencia

Garzás presenta cinco evidencias: (1) las ofertas de Scrum Master han caído un 67% en tres años, de 15.000 a menos de 5.000; (2) los equipos con Scrum Master dedicado pasaron del 54% (2020) al 37% (2025); (3) la formación en Scrum se ha desplomado — formadores de referencia reportan caídas de alumnos del 49% a menos del 5%; (4) los salarios de Scrum Master llevan años congelados mientras los de Product Manager han subido entre un 8 y un 12%; (5) empresas como Capital One eliminaron 1.100 puestos de su "familia ágil" en 2023, recolocando a los profesionales en otros roles.

#### Cinco causas de fondo

La primera causa es que la IA ha reducido drásticamente el tamaño de los equipos — Gartner predice que para 2029 el 60% de las organizaciones trabajará con equipos de 2-3 personas (tiny teams), reduciendo la necesidad de coordinación. La segunda es que el delivery se ha simplificado: lo que antes llevaba días ahora se hace en horas con nocode e IA. La tercera es la burbuja de certificaciones: empresas que querían "vestirse de ágiles" contrataron Scrum Masters certificados en masa sin formación real. La cuarta, derivada, es la proliferación de Scrum Masters sin conocimientos técnicos que no podían entender a sus equipos. La quinta causa, la más profunda, es la madurez del sector usando el concepto japonés **Shu-Ha-Ri**: las organizaciones ya han superado la fase de imitación (Shu) y están en las fases de adaptación (Ha) e innovación (Ri), por lo que ya no necesitan tutores de agilidad.

#### Consejos para quien trabaja en el sector digital

Garzás recomienda tres movimientos estratégicos: (1) abandonar la etiqueta de "Scrum Master" y moverse hacia roles como Delivery Manager o Product Manager; (2) desarrollar habilidades técnicas aprovechando que la IA permite a no-programadores crear soluciones (BYY coding, MCPs, automatizaciones); (3) moverse hacia el Discovery — la fase de identificar problemas y necesidades del usuario — que ha ganado protagonismo frente a un Delivery cada vez más automatizado.

#### La agilidad no ha muerto

El autor aclara que Scrum como framework se está diluyendo, pero el mindset ágil — trabajar por incrementos, aceptar el cambio, experimentar — es más necesario que nunca ante la adopción masiva y desordenada de IA. Advierte contra el "FOMO digital" que está llevando a muchas empresas a automatizar sin método, repitiendo errores del antiguo modelo en cascada.

### 🔗 Referencias
- 📄 Artículo/Web: https://www.birjob.com/blog/scrum-master-agile-coach-disappearing
- 📄 Artículo/Web: https://age-of-product.com/scrum-master-decline/
- 📄 Artículo/Web: https://www.bankingdive.com/news/capital-one-cuts-1100-tech-jobs-agile/640861/
- 📄 Artículo/Web: https://www.theregister.com/2023/01/20/capital_one/
- 📄 Artículo/Web: https://www.gartner.com/en/newsroom/press-releases/2026-07-07-gartner-predicts-60-percent-of-organizations-will-adopt-smaller-software-engineering-teams-by-2029
- 📄 Artículo/Web: https://fortune.com/2025/09/19/surviving-great-flattening-coming-extinction-of-middle-manager-layoffs/
- 📄 Artículo/Web: https://www.fastcompany.com/91548285/everyone-wants-to-kill-the-middle-manager-role-the-data-says-dont-do-it

---

## [Javier Garzás] Si solo usas ChatGPT o Copilot, estás muy lejos de trabajar productivamente con IA
**Fecha:** 2026-07-19
**URL:** https://www.youtube.com/watch?v=Kdf7JZk8J0Q
**Video ID:** Kdf7JZk8J0Q

### 📝 Resumen

Javier Garzás presenta una hoja de ruta práctica de cinco niveles de madurez en adopción de inteligencia artificial generativa, basada en su experiencia con proyectos profesionales reales. El vídeo parte de una constatación clave: la mayoría de usuarios y empresas creen que usar IA equivale a usar un chatbot, cuando en realidad existe un espectro mucho más amplio de capacidades que va desde el uso amateur hasta los agentes autónomos especializados. Garzás adapta el modelo de madurez de CoinTelligence (Molit) para crear una guía que permite a profesionales y equipos identificar en qué nivel se encuentran y cuál es el siguiente paso lógico en su evolución.

#### Nivel 1: Uso básico y amateur — el chatbot aumentado

El escalón más básico, donde se encuentra la gran mayoría de usuarios. Se caracteriza por el uso de la IA como un mero buscador mejorado: redactar correos, generar imágenes con herramientas como DALL-E o Midjourney, crear presentaciones con Gamma, o usar navegadores aumentados como Comet. En este nivel no hay integración profunda ni mejora real de procesos. Garzás advierte que quedarse aquí es el error más común, ya que se desaprovecha todo el potencial transformador de la tecnología.

#### Nivel 2: Asistente profesional — prompt engineering y contexto

Aquí la IA se utiliza como asistente profesional con técnicas avanzadas de prompting. Incluye la creación de bibliotecas de prompts como activos organizacionales, el uso de MCP (Model Context Protocol) para conectar chatbots con herramientas externas como CRMs o gestores documentales, y la ingeniería de contexto —dotar a los prompts de información específica de la organización. Garzás menciona los GPTs (ChatGPT), proyectos (Claude) y gemas (Gemini) como soluciones que permiten gestionar este contexto sin necesidad de conocimientos técnicos avanzados.

#### Nivel 3: Automatización de procesos — vibe coding y RAG

El salto cualitativo llega cuando el equipo es capaz de crear pequeñas aplicaciones operativas internas mediante técnicas de vibe coding (sin necesidad de conocimientos técnicos). Garzás menciona Antigravity como herramienta para generar miniapps que resuelven problemas del día a día —como la generación masiva de certificados— que antes se hacían manualmente o simplemente no se hacían. También incluye workflows automatizados con herramientas como n8n o Make, añadiendo nodos de IA en procesos de facturación, CRM o bases de datos. Se introduce el RAG (Retrieval-Augmented Generation) como evolución de la ingeniería de contexto para conectar la IA a documentos, PDFs y bases de datos dinámicas.

#### Nivel 4: Mejora del ciclo de vida del producto

En este nivel la IA se aplica a mejorar el producto o servicio que la organización ofrece a usuarios reales. Garzás destaca tres aplicaciones principales: la mejora del Discovery (analizar mercados, usuarios y oportunidades con búsquedas profundas), el prototipado funcional con herramientas como Lovable (que permite crear prototipos operativos en lugar de PowerPoints estáticos), y el procesamiento masivo de información con herramientas como NotebookLM para sintetizar tendencias a partir de miles de documentos. También incluye el uso de IA en testing, validación y desarrollo aumentado.

#### Nivel 5: Agentes especializados — la IA actúa sola

El nivel más avanzado, donde la IA opera con alta autonomía aunque siempre bajo supervisión humana. Garzás describe agentes especializados por dominio (ventas, captación, seguimiento comercial) y workspaces de IA como Claude Cowork y OpenClaw, que se instalan 24/7 en el ordenador del usuario. Estos agentes pueden ejecutar tareas programadas a cualquier hora (por ejemplo, revisar correos a las 3 de la madrugada), operar el navegador de forma autónoma, y disparar workflows sin intervención directa. Garzás recomienda periodificar tareas en horas de baja demanda para optimizar el consumo de tokens.

### 🔗 Referencias
- 💬 Comunidad WhatsApp: https://api.whatsapp.com/send/?phone=34684724916&text=Hola%2C+quiero+unirme+a+la+comunidad&type=phone_number&app_absent=0
- 🔗 Artículo/Web: https://www.javiergarzas.com
- 💼 LinkedIn: https://www.linkedin.com/in/jgarzas/
---

## [Javier Garzás] Deja de usar ChatGPT o Claude y dirige agentes que trabajen mientras duermes
**Fecha:** 2026-07-15
**URL:** https://www.youtube.com/watch?v=YMbLelcaqHI
**Video ID:** YMbLelcaqHI

### 📝 Resumen

Javier Garzás, con más de 20 años en liderazgo de equipos de software, explica cómo la mayoría de los usuarios paga suscripciones de IA pero sigue usando únicamente el modo chat tradicional (reactivo), desaprovechando la capacidad de agentes autónomos que pueden trabajar mientras ellos descansan. El vídeo presenta una demo real en Claude (Anthropic) de un agente que prepara el daily de cada madrugada —el "233 Daily"— y muestra los 3 pasos esenciales para que cualquier persona sin conocimientos técnicos pueda montar su propio equipo de agentes.

#### Chat reactivo vs. modo agente proactivo

Garzás distingue dos formas de usar la IA que marcan una diferencia radical en productividad:

- **Modo chat tradicional (reactivo)**: el usuario pregunta, la IA responde, y se genera un "pimponeo" constante de ida y vuelta. Es el uso más común pero el menos eficiente.
- **Modo agente (proactivo)**: se le da un objetivo al agente y este se busca la vida para resolverlo de forma autónoma, tomando decisiones sin supervisión constante.

#### Paso 1: Empaquetar — escribir la receta una vez

El primer paso consiste en crear una **rutina** en Claude (sección Code → Rutinas). Se redacta una instrucción clara en lenguaje natural ("en cristiano") que define qué debe hacer el agente, con qué criterios y qué formato de salida debe generar.

#### Paso 2: Encargárselo — darle las manos con conectores MCP

El agente necesita acceso a las herramientas para poder trabajar mediante **conectores MCP** (Model Context Protocol): Google Drive, Gmail, Google Calendar y Notion.

#### Paso 3: Ponerle despertador — ejecución programada

Garzás recomienda lanzar los agentes a las **3 de la madrugada**. Cuando el equipo llega por la mañana, el backlog está priorizado, las alertas preparadas y los correos importantes resumidos.

#### Equivalente en ChatGPT: tareas programadas

- **Claude** → Rutinas / **ChatGPT** → Tareas programadas / **Gemini** → Acciones programadas

#### Reflexión final / Conclusiones

Garzás lanza una pregunta provocadora: "¿Trabaja la IA por ti mientras duermes?" Montar un agente básico no requiere conocimientos técnicos y puede hacerse en minutos.

---

### 🔗 Referencias

- 🔗 Rutinas de Claude: https://claude.ai (Code → Rutinas)
- 🔗 Tareas programadas ChatGPT: https://chatgpt.com (Programadas)
- 🔗 IA-Skills: https://youtu.be/v95f4EL8_nQ

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

## [Javier Garzás] ¿Es el fin de Jira y Notion? La IA cambia las reglas
**Fecha:** 2026-06-24
**URL:** https://www.youtube.com/watch?v=kuN1cwb6P50
**Video ID:** kuN1cwb6P50

### 📝 Resumen

Javier Garzás analiza el momento crítico que atraviesa la industria del software de gestión empresarial —el llamado "SaaS Apocalipsis"— donde Atlassian (dueños de Jira) acaba de firmar uno de sus peores años bursátiles, mientras herramientas de infraestructura "viejunas" como Supabase, Drupal y WordPress resurgen con fuerza gracias a la inteligencia artificial. El vídeo explica por qué la IA, y en concreto el protocolo MCP (Model Context Protocol), está cambiando radicalmente la forma en que los profesionales interactúan con sus herramientas de gestión, y por qué los fabricantes tradicionales están perdiendo el control de sus propias interfaces.

#### El SaaS Apocalipsis — el declive de las herramientas de gestión tradicionales

Garzás introduce el concepto de "SaaS Apocalipsis" para describir el pánico en el sector del software de gestión como servicio. Herramientas como Jira, Notion, Monday, los CRMs y los gestores documentales están viendo caer su valoración y uso. La causa: la IA está permitiendo a los usuarios saltarse las interfaces tradicionales y acceder directamente a los datos a través de chatbots.

- **Atlassian en caída**: la empresa dueña de Jira y Confluence ha firmado uno de sus peores años en bolsa. Wall Street se pregunta abiertamente si la IA va a "matar" su negocio.
- **La paradoja**: mientras caen las herramientas de gestión, resucitan herramientas "viejunas" de infraestructura como Drupal (CMS de los años 2000), WordPress y Supabase. Garzás relata cómo en la IA Summit de Londres 2026 se encontró con un stand de Drupal patrocinando el evento — algo impensable hace dos años.
- **Goldman Sachs lo confirma**: el banco de inversión ha señalado a Supabase y otras herramientas de infraestructura como las grandes ganadoras de la nueva economía digital impulsada por IA. Supabase acaba de levantar 500 millones de dólares.

#### MCP — el protocolo que lo cambió todo

El **Model Context Protocol (MCP)** es, según Garzás, la tecnología que ha cambiado para siempre la forma de trabajar con herramientas de gestión. Permite que los chatbots de IA (ChatGPT, Claude, Gemini) lean y escriban directamente en múltiples herramientas de gestión simultáneamente, sin necesidad de copy-paste ni configuraciones complejas.

- **Antes del MCP**: los profesionales vivían en dos mundos separados — las herramientas de gestión (Jira, Notion, email, calendario) por un lado, y los chatbots de IA por otro. Para usar la IA, había que extraer datos manualmente de las herramientas, pasarlos al chatbot, y luego llevar el resultado de vuelta.
- **Con el MCP**: desde un solo chatbot se puede leer un ticket de Jira, extraer datos de Notion, escribir en Google Calendar, y enviar un email — todo mediante prompts en lenguaje natural y sin cambiar de interfaz.
- **Mezcla de datos**: la capacidad más poderosa del MCP es poder combinar datos de diferentes herramientas en un mismo prompt. Por ejemplo, extraer una tarea de un tablero Kanban en Notion, procesarla con una técnica de priorización, y llevarla como evento a Google Calendar.
- **Eliminación del coste de aprendizaje**: al operar a través del chatbot vía MCP, el usuario ya no necesita aprender la interfaz de cada herramienta ni sus actualizaciones periódicas. El "front-end" de todo es el chatbot.

#### El cambio de comportamiento — del acceso directo al acceso vía chatbot

Garzás revela una regla interna que él y su equipo se han autoimpuesto: **"si puedo hacerlo mediante un chatbot, no voy a la herramienta"**. Ir directamente a la interfaz de Jira, Notion o Google Calendar es considerado "viejuno" e ineficiente.

- **Ejemplo con Google Calendar**: programar un evento recurrente en Google Calendar requiere navegar menús, fechas y configuraciones. En cambio, desde un chatbot se puede pedir en lenguaje natural, y el MCP se encarga de la ejecución. Además, el prompt puede incluir inteligencia adicional (ej: "sabes que los martes no te conviene, ponlo en miércoles").
- **Creación de interfaces propias**: Garzás va más allá: no solo se accede a las herramientas vía chatbot, sino que ahora cualquier profesional sin conocimientos técnicos puede crearse sus propias interfaces personalizadas usando herramientas como Lovable, los artefactos de Claude, o incluso WordPress y Drupal. Si las vistas que ofrece el fabricante no son suficientes, el usuario puede construir las suyas.
- **La limitación de las IAs integradas en las herramientas**: Garzás critica a fabricantes como Atlassian y Notion por incorporar funcionalidades de IA limitadas a su propio ecosistema. "La IA de Atlassian solo ve datos de Atlassian", explica. Esto es una "limitación brutal" comparada con lo que permite un chatbot conectado vía MCP a múltiples fuentes simultáneamente.

#### Herramientas de infraestructura — el resurgimiento de lo "viejuno"

Mientras las herramientas de gestión caen, las herramientas de infraestructura están viviendo una segunda edad de oro. Garzás explica la razón: cuando un perfil no técnico crea pequeñas aplicaciones con IA (vibe coding), necesita **dónde guardar los datos y dónde visualizarlos**.

- **Supabase**: base de datos que ha resurgido como solución para que no-técnicos almacenen los resultados de sus aplicaciones creadas con IA. Acaba de levantar 500 millones de dólares.
- **Drupal y WordPress**: gestores de contenido clásicos que ahora se posicionan como "herramientas de infraestructura" para los desarrollos que personas no técnicas están haciendo para resolver sus problemas particulares.
- **El nicho olvidado**: Garzás recalca que estas aplicaciones no son software "liberable a producción para miles de usuarios", sino pequeñas soluciones para problemas específicos — y ahí está la clave que mucha gente no está viendo.
- **Ejemplos prácticos**: Garzás y su equipo han creado CRMs pequeños para necesidades específicas, generadores de diplomas formativos, y "centenares de pequeñas aplicaciones, automatizaciones y agentes" que resuelven problemas que antes eran manuales o simplemente no se hacían.

#### Una IA entrenada con 20 años de material formativo

Garzás comparte un proyecto personal ambicioso: está entrenando una IA con todos los materiales que ha generado en más de 20 años de carrera, incluyendo más de 100.000 alumnos formados, tableros de Miro, dibujos, y contenido formativo. Esta IA será capaz de trasladar todo ese conocimiento acumulado a nuevas generaciones de gestores de producto.

#### Reflexión final / Conclusiones

Garzás es claro: las herramientas de gestión tradicionales no van a desaparecer porque siguen siendo necesarias como repositorios de datos, pero su época de esplendor ha pasado. El futuro está en acceder a esos datos a través de chatbots de IA vía MCP, saltándose las interfaces de los fabricantes y creando las propias cuando sea necesario. La recomendación para cualquier profesional del sector es adoptar una mentalidad "IA First": por defecto, ir primero al chatbot y solo entrar a las herramientas de gestión para temas puntuales. El que no adopte este cambio ahora, según Garzás, llegará tarde.

---

### 🔗 Referencias

- 🔗 Comunidad WhatsApp: https://javiergarzas.com/link-whatsapp-youtube-javier-garzas

## [Javier Garzás] La Gestión que conocías ya No existe: la era de los agentes de IA (Londres 2026)
**Fecha:** 2026-06-17
**URL:** https://www.youtube.com/watch?v=LgoxHel-Tas
**Video ID:** LgoxHel-Tas

### 📝 Resumen

Javier Garzás viajó a Londres para asistir a la **IA Summit 2026**, celebrada en el emblemático Tobacco Dock (un antiguo almacén de tabaco del siglo XIX reconvertido en centro de convenciones). Desde allí, comparte las cinco tendencias clave que observó en el evento, con un enfoque en cómo la inteligencia artificial está transformando la gestión de productos digitales y el rol del product manager. El mensaje central es contundente: quien gestiona ahora también construye, y la mayoría de profesionales todavía no lo ha asimilado.

#### El nuevo rol Builder — el gestor que construye con IA

La tendencia número uno que Garzás identificó en la cumbre es la emergencia de un nuevo perfil profesional, denominado indistintamente como **Builder**, **Platform** o **Creador**. Este rol no existía hasta hace un año y consiste en alguien que crea soluciones funcionales con IA sin necesidad de conocimientos técnicos profundos de programación. Las grandes empresas presentes (Nvidia, Google, IBM) validaron esta tendencia: se busca a alguien que conozca todas las herramientas, arquitecturas y formas de crear con IA para acelerar productos y procesos.

- Este perfil rompe las fronteras entre los roles tradicionales de product manager, diseñador y gestor.
- La clave habilitante: la IA permite crear sin conocimientos técnicos avanzados.
- Garzás destaca que los perfiles más valorados hoy son los **"extécnicos"** — profesionales que fueron programadores, dejaron la técnica por la gestión, y ahora vuelven a crear porque la barrera ha caído drásticamente.

#### El SaaS Apocalipsis — las herramientas de gestión tradicionales caen

Garzás observó una paradoja en los stands de los patrocinadores: mientras herramientas modernas de gestión como Notion o CRMs brillaban por su ausencia, tecnologías legacy como **Drupal** (un CMS de los años 2000) estaban presentes. Esto refleja una tendencia profunda: las herramientas SaaS de gestión se están quedando como meros **repositorios de datos**, mientras que los profesionales construyen su propia capa de integración con IA por encima.

- Las herramientas de gestión tradicionales (Notion, Mailchimp, gestores de clientes) se convierten en repositorios legacy de los que se extraen datos, pero ya no se usan para visualizar o gestionar.
- Emergen hacia arriba las empresas nativas de IA y las plataformas de infraestructura (Supabase, etc.).
- Las empresas de gestión "de medio" están en una posición peligrosa: demasiado específicas para sobrevivir como plataformas, pero no lo suficientemente útiles como herramientas autónomas.
- La capacidad de cualquiera de crear sus propias soluciones con IA acelera esta tendencia: pequeñas aplicaciones que cruzan bases de datos y generan informes reemplazan suscripciones costosas.

#### La productividad real vs. el mito del profesional 10x

Una de las ponencias principales sacó a relucir el libro **"Peopleware"** de Tom DeMarco (años 80), generando un debate sobre si realmente estamos siendo más productivos con IA. La tesis principal: los modelos de trabajo legacy —reuniones, cambios de contexto, cargas cognitivas disparadas— están frenando el potencial que la IA ofrece.

- El cambio de contexto y las interrupciones constantes son el mayor lastre para la productividad real.
- Las metodologías tradicionales (Scrum, marcos de trabajo antiguos) se han quedado obsoletas en el nuevo paradigma.
- La carga cognitiva es un límite humano fundamental: aunque los agentes trabajen en paralelo, el humano solo puede gestionar un número finito de estímulos.
- Emerge la necesidad de refactorizar los modelos de trabajo para eliminar fricción, no solo añadir IA.

#### El fin de las especificaciones escritas — prototipar es la nueva especificación

Garzás observó una práctica recurrente entre los ponentes: en lugar de describir lo que querían construir con diapositivas, directamente abrían herramientas como **Claude Code** y creaban prototipos funcionales en tiempo real. Un ponente construyó una web de recomendación de vinos en directo frente a cientos de asistentes, conectando MCPs, skills y usando incluso **HeyGen** (generación de avatares) y ElevenLabs para clonar su voz.

- La especificación de requisitos tradicional está muerta; las historias de usuario están en "congelación evolutiva".
- El principio clave: **"Enséñamelo, no me lo describas"** — un prototipo funcionando vale más que mil palabras en un documento.
- Las zonas de patrocinadores confirmaron esta tendencia: la mayoría de stands ofrecían herramientas para capacitar a los profesionales a crear prototipos, no a escribir especificaciones.

#### Controlar la fauna de agentes — la ingeniería del arnés

La quinta tendencia, y la más avanzada, aborda cómo controlar la diversidad de agentes de IA que los profesionales están desplegando. Garzás distingue entre workflows agénticos (que ya están muertos como tendencia) y **agentes autónomos** (IA a la que no hay que decirle paso a paso lo que hacer), que ya es un tema maduro.

- Las organizaciones tienen múltiples agentes trabajando: unos inspeccionan mercados, otros revisan tendencias en emails, otros cruzan datos.
- Garzás introduce el concepto de **"ingeniería del arnés"** (harness engineering): igual que un arnés de escalada protege de una caída, se necesitan sistemas que controlen a los agentes, que pongan carriles a la IA para que no se desvíe.
- Hace un año se hablaba de workflows con nodos que llamaban a un LLM — eso ha desaparecido. Ahora se habla de cómo gestionar la fauna heterogénea de agentes.

#### Reflexión final / Conclusiones

Garzás cierra con un mensaje urgente: el ritmo de cambio es tan rápido que lo que era tendencia el año pasado ya está obsoleto hoy. Recomienda subirse al carro cuanto antes, crear una rutina de aprendizaje constante (como ir al gimnasio cada día) y unirse a comunidades para no ir solo. Invita a su grupo gratuito de WhatsApp donde comparte aprendizajes de forma más ligera y frecuente. La gestión digital ha cambiado para siempre: quien gestiona ahora construye, y la mayoría todavía no lo sabe.

---

### 🔗 Referencias

- 🔗 WhatsApp: https://chat.whatsapp.com/J1h3GHHs3lf8HkaoMGDhRF

## [Javier Garzás] Ya no gestionas, ahora tú también construyes con IA (y la mayoría no lo sabe)
**Fecha:** 2026-06-11
**URL:** https://www.youtube.com/watch?v=Zklb5vmFnOU
**Video ID:** Zklb5vmFnOU

### 📝 Resumen
No se pudo obtener la transcripción para este video.

### 🔗 Referencias
- 🔗 Artículo: https://chat.whatsapp.com/J1h3GHHs3lf8HkaoMGDhRF

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
