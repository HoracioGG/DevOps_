# DevOps
## 1. Principios de la Filosofía DevOps
La filosofía DevOps se basa en una serie de principios y prácticas diseñadas para integrar los equipos de desarrollo (Dev) y operaciones (Ops) en una sola entidad colaborativa. Este enfoque busca mejorar la entrega de software, optimizando el tiempo, los recursos, y aumentando la calidad. Los principales principios de DevOps incluyen:

1. **Integración Continua (CI)**:
La Integración Continua o Continuous Integration (CI) se refiere a la práctica de integrar los cambios de código en un repositorio compartido varias veces al día. Esta integración frecuente permite identificar problemas y conflictos de manera temprana. Cada vez que se integra el código, se ejecutan automáticamente una serie de pruebas para verificar que la nueva adición no haya causado errores.

2. **Entrega Continua (CD)**:
La Entrega Continua o Continuous Delivery (CD) es una extensión de la Integración Continua y se enfoca en tener el software siempre listo para ser desplegado en producción. Esto implica que cada cambio en el código pase por un proceso de pruebas, integración y entrega automatizado, asegurando que el código pueda lanzarse en cualquier momento.

3. **Infraestructura como Código (IaC)**:
La Infraestructura como Código o Infrastructure as Code (IaC) es un principio que se basa en gestionar y aprovisionar la infraestructura a través de archivos de configuración en lugar de procesos manuales. Esto permite que las configuraciones de servidores y entornos de desarrollo se mantengan en archivos de código, facilitando su reutilización y control de versiones.

4. **Monitorización y Logging**:
La Monitorización y Logging son prácticas fundamentales en DevOps para asegurarse de que todos los servicios y aplicaciones estén funcionando correctamente en tiempo real. La monitorización implica rastrear el desempeño de las aplicaciones y recursos, mientras que el logging (registro de eventos) permite guardar los datos generados en caso de fallos.

5. **Cultura Colaborativa DevOps**:
Uno de los principios fundamentales en DevOps es la cultura colaborativa. Esto implica la creación de un ambiente donde los equipos de desarrollo y operaciones trabajen juntos hacia objetivos comunes, compartiendo responsabilidades y conocimientos. La cultura colaborativa se basa en la confianza, la comunicación abierta y el respeto mutuo.

## 2. Herramientas Populares en Cada Fase de DevOps

| **FASE** | HERRAMIENTA | **FUNCIÓN** |
| :-: | :-: | :-: |
| Planificación | Jira | Gestión de proyectos y tareas; permite la planificación y asignación de tareas al equipo de desarrollo |
| Gestión de Código | Git | Sistema de control de versiones distribuido, que permite a los desarrolladores trabajar en paralelo en el código sin conflictos |
| Automatización de Pruebas | Selenium | Herramienta de automatización para pruebas de aplicaciones web, que permite ejecutar pruebas de regresión y garantizar la calidad |
| Integración y Entrega Continua | Jenkins, GitLab CI/CD | Jenkins permite la integración y entrega continua mediante la ejecución automática de pruebas e integraciones cada vez que se produce un cambio en el código |
| Gestión de Configuración | Ansible, Chef | Herramientas de gestión de configuración que permiten definir, gestionar y mantener la infraestructura de manera automatizada a través de scripts |
| Monitorizació | Prometheus, Nagios | Prometheus recolecta métricas en tiempo real para monitorización, mientras que Nagios permite la vigilancia continua de sistemas, redes y aplicaciones |
| Contenedores y Orquestación | Docker, Kubernetes | Docker crea contenedores que aislan aplicaciones, mientras que Kubernetes gestiona y coordina contenedores a gran escala |


## **3. Ejemplos de Implementación DevOps y Beneficios Obtenidos**
### *Caso 1: Netflix*

Tecnologías utilizadas: Netflix emplea herramientas como Spinnaker para la entrega continua y Docker y Kubernetes para la contenedorización y orquestación. Utilizan Chaos Monkey para la prueba de resiliencia de sus sistemas.

***Beneficios:***
Netflix ha mejorado la confiabilidad y velocidad en sus despliegues de producción.
Reducción de errores y tiempos de inactividad mediante pruebas automatizadas y entrega continua.

### *Caso 2: Amazon*

Tecnologías utilizadas: Amazon usa herramientas de CI/CD internas y también Jenkins y AWS CodePipeline. También emplea Infrastructure as Code mediante AWS CloudFormation.

***Beneficios:***
Amazon ha logrado optimizar sus procesos de desarrollo y despliegue, permitiendo implementaciones de código cada 11.6 segundos.
Mayor flexibilidad para introducir cambios y responder a las necesidades del cliente.

### *Caso 3: Etsy*

Tecnologías utilizadas: Etsy utiliza Jenkins para CI/CD y Docker para contenedores, así como herramientas de monitorización como Nagios y Grafana.

***Beneficios:***
Etsy ha logrado reducir significativamente sus tiempos de despliegue y ha mejorado la calidad del código.
Mayor satisfacción de sus desarrolladores y menos tiempo de inactividad en sus aplicaciones.
