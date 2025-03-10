# SkillSwap: Plataforma de Intercambio de Conocimientos

## Objetivo

El proyecto **SkillSwap** consiste en desarrollar una plataforma de intercambio de conocimientos, donde los usuarios pueden ofrecer tutorías en habilidades específicas (programación, diseño, idiomas, etc.) y, a cambio, recibir créditos que les permitan acceder a otras clases. La aplicación estará disponible en versiones web y móvil, facilitando la conexión entre usuarios interesados en aprender y enseñar.

El desarrollo de la plataforma se llevará a cabo cumpliendo con las normas **ISO de calidad** y estándares internacionales, con el objetivo de garantizar la eficiencia, seguridad, accesibilidad y sostenibilidad del sistema.

## Alcance

Desarrollar una plataforma digital innovadora que permita a personas intercambiar conocimientos y habilidades de manera accesible y equitativa. La plataforma está diseñada para fomentar el aprendizaje colaborativo, donde cada usuario puede actuar tanto como estudiante como instructor, generando una comunidad dinámica de enseñanza y aprendizaje. A través de un sistema basado en créditos, los usuarios pueden ofrecer tutorías en sus áreas de experiencia y, a cambio, obtener créditos para acceder a otras clases en temas de su interés. Esto elimina las barreras económicas del aprendizaje tradicional y promueve una cultura de intercambio de conocimientos sin necesidad de transacciones monetarias directas.

Además, SkillSwap busca aprovechar tecnologías avanzadas para mejorar la experiencia del usuario, incluyendo algoritmos de recomendación personalizados, integración con videollamadas y herramientas interactivas para la enseñanza en línea. La plataforma también incorpora un sistema de reputación y verificación de identidad para garantizar un entorno seguro y confiable para todos los participantes.

## SMART

**Específico:** Desarrollar y lanzar SkillSwap, una plataforma de intercambio de conocimientos, con las funcionalidades esenciales: sistema de créditos, tutorías, videollamadas y sistema de reputación. El objetivo es atraer a 10,000 usuarios activos y lograr una alta satisfacción del usuario, brindando una experiencia intuitiva y segura.

**Medible:** Lograr 10,000 usuarios activos registrados dentro de los primeros 6 meses. Obtener una tasa de satisfacción del 85% o superior en encuestas de usuarios. Asegurar que las funcionalidades clave (sistema de créditos y videollamadas) estén operativas desde el lanzamiento. Además, alcanzar un crecimiento del 30% mensual en la base de usuarios mediante estrategias de marketing digital y publicaciones en redes sociales.

**Alcanzable:** Utilizar un enfoque de desarrollo ágil, aplicar una estrategia de marketing digital bien definida (incluyendo la creación de contenido y publicidad en redes sociales), y asegurar la recopilación continua de feedback de los usuarios para mejorar el producto. Se aprovecharán herramientas como algoritmos de recomendación y videollamadas para mejorar la experiencia del usuario.

**Relevante:** Facilitar el acceso al aprendizaje colaborativo a nivel global, eliminando las barreras económicas mediante el sistema de créditos. Promover una cultura de intercambio de conocimientos sin necesidad de transacciones monetarias directas, apoyando el crecimiento personal y profesional de los usuarios.

**Tiempo:** Lanzar la plataforma en un plazo de 12 meses, con los resultados clave alcanzados. Durante los primeros 3 meses, se implementarán campañas de marketing en redes sociales (Facebook, Instagram, LinkedIn, Twitter), con el objetivo de generar al menos 50,000 interacciones (me gusta, comentarios, compartidos) en publicaciones clave, tanto en la fase de pre-lanzamiento como durante el lanzamiento.

## Definicion de Factibilidad
Estos estudios estiman la probabilidad de éxito en un emprendimiento y sirven para ajustar nuestras expectativas o llevar a cabo acciones correctivas para alcanzar las metas trazadas.

## Factibilidad

### Factibilidad Técnica y Económica para SkillSwap

#### **Factibilidad Técnica:**

##### **1. Infraestructura de Servidores:**
Se debe evaluar si los servidores actuales pueden manejar el tráfico esperado, ofreciendo la escalabilidad necesaria para adaptarse al crecimiento futuro de la plataforma. Además, se debe asegurar que los recursos de hardware sean suficientes para evitar caídas o problemas de rendimiento durante picos de tráfico.

##### **2. Integración de Sistemas:**
Una de las funcionalidades clave de la plataforma SkillSwap es la integración de sistemas como videoconferencias, gestión de créditos y herramientas interactivas de enseñanza. Será necesario analizar la capacidad de integrar estos sistemas de manera eficiente para ofrecer una experiencia fluida a los usuarios.

##### **3. Seguridad y Protección de Datos:**
El cumplimiento de las normativas de seguridad de la información es esencial para proteger los datos sensibles de los usuarios. SkillSwap debe implementar políticas robustas para garantizar la privacidad y la seguridad de la información que los usuarios compartan, incluidas las medidas de encriptación y autenticación.

#### **Factibilidad Económica:**

##### **1. Costos Iniciales:**
Es necesario estimar los costos iniciales para desarrollar la plataforma, lo que incluye gastos de diseño, programación, pruebas y lanzamiento. Es importante definir una estructura de costos que contemple la contratación de personal necesario, infraestructura tecnológica y otros recursos.

##### **2. Costos Operativos:**
Además de los costos iniciales, SkillSwap debe considerar los gastos recurrentes asociados con el mantenimiento y operación de la plataforma. Esto incluye los costos de servidores, actualizaciones, soporte técnico y la contratación de personal para la gestión continua del proyecto.

