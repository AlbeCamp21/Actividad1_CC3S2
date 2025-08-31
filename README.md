# Actividad 1: introducción devops, devsecops

**Nombre:** Luis Alanya Campos - 20210290J

**Fecha y tiempo invertido:** 

**Contexto del entorno:** 

## Desarrollo de la Actividad 1

### 1. DevOps vs cascada tradicional (investigación + comparación)

**1.1.** DevOps vs Cascada

![devops_vs_cascada.png](imagenes/devops_vs_cascada.png)

La imagen ayuda a diferenciar (de manera visual y fácil) las dos metodologías: DevOps y Cascada.

En el caso de la metodología de la cascada, vemos como la retroalimentación se hace en el proceso final del proyecto, retrasando las mejoras que se pudo haber hecho en previas etapas.

En el caso de la metodología DevOps, la retroalimentación se realiza en cualquier fase, y se hacen hacía cualquier fase. Así, cualquier crítica que se quiera hacer será siempre escuchada, haciendo más eficiente la comunicación y fortaleciendo el trabajo en equipo.

**1.2.** Explica por qué DevOps acelera y reduce riesgo en software para la nube frente a cascada (feedback continuo, pequeños lotes, automatización)

La metodología DevOps permite acelerar y reducir los riesgos en el tema de desarrollo de software para la nube, esto debido a que se recibe feedback/retroalimentación de forma seguida, detectando los errores tempranamente y corrigiéndolos. También, se trabaja en lotes pequeños de cambios, haciendo más fácil la detección y solución de problemas sin ponen en riesgo todo el sistema.

En el tema de la automatización, según Redondo y Cárdenas (2022), la automatización de pruebas y despliegue (CI/CD) disminuye de igual manera los errores humanos y también hace que todos los procesos sean más rápidos, a comparación del método en cascada, método tradicional donde los cambios se revisan y entregan solamente en la parte final. 

**1.3.** **Pregunta retadora:** señala un **contexto real** donde un enfoque cercano a cascada sigue siendo razonable (por ejemplo, sistemas con certificaciones regulatorias estrictas o fuerte acoplamiento hardware). Expón **dos criterios verificables** y **los trade-offs** (velocidad vs. conformidad/seguridad).

Un contexto real podría ser el desarrollo de software para el área de la medicina (equipos médicos), por ejemplo una máquina de escaneo de rayos X. Para estos casos se necesitan de certificaciones de entes reguladoras, además de una documentación detallada.

Criterios verificables:
- El cumplimiento de normativas y certificaciones, en este caso, la certificación ISO para dispositivos médicos.
- Realización de documentación completa, además de mantener una trazabilidad de los cambios que se hagan.

Trade-offs:
- Velocidad: El proceso en estos casos son más lentos debido a que cada fase debe completarse y luego pasar por un proceso de validación antes de pasar a la siguiente fase.
- Conformidad/seguridad: Para este caso, se prioriza la seguridad y el cumplimiento de normas envés de la rapidez, con el fin de reducir riesgos

