# 📹 Resúmenes — Matt Wolfe

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

