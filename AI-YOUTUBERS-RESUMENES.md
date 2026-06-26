# 📹 Resúmenes Diarios — IA YouTubers

---

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