##### **3. Modelo de Ingresos:**
Para asegurar la rentabilidad de la plataforma, se debe definir el modelo de ingresos. SkillSwap puede generar ingresos a través de diferentes métodos como suscripciones, comisiones por transacciones o publicidad, o una combinación de estos. Cada uno de estos modelos tiene implicaciones diferentes en cuanto a flujo de ingresos y estrategias comerciales.

##### **4. Análisis de Rentabilidad:**
El análisis de rentabilidad permite proyectar los ingresos potenciales de la plataforma, comparar con los costos y calcular el retorno de inversión (ROI) esperado. Esto es crucial para determinar si el proyecto es financieramente viable y para definir el período de recuperación de la inversión.

# Framework a utilizar
##  ASP.NET Core 

### Justificación de la Elección de ASP.NET Core para SkillSwap


- **Rendimiento y Escalabilidad:**  
  ASP.NET Core ofrece un entorno de ejecución de alto rendimiento, ideal para aplicaciones que requieren escalabilidad y capacidad para manejar un alto volumen de tráfico.

- **Multiplataforma:**  
  Permite el desarrollo y despliegue de aplicaciones en Windows, Linux y macOS, brindando flexibilidad en la infraestructura y reducción de costos operativos.

- **Arquitectura:**  
  Soporta patrones arquitectónicos como MVC (Modelo-Vista-Controlador), facilitando la separación de responsabilidades y mejorando el mantenimiento del código.

- **Integración de Funcionalidades:**  
  Facilita la incorporación de características como videoconferencias, gestión de créditos y herramientas interactivas de enseñanza, esenciales para SkillSwap.

- **Seguridad Robusta:**  
  Proporciona herramientas y bibliotecas para implementar medidas de seguridad avanzadas, protegiendo la información sensible de los usuarios.

# Gestión de Riesgos

## Proceso de Gestión de Riesgos

- **Identificación de Riesgos:**
  Detectar y documentar los riesgos potenciales.
  
- **Análisis de Riesgos:**
  Analizar la probabilidad de que cada riesgo ocurra y el impacto que tendría, priorizándolos según su gravedad.
  
- **Planificación ante el Riesgo:**
  Desarrollar estrategias y acciones específicas para mitigar, transferir, aceptar o evitar cada riesgo identificado.
  
- **Implementación de Respuestas:**
  Ejecutar las acciones planificadas para gestionar los riesgos de manera efectiva.

- **Monitorización del Riesgo:**
  Supervisar continuamente los riesgos y las respuestas implementadas, ajustando las estrategias según sea necesario.

## Estrategias de Acción para Mejorar la Calidad de las Videollamadas

### Optimización de la Infraestructura Tecnológica

- **Ancho de Banda Adecuado:** Asegurarse de que tanto instructores como estudiantes dispongan de conexiones a Internet con suficiente ancho de banda para soportar videollamadas de alta calidad.
- **Equipos Actualizados:** Utilizar dispositivos con especificaciones adecuadas, incluyendo cámaras y micrófonos de calidad, para mejorar la claridad visual y auditiva.

### Selección de Plataformas de Videoconferencia Fiables

- **Evaluación de Herramientas:** Optar por plataformas reconocidas que ofrezcan estabilidad, seguridad y funcionalidades adecuadas para el entorno educativo.
- **Pruebas Previas:** Realizar pruebas piloto antes de las sesiones en vivo para familiarizarse con las herramientas y ajustar configuraciones según sea necesario.

### Capacitación en Competencias Digitales

- **Formación para Usuarios:** Brindar capacitación a estudiantes y docentes en el uso efectivo de las herramientas tecnológicas, incluyendo resolución de problemas comunes y buenas prácticas.
- **Soporte Técnico:** Establecer canales de soporte técnico accesibles para resolver inconvenientes durante las sesiones.

### Gestión de la Calidad de la Red

- **Priorización de Tráfico:** Implementar Quality of Service (QoS) en redes para priorizar el tráfico de videoconferencia y minimizar interferencias.
- **Redundancia de Conexiones:** Contar con conexiones de respaldo o sistemas de conmutación por error para garantizar la continuidad en caso de fallas.

### Monitoreo y Evaluación Continua

- **Recopilación de Feedback:** Solicitar retroalimentación regular de los participantes sobre la calidad técnica y pedagógica de las sesiones.
- **Análisis de Datos:** Revisar métricas de rendimiento de las videollamadas para identificar patrones y áreas de mejora.


#  Herramienta de gestión/seguimiento 

## Jira
### Características de la Herramienta de Gestión de Proyectos Jira 

- **Gestión de Incidencias:**
  Permite registrar y seguir errores, tareas y mejoras durante el ciclo de vida del proyecto.

- **Flujos de Trabajo Personalizables:**
  Ofrece la posibilidad de diseñar flujos de trabajo adaptados a las necesidades específicas de cada equipo o proyecto.

- **Integraciones:**
  Se integra con diversas herramientas como sistemas de control de versiones y plataformas de comunicación, facilitando la colaboración entre equipos.

- **Informes y Dashboards:**
  Proporciona paneles de control y reportes detallados que permiten monitorear el progreso y desempeño del proyecto en tiempo real.
  

  
![atlassian-jira-logo-large](https://github.com/user-attachments/assets/e68983fb-8b2d-4d9b-9825-df303af981ab)



