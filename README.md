# 🚗 Sistema de Transporte Autónomo Multicarro con Grúa
¡Bienvenido!

Este proyecto consiste en el desarrollo de un sistema autónomo de transporte de objetos, utilizando carros seguidores de línea inteligentes equipados con sensores, control PID, comunicación inalámbrica y un sistema de grúa para carga y descarga.

El sistema permite que varios carros funcionen de manera independiente o coordinada, pudiendo:

- Seguir rutas predefinidas tipo “mapa”.

- Recoger, transportar y entregar carga automáticamente.

- Coordinar intercambio de carga entre carros.

- Ser controlados desde un servidor central o aplicación remota.

Este proyecto nace de la necesidad de automatizar procesos logísticos en entornos educativos, industriales o experimentales, aplicando conceptos de robótica móvil, control de movimiento, electrónica digital y programación modular.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# 🎯 Objetivo del Proyecto
Implementar un sistema completo y funcional de transporte autónomo basado en carros seguidores, integrando:

- Control electrónico (motores, sensores, grúa, alimentación).

- Comunicación inalámbrica entre múltiples carros.

- Sistema de planificación y asignación de tareas.

- Coordinación entre unidades y transferencia de carga.

- Desarrollo estructurado con metodología ágil y control de versiones.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# 📦 Componentes Principales
| Módulo                                       | Funcionalidad                                 |
| -------------------------------------------- | --------------------------------------------- |
| 🤖 **Carro Seguidor**                        | Se desplaza siguiendo ruta y ejecuta misiones |
| 🏗️ **Grúa**                                  | Eleva, sujeta y libera cargas                 |
| 🎯 **Sensores de Línea**                     | Detectan trayecto para navegación             |
| 🚧 **Sensor de Obstáculos**                  | Prevención de colisiones                      |
| ⚙️ **Control PID + PWM**                     | Ajuste de velocidad y estabilidad             |
| 🌐 **Módulo WiFi / Comunicación**            | Reporta estado y recibe órdenes               |
| 🔋 **Sistema de Alimentación**               | Batería y regulación de voltaje               |
| 🧠 **Servidor Central / Control Multicarro** | Coordina y asigna tareas                      |

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# 👥 Integrantes del Equipo
- Cristian David Aguilar Becerra (202478586)
- Martin David Cortes Osorio (202478552)
- Carlos Andres Dominguez Aristizabal
- Juan Jose Gil Cortes

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# 🚀 Tecnologías y Herramientas
| Área                    | Tecnología / Herramienta                   |
| ----------------------- | ------------------------------------------ |
| Microcontrolador        | ESP32                                      |
| Diseño Electrónico      | PCB, Puente H, Reguladores                 |
| Control de Movimiento   | Motores DC + PWM + PID                     |
| Sensado                 | Sensores IR, Ultrasonido / IR Proximidad   |
| Comunicación            | WiFi / Protocolo interno por sockets       |
| Programación            | Micropython                                |
| Documentación y Gestión | GitHub Issues • GitHub Projects • Markdown |
| Lógica del Sistema      | Máquina de Estados / Modelo Mealy          |

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# 📂 Estructura del Repositorio
Este repositorio está organizado usando GitHub Issues como tareas, cubriendo cada módulo:

- Ubicación del carro

- Sensores de línea

- Control PID

- Grúa y servos

- Transferencia entre carros

- Sistema multicarro

- Alimentación y baterías

- PCB

- Comunicación inalámbrica

Cada Issue representa una parte funcional claramente definible del proyecto.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Acuerdos del Equipo
# 🧱 Metodología de Trabajo
- Scrum + Kanban usando GitHub Projects.

- Issues como tareas.

- Commits pequeños y con descripción clara.

- Pull Requests para integrar código.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# 📝 Tareas del Proyecto (GitHub Issues)
### Fase 1: Documentación, Análisis y Diseño

