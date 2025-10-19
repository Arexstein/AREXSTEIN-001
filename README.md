/*
# The Architect's Codex: A 6-Week Bootcamp

Este no es un simple repositorio de apuntes. Es un plan de entrenamiento intensivo diseñado para forjar arquitectos de software. El objetivo es simple: pasar de los fundamentos a la estrategia avanzada en seis semanas de trabajo disciplinado.

La teoría sin práctica es inútil. Cada concepto se acompaña de un desafío tangible. Prepárate para escribir código, diseñar sistemas y justificar cada una de tus decisiones.

---

## La Hoja de Ruta

El plan está dividido en tres fases. Cada una construye sobre la anterior, creando una base de conocimiento robusta y coherente.

### Fase 1: Cimientos Sólidos (Semanas 1-2)
**Objetivo:** Internalizar los principios y patrones que definen el software de calidad. Esta base no es negociable.

#### **Semana 1: Principios y Patrones Fundamentales**

* **Día 1: Principios SOLID (S, O, L)**
    * **Teoría:** Estudio de Responsabilidad Única (SRP), Abierto/Cerrado (OCP) y Sustitución de Liskov (LSP). Profundiza más allá de la definición con ejemplos de código que violen y cumplan cada principio.
    * **Práctica:** Desarrolla una aplicación de consola que viole intencionadamente estos tres principios. Luego, refactorízala para cumplirlos. Compara ambas versiones en Git.

* **Día 2: Principios SOLID (I, D) y GRASP**
    * **Teoría:** Domina la Segregación de Interfaces (ISP) y la Inversión de Dependencias (DIP). Investiga los patrones GRASP (Experto, Creador, Alta Cohesión, Bajo Acoplamiento).
    * **Práctica:** Sobre la aplicación anterior, aplica ISP y utiliza Inyección de Dependencias para cumplir con DIP. Documenta cómo se logra la Alta Cohesión.

* **Día 3: Patrones de Diseño GoF (Creacionales)**
    * **Teoría:** Estudio de Factory Method, Abstract Factory, Singleton y Builder.
    * **Práctica:** Implementa cada patrón. Usa un Factory para conexiones a BBDD, un Builder para un objeto de configuración complejo y un Singleton para un servicio de logging.

* **Día 4: Patrones de Diseño GoF (Estructurales)**
    * **Teoría:** Estudio de Adapter, Decorator, Facade y Proxy.
    * **Práctica:** Crea un Adapter para una API externa, un Decorator para añadir caché a un repositorio y una Facade para simplificar un subsistema de notificaciones.

* **Día 5: Patrones de Diseño GoF (Comportamiento)**
    * **Teoría:** Estudio de Strategy, Observer y Command.
    * **Práctica:** Implementa Strategy para métodos de pago, Observer para actualizaciones de UI y Command para encapsular acciones de usuario.

* **Día 6: Refactorización y Consolidación**
    * **Práctica:** Toma un proyecto antiguo. Dedica cuatro horas a refactorizarlo aplicando un mínimo de cinco principios o patrones aprendidos. Documenta cada cambio con un commit descriptivo.

* **Día 7: Descanso y Repaso Activo**
    * Crea un mapa mental o una hoja de referencia que resuma los principios y patrones de la semana, el problema que resuelven y cuándo aplicarlos.

#### **Semana 2: Estilos Arquitectónicos y Comunicación**

* **Día 8: Arquitecturas Monolíticas y en Capas (N-Tier)**
    * **Teoría:** Análisis de los pros y contras de los monolitos y la arquitectura en capas (Presentación, Lógica, Datos).
    * **Práctica:** Dibuja el diagrama de una aplicación web estándar usando N-Tier y crea la estructura de directorios y clases base para cada capa.

* **Día 9: SOA y Microservicios**
    * **Teoría:** Evolución de SOA a microservicios. Estudio de conceptos clave de DDD como Bounded Context.
    * **Práctica:** Rediseña la aplicación anterior bajo una arquitectura de microservicios. Identifica los servicios y dibuja su comunicación.

* **Día 10: APIs y Comunicación Síncrona (REST y gRPC)**
    * **Teoría:** Principios de REST y comparación con gRPC/Protobuf.
    * **Práctica:** Crea dos microservicios que se comuniquen vía API REST. Define el contrato con OpenAPI/Swagger.

* **Día 11: Comunicación Asíncrona (Colas de Mensajes)**
    * **Teoría:** Rol del message broker, patrones Publish/Subscribe y Competing Consumers.
    * **Práctica:** Con Docker, levanta RabbitMQ o NATS. Modifica los microservicios del día anterior para que se comuniquen de forma asíncrona.

* **Día 12: Diseño de Bases de Datos (SQL vs. NoSQL)**
    * **Teoría:** Teorema CAP y casos de uso para bases de datos relacionales, documentales, clave-valor y de grafos.
    * **Práctica:** Diseña el esquema de BBDD para un E-commerce usando un modelo relacional (PostgreSQL) y uno documental (MongoDB). Justifica las diferencias.

* **Día 13: Diseño de Sistema (Caso Práctico)**
    * **Práctica:** Resuelve un problema de diseño de principio a fin, como "Diseña un acortador de URLs". Dibuja la arquitectura, justifica las decisiones tecnológicas e identifica cuellos de botella.

* **Día 14: Descanso y Repaso Activo**
    * Visualiza una charla de una conferencia de arquitectura de software (GOTO;, Martin Fowler) y resume los puntos clave.

### Fase 2: Sistemas Distribuidos y Resilientes (Semanas 3-4)
**Objetivo:** Diseñar sistemas que sobreviven a fallos, escalan bajo demanda y mantienen un rendimiento óptimo.

### Fase 3: Arquitectura Avanzada y Estrategia (Semanas 5-6)
**Objetivo:** Trascender el diseño técnico para dominar la estrategia arquitectónica, la toma de decisiones y los aspectos no funcionales críticos.

---

## Metodología de Trabajo

1.  **Fork, no solo clones.** Haz tuyo este repositorio. Úsalo para documentar tu progreso, subir tu código y guardar tus diagramas.
2.  **La disciplina es la clave.** Este plan solo funciona con dedicación. Comprométete con las horas de estudio y práctica.
3.  **Código, no solo diagramas.** La práctica es innegociable. La arquitectura que no se puede implementar es solo una fantasía.
4.  **Documenta tu razonamiento.** Usa este mismo README o Architecture Decision Records (ADRs) para justificar tus elecciones. El "porqué" es tan importante como el "qué".

---

## Contribuciones

Si encuentras formas de mejorar este plan, ya sea añadiendo recursos, aclarando conceptos o proponiendo mejores ejercicios prácticos, las contribuciones son bienvenidas. Abre un Pull Request para iniciar la discusión.

---

## Licencia

Este trabajo está disponible bajo la Licencia MIT.
*/