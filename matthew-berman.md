# 📹 Resúmenes — Matthew Berman

Generado automáticamente.
==================================================


## [Matthew Berman] MYTHOS is LIVE!!!! — Análisis completo de Claude Fable 5
**Fecha:** 2026-06-09
**URL:** https://www.youtube.com/watch?v=e-4xG1U7M70
**Video ID:** e-4xG1U7M70

### 📝 Resumen

Anthropic lanzó oficialmente Mythos 5, su modelo más esperado, bajo la forma de **Claude Fable 5** — una versión con salvaguardas de seguridad del modelo Mythos original. Matthew Berman realizó una transmisión en vivo de casi dos horas donde probó el modelo en profundidad, mostró benchmarks, compartió sus impresiones tras una semana de uso temprano y ejecutó demos en vivo de generación de código, simulaciones físicas y creación de video. El modelo, con aproximadamente **10 billones de parámetros**, representa un salto generacional significativo respecto a Claude Opus 4.8 y GPT 5.5, aunque con un costo elevado y algunas peculiaridades notables.

#### Mythos y Fable: dos caras del mismo modelo

Anthropic lanzó Mythos 5 en dos variantes. **Mythos 5** es la versión sin restricciones, entregada exclusivamente a la comunidad de seguridad informática para encontrar vulnerabilidades, bugs y zero-days. **Fable 5** es la misma arquitectura pero con guardrails de seguridad para uso general. El nombre "Fable" se suma a la familia Claude (Haiku, Sonnet, Opus) como el nuevo modelo frontera de la compañía.

- **Disponibilidad**: Fable 5 está accesible en Claude Desktop y Claude Co-work Desktop, pero no en Claude Code Desktop al momento de la transmisión (el despliegue se estaba realizando gradualmente).
- Los usuarios necesitan una suscripción Max (plan de 20x o superior) para acceder al modelo.

#### Resultados en benchmarks

Fable 5 muestra mejoras sustanciales frente a Claude Opus 4.8 y GPT 5.5 en prácticamente todos los benchmarks estándar:

- **SWEBench Pro**: 80% — frente al 69% de Opus 4.8 y 58% de GPT 5.5. Una mejora de 11 y 22 puntos porcentuales respectivamente.
- **Frontier Code Diamond**: 29.3% — más del doble que Opus 4.8 (14.5%) y casi 6 veces más que GPT 5.5 (5.7%).
- **GDP-Val** (benchmark de conocimiento general creado por OpenAI): 1,932 puntos — superando a Opus 4.8 (1,890) y GPT 5.5 (1,760).
- **Razonamiento espacial**: 38.6% — notable mejora frente al bajo rendimiento de Opus 4.8 en esta categoría.
- **Tool Use**: mejora de varios puntos porcentuales respecto a modelos anteriores.
- **Computer Use**: 85% — competitivo con GPT 5.5, aunque Berman señala que GPT 5.5 sigue siendo el mejor para uso en navegador.
- **Legal Agent Benchmark**: 13% — frente al 10% de Opus 4.8 y solo 2% de modelos anteriores.
- **Terminal Bench**: 83.4-88% — resultados sólidos para coding agentico.

Berman señala que, aunque los benchmarks muestran mejoras, la sensación real al usar el modelo es aún más impresionante que lo que los números sugieren.

#### Capacidades destacadas y comportamiento único

El modelo se siente fundamentalmente diferente a cualquier otro modelo que Berman haya probado:

- **Horizontes temporales largos**: Fable 5 puede trabajar de forma autónoma durante períodos prolongados sin perder coherencia. Ninguna tarea, por compleja que fuera, logró que el modelo se atascara.
- **Exploración profunda**: Incluso para tareas pequeñas, Fable 5 tiende a examinar todo el código base, considerar todos los ángulos posibles y ejecutar exploraciones exhaustivas.
- **Densidad informativa**: El output de Fable 5 es extremadamente denso en información, utilizando vocabulario complejo y descripciones detalladas que requieren una lectura más lenta y cuidadosa.
- **Eficiencia de tokens**: A pesar de su verbosidad, el modelo es más eficiente en tokens que modelos anteriores, transmitiendo más información por token.
- **Velocidad lenta**: El modelo es significativamente más lento que Opus 4.8 y GPT 5.5, generando aproximadamente 7,000 tokens en 2 minutos al inicio de las tareas.