- PROJECT-SETUP-01: Configuración Inicial del Proyecto y Documentación
- TASK-DOC-01: Recolección y Redacción de Requerimientos del Sistema
- TASK-DOC-02: Especificación de Roles (Carro, Grúa, Servidor)
- TASK-DIAGRAMS-01: Diseño de Diagrama de Casos de Uso
- TASK-DIAGRAMS-02: Diseño de Diagrama de Clases
- TASK-DIAGRAMS-03: Diseño de Modelo de Estados (Mealy)
- TASK-DIAGRAMS-04: Diseño del Mapa (Plano de recorrido de carros)
- TASK-GIT-01: Creación y Organización del Repositorio GitHub
- TASK-GIT-02: Definición y Documentación de la Estrategia de Branching

### Fase 2: Desarrollo del Carro Seguidor (Hardware + Software)

- **EPIC-CARRO-01**: Plataforma Mecánica y Electrónica
- TASK-CARRO-HW-01: Diseño y Ensamblaje del Chasis del Carro
- TASK-CARRO-HW-02: Selección y Montaje de Motores
- TASK-CARRO-HW-03: Instalación del Sistema de Alimentación (Batería + Regulación)
- TASK-CARRO-HW-04: Diseño y Fabricación de PCB del Carro
- **EPIC-CARRO-02**: Sensores y Percepción
- TASK-CARRO-SENS-01: Integración y Calibración de Sensores de Línea (IR)
- TASK-CARRO-SENS-02: Integración del Sensor de Obstáculos (Ultrasonido / IR)
- TASK-CARRO-SENS-03: Implementación del Sistema de Ubicación en Mapa
- **EPIC-CARRO-03**: Control y Movimiento
- TASK-CARRO-SW-01: Programación de Control PWM para Motores
- TASK-CARRO-SW-02: Implementación del Control PID para corrección de trayectoria
- TASK-CARRO-SW-03: Programación del Driver de Motores (Puente H)
- TASK-CARRO-SW-04: Lógica de Movimiento y Navegación entre Nodos
- **EPIC-CARRO-04**: Comunicación
- TASK-CARRO-COM-01: Integración del Módulo WiFi / ESP32 / NRF / XBee
- TASK-CARRO-COM-02: Protocolo de Mensajería con Servidor Central
- TASK-CARRO-COM-03: Envío de Estado (posición, carga, batería)

### Fase 3: Desarrollo de la Grúa

- **EPIC-GRUA-01**: Diseño Mecánico y Electrónico
- TASK-GRUA-HW-01: Diseño y Ensamblaje de la Estructura de la Grúa
- TASK-GRUA-HW-02: Selección e Instalación de Servomotores
- TASK-GRUA-HW-03: Instalación de Sistema de Alimentación y Regulación
- TASK-GRUA-HW-04: Diseño y Fabricación de PCB de la Grúa
- **EPIC-GRUA-02**: Diseño Mecánico y Electrónico
- TASK-GRUA-SW-01: Programación de Servomotores
- TASK-GRUA-SW-02: Detección de Carga (Sensor / Pinza)
- TASK-GRUA-SW-03: Secuencia de Agarre, Elevación, Transporte y Liberación

### Fase 4: Desarrollo de la Grúa

- **EPIC-MULTICARRO-01**: Arquitectura de Comunicación
- TASK-MC-SRV-01: Diseño del Servidor Central (App / PC / ESP32 Maestro)
- TASK-MC-SRV-02: Implementar Protocolo de Comunicación entre Carros
- TASK-MC-SRV-03: Sincronización de Mensajes y Estados
- **EPIC-MULTICARRO-02**: Coordinación y Logística
- TASK-MC-ALG-01: Algoritmo de Asignación de Tareas a Carros
- TASK-MC-ALG-02: Gestión de Prioridad y Selección de Carro
- TASK-MC-ALG-03: Transferencia de Carga entre Carros

### Fase 5: Integración, Pruebas y Optimización

- TEST-01: Pruebas de Movimiento del Carro sin Carga
- TEST-02: Pruebas de Movimiento con Carga
- TEST-03: Pruebas del Sistema de Grúa Independiente
- TEST-04: Pruebas de Sincronización Multicarro
- TEST-05: Pruebas de Seguridad (evitar colisión / fallo sensor)
- OPT-01: Ajuste Fino del PID
- OPT-02: Optimización de Rutas y Nodos
