# Ingeniería de Sistemas Agénticos en 2026

Guía de arquitectura end-to-end para construir sistemas agénticos que funcionen en producción. No es un tutorial ni un framework: son patrones, trade-offs y decisiones que separan demos de sistemas que escalan.

---

## Qué hay en este repo

**[agent-systems-guide-jan2026.md](./agent-systems-guide-jan2026.md)** — Documento técnico (~1.400 líneas) que cubre:

| Sección | Contenido |
|--------|-----------|
| **Fundamentos** | Definición operacional de agente, workflows vs agents, capacidades core (planning, memory, tools, self-eval) |
| **Arquitecturas** | Single-agent, multi-agent (orchestrator-worker), hierarchical; cuándo usar cada una |
| **Patrones** | Augmented LLM, prompt chaining, routing, parallelization, evaluator-optimizer |
| **Infraestructura** | Stack real (models, MCP, memory, observability), frameworks en 2026 |
| **Memory** | RAG vs agentic RAG, arquitectura en capas, memory decay |
| **Evaluación** | Métricas que importan en producción, testing pyramid para agents |
| **Observability** | Tracing, Langfuse vs LangSmith, dashboard mínimo viable |
| **Deployment** | Kubernetes, autoscaling, seguridad (prompt injection, tool access, data leakage) |
| **Trade-offs** | Framework selection, memory strategy, single vs multi-agent |
| **Tendencias** | MCP, SLMs fine-tuned, world models, agentic browsers |

Incluye diagramas Mermaid, referencias a producción (LinkedIn SQL Bot, Replit Agent, Elastic, Rexera) y fuentes actualizadas a enero 2026.

---

## Para quién es

- **Sí:** Ingenieros de IA/ML que diseñan o mantienen sistemas agénticos en producción (o van a hacerlo).
- **Sí:** Tech leads y arquitectos que necesitan criterio para elegir patrones, frameworks y métricas.
- **No:** Introducción a LLMs, teoría de agentes académica o ejemplos tipo "hello world".

---

## Cómo leerlo

El documento está en Markdown con Mermaid. Para ver los diagramas correctamente:

- **GitHub:** los renderiza nativo en [agent-systems-guide-jan2026.md](./agent-systems-guide-jan2026.md).
- **Local:** cualquier editor con soporte Mermaid (VS Code con extensión, Obsidian, etc.) o exportar a PDF/HTML con [Mermaid Live Editor](https://mermaid.live).

---

## Autor y contacto

**Ignacio Zúñiga Navarro** — AI Engineer @ [factor.com.ar](https://factor.com.ar)

- [LinkedIn](https://www.linkedin.com/in/ignaciozuniganavarro/)
- [GitHub @ign24](https://github.com/ign24)

Correcciones, sugerencias o preguntas: abrí un [issue](https://github.com/ign24/agents/issues) o un PR.

---

## Licencia

El contenido de esta guía está bajo [MIT](./LICENSE). Podés usar, compartir y adaptar el material con atribución. Si te resultó útil, darle una ⭐ al repo o compartirlo con tu equipo ayuda a que llegue a más gente.

---

*Última actualización del documento: Enero 2026.*