#### Caso de uso real: Stripe y la migración de código de 50M de líneas

Stripe reportó durante las pruebas tempranas que Fable 5 logró comprimir **meses de trabajo de ingeniería en días** sobre una base de código Ruby de 50 millones de líneas. El modelo realizó una migración completa del código base en un día que, de otro modo, habría requerido un equipo completo durante más de dos meses. Berman destaca que, para tareas de esta envergadura, el precio de $50 por millón de tokens de salida resulta una ganga en comparación con el costo de mantener equipos de ingeniería.

#### Precios y estrategia de ruteo de modelos

El precio de Fable 5 es de **$10 por millón de tokens de entrada** y **$50 por millón de tokens de salida**. Berman considera que, aunque es caro, esperaba que fuera aún más costoso. Recomienda enfáticamente una estrategia de **model routing**: usar Fable 5 solo para las tareas más complejas y críticas, mientras que para el resto se deben usar modelos más económicos como Sonnet o Haiku.

- El costo es menos de la mitad que el del preview de Claude Mythos.
- Berman advierte que ya se están viendo empresas con facturas extremadamente altas de Anthropic y OpenAI, por lo que saber rutear tareas al modelo adecuado será una habilidad crucial.

#### Demos en vivo: simulaciones, cubos de Rubik y video generado por IA

Durante la transmisión, Berman ejecutó múltiples pruebas en vivo con resultados impresionantes:

- **Simulador de dinámica de fluidos**: Fable 5 creó desde cero un simulador interactivo con trazado de rayos, múltiples modos de visualización (presión, vorticidad, campo de velocidades) y efectos visuales avanzados. Fue calificado como "la mejor simulación de fluidos jamás creada por un modelo de IA".
- **Cubo de Rubik 3D**: El modelo generó un simulador de cubo Rubik completamente funcional con capacidades de rotación, mezcla y resolución automática, con gráficos realistas que incluyen reflejos y sombras.
- **Generación de video sin dirección**: Berman le pidió al modelo que creara un video "sin tema, sin dirección" y Fable 5 produjo un video musical completo con animación y banda sonora, aunque QuickTime se congeló al reproducirlo.
- **Simulador de ciudades (Sim City)**: Se ejecutó en Ultra Code con múltiples agentes en paralelo, aunque no había finalizado al momento de terminar la transmisión.

#### Sistemas de esfuerzo y modos de trabajo

Fable 5 introduce niveles de esfuerzo configurables: medium, high, max y un modo especial **Ultra Code** que despliega múltiples subagentes en paralelo mediante workflows dinámicos. Durante la demo, Berman logró que el modelo ejecutara **63 agentes en paralelo** usando el modo de workflows.

- El modelo también introdujo comandos como `/effort`, `/goal`, y `/workflows` para controlar su comportamiento.
- Berman experimentó dificultades técnicas para hacer funcionar los workflows dinámicos, pero eventualmente lograron activarse.

#### Reflexión final / Conclusiones

Claude Fable 5 representa un salto cualitativo en capacidades de IA, especialmente en tareas que requieren horizontes temporales largos y exploración profunda de código. Sin embargo, su lentitud, alto costo y la necesidad de planes de suscripción específicos limitan su accesibilidad. Berman enfatiza que el futuro será un **mundo multimodelo** donde la clave estará en saber qué modelo usar para cada tarea, y Fable 5 está diseñado para ser el modelo "martillo nuclear" reservado para los problemas más difíciles. La información densa y el comportamiento exploratorio del modelo sugieren una nueva dirección en el desarrollo de IA, donde los modelos no solo responden preguntas, sino que emprenden investigaciones autónomas profundas.

---


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
