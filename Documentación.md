# **DOCUMENTACIÓN DEL PROYECTO: SISTEMA DE GESTIÓN ACADÉMICA (SGA)**

*Integrantes:*

- Valery Gabriela Alarcón Peña
- Mary Fernanda Rodríguez Morales

*Profesor:*

- Ing. Hely Suárez Marín

---

## **RESUMEN EJECUTIVO**

*El Sistema de Gestión Académica (SGA) es una aplicación móvil desarrollada en Python utilizando Kivy, diseñada para funcionar en dispositivos Android. Su objetivo es permitir que los estudiantes organicen sus actividades académicas desde una sola herramienta, fácil de usar, con almacenamiento local en SQLite y funcionamiento sin conexión a internet.*

*El SGA integra gestión de tareas, horarios, calificaciones, recordatorios y personalización, creando un entorno organizado, accesible y moderno. De esta manera, los estudiantes pueden mejorar su productividad, mantener seguimiento de su rendimiento y optimizar la administración de su tiempo.*

---

## **PROBLEMA**

*Los estudiantes utilizan múltiples herramientas digitales aisladas para manejar sus actividades académicas: notas, calendarios, recordatorios, hojas de cálculo, etc. Esto genera:*

- Desorganización
- Pérdida de información
- Dificultad para hacer seguimiento académico
- Falta de centralización
- Problemas al alternar entre distintas aplicaciones
- Dependencia de internet para sincronizar datos

*La ausencia de una herramienta unificada afecta directamente la productividad y el rendimiento académico de los estudiantes.*

---

## **SOLUCIÓN**

*El SGA ofrece una aplicación completa y centralizada que:*

- Funciona exclusivamente en **móviles Android**
- Está desarrollada en **Python**
- Utiliza **Kivy**
- Almacena los datos en **SQLite**
- No requiere conexión a internet

### *Funcionalidades principales*

- Registro y control de tareas con fechas de entrega
- Gestión de calificaciones y cálculo automático de promedios
- Organización visual de horarios
- Recordatorios personalizados por fecha y hora
- Personalización completa de la interfaz

---

## **OBJETIVOS**

### *Objetivo General*

*Desarrollar una aplicación móvil en Python que permita gestionar tareas, calificaciones, horarios, recordatorios y configuraciones personales.*

### *Objetivos Específicos*

- Diseñar una interfaz adaptable a dispositivos Android
- Implementar una base de datos SQLite con llaves primarias y foráneas
- Programar módulos funcionales de tareas, notas, horarios y recordatorios
- Elaborar diagramas UML estructurales y dinámicos
- Garantizar la seguridad y persistencia de datos
- Optimizar la navegación y experiencia del usuario

---

## **ALCANCE DEL PROYECTO**

*El Sistema de Gestión Académica permite:*

- Registrar, editar y eliminar tareas
- Registrar calificaciones y calcular promedios
- Gestionar horarios académicos
- Crear recordatorios personalizados
- Personalizar temas y colores

*El sistema es totalmente funcional offline, pero está preparado para futuras integraciones en la nube.*

---

## **METODOLOGÍA DE DESARROLLO**

*La metodología utilizada es una Agile híbrida combinando:*

- Scrum (iteraciones y mejoras continuas)
- Cascada mejorada (fases ordenadas y documentadas)

### *Fases del desarrollo*

1. Análisis de requerimientos
2. Diseño UML y MER
3. Desarrollo en Python con Kivy
4. Pruebas y depuración
5. Documentación final

---

## **REQUERIMIENTOS DEL SISTEMA**

### *Requerimientos Funcionales (RF)*

- **RF01:** Registrar, modificar y eliminar tareas
- **RF02:** Asignar tareas a materias
- **RF03:** Registrar calificaciones y calcular promedios
- **RF04:** Gestionar horarios académicos
- **RF05:** Crear recordatorios
- **RF06:** Personalizar apariencia
- **RF07:** Almacenar datos en SQLite
- **RF08:** Sincronizar versiones con exportación/importación manual

### *Requerimientos No Funcionales (RNF)*

- **RNF01:** Compatible con Android
- **RNF02:** Tiempo de respuesta menor a 2 segundos
- **RNF03:** Interfaz adaptable a distintas resoluciones móviles
- **RNF04:** Interfaz intuitiva
- **RNF05:** Código modular y documentado

---

## **ARQUITECTURA DEL SISTEMA**

*El sistema se basa en el patrón Modelo–Vista–Controlador (MVC):*

- **Modelo:** lógica de datos y conexión con SQLite
- **Vista:** interfaz Kivy
- **Controlador:** validaciones y manejo de eventos

*Esta arquitectura permite un desarrollo organizado y escalable.*

---

## **DIAGRAMAS UML**

### *Diagramas Estáticos*

- Diagrama de clases
- Diagrama de objetos
- Diagrama de componentes
- Diagrama de paquetes
- Diagrama de despliegue
- Diagrama de estructura compuesta

### *Diagramas Dinámicos*

- Casos de uso
- Secuencia
- Comunicación
- Actividades
- Estados
- Tiempo

---

## **CRONOGRAMA GENERAL**

| Fase | Actividad                      | Duración  |
| ---- | ------------------------------ | --------- |
| 1    | Análisis de requerimientos     | 2 semanas |
| 2    | Diseño UML y modelo ER         | 2 semanas |
| 3    | Implementación en Android      | 4 semanas |
| 4    | Pruebas y validación           | 2 semanas |
| 5    | Documentación y entrega        | 1 semana  |

---

## **CONCLUSIÓN**

*El Sistema de Gestión Académica (SGA) brinda una solución completa e intuitiva para que los estudiantes organicen su vida académica. Su diseño móvil permite acceder a la información desde cualquier dispositivo Android sin internet, mientras que sus tecnologías base (Python, Kivy y SQLite) aseguran un desarrollo seguro, accesible y escalable.*

*Los diagramas UML y el diseño modular garantizan que el sistema pueda expandirse con nuevas funcionalidades a futuro, consolidándose como una herramienta eficiente y sostenible para el entorno educativo actual.*
